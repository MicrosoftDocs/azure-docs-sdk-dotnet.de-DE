<Type Name="ApplicationSecurityGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ApplicationSecurityGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ApplicationSecurityGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ApplicationSecurityGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ApplicationSecurityGroupsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9c88d-101">Erweiterungsmethoden für ApplicationSecurityGroupsOperations.</span><span class="sxs-lookup"><span data-stu-id="9c88d-101">Extension methods for ApplicationSecurityGroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName, Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName, class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IApplicationSecurityGroupsOperations, resourceGroupName As String, applicationSecurityGroupName As String, parameters As ApplicationSecurityGroup) As ApplicationSecurityGroup" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup -&gt; Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, applicationSecurityGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c88d-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-103">The name of the resource group.</span></span>
            </param>
        <param name="applicationSecurityGroupName">
            <span data-ttu-id="9c88d-104">Der Name der Sicherheitsgruppe der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9c88d-104">The name of the application security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9c88d-105">Parameter für das Erstellen oder aktualisieren ApplicationSecurityGroup zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="9c88d-105">Parameters supplied to the create or update ApplicationSecurityGroup operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-106">Erstellt oder aktualisiert eine Anwendung-Sicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-106">Creates or updates an application security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName, Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName, class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, applicationSecurityGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c88d-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-108">The name of the resource group.</span></span>
            </param>
        <param name="applicationSecurityGroupName">
            <span data-ttu-id="9c88d-109">Der Name der Sicherheitsgruppe der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9c88d-109">The name of the application security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9c88d-110">Parameter für das Erstellen oder aktualisieren ApplicationSecurityGroup zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="9c88d-110">Parameters supplied to the create or update ApplicationSecurityGroup operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c88d-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c88d-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-112">Erstellt oder aktualisiert eine Anwendung-Sicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-112">Creates or updates an application security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IApplicationSecurityGroupsOperations, resourceGroupName As String, applicationSecurityGroupName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.BeginDelete (operations, resourceGroupName, applicationSecurityGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationSecurityGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c88d-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-114">The name of the resource group.</span></span>
            </param>
        <param name="applicationSecurityGroupName">
            <span data-ttu-id="9c88d-115">Der Name der Sicherheitsgruppe der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9c88d-115">The name of the application security group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-116">Löscht die angegebene Anwendung Sicherheitsgruppe an.</span><span class="sxs-lookup"><span data-stu-id="9c88d-116">Deletes the specified application security group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, applicationSecurityGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationSecurityGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c88d-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-118">The name of the resource group.</span></span>
            </param>
        <param name="applicationSecurityGroupName">
            <span data-ttu-id="9c88d-119">Der Name der Sicherheitsgruppe der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9c88d-119">The name of the application security group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c88d-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c88d-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-121">Löscht die angegebene Anwendung Sicherheitsgruppe an.</span><span class="sxs-lookup"><span data-stu-id="9c88d-121">Deletes the specified application security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup CreateOrUpdate (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName, Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup CreateOrUpdate(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName, class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IApplicationSecurityGroupsOperations, resourceGroupName As String, applicationSecurityGroupName As String, parameters As ApplicationSecurityGroup) As ApplicationSecurityGroup" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup -&gt; Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, applicationSecurityGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c88d-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-123">The name of the resource group.</span></span>
            </param>
        <param name="applicationSecurityGroupName">
            <span data-ttu-id="9c88d-124">Der Name der Sicherheitsgruppe der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9c88d-124">The name of the application security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9c88d-125">Parameter für das Erstellen oder aktualisieren ApplicationSecurityGroup zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="9c88d-125">Parameters supplied to the create or update ApplicationSecurityGroup operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-126">Erstellt oder aktualisiert eine Anwendung-Sicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-126">Creates or updates an application security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName, Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName, class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, applicationSecurityGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c88d-128">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-128">The name of the resource group.</span></span>
            </param>
        <param name="applicationSecurityGroupName">
            <span data-ttu-id="9c88d-129">Der Name der Sicherheitsgruppe der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9c88d-129">The name of the application security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9c88d-130">Parameter für das Erstellen oder aktualisieren ApplicationSecurityGroup zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="9c88d-130">Parameters supplied to the create or update ApplicationSecurityGroup operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c88d-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c88d-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-132">Erstellt oder aktualisiert eine Anwendung-Sicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-132">Creates or updates an application security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IApplicationSecurityGroupsOperations, resourceGroupName As String, applicationSecurityGroupName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.Delete (operations, resourceGroupName, applicationSecurityGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationSecurityGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c88d-134">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-134">The name of the resource group.</span></span>
            </param>
        <param name="applicationSecurityGroupName">
            <span data-ttu-id="9c88d-135">Der Name der Sicherheitsgruppe der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9c88d-135">The name of the application security group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-136">Löscht die angegebene Anwendung Sicherheitsgruppe an.</span><span class="sxs-lookup"><span data-stu-id="9c88d-136">Deletes the specified application security group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.DeleteAsync (operations, resourceGroupName, applicationSecurityGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationSecurityGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c88d-138">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-138">The name of the resource group.</span></span>
            </param>
        <param name="applicationSecurityGroupName">
            <span data-ttu-id="9c88d-139">Der Name der Sicherheitsgruppe der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9c88d-139">The name of the application security group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c88d-140">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c88d-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-141">Löscht die angegebene Anwendung Sicherheitsgruppe an.</span><span class="sxs-lookup"><span data-stu-id="9c88d-141">Deletes the specified application security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup Get (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup Get(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.Get(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IApplicationSecurityGroupsOperations, resourceGroupName As String, applicationSecurityGroupName As String) As ApplicationSecurityGroup" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.Get (operations, resourceGroupName, applicationSecurityGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationSecurityGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-142">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c88d-143">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-143">The name of the resource group.</span></span>
            </param>
        <param name="applicationSecurityGroupName">
            <span data-ttu-id="9c88d-144">Der Name der Sicherheitsgruppe der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9c88d-144">The name of the application security group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-145">Ruft Informationen über die Sicherheitsgruppe "angegebene Anwendung" ab.</span><span class="sxs-lookup"><span data-stu-id="9c88d-145">Gets information about the specified application security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; GetAsync (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; GetAsync(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, string applicationSecurityGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.GetAsync (operations, resourceGroupName, applicationSecurityGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationSecurityGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c88d-147">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-147">The name of the resource group.</span></span>
            </param>
        <param name="applicationSecurityGroupName">
            <span data-ttu-id="9c88d-148">Der Name der Sicherheitsgruppe der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9c88d-148">The name of the application security group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c88d-149">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c88d-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-150">Ruft Informationen über die Sicherheitsgruppe "angegebene Anwendung" ab.</span><span class="sxs-lookup"><span data-stu-id="9c88d-150">Gets information about the specified application security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; List (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; List(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.List(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IApplicationSecurityGroupsOperations, resourceGroupName As String) As IPage(Of ApplicationSecurityGroup)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c88d-152">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-152">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-153">Ruft die Anwendung-Sicherheitsgruppen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-153">Gets all the application security groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; ListAll (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; ListAll(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.ListAll(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As IApplicationSecurityGroupsOperations) As IPage(Of ApplicationSecurityGroup)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-154">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-155">Ruft alle Sicherheitsgruppen für die Anwendung in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="9c88d-155">Gets all application security groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions/&lt;ListAllAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-156">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-156">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c88d-157">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c88d-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-158">Ruft alle Sicherheitsgruppen für die Anwendung in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="9c88d-158">Gets all application security groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; ListAllNext (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; ListAllNext(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.ListAllNext(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As IApplicationSecurityGroupsOperations, nextPageLink As String) As IPage(Of ApplicationSecurityGroup)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-159">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-159">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9c88d-160">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9c88d-160">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-161">Ruft alle Sicherheitsgruppen für die Anwendung in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="9c88d-161">Gets all application security groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions/&lt;ListAllNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-162">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9c88d-163">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9c88d-163">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c88d-164">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c88d-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-165">Ruft alle Sicherheitsgruppen für die Anwendung in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="9c88d-165">Gets all application security groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c88d-167">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-167">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c88d-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c88d-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-169">Ruft die Anwendung-Sicherheitsgruppen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-169">Gets all the application security groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; ListNext (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; ListNext(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IApplicationSecurityGroupsOperations, nextPageLink As String) As IPage(Of ApplicationSecurityGroup)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-170">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-170">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9c88d-171">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9c88d-171">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-172">Ruft die Anwendung-Sicherheitsgruppen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-172">Gets all the application security groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationSecurityGroupsOperationsExtensions/&lt;ListNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationSecurityGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c88d-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c88d-173">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9c88d-174">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9c88d-174">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c88d-175">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c88d-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c88d-176">Ruft die Anwendung-Sicherheitsgruppen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c88d-176">Gets all the application security groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>