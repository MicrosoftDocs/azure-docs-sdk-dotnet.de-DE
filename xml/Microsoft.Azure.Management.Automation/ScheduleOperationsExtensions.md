<Type Name="ScheduleOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ScheduleOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ScheduleOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ScheduleOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ScheduleOperationsExtensions = class" />
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
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IScheduleOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IScheduleOperations, resourceGroupName As String, automationAccount As String, parameters As ScheduleCreateOrUpdateParameters) As ScheduleCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IScheduleOperations * string * string * Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e54b1-101">Verweis auf die Microsoft.Azure.Management.Automation.IScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="e54b1-101">Reference to the Microsoft.Azure.Management.Automation.IScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e54b1-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-102">Required.</span></span> <span data-ttu-id="e54b1-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e54b1-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e54b1-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-104">Required.</span></span> <span data-ttu-id="e54b1-105">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="e54b1-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e54b1-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-106">Required.</span></span> <span data-ttu-id="e54b1-107">Die Parameter für den Zeitplan erstellen oder Aktualisieren zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="e54b1-107">The parameters supplied to the create or update schedule operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e54b1-108">Erstellen Sie einen Zeitplan an.</span><span class="sxs-lookup"><span data-stu-id="e54b1-108">Create a schedule.</span></span>  <span data-ttu-id="e54b1-109">(siehe http://aka.ms/azureautomationsdk/scheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="e54b1-109">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e54b1-110">Das Antwort-Modell für den Zeitplan erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="e54b1-110">The response model for the create or update schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IScheduleOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IScheduleOperations, resourceGroupName As String, automationAccount As String, parameters As ScheduleCreateOrUpdateParameters) As Task(Of ScheduleCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IScheduleOperations * string * string * Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e54b1-111">Verweis auf die Microsoft.Azure.Management.Automation.IScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="e54b1-111">Reference to the Microsoft.Azure.Management.Automation.IScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e54b1-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-112">Required.</span></span> <span data-ttu-id="e54b1-113">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e54b1-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e54b1-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-114">Required.</span></span> <span data-ttu-id="e54b1-115">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="e54b1-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e54b1-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-116">Required.</span></span> <span data-ttu-id="e54b1-117">Die Parameter für den Zeitplan erstellen oder Aktualisieren zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="e54b1-117">The parameters supplied to the create or update schedule operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e54b1-118">Erstellen Sie einen Zeitplan an.</span><span class="sxs-lookup"><span data-stu-id="e54b1-118">Create a schedule.</span></span>  <span data-ttu-id="e54b1-119">(siehe http://aka.ms/azureautomationsdk/scheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="e54b1-119">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e54b1-120">Das Antwort-Modell für den Zeitplan erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="e54b1-120">The response model for the create or update schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount, string scheduleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount, string scheduleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IScheduleOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IScheduleOperations, resourceGroupName As String, automationAccount As String, scheduleName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IScheduleOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, scheduleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="scheduleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e54b1-121">Verweis auf die Microsoft.Azure.Management.Automation.IScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="e54b1-121">Reference to the Microsoft.Azure.Management.Automation.IScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e54b1-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-122">Required.</span></span> <span data-ttu-id="e54b1-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e54b1-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e54b1-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-124">Required.</span></span> <span data-ttu-id="e54b1-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="e54b1-125">The automation account name.</span></span>
            </param>
        <param name="scheduleName">
            <span data-ttu-id="e54b1-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-126">Required.</span></span> <span data-ttu-id="e54b1-127">Der Zeitplanname.</span><span class="sxs-lookup"><span data-stu-id="e54b1-127">The schedule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e54b1-128">Löschen des Zeitplans Zeitplan namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="e54b1-128">Delete the schedule identified by schedule name.</span></span>  <span data-ttu-id="e54b1-129">(siehe http://aka.ms/azureautomationsdk/scheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="e54b1-129">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e54b1-130">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="e54b1-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount, string scheduleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount, string scheduleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IScheduleOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IScheduleOperations, resourceGroupName As String, automationAccount As String, scheduleName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IScheduleOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, scheduleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="scheduleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e54b1-131">Verweis auf die Microsoft.Azure.Management.Automation.IScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="e54b1-131">Reference to the Microsoft.Azure.Management.Automation.IScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e54b1-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-132">Required.</span></span> <span data-ttu-id="e54b1-133">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e54b1-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e54b1-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-134">Required.</span></span> <span data-ttu-id="e54b1-135">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="e54b1-135">The automation account name.</span></span>
            </param>
        <param name="scheduleName">
            <span data-ttu-id="e54b1-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-136">Required.</span></span> <span data-ttu-id="e54b1-137">Der Zeitplanname.</span><span class="sxs-lookup"><span data-stu-id="e54b1-137">The schedule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e54b1-138">Löschen des Zeitplans Zeitplan namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="e54b1-138">Delete the schedule identified by schedule name.</span></span>  <span data-ttu-id="e54b1-139">(siehe http://aka.ms/azureautomationsdk/scheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="e54b1-139">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e54b1-140">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="e54b1-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ScheduleGetResponse Get (this Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount, string scheduleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ScheduleGetResponse Get(class Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount, string scheduleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IScheduleOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IScheduleOperations, resourceGroupName As String, automationAccount As String, scheduleName As String) As ScheduleGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IScheduleOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.ScheduleGetResponse" Usage="Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.Get (operations, resourceGroupName, automationAccount, scheduleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ScheduleGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="scheduleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e54b1-141">Verweis auf die Microsoft.Azure.Management.Automation.IScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="e54b1-141">Reference to the Microsoft.Azure.Management.Automation.IScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e54b1-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-142">Required.</span></span> <span data-ttu-id="e54b1-143">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e54b1-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e54b1-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-144">Required.</span></span> <span data-ttu-id="e54b1-145">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="e54b1-145">The automation account name.</span></span>
            </param>
        <param name="scheduleName">
            <span data-ttu-id="e54b1-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-146">Required.</span></span> <span data-ttu-id="e54b1-147">Der Zeitplanname.</span><span class="sxs-lookup"><span data-stu-id="e54b1-147">The schedule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e54b1-148">Abgerufen Sie den Zeitplanname identifizierten Zeitplan werden.</span><span class="sxs-lookup"><span data-stu-id="e54b1-148">Retrieve the schedule identified by schedule name.</span></span>  <span data-ttu-id="e54b1-149">(siehe http://aka.ms/azureautomationsdk/scheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="e54b1-149">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e54b1-150">Das Antwort-Modell für den Abrufvorgang für den Zeitplan.</span><span class="sxs-lookup"><span data-stu-id="e54b1-150">The response model for the get schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount, string scheduleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ScheduleGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount, string scheduleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IScheduleOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IScheduleOperations, resourceGroupName As String, automationAccount As String, scheduleName As String) As Task(Of ScheduleGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IScheduleOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, scheduleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="scheduleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e54b1-151">Verweis auf die Microsoft.Azure.Management.Automation.IScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="e54b1-151">Reference to the Microsoft.Azure.Management.Automation.IScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e54b1-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-152">Required.</span></span> <span data-ttu-id="e54b1-153">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e54b1-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e54b1-154">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-154">Required.</span></span> <span data-ttu-id="e54b1-155">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="e54b1-155">The automation account name.</span></span>
            </param>
        <param name="scheduleName">
            <span data-ttu-id="e54b1-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-156">Required.</span></span> <span data-ttu-id="e54b1-157">Der Zeitplanname.</span><span class="sxs-lookup"><span data-stu-id="e54b1-157">The schedule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e54b1-158">Abgerufen Sie den Zeitplanname identifizierten Zeitplan werden.</span><span class="sxs-lookup"><span data-stu-id="e54b1-158">Retrieve the schedule identified by schedule name.</span></span>  <span data-ttu-id="e54b1-159">(siehe http://aka.ms/azureautomationsdk/scheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="e54b1-159">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e54b1-160">Das Antwort-Modell für den Abrufvorgang für den Zeitplan.</span><span class="sxs-lookup"><span data-stu-id="e54b1-160">The response model for the get schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ScheduleListResponse List (this Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ScheduleListResponse List(class Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.List(Microsoft.Azure.Management.Automation.IScheduleOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IScheduleOperations, resourceGroupName As String, automationAccount As String) As ScheduleListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IScheduleOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.ScheduleListResponse" Usage="Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.List (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ScheduleListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e54b1-161">Verweis auf die Microsoft.Azure.Management.Automation.IScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="e54b1-161">Reference to the Microsoft.Azure.Management.Automation.IScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e54b1-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-162">Required.</span></span> <span data-ttu-id="e54b1-163">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e54b1-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e54b1-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-164">Required.</span></span> <span data-ttu-id="e54b1-165">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="e54b1-165">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e54b1-166">Abrufen einer Liste auszuwählen.</span><span class="sxs-lookup"><span data-stu-id="e54b1-166">Retrieve a list of schedules.</span></span>  <span data-ttu-id="e54b1-167">(siehe http://aka.ms/azureautomationsdk/scheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="e54b1-167">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e54b1-168">Das Antwort-Modell für den Zeitplan Auflistungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="e54b1-168">The response model for the list schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ScheduleListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IScheduleOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IScheduleOperations, resourceGroupName As String, automationAccount As String) As Task(Of ScheduleListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IScheduleOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e54b1-169">Verweis auf die Microsoft.Azure.Management.Automation.IScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="e54b1-169">Reference to the Microsoft.Azure.Management.Automation.IScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e54b1-170">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-170">Required.</span></span> <span data-ttu-id="e54b1-171">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e54b1-171">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e54b1-172">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-172">Required.</span></span> <span data-ttu-id="e54b1-173">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="e54b1-173">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e54b1-174">Abrufen einer Liste auszuwählen.</span><span class="sxs-lookup"><span data-stu-id="e54b1-174">Retrieve a list of schedules.</span></span>  <span data-ttu-id="e54b1-175">(siehe http://aka.ms/azureautomationsdk/scheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="e54b1-175">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e54b1-176">Das Antwort-Modell für den Zeitplan Auflistungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="e54b1-176">The response model for the list schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ScheduleListResponse ListNext (this Microsoft.Azure.Management.Automation.IScheduleOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ScheduleListResponse ListNext(class Microsoft.Azure.Management.Automation.IScheduleOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IScheduleOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IScheduleOperations, nextLink As String) As ScheduleListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IScheduleOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.ScheduleListResponse" Usage="Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ScheduleListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IScheduleOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e54b1-177">Verweis auf die Microsoft.Azure.Management.Automation.IScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="e54b1-177">Reference to the Microsoft.Azure.Management.Automation.IScheduleOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="e54b1-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-178">Required.</span></span> <span data-ttu-id="e54b1-179">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="e54b1-179">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e54b1-180">Abrufen von weiter Liste auszuwählen.</span><span class="sxs-lookup"><span data-stu-id="e54b1-180">Retrieve next list of schedules.</span></span>  <span data-ttu-id="e54b1-181">(siehe http://aka.ms/azureautomationsdk/scheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="e54b1-181">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e54b1-182">Das Antwort-Modell für den Zeitplan Auflistungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="e54b1-182">The response model for the list schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IScheduleOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ScheduleListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IScheduleOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IScheduleOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IScheduleOperations, nextLink As String) As Task(Of ScheduleListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IScheduleOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IScheduleOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e54b1-183">Verweis auf die Microsoft.Azure.Management.Automation.IScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="e54b1-183">Reference to the Microsoft.Azure.Management.Automation.IScheduleOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="e54b1-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-184">Required.</span></span> <span data-ttu-id="e54b1-185">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="e54b1-185">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e54b1-186">Abrufen von weiter Liste auszuwählen.</span><span class="sxs-lookup"><span data-stu-id="e54b1-186">Retrieve next list of schedules.</span></span>  <span data-ttu-id="e54b1-187">(siehe http://aka.ms/azureautomationsdk/scheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="e54b1-187">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e54b1-188">Das Antwort-Modell für den Zeitplan Auflistungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="e54b1-188">The response model for the list schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Patch (this Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Patch(class Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.IScheduleOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As IScheduleOperations, resourceGroupName As String, automationAccount As String, parameters As SchedulePatchParameters) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.IScheduleOperations * string * string * Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.Patch (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e54b1-189">Verweis auf die Microsoft.Azure.Management.Automation.IScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="e54b1-189">Reference to the Microsoft.Azure.Management.Automation.IScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e54b1-190">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-190">Required.</span></span> <span data-ttu-id="e54b1-191">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e54b1-191">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e54b1-192">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-192">Required.</span></span> <span data-ttu-id="e54b1-193">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="e54b1-193">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e54b1-194">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-194">Required.</span></span> <span data-ttu-id="e54b1-195">Die Parameter für den Patch Zeitplan zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="e54b1-195">The parameters supplied to the patch schedule operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e54b1-196">Aktualisieren Sie den Zeitplan Zeitplan namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="e54b1-196">Update the schedule identified by schedule name.</span></span>  <span data-ttu-id="e54b1-197">(siehe http://aka.ms/azureautomationsdk/scheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="e54b1-197">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e54b1-198">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="e54b1-198">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.IScheduleOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.IScheduleOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As IScheduleOperations, resourceGroupName As String, automationAccount As String, parameters As SchedulePatchParameters) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.IScheduleOperations * string * string * Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ScheduleOperationsExtensions.PatchAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e54b1-199">Verweis auf die Microsoft.Azure.Management.Automation.IScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="e54b1-199">Reference to the Microsoft.Azure.Management.Automation.IScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e54b1-200">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-200">Required.</span></span> <span data-ttu-id="e54b1-201">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e54b1-201">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e54b1-202">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-202">Required.</span></span> <span data-ttu-id="e54b1-203">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="e54b1-203">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e54b1-204">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e54b1-204">Required.</span></span> <span data-ttu-id="e54b1-205">Die Parameter für den Patch Zeitplan zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="e54b1-205">The parameters supplied to the patch schedule operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e54b1-206">Aktualisieren Sie den Zeitplan Zeitplan namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="e54b1-206">Update the schedule identified by schedule name.</span></span>  <span data-ttu-id="e54b1-207">(siehe http://aka.ms/azureautomationsdk/scheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="e54b1-207">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e54b1-208">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="e54b1-208">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>