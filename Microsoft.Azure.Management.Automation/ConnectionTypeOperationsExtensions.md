<Type Name="ConnectionTypeOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ConnectionTypeOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ConnectionTypeOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ConnectionTypeOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ConnectionTypeOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IConnectionTypeOperations, resourceGroupName As String, automationAccount As String, parameters As ConnectionTypeCreateOrUpdateParameters) As ConnectionTypeCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string * string * Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="aa6c3-101">Verweis auf die Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-101">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="aa6c3-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-102">Required.</span></span> <span data-ttu-id="aa6c3-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="aa6c3-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="aa6c3-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-104">Required.</span></span> <span data-ttu-id="aa6c3-105">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="aa6c3-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-106">Required.</span></span> <span data-ttu-id="aa6c3-107">Die Parameter für den Verbindungstyp CREATE- oder Update zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-107">The parameters supplied to the create or update connectiontype operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="aa6c3-108">Erstellen Sie einen Verbindungstyp.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-108">Create a connectiontype.</span></span>  <span data-ttu-id="aa6c3-109">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="aa6c3-109">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="aa6c3-110">Das Antwort-Modell für den Vorgang erstellen oder aktualisieren Verbindung Typ.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-110">The response model for the create or update connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IConnectionTypeOperations, resourceGroupName As String, automationAccount As String, parameters As ConnectionTypeCreateOrUpdateParameters) As Task(Of ConnectionTypeCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string * string * Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="aa6c3-111">Verweis auf die Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-111">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="aa6c3-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-112">Required.</span></span> <span data-ttu-id="aa6c3-113">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="aa6c3-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="aa6c3-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-114">Required.</span></span> <span data-ttu-id="aa6c3-115">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="aa6c3-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-116">Required.</span></span> <span data-ttu-id="aa6c3-117">Die Parameter für den Verbindungstyp CREATE- oder Update zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-117">The parameters supplied to the create or update connectiontype operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="aa6c3-118">Erstellen Sie einen Verbindungstyp.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-118">Create a connectiontype.</span></span>  <span data-ttu-id="aa6c3-119">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="aa6c3-119">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="aa6c3-120">Das Antwort-Modell für den Vorgang erstellen oder aktualisieren Verbindung Typ.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-120">The response model for the create or update connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, string connectionTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, string connectionTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IConnectionTypeOperations, resourceGroupName As String, automationAccount As String, connectionTypeName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, connectionTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="connectionTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="aa6c3-121">Verweis auf die Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-121">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="aa6c3-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-122">Required.</span></span> <span data-ttu-id="aa6c3-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="aa6c3-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="aa6c3-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-124">Required.</span></span> <span data-ttu-id="aa6c3-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-125">The automation account name.</span></span>
            </param>
        <param name="connectionTypeName">
            <span data-ttu-id="aa6c3-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-126">Required.</span></span> <span data-ttu-id="aa6c3-127">Der Name der Verbindungstyp.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-127">The name of connectiontype.</span></span>
            </param>
        <summary>
            <span data-ttu-id="aa6c3-128">Löschen Sie den Verbindungstyp an.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-128">Delete the connectiontype.</span></span>  <span data-ttu-id="aa6c3-129">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="aa6c3-129">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="aa6c3-130">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, string connectionTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, string connectionTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IConnectionTypeOperations, resourceGroupName As String, automationAccount As String, connectionTypeName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, connectionTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="connectionTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="aa6c3-131">Verweis auf die Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-131">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="aa6c3-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-132">Required.</span></span> <span data-ttu-id="aa6c3-133">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="aa6c3-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="aa6c3-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-134">Required.</span></span> <span data-ttu-id="aa6c3-135">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-135">The automation account name.</span></span>
            </param>
        <param name="connectionTypeName">
            <span data-ttu-id="aa6c3-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-136">Required.</span></span> <span data-ttu-id="aa6c3-137">Der Name der Verbindungstyp.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-137">The name of connectiontype.</span></span>
            </param>
        <summary>
            <span data-ttu-id="aa6c3-138">Löschen Sie den Verbindungstyp an.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-138">Delete the connectiontype.</span></span>  <span data-ttu-id="aa6c3-139">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="aa6c3-139">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="aa6c3-140">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse Get (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, string connectionTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse Get(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, string connectionTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IConnectionTypeOperations, resourceGroupName As String, automationAccount As String, connectionTypeName As String) As ConnectionTypeGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.Get (operations, resourceGroupName, automationAccount, connectionTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="connectionTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="aa6c3-141">Verweis auf die Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-141">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="aa6c3-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-142">Required.</span></span> <span data-ttu-id="aa6c3-143">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="aa6c3-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="aa6c3-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-144">Required.</span></span> <span data-ttu-id="aa6c3-145">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-145">The automation account name.</span></span>
            </param>
        <param name="connectionTypeName">
            <span data-ttu-id="aa6c3-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-146">Required.</span></span> <span data-ttu-id="aa6c3-147">Der Name der Verbindungstyp.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-147">The name of connectiontype.</span></span>
            </param>
        <summary>
            <span data-ttu-id="aa6c3-148">Rufen Sie den Verbindungstyp Verbindungstyp namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-148">Retrieve the connectiontype identified by connectiontype name.</span></span>
            <span data-ttu-id="aa6c3-149">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="aa6c3-149">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="aa6c3-150">Das Antwort-Modell für den Abrufvorgang für Verbindung Typ.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-150">The response model for the get connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, string connectionTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, string connectionTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IConnectionTypeOperations, resourceGroupName As String, automationAccount As String, connectionTypeName As String) As Task(Of ConnectionTypeGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, connectionTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="connectionTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="aa6c3-151">Verweis auf die Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-151">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="aa6c3-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-152">Required.</span></span> <span data-ttu-id="aa6c3-153">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="aa6c3-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="aa6c3-154">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-154">Required.</span></span> <span data-ttu-id="aa6c3-155">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-155">The automation account name.</span></span>
            </param>
        <param name="connectionTypeName">
            <span data-ttu-id="aa6c3-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-156">Required.</span></span> <span data-ttu-id="aa6c3-157">Der Name der Verbindungstyp.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-157">The name of connectiontype.</span></span>
            </param>
        <summary>
            <span data-ttu-id="aa6c3-158">Rufen Sie den Verbindungstyp Verbindungstyp namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-158">Retrieve the connectiontype identified by connectiontype name.</span></span>
            <span data-ttu-id="aa6c3-159">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="aa6c3-159">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="aa6c3-160">Das Antwort-Modell für den Abrufvorgang für Verbindung Typ.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-160">The response model for the get connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse List (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse List(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.List(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IConnectionTypeOperations, resourceGroupName As String, automationAccount As String) As ConnectionTypeListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.List (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="aa6c3-161">Verweis auf die Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-161">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="aa6c3-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-162">Required.</span></span> <span data-ttu-id="aa6c3-163">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="aa6c3-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="aa6c3-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-164">Required.</span></span> <span data-ttu-id="aa6c3-165">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-165">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="aa6c3-166">Eine Liste der Connectiontypes abzurufen.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-166">Retrieve a list of connectiontypes.</span></span>  <span data-ttu-id="aa6c3-167">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="aa6c3-167">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="aa6c3-168">Das Antwort-Modell für den Typ des auflistungsvorgangs-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-168">The response model for the list connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IConnectionTypeOperations, resourceGroupName As String, automationAccount As String) As Task(Of ConnectionTypeListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="aa6c3-169">Verweis auf die Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-169">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="aa6c3-170">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-170">Required.</span></span> <span data-ttu-id="aa6c3-171">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="aa6c3-171">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="aa6c3-172">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-172">Required.</span></span> <span data-ttu-id="aa6c3-173">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-173">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="aa6c3-174">Eine Liste der Connectiontypes abzurufen.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-174">Retrieve a list of connectiontypes.</span></span>  <span data-ttu-id="aa6c3-175">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="aa6c3-175">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="aa6c3-176">Das Antwort-Modell für den Typ des auflistungsvorgangs-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-176">The response model for the list connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse ListNext (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse ListNext(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IConnectionTypeOperations, nextLink As String) As ConnectionTypeListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="aa6c3-177">Verweis auf die Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-177">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="aa6c3-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-178">Required.</span></span> <span data-ttu-id="aa6c3-179">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-179">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="aa6c3-180">Abgerufen Sie weitere Liste der Connectiontypes werden.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-180">Retrieve next list of connectiontypes.</span></span>  <span data-ttu-id="aa6c3-181">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="aa6c3-181">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="aa6c3-182">Das Antwort-Modell für den Typ des auflistungsvorgangs-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-182">The response model for the list connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IConnectionTypeOperations, nextLink As String) As Task(Of ConnectionTypeListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="aa6c3-183">Verweis auf die Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-183">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="aa6c3-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-184">Required.</span></span> <span data-ttu-id="aa6c3-185">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-185">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="aa6c3-186">Abgerufen Sie weitere Liste der Connectiontypes werden.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-186">Retrieve next list of connectiontypes.</span></span>  <span data-ttu-id="aa6c3-187">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="aa6c3-187">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="aa6c3-188">Das Antwort-Modell für den Typ des auflistungsvorgangs-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="aa6c3-188">The response model for the list connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>