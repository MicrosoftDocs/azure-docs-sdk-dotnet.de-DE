<Type Name="LinkedServicesOperationsExtensions" FullName="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LinkedServicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LinkedServicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LinkedServicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LinkedServicesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8556c-101">Erweiterungsmethoden für LinkedServicesOperations.</span><span class="sxs-lookup"><span data-stu-id="8556c-101">Extension methods for LinkedServicesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.LinkedService CreateOrUpdate (this Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName, Microsoft.Azure.Management.OperationalInsights.Models.LinkedService parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService CreateOrUpdate(class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName, class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.LinkedService)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ILinkedServicesOperations, resourceGroupName As String, workspaceName As String, linkedServiceName As String, parameters As LinkedService) As LinkedService" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.LinkedService -&gt; Microsoft.Azure.Management.OperationalInsights.Models.LinkedService" Usage="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, workspaceName, linkedServiceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.LinkedService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.LinkedService" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8556c-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8556c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8556c-103">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8556c-103">The name of the resource group to get.</span></span> <span data-ttu-id="8556c-104">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="8556c-104">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="8556c-105">Name des der Protokollanalyse-Arbeitsbereich, die die Ressource LinkedServices enthält</span><span class="sxs-lookup"><span data-stu-id="8556c-105">Name of the Log Analytics Workspace that will contain the linkedServices resource</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="8556c-106">Name der Ressource linkedServices</span><span class="sxs-lookup"><span data-stu-id="8556c-106">Name of the linkedServices resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8556c-107">Die Parameter zum Erstellen oder Aktualisieren eines verknüpften Diensts erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8556c-107">The parameters required to create or update a linked service.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8556c-108">Erstellen oder Aktualisieren eines verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="8556c-108">Create or update a linked service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName, Microsoft.Azure.Management.OperationalInsights.Models.LinkedService parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName, class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.LinkedService,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.LinkedService * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, workspaceName, linkedServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.LinkedService" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8556c-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8556c-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8556c-110">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8556c-110">The name of the resource group to get.</span></span> <span data-ttu-id="8556c-111">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="8556c-111">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="8556c-112">Name des der Protokollanalyse-Arbeitsbereich, die die Ressource LinkedServices enthält</span><span class="sxs-lookup"><span data-stu-id="8556c-112">Name of the Log Analytics Workspace that will contain the linkedServices resource</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="8556c-113">Name der Ressource linkedServices</span><span class="sxs-lookup"><span data-stu-id="8556c-113">Name of the linkedServices resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8556c-114">Die Parameter zum Erstellen oder Aktualisieren eines verknüpften Diensts erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8556c-114">The parameters required to create or update a linked service.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8556c-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8556c-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8556c-116">Erstellen oder Aktualisieren eines verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="8556c-116">Create or update a linked service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.Delete(Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ILinkedServicesOperations, resourceGroupName As String, workspaceName As String, linkedServiceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.Delete (operations, resourceGroupName, workspaceName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8556c-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8556c-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8556c-118">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8556c-118">The name of the resource group to get.</span></span> <span data-ttu-id="8556c-119">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="8556c-119">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="8556c-120">Name des der Protokollanalyse-Arbeitsbereich mit der LinkedServices Ressource</span><span class="sxs-lookup"><span data-stu-id="8556c-120">Name of the Log Analytics Workspace that contains the linkedServices resource</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="8556c-121">Name des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="8556c-121">Name of the linked service.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8556c-122">Löscht eine Instanz des verknüpften Diensts an.</span><span class="sxs-lookup"><span data-stu-id="8556c-122">Deletes a linked service instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.DeleteAsync (operations, resourceGroupName, workspaceName, linkedServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8556c-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8556c-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8556c-124">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8556c-124">The name of the resource group to get.</span></span> <span data-ttu-id="8556c-125">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="8556c-125">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="8556c-126">Name des der Protokollanalyse-Arbeitsbereich mit der LinkedServices Ressource</span><span class="sxs-lookup"><span data-stu-id="8556c-126">Name of the Log Analytics Workspace that contains the linkedServices resource</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="8556c-127">Name des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="8556c-127">Name of the linked service.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8556c-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8556c-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8556c-129">Löscht eine Instanz des verknüpften Diensts an.</span><span class="sxs-lookup"><span data-stu-id="8556c-129">Deletes a linked service instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.LinkedService Get (this Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService Get(class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.Get(Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ILinkedServicesOperations, resourceGroupName As String, workspaceName As String, linkedServiceName As String) As LinkedService" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations * string * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.LinkedService" Usage="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.Get (operations, resourceGroupName, workspaceName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.LinkedService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8556c-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8556c-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8556c-131">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8556c-131">The name of the resource group to get.</span></span> <span data-ttu-id="8556c-132">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="8556c-132">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="8556c-133">Name des der Protokollanalyse-Arbeitsbereich mit der LinkedServices Ressource</span><span class="sxs-lookup"><span data-stu-id="8556c-133">Name of the Log Analytics Workspace that contains the linkedServices resource</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="8556c-134">Name des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="8556c-134">Name of the linked service.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8556c-135">Ruft eine Instanz des verknüpften Diensts ab.</span><span class="sxs-lookup"><span data-stu-id="8556c-135">Gets a linked service instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt; GetAsync (this Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt; GetAsync(class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.GetAsync(Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.GetAsync (operations, resourceGroupName, workspaceName, linkedServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8556c-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8556c-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8556c-137">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8556c-137">The name of the resource group to get.</span></span> <span data-ttu-id="8556c-138">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="8556c-138">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="8556c-139">Name des der Protokollanalyse-Arbeitsbereich mit der LinkedServices Ressource</span><span class="sxs-lookup"><span data-stu-id="8556c-139">Name of the Log Analytics Workspace that contains the linkedServices resource</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="8556c-140">Name des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="8556c-140">Name of the linked service.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8556c-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8556c-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8556c-142">Ruft eine Instanz des verknüpften Diensts ab.</span><span class="sxs-lookup"><span data-stu-id="8556c-142">Gets a linked service instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspace">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt; ListByWorkspace (this Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt; ListByWorkspace(class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.ListByWorkspace(Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByWorkspace (operations As ILinkedServicesOperations, resourceGroupName As String, workspaceName As String) As IEnumerable(Of LinkedService)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspace : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.ListByWorkspace (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8556c-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8556c-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8556c-144">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8556c-144">The name of the resource group to get.</span></span> <span data-ttu-id="8556c-145">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="8556c-145">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="8556c-146">Der Name des der Protokollanalyse-Arbeitsbereich, die die verknüpften Dienste enthält.</span><span class="sxs-lookup"><span data-stu-id="8556c-146">Name of the Log Analytics Workspace that contains the linked services.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8556c-147">Ruft die verknüpften Dienste-Instanzen in einem Arbeitsbereich ab.</span><span class="sxs-lookup"><span data-stu-id="8556c-147">Gets the linked services instances in a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt; ListByWorkspaceAsync (this Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt; ListByWorkspaceAsync(class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.ListByWorkspaceAsync(Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceAsync : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.ListByWorkspaceAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions/&lt;ListByWorkspaceAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8556c-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8556c-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8556c-149">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8556c-149">The name of the resource group to get.</span></span> <span data-ttu-id="8556c-150">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="8556c-150">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="8556c-151">Der Name des der Protokollanalyse-Arbeitsbereich, die die verknüpften Dienste enthält.</span><span class="sxs-lookup"><span data-stu-id="8556c-151">Name of the Log Analytics Workspace that contains the linked services.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8556c-152">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8556c-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8556c-153">Ruft die verknüpften Dienste-Instanzen in einem Arbeitsbereich ab.</span><span class="sxs-lookup"><span data-stu-id="8556c-153">Gets the linked services instances in a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>