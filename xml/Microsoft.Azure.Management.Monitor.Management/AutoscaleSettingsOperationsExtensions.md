<Type Name="AutoscaleSettingsOperationsExtensions" FullName="Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AutoscaleSettingsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AutoscaleSettingsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AutoscaleSettingsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AutoscaleSettingsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e0ffe-101">Erweiterungsmethoden für AutoscaleSettingsOperations.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-101">Extension methods for AutoscaleSettingsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource CreateOrUpdate (this Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, string autoscaleSettingName, Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource CreateOrUpdate(class Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, string autoscaleSettingName, class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations,System.String,System.String,Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IAutoscaleSettingsOperations, resourceGroupName As String, autoscaleSettingName As String, parameters As AutoscaleSettingResource) As AutoscaleSettingResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations * string * string * Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource -&gt; Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource" Usage="Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, autoscaleSettingName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="autoscaleSettingName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0ffe-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e0ffe-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-103">The name of the resource group.</span></span>
            </param>
        <param name="autoscaleSettingName">
            <span data-ttu-id="e0ffe-104">Der Name der Einstellung zur automatischen Skalierung.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-104">The autoscale setting name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e0ffe-105">Parameter für den Vorgang bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-105">Parameters supplied to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0ffe-106">Erstellt oder aktualisiert eine Einstellung zum automatischen Skalieren.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-106">Creates or updates an autoscale setting.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, string autoscaleSettingName, Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, string autoscaleSettingName, class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations,System.String,System.String,Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations * string * string * Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, autoscaleSettingName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="autoscaleSettingName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0ffe-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e0ffe-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-108">The name of the resource group.</span></span>
            </param>
        <param name="autoscaleSettingName">
            <span data-ttu-id="e0ffe-109">Der Name der Einstellung zur automatischen Skalierung.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-109">The autoscale setting name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e0ffe-110">Parameter für den Vorgang bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-110">Parameters supplied to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e0ffe-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0ffe-112">Erstellt oder aktualisiert eine Einstellung zum automatischen Skalieren.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-112">Creates or updates an autoscale setting.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, string autoscaleSettingName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, string autoscaleSettingName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.Delete(Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IAutoscaleSettingsOperations, resourceGroupName As String, autoscaleSettingName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.Delete (operations, resourceGroupName, autoscaleSettingName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="autoscaleSettingName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0ffe-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e0ffe-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-114">The name of the resource group.</span></span>
            </param>
        <param name="autoscaleSettingName">
            <span data-ttu-id="e0ffe-115">Der Name der Einstellung zur automatischen Skalierung.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-115">The autoscale setting name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0ffe-116">Löscht und die Einstellung zum automatischen Skalieren</span><span class="sxs-lookup"><span data-stu-id="e0ffe-116">Deletes and autoscale setting</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, string autoscaleSettingName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, string autoscaleSettingName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.DeleteAsync (operations, resourceGroupName, autoscaleSettingName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="autoscaleSettingName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0ffe-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e0ffe-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-118">The name of the resource group.</span></span>
            </param>
        <param name="autoscaleSettingName">
            <span data-ttu-id="e0ffe-119">Der Name der Einstellung zur automatischen Skalierung.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-119">The autoscale setting name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e0ffe-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0ffe-121">Löscht und die Einstellung zum automatischen Skalieren</span><span class="sxs-lookup"><span data-stu-id="e0ffe-121">Deletes and autoscale setting</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource Get (this Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, string autoscaleSettingName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource Get(class Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, string autoscaleSettingName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.Get(Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IAutoscaleSettingsOperations, resourceGroupName As String, autoscaleSettingName As String) As AutoscaleSettingResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations * string * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource" Usage="Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.Get (operations, resourceGroupName, autoscaleSettingName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="autoscaleSettingName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0ffe-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e0ffe-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-123">The name of the resource group.</span></span>
            </param>
        <param name="autoscaleSettingName">
            <span data-ttu-id="e0ffe-124">Der Name der Einstellung zur automatischen Skalierung.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-124">The autoscale setting name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0ffe-125">Ruft eine skalierungseinstellung für die automatische</span><span class="sxs-lookup"><span data-stu-id="e0ffe-125">Gets an autoscale setting</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt; GetAsync (this Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, string autoscaleSettingName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt; GetAsync(class Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, string autoscaleSettingName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.GetAsync (operations, resourceGroupName, autoscaleSettingName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="autoscaleSettingName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0ffe-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e0ffe-127">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-127">The name of the resource group.</span></span>
            </param>
        <param name="autoscaleSettingName">
            <span data-ttu-id="e0ffe-128">Der Name der Einstellung zur automatischen Skalierung.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-128">The autoscale setting name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e0ffe-129">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0ffe-130">Ruft eine skalierungseinstellung für die automatische</span><span class="sxs-lookup"><span data-stu-id="e0ffe-130">Gets an autoscale setting</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt; ListByResourceGroup (this Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt; ListByResourceGroup(class Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IAutoscaleSettingsOperations, resourceGroupName As String) As IPage(Of AutoscaleSettingResource)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0ffe-131">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e0ffe-132">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-132">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0ffe-133">Listet die Einstellungen für automatische Skalierung für eine Ressourcengruppe ein.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-133">Lists the autoscale settings for a resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0ffe-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e0ffe-135">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-135">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e0ffe-136">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0ffe-137">Listet die Einstellungen für automatische Skalierung für eine Ressourcengruppe ein.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-137">Lists the autoscale settings for a resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IAutoscaleSettingsOperations, nextPageLink As String) As IPage(Of AutoscaleSettingResource)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0ffe-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-138">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e0ffe-139">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-139">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0ffe-140">Listet die Einstellungen für automatische Skalierung für eine Ressourcengruppe ein.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-140">Lists the autoscale settings for a resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0ffe-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-141">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e0ffe-142">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-142">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e0ffe-143">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0ffe-144">Listet die Einstellungen für automatische Skalierung für eine Ressourcengruppe ein.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-144">Lists the autoscale settings for a resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource Update (this Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, string autoscaleSettingName, Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch autoscaleSettingResource);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource Update(class Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, string autoscaleSettingName, class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch autoscaleSettingResource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.Update(Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations,System.String,System.String,Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations * string * string * Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch -&gt; Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource" Usage="Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.Update (operations, resourceGroupName, autoscaleSettingName, autoscaleSettingResource)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="autoscaleSettingName" Type="System.String" />
        <Parameter Name="autoscaleSettingResource" Type="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0ffe-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e0ffe-146">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-146">The name of the resource group.</span></span>
            </param>
        <param name="autoscaleSettingName">
            <span data-ttu-id="e0ffe-147">Der Name der Einstellung zur automatischen Skalierung.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-147">The autoscale setting name.</span></span>
            </param>
        <param name="autoscaleSettingResource">
            <span data-ttu-id="e0ffe-148">Parameter für den Vorgang bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-148">Parameters supplied to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0ffe-149">Aktualisiert eine vorhandene AutoscaleSettingsResource an.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-149">Updates an existing AutoscaleSettingsResource.</span></span> <span data-ttu-id="e0ffe-150">Zum Aktualisieren verwenden andere Felder die CreateOrUpdate-Methode.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-150">To update other fields use the CreateOrUpdate method.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt; UpdateAsync (this Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, string autoscaleSettingName, Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch autoscaleSettingResource, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt; UpdateAsync(class Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations operations, string resourceGroupName, string autoscaleSettingName, class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch autoscaleSettingResource, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations,System.String,System.String,Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations * string * string * Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions.UpdateAsync (operations, resourceGroupName, autoscaleSettingName, autoscaleSettingResource, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.AutoscaleSettingsOperationsExtensions/&lt;UpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="autoscaleSettingName" Type="System.String" />
        <Parameter Name="autoscaleSettingResource" Type="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0ffe-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e0ffe-152">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-152">The name of the resource group.</span></span>
            </param>
        <param name="autoscaleSettingName">
            <span data-ttu-id="e0ffe-153">Der Name der Einstellung zur automatischen Skalierung.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-153">The autoscale setting name.</span></span>
            </param>
        <param name="autoscaleSettingResource">
            <span data-ttu-id="e0ffe-154">Parameter für den Vorgang bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-154">Parameters supplied to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e0ffe-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0ffe-156">Aktualisiert eine vorhandene AutoscaleSettingsResource an.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-156">Updates an existing AutoscaleSettingsResource.</span></span> <span data-ttu-id="e0ffe-157">Zum Aktualisieren verwenden andere Felder die CreateOrUpdate-Methode.</span><span class="sxs-lookup"><span data-stu-id="e0ffe-157">To update other fields use the CreateOrUpdate method.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>