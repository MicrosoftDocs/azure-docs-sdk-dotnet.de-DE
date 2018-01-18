<Type Name="DscNodeReportsOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DscNodeReportsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DscNodeReportsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DscNodeReportsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DscNodeReportsOperationsExtensions = class" />
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
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse Get (this Microsoft.Azure.Management.Automation.IDscNodeReportsOperations operations, string resourceGroupName, string automationAccount, Guid nodeId, Guid reportId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse Get(class Microsoft.Azure.Management.Automation.IDscNodeReportsOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid nodeId, valuetype System.Guid reportId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IDscNodeReportsOperations,System.String,System.String,System.Guid,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDscNodeReportsOperations, resourceGroupName As String, automationAccount As String, nodeId As Guid, reportId As Guid) As DscNodeReportGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IDscNodeReportsOperations * string * string * Guid * Guid -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions.Get (operations, resourceGroupName, automationAccount, nodeId, reportId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeReportsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
        <Parameter Name="reportId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7d78-101">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.</span><span class="sxs-lookup"><span data-stu-id="f7d78-101">Reference to the Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7d78-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-102">Required.</span></span> <span data-ttu-id="f7d78-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="f7d78-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f7d78-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-104">Required.</span></span> <span data-ttu-id="f7d78-105">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="f7d78-105">The automation account name.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="f7d78-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-106">Required.</span></span> <span data-ttu-id="f7d78-107">Der Dsc-Knoten-Id an.</span><span class="sxs-lookup"><span data-stu-id="f7d78-107">The Dsc node id.</span></span>
            </param>
        <param name="reportId">
            <span data-ttu-id="f7d78-108">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-108">Required.</span></span> <span data-ttu-id="f7d78-109">Die Id des Berichts.</span><span class="sxs-lookup"><span data-stu-id="f7d78-109">The report id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7d78-110">Abrufen der Dsc-Knoten-Berichtsdaten nach Knoten-Id und Bericht-Id an.  (siehe http://aka.ms/azureautomationsdk/dscnodereportoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="f7d78-110">Retrieve the Dsc node report data by node id and report id.  (see http://aka.ms/azureautomationsdk/dscnodereportoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f7d78-111">Das Antwort-Modell für die Get Berichtsvorgang für dsc-Knoten.</span><span class="sxs-lookup"><span data-stu-id="f7d78-111">The response model for the get dsc node report operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IDscNodeReportsOperations operations, string resourceGroupName, string automationAccount, Guid nodeId, Guid reportId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IDscNodeReportsOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid nodeId, valuetype System.Guid reportId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IDscNodeReportsOperations,System.String,System.String,System.Guid,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IDscNodeReportsOperations, resourceGroupName As String, automationAccount As String, nodeId As Guid, reportId As Guid) As Task(Of DscNodeReportGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IDscNodeReportsOperations * string * string * Guid * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, nodeId, reportId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeReportsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
        <Parameter Name="reportId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7d78-112">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.</span><span class="sxs-lookup"><span data-stu-id="f7d78-112">Reference to the Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7d78-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-113">Required.</span></span> <span data-ttu-id="f7d78-114">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="f7d78-114">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f7d78-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-115">Required.</span></span> <span data-ttu-id="f7d78-116">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="f7d78-116">The automation account name.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="f7d78-117">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-117">Required.</span></span> <span data-ttu-id="f7d78-118">Der Dsc-Knoten-Id an.</span><span class="sxs-lookup"><span data-stu-id="f7d78-118">The Dsc node id.</span></span>
            </param>
        <param name="reportId">
            <span data-ttu-id="f7d78-119">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-119">Required.</span></span> <span data-ttu-id="f7d78-120">Die Id des Berichts.</span><span class="sxs-lookup"><span data-stu-id="f7d78-120">The report id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7d78-121">Abrufen der Dsc-Knoten-Berichtsdaten nach Knoten-Id und Bericht-Id an.  (siehe http://aka.ms/azureautomationsdk/dscnodereportoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="f7d78-121">Retrieve the Dsc node report data by node id and report id.  (see http://aka.ms/azureautomationsdk/dscnodereportoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f7d78-122">Das Antwort-Modell für die Get Berichtsvorgang für dsc-Knoten.</span><span class="sxs-lookup"><span data-stu-id="f7d78-122">The response model for the get dsc node report operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse GetContent (this Microsoft.Azure.Management.Automation.IDscNodeReportsOperations operations, string resourceGroupName, string automationAccount, Guid nodeId, Guid reportId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse GetContent(class Microsoft.Azure.Management.Automation.IDscNodeReportsOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid nodeId, valuetype System.Guid reportId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions.GetContent(Microsoft.Azure.Management.Automation.IDscNodeReportsOperations,System.String,System.String,System.Guid,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetContent (operations As IDscNodeReportsOperations, resourceGroupName As String, automationAccount As String, nodeId As Guid, reportId As Guid) As DscNodeReportGetContentResponse" />
      <MemberSignature Language="F#" Value="static member GetContent : Microsoft.Azure.Management.Automation.IDscNodeReportsOperations * string * string * Guid * Guid -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions.GetContent (operations, resourceGroupName, automationAccount, nodeId, reportId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeReportsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
        <Parameter Name="reportId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7d78-123">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.</span><span class="sxs-lookup"><span data-stu-id="f7d78-123">Reference to the Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7d78-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-124">Required.</span></span> <span data-ttu-id="f7d78-125">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="f7d78-125">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f7d78-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-126">Required.</span></span> <span data-ttu-id="f7d78-127">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="f7d78-127">The automation account name.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="f7d78-128">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-128">Required.</span></span> <span data-ttu-id="f7d78-129">Der Dsc-Knoten-Id an.</span><span class="sxs-lookup"><span data-stu-id="f7d78-129">The Dsc node id.</span></span>
            </param>
        <param name="reportId">
            <span data-ttu-id="f7d78-130">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-130">Required.</span></span> <span data-ttu-id="f7d78-131">Die Id des Berichts.</span><span class="sxs-lookup"><span data-stu-id="f7d78-131">The report id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7d78-132">Abrufen der Dsc-Knoten-Berichte nach Knoten-Id und Bericht-Id an.  (siehe http://aka.ms/azureautomationsdk/dscnodereportoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="f7d78-132">Retrieve the Dsc node reports by node id and report id.  (see http://aka.ms/azureautomationsdk/dscnodereportoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f7d78-133">Das Antwort-Modell für das Get Bericht Inhalt des Knotens.</span><span class="sxs-lookup"><span data-stu-id="f7d78-133">The response model for the get node report content operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse&gt; GetContentAsync (this Microsoft.Azure.Management.Automation.IDscNodeReportsOperations operations, string resourceGroupName, string automationAccount, Guid nodeId, Guid reportId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse&gt; GetContentAsync(class Microsoft.Azure.Management.Automation.IDscNodeReportsOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid nodeId, valuetype System.Guid reportId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions.GetContentAsync(Microsoft.Azure.Management.Automation.IDscNodeReportsOperations,System.String,System.String,System.Guid,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetContentAsync (operations As IDscNodeReportsOperations, resourceGroupName As String, automationAccount As String, nodeId As Guid, reportId As Guid) As Task(Of DscNodeReportGetContentResponse)" />
      <MemberSignature Language="F#" Value="static member GetContentAsync : Microsoft.Azure.Management.Automation.IDscNodeReportsOperations * string * string * Guid * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions.GetContentAsync (operations, resourceGroupName, automationAccount, nodeId, reportId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeReportsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
        <Parameter Name="reportId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7d78-134">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.</span><span class="sxs-lookup"><span data-stu-id="f7d78-134">Reference to the Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7d78-135">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-135">Required.</span></span> <span data-ttu-id="f7d78-136">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="f7d78-136">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f7d78-137">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-137">Required.</span></span> <span data-ttu-id="f7d78-138">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="f7d78-138">The automation account name.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="f7d78-139">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-139">Required.</span></span> <span data-ttu-id="f7d78-140">Der Dsc-Knoten-Id an.</span><span class="sxs-lookup"><span data-stu-id="f7d78-140">The Dsc node id.</span></span>
            </param>
        <param name="reportId">
            <span data-ttu-id="f7d78-141">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-141">Required.</span></span> <span data-ttu-id="f7d78-142">Die Id des Berichts.</span><span class="sxs-lookup"><span data-stu-id="f7d78-142">The report id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7d78-143">Abrufen der Dsc-Knoten-Berichte nach Knoten-Id und Bericht-Id an.  (siehe http://aka.ms/azureautomationsdk/dscnodereportoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="f7d78-143">Retrieve the Dsc node reports by node id and report id.  (see http://aka.ms/azureautomationsdk/dscnodereportoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f7d78-144">Das Antwort-Modell für das Get Bericht Inhalt des Knotens.</span><span class="sxs-lookup"><span data-stu-id="f7d78-144">The response model for the get node report content operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse List (this Microsoft.Azure.Management.Automation.IDscNodeReportsOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse List(class Microsoft.Azure.Management.Automation.IDscNodeReportsOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions.List(Microsoft.Azure.Management.Automation.IDscNodeReportsOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDscNodeReportsOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodeReportListParameters) As DscNodeReportListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IDscNodeReportsOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions.List (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeReportsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7d78-145">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.</span><span class="sxs-lookup"><span data-stu-id="f7d78-145">Reference to the Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7d78-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-146">Required.</span></span> <span data-ttu-id="f7d78-147">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="f7d78-147">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f7d78-148">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-148">Required.</span></span> <span data-ttu-id="f7d78-149">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="f7d78-149">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f7d78-150">Optional.</span><span class="sxs-lookup"><span data-stu-id="f7d78-150">Optional.</span></span> <span data-ttu-id="f7d78-151">Die Parameter für die Liste zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="f7d78-151">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7d78-152">Abrufen der Liste der Dsc-Knoten-Bericht nach Knoten-Id und Bericht-Id an.  (siehe http://aka.ms/azureautomationsdk/dscnodereportoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="f7d78-152">Retrieve the Dsc node report list by node id and report id.  (see http://aka.ms/azureautomationsdk/dscnodereportoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f7d78-153">Das Antwort-Modell für die Liste dsc-Knoten-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f7d78-153">The response model for the list dsc nodes operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IDscNodeReportsOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IDscNodeReportsOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IDscNodeReportsOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDscNodeReportsOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodeReportListParameters) As Task(Of DscNodeReportListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IDscNodeReportsOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeReportsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7d78-154">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.</span><span class="sxs-lookup"><span data-stu-id="f7d78-154">Reference to the Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7d78-155">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-155">Required.</span></span> <span data-ttu-id="f7d78-156">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="f7d78-156">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f7d78-157">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-157">Required.</span></span> <span data-ttu-id="f7d78-158">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="f7d78-158">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f7d78-159">Optional.</span><span class="sxs-lookup"><span data-stu-id="f7d78-159">Optional.</span></span> <span data-ttu-id="f7d78-160">Die Parameter für die Liste zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="f7d78-160">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7d78-161">Abrufen der Liste der Dsc-Knoten-Bericht nach Knoten-Id und Bericht-Id an.  (siehe http://aka.ms/azureautomationsdk/dscnodereportoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="f7d78-161">Retrieve the Dsc node report list by node id and report id.  (see http://aka.ms/azureautomationsdk/dscnodereportoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f7d78-162">Das Antwort-Modell für die Liste dsc-Knoten-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f7d78-162">The response model for the list dsc nodes operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse ListNext (this Microsoft.Azure.Management.Automation.IDscNodeReportsOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse ListNext(class Microsoft.Azure.Management.Automation.IDscNodeReportsOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IDscNodeReportsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDscNodeReportsOperations, nextLink As String) As DscNodeReportListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IDscNodeReportsOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeReportsOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7d78-163">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.</span><span class="sxs-lookup"><span data-stu-id="f7d78-163">Reference to the Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="f7d78-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-164">Required.</span></span> <span data-ttu-id="f7d78-165">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="f7d78-165">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7d78-166">Abrufen der Liste der Dsc-Knoten-Bericht nach Knoten-Id und Bericht-Id an.  (siehe http://aka.ms/azureautomationsdk/dscnodereportoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="f7d78-166">Retrieve the Dsc node report list by node id and report id.  (see http://aka.ms/azureautomationsdk/dscnodereportoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f7d78-167">Das Antwort-Modell für die Liste dsc-Knoten-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f7d78-167">The response model for the list dsc nodes operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IDscNodeReportsOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IDscNodeReportsOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IDscNodeReportsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDscNodeReportsOperations, nextLink As String) As Task(Of DscNodeReportListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IDscNodeReportsOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeReportsOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeReportsOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7d78-168">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.</span><span class="sxs-lookup"><span data-stu-id="f7d78-168">Reference to the Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="f7d78-169">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7d78-169">Required.</span></span> <span data-ttu-id="f7d78-170">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="f7d78-170">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7d78-171">Abrufen der Liste der Dsc-Knoten-Bericht nach Knoten-Id und Bericht-Id an.  (siehe http://aka.ms/azureautomationsdk/dscnodereportoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="f7d78-171">Retrieve the Dsc node report list by node id and report id.  (see http://aka.ms/azureautomationsdk/dscnodereportoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f7d78-172">Das Antwort-Modell für die Liste dsc-Knoten-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f7d78-172">The response model for the list dsc nodes operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>