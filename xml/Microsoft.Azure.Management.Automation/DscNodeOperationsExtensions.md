<Type Name="DscNodeOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DscNodeOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DscNodeOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DscNodeOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DscNodeOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, Guid nodeId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid nodeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IDscNodeOperations, resourceGroupName As String, automationAccount As String, nodeId As Guid) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IDscNodeOperations * string * string * Guid -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, nodeId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c28c1-101">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeOperations.</span><span class="sxs-lookup"><span data-stu-id="c28c1-101">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c28c1-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-102">Required.</span></span> <span data-ttu-id="c28c1-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c28c1-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="c28c1-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-104">Required.</span></span> <span data-ttu-id="c28c1-105">Automation-Kontonamen.</span><span class="sxs-lookup"><span data-stu-id="c28c1-105">Automation account name.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="c28c1-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-106">Required.</span></span> <span data-ttu-id="c28c1-107">Die Knoten-ID.</span><span class="sxs-lookup"><span data-stu-id="c28c1-107">The node id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c28c1-108">Löschen der dsc-Knoten, die durch die Knoten-Id identifiziert.  (siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c28c1-108">Delete the dsc node identified by node id.  (see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c28c1-109">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="c28c1-109">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, Guid nodeId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid nodeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IDscNodeOperations, resourceGroupName As String, automationAccount As String, nodeId As Guid) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IDscNodeOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, nodeId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c28c1-110">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeOperations.</span><span class="sxs-lookup"><span data-stu-id="c28c1-110">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c28c1-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-111">Required.</span></span> <span data-ttu-id="c28c1-112">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c28c1-112">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="c28c1-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-113">Required.</span></span> <span data-ttu-id="c28c1-114">Automation-Kontonamen.</span><span class="sxs-lookup"><span data-stu-id="c28c1-114">Automation account name.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="c28c1-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-115">Required.</span></span> <span data-ttu-id="c28c1-116">Die Knoten-ID.</span><span class="sxs-lookup"><span data-stu-id="c28c1-116">The node id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c28c1-117">Löschen der dsc-Knoten, die durch die Knoten-Id identifiziert.  (siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c28c1-117">Delete the dsc node identified by node id.  (see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c28c1-118">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="c28c1-118">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse Get (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, Guid nodeId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse Get(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid nodeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDscNodeOperations, resourceGroupName As String, automationAccount As String, nodeId As Guid) As DscNodeGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IDscNodeOperations * string * string * Guid -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.Get (operations, resourceGroupName, automationAccount, nodeId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c28c1-119">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeOperations.</span><span class="sxs-lookup"><span data-stu-id="c28c1-119">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c28c1-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-120">Required.</span></span> <span data-ttu-id="c28c1-121">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c28c1-121">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="c28c1-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-122">Required.</span></span> <span data-ttu-id="c28c1-123">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="c28c1-123">The automation account name.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="c28c1-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-124">Required.</span></span> <span data-ttu-id="c28c1-125">Die Knoten-ID.</span><span class="sxs-lookup"><span data-stu-id="c28c1-125">The node id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c28c1-126">Abrufen der dsc-Knoten, die durch die Knoten-Id identifiziert.  (siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c28c1-126">Retrieve the dsc node identified by node id.  (see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c28c1-127">Das Antwort-Modell für die Get dsc-Knotens.</span><span class="sxs-lookup"><span data-stu-id="c28c1-127">The response model for the get dsc node operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, Guid nodeId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid nodeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IDscNodeOperations, resourceGroupName As String, automationAccount As String, nodeId As Guid) As Task(Of DscNodeGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IDscNodeOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, nodeId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c28c1-128">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeOperations.</span><span class="sxs-lookup"><span data-stu-id="c28c1-128">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c28c1-129">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-129">Required.</span></span> <span data-ttu-id="c28c1-130">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c28c1-130">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="c28c1-131">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-131">Required.</span></span> <span data-ttu-id="c28c1-132">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="c28c1-132">The automation account name.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="c28c1-133">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-133">Required.</span></span> <span data-ttu-id="c28c1-134">Die Knoten-ID.</span><span class="sxs-lookup"><span data-stu-id="c28c1-134">The node id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c28c1-135">Abrufen der dsc-Knoten, die durch die Knoten-Id identifiziert.  (siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c28c1-135">Retrieve the dsc node identified by node id.  (see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c28c1-136">Das Antwort-Modell für die Get dsc-Knotens.</span><span class="sxs-lookup"><span data-stu-id="c28c1-136">The response model for the get dsc node operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeListResponse List (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeListResponse List(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.List(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDscNodeOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodeListParameters) As DscNodeListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IDscNodeOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodeListParameters -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeListResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.List (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c28c1-137">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeOperations.</span><span class="sxs-lookup"><span data-stu-id="c28c1-137">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c28c1-138">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-138">Required.</span></span> <span data-ttu-id="c28c1-139">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c28c1-139">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="c28c1-140">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-140">Required.</span></span> <span data-ttu-id="c28c1-141">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="c28c1-141">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c28c1-142">Optional.</span><span class="sxs-lookup"><span data-stu-id="c28c1-142">Optional.</span></span> <span data-ttu-id="c28c1-143">Die Parameter für die Liste zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="c28c1-143">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c28c1-144">Eine Liste der dsc-Knoten abzurufen.</span><span class="sxs-lookup"><span data-stu-id="c28c1-144">Retrieve a list of dsc nodes.</span></span>  <span data-ttu-id="c28c1-145">(siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c28c1-145">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c28c1-146">Das Antwort-Modell für die Liste dsc-Knoten-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c28c1-146">The response model for the list dsc nodes operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDscNodeOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodeListParameters) As Task(Of DscNodeListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IDscNodeOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodeListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c28c1-147">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeOperations.</span><span class="sxs-lookup"><span data-stu-id="c28c1-147">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c28c1-148">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-148">Required.</span></span> <span data-ttu-id="c28c1-149">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c28c1-149">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="c28c1-150">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-150">Required.</span></span> <span data-ttu-id="c28c1-151">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="c28c1-151">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c28c1-152">Optional.</span><span class="sxs-lookup"><span data-stu-id="c28c1-152">Optional.</span></span> <span data-ttu-id="c28c1-153">Die Parameter für die Liste zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="c28c1-153">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c28c1-154">Eine Liste der dsc-Knoten abzurufen.</span><span class="sxs-lookup"><span data-stu-id="c28c1-154">Retrieve a list of dsc nodes.</span></span>  <span data-ttu-id="c28c1-155">(siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c28c1-155">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c28c1-156">Das Antwort-Modell für die Liste dsc-Knoten-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c28c1-156">The response model for the list dsc nodes operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeListResponse ListNext (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeListResponse ListNext(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDscNodeOperations, nextLink As String) As DscNodeListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IDscNodeOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeListResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c28c1-157">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeOperations.</span><span class="sxs-lookup"><span data-stu-id="c28c1-157">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="c28c1-158">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-158">Required.</span></span> <span data-ttu-id="c28c1-159">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="c28c1-159">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c28c1-160">Rufen Sie weitere Liste der Konfigurationen.</span><span class="sxs-lookup"><span data-stu-id="c28c1-160">Retrieve next list of configurations.</span></span>  <span data-ttu-id="c28c1-161">(siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c28c1-161">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c28c1-162">Das Antwort-Modell für die Liste dsc-Knoten-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c28c1-162">The response model for the list dsc nodes operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDscNodeOperations, nextLink As String) As Task(Of DscNodeListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IDscNodeOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c28c1-163">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeOperations.</span><span class="sxs-lookup"><span data-stu-id="c28c1-163">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="c28c1-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-164">Required.</span></span> <span data-ttu-id="c28c1-165">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="c28c1-165">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c28c1-166">Rufen Sie weitere Liste der Konfigurationen.</span><span class="sxs-lookup"><span data-stu-id="c28c1-166">Retrieve next list of configurations.</span></span>  <span data-ttu-id="c28c1-167">(siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c28c1-167">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c28c1-168">Das Antwort-Modell für die Liste dsc-Knoten-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c28c1-168">The response model for the list dsc nodes operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse Patch (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse Patch(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As IDscNodeOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodePatchParameters) As DscNodePatchResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.IDscNodeOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters -&gt; Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.Patch (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c28c1-169">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeOperations.</span><span class="sxs-lookup"><span data-stu-id="c28c1-169">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c28c1-170">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-170">Required.</span></span> <span data-ttu-id="c28c1-171">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c28c1-171">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="c28c1-172">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-172">Required.</span></span> <span data-ttu-id="c28c1-173">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="c28c1-173">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c28c1-174">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-174">Required.</span></span> <span data-ttu-id="c28c1-175">Parameter, die auf den Patch für dsc-Knoten angegeben.</span><span class="sxs-lookup"><span data-stu-id="c28c1-175">Parameters supplied to the patch dsc node.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c28c1-176">Aktualisieren Sie den dsc-Knoten.</span><span class="sxs-lookup"><span data-stu-id="c28c1-176">Update the dsc node.</span></span>  <span data-ttu-id="c28c1-177">(siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c28c1-177">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c28c1-178">Das Antwort-Modell für die Patch-dsc-Knoten-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c28c1-178">The response model for the patch dsc node operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As IDscNodeOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodePatchParameters) As Task(Of DscNodePatchResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.IDscNodeOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.PatchAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c28c1-179">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeOperations.</span><span class="sxs-lookup"><span data-stu-id="c28c1-179">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c28c1-180">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-180">Required.</span></span> <span data-ttu-id="c28c1-181">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c28c1-181">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="c28c1-182">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-182">Required.</span></span> <span data-ttu-id="c28c1-183">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="c28c1-183">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c28c1-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c28c1-184">Required.</span></span> <span data-ttu-id="c28c1-185">Parameter, die auf den Patch für dsc-Knoten angegeben.</span><span class="sxs-lookup"><span data-stu-id="c28c1-185">Parameters supplied to the patch dsc node.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c28c1-186">Aktualisieren Sie den dsc-Knoten.</span><span class="sxs-lookup"><span data-stu-id="c28c1-186">Update the dsc node.</span></span>  <span data-ttu-id="c28c1-187">(siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c28c1-187">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c28c1-188">Das Antwort-Modell für die Patch-dsc-Knoten-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c28c1-188">The response model for the patch dsc node operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>