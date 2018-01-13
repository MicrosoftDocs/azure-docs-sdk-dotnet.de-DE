<Type Name="HybridRunbookWorkerGroupOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class HybridRunbookWorkerGroupOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit HybridRunbookWorkerGroupOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module HybridRunbookWorkerGroupOperationsExtensions" />
  <TypeSignature Language="F#" Value="type HybridRunbookWorkerGroupOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IHybridRunbookWorkerGroupOperations, resourceGroupName As String, automationAccount As String, hybridRunbookWorkerGroupName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, hybridRunbookWorkerGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b306d-101">Verweis auf die Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span><span class="sxs-lookup"><span data-stu-id="b306d-101">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b306d-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-102">Required.</span></span> <span data-ttu-id="b306d-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b306d-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b306d-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-104">Required.</span></span> <span data-ttu-id="b306d-105">Automation-Kontonamen.</span><span class="sxs-lookup"><span data-stu-id="b306d-105">Automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="b306d-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-106">Required.</span></span> <span data-ttu-id="b306d-107">Der Gruppenname von Hybrid Runbook worker</span><span class="sxs-lookup"><span data-stu-id="b306d-107">The hybrid runbook worker group name</span></span>
            </param>
        <summary>
            <span data-ttu-id="b306d-108">Löschen Sie eine Hybrid Runbook Worker-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b306d-108">Delete a hybrid runbook worker group.</span></span>  <span data-ttu-id="b306d-109">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b306d-109">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b306d-110">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="b306d-110">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IHybridRunbookWorkerGroupOperations, resourceGroupName As String, automationAccount As String, hybridRunbookWorkerGroupName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, hybridRunbookWorkerGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b306d-111">Verweis auf die Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span><span class="sxs-lookup"><span data-stu-id="b306d-111">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b306d-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-112">Required.</span></span> <span data-ttu-id="b306d-113">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b306d-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b306d-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-114">Required.</span></span> <span data-ttu-id="b306d-115">Automation-Kontonamen.</span><span class="sxs-lookup"><span data-stu-id="b306d-115">Automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="b306d-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-116">Required.</span></span> <span data-ttu-id="b306d-117">Der Gruppenname von Hybrid Runbook worker</span><span class="sxs-lookup"><span data-stu-id="b306d-117">The hybrid runbook worker group name</span></span>
            </param>
        <summary>
            <span data-ttu-id="b306d-118">Löschen Sie eine Hybrid Runbook Worker-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b306d-118">Delete a hybrid runbook worker group.</span></span>  <span data-ttu-id="b306d-119">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b306d-119">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b306d-120">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="b306d-120">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse Get (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse Get(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IHybridRunbookWorkerGroupOperations, resourceGroupName As String, automationAccount As String, hybridRunbookWorkerGroupName As String) As HybridRunbookWorkerGroupGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.Get (operations, resourceGroupName, automationAccount, hybridRunbookWorkerGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b306d-121">Verweis auf die Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span><span class="sxs-lookup"><span data-stu-id="b306d-121">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b306d-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-122">Required.</span></span> <span data-ttu-id="b306d-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b306d-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b306d-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-124">Required.</span></span> <span data-ttu-id="b306d-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b306d-125">The automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="b306d-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-126">Required.</span></span> <span data-ttu-id="b306d-127">Der Gruppenname von Hybrid Runbook worker</span><span class="sxs-lookup"><span data-stu-id="b306d-127">The hybrid runbook worker group name</span></span>
            </param>
        <summary>
            <span data-ttu-id="b306d-128">Abrufen einer Hybrid Runbook Worker-gruppendiagramms.</span><span class="sxs-lookup"><span data-stu-id="b306d-128">Retrieve a hybrid runbook worker group.</span></span>  <span data-ttu-id="b306d-129">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b306d-129">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b306d-130">Das Antwort-Modell für den Hybrid Runbook Worker-Gruppe Abrufvorgang.</span><span class="sxs-lookup"><span data-stu-id="b306d-130">The response model for the get hybrid runbook worker group operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IHybridRunbookWorkerGroupOperations, resourceGroupName As String, automationAccount As String, hybridRunbookWorkerGroupName As String) As Task(Of HybridRunbookWorkerGroupGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, hybridRunbookWorkerGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b306d-131">Verweis auf die Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span><span class="sxs-lookup"><span data-stu-id="b306d-131">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b306d-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-132">Required.</span></span> <span data-ttu-id="b306d-133">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b306d-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b306d-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-134">Required.</span></span> <span data-ttu-id="b306d-135">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b306d-135">The automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="b306d-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-136">Required.</span></span> <span data-ttu-id="b306d-137">Der Gruppenname von Hybrid Runbook worker</span><span class="sxs-lookup"><span data-stu-id="b306d-137">The hybrid runbook worker group name</span></span>
            </param>
        <summary>
            <span data-ttu-id="b306d-138">Abrufen einer Hybrid Runbook Worker-gruppendiagramms.</span><span class="sxs-lookup"><span data-stu-id="b306d-138">Retrieve a hybrid runbook worker group.</span></span>  <span data-ttu-id="b306d-139">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b306d-139">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b306d-140">Das Antwort-Modell für den Hybrid Runbook Worker-Gruppe Abrufvorgang.</span><span class="sxs-lookup"><span data-stu-id="b306d-140">The response model for the get hybrid runbook worker group operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse List (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse List(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.List(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IHybridRunbookWorkerGroupOperations, resourceGroupName As String, automationAccount As String) As HybridRunbookWorkerGroupsListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.List (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b306d-141">Verweis auf die Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span><span class="sxs-lookup"><span data-stu-id="b306d-141">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b306d-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-142">Required.</span></span> <span data-ttu-id="b306d-143">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b306d-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b306d-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-144">Required.</span></span> <span data-ttu-id="b306d-145">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b306d-145">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b306d-146">Rufen Sie eine Liste von Hybrid Runbook Worker-Gruppen.</span><span class="sxs-lookup"><span data-stu-id="b306d-146">Retrieve a list of hybrid runbook worker groups.</span></span>  <span data-ttu-id="b306d-147">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b306d-147">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b306d-148">Das Antwort-Modell für die Liste Hybrid Runbook Worker-Gruppen.</span><span class="sxs-lookup"><span data-stu-id="b306d-148">The response model for the list hybrid runbook worker groups.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IHybridRunbookWorkerGroupOperations, resourceGroupName As String, automationAccount As String) As Task(Of HybridRunbookWorkerGroupsListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b306d-149">Verweis auf die Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span><span class="sxs-lookup"><span data-stu-id="b306d-149">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b306d-150">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-150">Required.</span></span> <span data-ttu-id="b306d-151">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b306d-151">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b306d-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-152">Required.</span></span> <span data-ttu-id="b306d-153">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b306d-153">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b306d-154">Rufen Sie eine Liste von Hybrid Runbook Worker-Gruppen.</span><span class="sxs-lookup"><span data-stu-id="b306d-154">Retrieve a list of hybrid runbook worker groups.</span></span>  <span data-ttu-id="b306d-155">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b306d-155">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b306d-156">Das Antwort-Modell für die Liste Hybrid Runbook Worker-Gruppen.</span><span class="sxs-lookup"><span data-stu-id="b306d-156">The response model for the list hybrid runbook worker groups.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse ListNext (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse ListNext(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IHybridRunbookWorkerGroupOperations, nextLink As String) As HybridRunbookWorkerGroupsListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b306d-157">Verweis auf die Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span><span class="sxs-lookup"><span data-stu-id="b306d-157">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="b306d-158">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-158">Required.</span></span> <span data-ttu-id="b306d-159">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="b306d-159">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b306d-160">Rufen Sie weitere Liste der Hybrid Runbook Worker-Gruppen.</span><span class="sxs-lookup"><span data-stu-id="b306d-160">Retrieve next list of hybrid runbook worker groups.</span></span>  <span data-ttu-id="b306d-161">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b306d-161">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b306d-162">Das Antwort-Modell für die Liste Hybrid Runbook Worker-Gruppen.</span><span class="sxs-lookup"><span data-stu-id="b306d-162">The response model for the list hybrid runbook worker groups.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IHybridRunbookWorkerGroupOperations, nextLink As String) As Task(Of HybridRunbookWorkerGroupsListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b306d-163">Verweis auf die Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span><span class="sxs-lookup"><span data-stu-id="b306d-163">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="b306d-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-164">Required.</span></span> <span data-ttu-id="b306d-165">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="b306d-165">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b306d-166">Rufen Sie weitere Liste der Hybrid Runbook Worker-Gruppen.</span><span class="sxs-lookup"><span data-stu-id="b306d-166">Retrieve next list of hybrid runbook worker groups.</span></span>  <span data-ttu-id="b306d-167">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b306d-167">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b306d-168">Das Antwort-Modell für die Liste Hybrid Runbook Worker-Gruppen.</span><span class="sxs-lookup"><span data-stu-id="b306d-168">The response model for the list hybrid runbook worker groups.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse Patch (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse Patch(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As IHybridRunbookWorkerGroupOperations, resourceGroupName As String, automationAccount As String, hybridRunbookWorkerGroupName As String, parameters As HybridRunbookWorkerGroupPatchParameters) As HybridRunbookWorkerGroupPatchResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string * string * string * Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters -&gt; Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.Patch (operations, resourceGroupName, automationAccount, hybridRunbookWorkerGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b306d-169">Verweis auf die Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span><span class="sxs-lookup"><span data-stu-id="b306d-169">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b306d-170">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-170">Required.</span></span> <span data-ttu-id="b306d-171">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b306d-171">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b306d-172">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-172">Required.</span></span> <span data-ttu-id="b306d-173">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b306d-173">The automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="b306d-174">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-174">Required.</span></span> <span data-ttu-id="b306d-175">Der Gruppenname von Hybrid Runbook worker</span><span class="sxs-lookup"><span data-stu-id="b306d-175">The hybrid runbook worker group name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b306d-176">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-176">Required.</span></span> <span data-ttu-id="b306d-177">Hybrid Runbook Worker-Gruppe</span><span class="sxs-lookup"><span data-stu-id="b306d-177">The hybrid runbook worker group</span></span>
            </param>
        <summary>
            <span data-ttu-id="b306d-178">Aktualisieren Sie eine Hybrid Runbook Worker-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b306d-178">Update a hybrid runbook worker group.</span></span>  <span data-ttu-id="b306d-179">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b306d-179">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b306d-180">Das Antwort-Modell für den Patch Hybrid Runbook Worker-Gruppe-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b306d-180">The response model for the patch hybrid runbook worker group operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As IHybridRunbookWorkerGroupOperations, resourceGroupName As String, automationAccount As String, hybridRunbookWorkerGroupName As String, parameters As HybridRunbookWorkerGroupPatchParameters) As Task(Of HybridRunbookWorkerGroupPatchResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string * string * string * Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt;" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.PatchAsync (operations, resourceGroupName, automationAccount, hybridRunbookWorkerGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b306d-181">Verweis auf die Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span><span class="sxs-lookup"><span data-stu-id="b306d-181">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b306d-182">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-182">Required.</span></span> <span data-ttu-id="b306d-183">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b306d-183">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b306d-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-184">Required.</span></span> <span data-ttu-id="b306d-185">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b306d-185">The automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="b306d-186">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-186">Required.</span></span> <span data-ttu-id="b306d-187">Der Gruppenname von Hybrid Runbook worker</span><span class="sxs-lookup"><span data-stu-id="b306d-187">The hybrid runbook worker group name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b306d-188">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b306d-188">Required.</span></span> <span data-ttu-id="b306d-189">Hybrid Runbook Worker-Gruppe</span><span class="sxs-lookup"><span data-stu-id="b306d-189">The hybrid runbook worker group</span></span>
            </param>
        <summary>
            <span data-ttu-id="b306d-190">Aktualisieren Sie eine Hybrid Runbook Worker-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b306d-190">Update a hybrid runbook worker group.</span></span>  <span data-ttu-id="b306d-191">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b306d-191">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b306d-192">Das Antwort-Modell für den Patch Hybrid Runbook Worker-Gruppe-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b306d-192">The response model for the patch hybrid runbook worker group operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>