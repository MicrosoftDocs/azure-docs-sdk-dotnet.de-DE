<Type Name="TestJobOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TestJobOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TestJobOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TestJobOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TestJobOperationsExtensions = class" />
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
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse Create (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse Create(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Create(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, parameters As TestJobCreateParameters) As TestJobCreateResponse" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters -&gt; Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Create (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="790ae-101">Verweis auf die Microsoft.Azure.Management.Automation.ITestJobOperations.</span><span class="sxs-lookup"><span data-stu-id="790ae-101">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="790ae-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-102">Required.</span></span> <span data-ttu-id="790ae-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="790ae-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="790ae-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-104">Required.</span></span> <span data-ttu-id="790ae-105">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="790ae-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="790ae-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-106">Required.</span></span> <span data-ttu-id="790ae-107">Für den Create Test Job-Vorgang angegebene Parameter.</span><span class="sxs-lookup"><span data-stu-id="790ae-107">The parameters supplied to the create test job operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="790ae-108">Erstellen eines Testauftrags des Runbooks.</span><span class="sxs-lookup"><span data-stu-id="790ae-108">Create a test job of the runbook.</span></span>  <span data-ttu-id="790ae-109">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="790ae-109">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="790ae-110">Das Antwort-Modell für das Erstellen, Testen Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="790ae-110">The response model for the create test job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt; CreateAsync (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt; CreateAsync(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateAsync (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, parameters As TestJobCreateParameters) As Task(Of TestJobCreateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.CreateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="790ae-111">Verweis auf die Microsoft.Azure.Management.Automation.ITestJobOperations.</span><span class="sxs-lookup"><span data-stu-id="790ae-111">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="790ae-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-112">Required.</span></span> <span data-ttu-id="790ae-113">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="790ae-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="790ae-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-114">Required.</span></span> <span data-ttu-id="790ae-115">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="790ae-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="790ae-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-116">Required.</span></span> <span data-ttu-id="790ae-117">Für den Create Test Job-Vorgang angegebene Parameter.</span><span class="sxs-lookup"><span data-stu-id="790ae-117">The parameters supplied to the create test job operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="790ae-118">Erstellen eines Testauftrags des Runbooks.</span><span class="sxs-lookup"><span data-stu-id="790ae-118">Create a test job of the runbook.</span></span>  <span data-ttu-id="790ae-119">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="790ae-119">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="790ae-120">Das Antwort-Modell für das Erstellen, Testen Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="790ae-120">The response model for the create test job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.TestJobGetResponse Get (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.TestJobGetResponse Get(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Get(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As TestJobGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.TestJobGetResponse" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Get (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.TestJobGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="790ae-121">Verweis auf die Microsoft.Azure.Management.Automation.ITestJobOperations.</span><span class="sxs-lookup"><span data-stu-id="790ae-121">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="790ae-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-122">Required.</span></span> <span data-ttu-id="790ae-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="790ae-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="790ae-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-124">Required.</span></span> <span data-ttu-id="790ae-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="790ae-125">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="790ae-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-126">Required.</span></span> <span data-ttu-id="790ae-127">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="790ae-127">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="790ae-128">Abrufen des Testauftrags für das angegebene Runbook an.</span><span class="sxs-lookup"><span data-stu-id="790ae-128">Retrieve the test job for the specified runbook.</span></span>  <span data-ttu-id="790ae-129">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="790ae-129">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="790ae-130">Das Antwort-Modell für die Get Job-Vorgang zu testen.</span><span class="sxs-lookup"><span data-stu-id="790ae-130">The response model for the get test job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of TestJobGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="790ae-131">Verweis auf die Microsoft.Azure.Management.Automation.ITestJobOperations.</span><span class="sxs-lookup"><span data-stu-id="790ae-131">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="790ae-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-132">Required.</span></span> <span data-ttu-id="790ae-133">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="790ae-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="790ae-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-134">Required.</span></span> <span data-ttu-id="790ae-135">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="790ae-135">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="790ae-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-136">Required.</span></span> <span data-ttu-id="790ae-137">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="790ae-137">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="790ae-138">Abrufen des Testauftrags für das angegebene Runbook an.</span><span class="sxs-lookup"><span data-stu-id="790ae-138">Retrieve the test job for the specified runbook.</span></span>  <span data-ttu-id="790ae-139">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="790ae-139">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="790ae-140">Das Antwort-Modell für die Get Job-Vorgang zu testen.</span><span class="sxs-lookup"><span data-stu-id="790ae-140">The response model for the get test job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resume">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Resume (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Resume(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Resume(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Resume (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Resume : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Resume (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="790ae-141">Verweis auf die Microsoft.Azure.Management.Automation.ITestJobOperations.</span><span class="sxs-lookup"><span data-stu-id="790ae-141">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="790ae-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-142">Required.</span></span> <span data-ttu-id="790ae-143">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="790ae-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="790ae-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-144">Required.</span></span> <span data-ttu-id="790ae-145">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="790ae-145">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="790ae-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-146">Required.</span></span> <span data-ttu-id="790ae-147">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="790ae-147">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="790ae-148">Fortsetzen des Testauftrags an.</span><span class="sxs-lookup"><span data-stu-id="790ae-148">Resume the test job.</span></span>  <span data-ttu-id="790ae-149">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="790ae-149">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="790ae-150">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="790ae-150">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.ResumeAsync(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ResumeAsync (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member ResumeAsync : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.ResumeAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="790ae-151">Verweis auf die Microsoft.Azure.Management.Automation.ITestJobOperations.</span><span class="sxs-lookup"><span data-stu-id="790ae-151">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="790ae-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-152">Required.</span></span> <span data-ttu-id="790ae-153">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="790ae-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="790ae-154">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-154">Required.</span></span> <span data-ttu-id="790ae-155">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="790ae-155">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="790ae-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-156">Required.</span></span> <span data-ttu-id="790ae-157">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="790ae-157">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="790ae-158">Fortsetzen des Testauftrags an.</span><span class="sxs-lookup"><span data-stu-id="790ae-158">Resume the test job.</span></span>  <span data-ttu-id="790ae-159">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="790ae-159">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="790ae-160">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="790ae-160">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Stop (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Stop(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Stop(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Stop (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Stop : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Stop (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="790ae-161">Verweis auf die Microsoft.Azure.Management.Automation.ITestJobOperations.</span><span class="sxs-lookup"><span data-stu-id="790ae-161">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="790ae-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-162">Required.</span></span> <span data-ttu-id="790ae-163">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="790ae-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="790ae-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-164">Required.</span></span> <span data-ttu-id="790ae-165">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="790ae-165">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="790ae-166">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-166">Required.</span></span> <span data-ttu-id="790ae-167">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="790ae-167">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="790ae-168">Beenden des Testauftrags an.</span><span class="sxs-lookup"><span data-stu-id="790ae-168">Stop the test job.</span></span>  <span data-ttu-id="790ae-169">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="790ae-169">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="790ae-170">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="790ae-170">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; StopAsync (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; StopAsync(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.StopAsync(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function StopAsync (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.StopAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="790ae-171">Verweis auf die Microsoft.Azure.Management.Automation.ITestJobOperations.</span><span class="sxs-lookup"><span data-stu-id="790ae-171">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="790ae-172">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-172">Required.</span></span> <span data-ttu-id="790ae-173">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="790ae-173">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="790ae-174">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-174">Required.</span></span> <span data-ttu-id="790ae-175">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="790ae-175">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="790ae-176">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-176">Required.</span></span> <span data-ttu-id="790ae-177">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="790ae-177">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="790ae-178">Beenden des Testauftrags an.</span><span class="sxs-lookup"><span data-stu-id="790ae-178">Stop the test job.</span></span>  <span data-ttu-id="790ae-179">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="790ae-179">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="790ae-180">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="790ae-180">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Suspend">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Suspend (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Suspend(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Suspend(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Suspend (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Suspend : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Suspend (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="790ae-181">Verweis auf die Microsoft.Azure.Management.Automation.ITestJobOperations.</span><span class="sxs-lookup"><span data-stu-id="790ae-181">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="790ae-182">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-182">Required.</span></span> <span data-ttu-id="790ae-183">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="790ae-183">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="790ae-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-184">Required.</span></span> <span data-ttu-id="790ae-185">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="790ae-185">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="790ae-186">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-186">Required.</span></span> <span data-ttu-id="790ae-187">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="790ae-187">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="790ae-188">Anhalten des Testauftrags an.</span><span class="sxs-lookup"><span data-stu-id="790ae-188">Suspend the test job.</span></span>  <span data-ttu-id="790ae-189">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="790ae-189">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="790ae-190">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="790ae-190">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.SuspendAsync(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SuspendAsync (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member SuspendAsync : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.SuspendAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="790ae-191">Verweis auf die Microsoft.Azure.Management.Automation.ITestJobOperations.</span><span class="sxs-lookup"><span data-stu-id="790ae-191">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="790ae-192">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-192">Required.</span></span> <span data-ttu-id="790ae-193">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="790ae-193">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="790ae-194">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-194">Required.</span></span> <span data-ttu-id="790ae-195">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="790ae-195">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="790ae-196">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="790ae-196">Required.</span></span> <span data-ttu-id="790ae-197">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="790ae-197">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="790ae-198">Anhalten des Testauftrags an.</span><span class="sxs-lookup"><span data-stu-id="790ae-198">Suspend the test job.</span></span>  <span data-ttu-id="790ae-199">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="790ae-199">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="790ae-200">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="790ae-200">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>