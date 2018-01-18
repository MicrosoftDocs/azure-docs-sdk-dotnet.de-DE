<Type Name="DscNodeConfigurationOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DscNodeConfigurationOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DscNodeConfigurationOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DscNodeConfigurationOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DscNodeConfigurationOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDscNodeConfigurationOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodeConfigurationCreateOrUpdateParameters) As DscNodeConfigurationGetResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2a04-101">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="d2a04-101">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d2a04-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-102">Required.</span></span> <span data-ttu-id="d2a04-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="d2a04-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d2a04-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-104">Required.</span></span> <span data-ttu-id="d2a04-105">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="d2a04-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d2a04-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-106">Required.</span></span> <span data-ttu-id="d2a04-107">Die CREATE- oder Update-Parameter für die Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="d2a04-107">The create or update parameters for configuration.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2a04-108">Die Name der Knotenkonfiguration identifizierte Knotenkonfiguration zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="d2a04-108">Create the node configuration identified by node configuration name.</span></span>  <span data-ttu-id="d2a04-109">(siehe http://aka.ms/azureautomationsdk/dscnodeconfigurations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="d2a04-109">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d2a04-110">Das Antwort-Modell für die Get-Konfigurationsvorgang für Dsc-Knoten.</span><span class="sxs-lookup"><span data-stu-id="d2a04-110">The response model for the get Dsc node configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IDscNodeConfigurationOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodeConfigurationCreateOrUpdateParameters) As Task(Of DscNodeConfigurationGetResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2a04-111">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="d2a04-111">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d2a04-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-112">Required.</span></span> <span data-ttu-id="d2a04-113">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="d2a04-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d2a04-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-114">Required.</span></span> <span data-ttu-id="d2a04-115">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="d2a04-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d2a04-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-116">Required.</span></span> <span data-ttu-id="d2a04-117">Die CREATE- oder Update-Parameter für die Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="d2a04-117">The create or update parameters for configuration.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2a04-118">Die Name der Knotenkonfiguration identifizierte Knotenkonfiguration zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="d2a04-118">Create the node configuration identified by node configuration name.</span></span>  <span data-ttu-id="d2a04-119">(siehe http://aka.ms/azureautomationsdk/dscnodeconfigurations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="d2a04-119">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d2a04-120">Das Antwort-Modell für die Get-Konfigurationsvorgang für Dsc-Knoten.</span><span class="sxs-lookup"><span data-stu-id="d2a04-120">The response model for the get Dsc node configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, string nodeConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, string nodeConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IDscNodeConfigurationOperations, resourceGroupName As String, automationAccount As String, nodeConfigurationName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, nodeConfigurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2a04-121">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="d2a04-121">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d2a04-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-122">Required.</span></span> <span data-ttu-id="d2a04-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="d2a04-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d2a04-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-124">Required.</span></span> <span data-ttu-id="d2a04-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="d2a04-125">The automation account name.</span></span>
            </param>
        <param name="nodeConfigurationName">
            <span data-ttu-id="d2a04-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-126">Required.</span></span> <span data-ttu-id="d2a04-127">Der Konfigurationsname der Dsc-Knoten.</span><span class="sxs-lookup"><span data-stu-id="d2a04-127">The Dsc node configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2a04-128">Löschen der Dsc-Knotenkonfigurationen durch Konfiguration des Knotens an.</span><span class="sxs-lookup"><span data-stu-id="d2a04-128">Delete the Dsc node configurations by node configuration.</span></span>  <span data-ttu-id="d2a04-129">(siehe http://aka.ms/azureautomationsdk/dscnodeconfigurations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="d2a04-129">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d2a04-130">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="d2a04-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, string nodeConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, string nodeConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IDscNodeConfigurationOperations, resourceGroupName As String, automationAccount As String, nodeConfigurationName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, nodeConfigurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2a04-131">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="d2a04-131">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d2a04-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-132">Required.</span></span> <span data-ttu-id="d2a04-133">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="d2a04-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d2a04-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-134">Required.</span></span> <span data-ttu-id="d2a04-135">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="d2a04-135">The automation account name.</span></span>
            </param>
        <param name="nodeConfigurationName">
            <span data-ttu-id="d2a04-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-136">Required.</span></span> <span data-ttu-id="d2a04-137">Der Konfigurationsname der Dsc-Knoten.</span><span class="sxs-lookup"><span data-stu-id="d2a04-137">The Dsc node configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2a04-138">Löschen der Dsc-Knotenkonfigurationen durch Konfiguration des Knotens an.</span><span class="sxs-lookup"><span data-stu-id="d2a04-138">Delete the Dsc node configurations by node configuration.</span></span>  <span data-ttu-id="d2a04-139">(siehe http://aka.ms/azureautomationsdk/dscnodeconfigurations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="d2a04-139">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d2a04-140">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="d2a04-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse Get (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, string nodeConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse Get(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, string nodeConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDscNodeConfigurationOperations, resourceGroupName As String, automationAccount As String, nodeConfigurationName As String) As DscNodeConfigurationGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.Get (operations, resourceGroupName, automationAccount, nodeConfigurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2a04-141">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="d2a04-141">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d2a04-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-142">Required.</span></span> <span data-ttu-id="d2a04-143">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="d2a04-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d2a04-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-144">Required.</span></span> <span data-ttu-id="d2a04-145">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="d2a04-145">The automation account name.</span></span>
            </param>
        <param name="nodeConfigurationName">
            <span data-ttu-id="d2a04-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-146">Required.</span></span> <span data-ttu-id="d2a04-147">Der Konfigurationsname der Dsc-Knoten.</span><span class="sxs-lookup"><span data-stu-id="d2a04-147">The Dsc node configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2a04-148">Abrufen der Dsc-Knotenkonfigurationen durch Konfiguration des Knotens an.</span><span class="sxs-lookup"><span data-stu-id="d2a04-148">Retrieve the Dsc node configurations by node configuration.</span></span>  <span data-ttu-id="d2a04-149">(siehe http://aka.ms/azureautomationsdk/dscnodeconfigurations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="d2a04-149">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d2a04-150">Das Antwort-Modell für die Get-Konfigurationsvorgang für Dsc-Knoten.</span><span class="sxs-lookup"><span data-stu-id="d2a04-150">The response model for the get Dsc node configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, string nodeConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, string nodeConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IDscNodeConfigurationOperations, resourceGroupName As String, automationAccount As String, nodeConfigurationName As String) As Task(Of DscNodeConfigurationGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, nodeConfigurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2a04-151">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="d2a04-151">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d2a04-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-152">Required.</span></span> <span data-ttu-id="d2a04-153">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="d2a04-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d2a04-154">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-154">Required.</span></span> <span data-ttu-id="d2a04-155">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="d2a04-155">The automation account name.</span></span>
            </param>
        <param name="nodeConfigurationName">
            <span data-ttu-id="d2a04-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-156">Required.</span></span> <span data-ttu-id="d2a04-157">Der Konfigurationsname der Dsc-Knoten.</span><span class="sxs-lookup"><span data-stu-id="d2a04-157">The Dsc node configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2a04-158">Abrufen der Dsc-Knotenkonfigurationen durch Konfiguration des Knotens an.</span><span class="sxs-lookup"><span data-stu-id="d2a04-158">Retrieve the Dsc node configurations by node configuration.</span></span>  <span data-ttu-id="d2a04-159">(siehe http://aka.ms/azureautomationsdk/dscnodeconfigurations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="d2a04-159">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d2a04-160">Das Antwort-Modell für die Get-Konfigurationsvorgang für Dsc-Knoten.</span><span class="sxs-lookup"><span data-stu-id="d2a04-160">The response model for the get Dsc node configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse List (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse List(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.List(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDscNodeConfigurationOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodeConfigurationListParameters) As DscNodeConfigurationListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.List (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2a04-161">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="d2a04-161">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d2a04-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-162">Required.</span></span> <span data-ttu-id="d2a04-163">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="d2a04-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d2a04-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-164">Required.</span></span> <span data-ttu-id="d2a04-165">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="d2a04-165">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d2a04-166">Optional.</span><span class="sxs-lookup"><span data-stu-id="d2a04-166">Optional.</span></span> <span data-ttu-id="d2a04-167">Die Parameter für die Liste zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="d2a04-167">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2a04-168">Eine Liste der dsc-Knotenkonfigurationen abzurufen.</span><span class="sxs-lookup"><span data-stu-id="d2a04-168">Retrieve a list of dsc node configurations.</span></span>  <span data-ttu-id="d2a04-169">(siehe http://aka.ms/azureautomationsdk/dscnodeconfigurations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="d2a04-169">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d2a04-170">Das Antwort-Modell für die Liste Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d2a04-170">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDscNodeConfigurationOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodeConfigurationListParameters) As Task(Of DscNodeConfigurationListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2a04-171">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="d2a04-171">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d2a04-172">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-172">Required.</span></span> <span data-ttu-id="d2a04-173">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="d2a04-173">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d2a04-174">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-174">Required.</span></span> <span data-ttu-id="d2a04-175">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="d2a04-175">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d2a04-176">Optional.</span><span class="sxs-lookup"><span data-stu-id="d2a04-176">Optional.</span></span> <span data-ttu-id="d2a04-177">Die Parameter für die Liste zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="d2a04-177">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2a04-178">Eine Liste der dsc-Knotenkonfigurationen abzurufen.</span><span class="sxs-lookup"><span data-stu-id="d2a04-178">Retrieve a list of dsc node configurations.</span></span>  <span data-ttu-id="d2a04-179">(siehe http://aka.ms/azureautomationsdk/dscnodeconfigurations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="d2a04-179">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d2a04-180">Das Antwort-Modell für die Liste Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d2a04-180">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse ListNext (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse ListNext(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDscNodeConfigurationOperations, nextLink As String) As DscNodeConfigurationListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2a04-181">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="d2a04-181">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="d2a04-182">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-182">Required.</span></span> <span data-ttu-id="d2a04-183">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="d2a04-183">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2a04-184">Abgerufen Sie weitere Liste der dsc-Knoten Configrations werden.</span><span class="sxs-lookup"><span data-stu-id="d2a04-184">Retrieve next list of dsc node configrations.</span></span>  <span data-ttu-id="d2a04-185">(siehe http://aka.ms/azureautomationsdk/dscnodeconfigurations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="d2a04-185">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d2a04-186">Das Antwort-Modell für die Liste Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d2a04-186">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDscNodeConfigurationOperations, nextLink As String) As Task(Of DscNodeConfigurationListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2a04-187">Verweis auf die Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="d2a04-187">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="d2a04-188">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d2a04-188">Required.</span></span> <span data-ttu-id="d2a04-189">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="d2a04-189">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2a04-190">Abgerufen Sie weitere Liste der dsc-Knoten Configrations werden.</span><span class="sxs-lookup"><span data-stu-id="d2a04-190">Retrieve next list of dsc node configrations.</span></span>  <span data-ttu-id="d2a04-191">(siehe http://aka.ms/azureautomationsdk/dscnodeconfigurations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="d2a04-191">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d2a04-192">Das Antwort-Modell für die Liste Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d2a04-192">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>