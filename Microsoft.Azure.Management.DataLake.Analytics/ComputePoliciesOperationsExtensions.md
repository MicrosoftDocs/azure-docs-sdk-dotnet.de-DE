<Type Name="ComputePoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ComputePoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ComputePoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ComputePoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ComputePoliciesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ae55e-101">Erweiterungsmethoden für ComputePoliciesOperations.</span><span class="sxs-lookup"><span data-stu-id="ae55e-101">Extension methods for ComputePoliciesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy CreateOrUpdate (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy CreateOrUpdate(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IComputePoliciesOperations, resourceGroupName As String, accountName As String, computePolicyName As String, parameters As ComputePolicyCreateOrUpdateParameters) As ComputePolicy" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, accountName, computePolicyName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ae55e-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ae55e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ae55e-103">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="ae55e-103">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="ae55e-104">Der Name des Data Lake Analytics-Konto hinzufügen oder ersetzen die Compute-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="ae55e-104">The name of the Data Lake Analytics account to add or replace the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="ae55e-105">Der Name der Compute-Richtlinie erstellt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="ae55e-105">The name of the compute policy to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ae55e-106">Zum Erstellen oder aktualisieren die Compute-Richtlinie angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="ae55e-106">Parameters supplied to create or update the compute policy.</span></span> <span data-ttu-id="ae55e-107">Die Max. Grad an Parallelität pro Auftrag Eigenschaft min Priorität pro Auftrag Eigenschaft oder beides muss vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="ae55e-107">The max degree of parallelism per job property, min priority per job property, or both must be present.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ae55e-108">Erstellt oder aktualisiert die angegebene Compute-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="ae55e-108">Creates or updates the specified compute policy.</span></span> <span data-ttu-id="ae55e-109">Während des Updates wird mit dieser neuen Richtlinie für die Berechnung die Compute-Richtlinie mit dem angegebenen Namen ersetzt.</span><span class="sxs-lookup"><span data-stu-id="ae55e-109">During update, the compute policy with the specified name will be replaced with this new compute policy.</span></span> <span data-ttu-id="ae55e-110">Ein Konto unterstützt höchstens 50-Richtlinien</span><span class="sxs-lookup"><span data-stu-id="ae55e-110">An account supports, at most, 50 policies</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, accountName, computePolicyName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ae55e-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ae55e-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ae55e-112">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="ae55e-112">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="ae55e-113">Der Name des Data Lake Analytics-Konto hinzufügen oder ersetzen die Compute-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="ae55e-113">The name of the Data Lake Analytics account to add or replace the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="ae55e-114">Der Name der Compute-Richtlinie erstellt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="ae55e-114">The name of the compute policy to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ae55e-115">Zum Erstellen oder aktualisieren die Compute-Richtlinie angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="ae55e-115">Parameters supplied to create or update the compute policy.</span></span> <span data-ttu-id="ae55e-116">Die Max. Grad an Parallelität pro Auftrag Eigenschaft min Priorität pro Auftrag Eigenschaft oder beides muss vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="ae55e-116">The max degree of parallelism per job property, min priority per job property, or both must be present.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ae55e-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ae55e-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ae55e-118">Erstellt oder aktualisiert die angegebene Compute-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="ae55e-118">Creates or updates the specified compute policy.</span></span> <span data-ttu-id="ae55e-119">Während des Updates wird mit dieser neuen Richtlinie für die Berechnung die Compute-Richtlinie mit dem angegebenen Namen ersetzt.</span><span class="sxs-lookup"><span data-stu-id="ae55e-119">During update, the compute policy with the specified name will be replaced with this new compute policy.</span></span> <span data-ttu-id="ae55e-120">Ein Konto unterstützt höchstens 50-Richtlinien</span><span class="sxs-lookup"><span data-stu-id="ae55e-120">An account supports, at most, 50 policies</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IComputePoliciesOperations, resourceGroupName As String, accountName As String, computePolicyName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Delete (operations, resourceGroupName, accountName, computePolicyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ae55e-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ae55e-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ae55e-122">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="ae55e-122">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="ae55e-123">Der Name des Data Lake Analytics-Kontos aus der die Compute-Richtlinie gelöscht.</span><span class="sxs-lookup"><span data-stu-id="ae55e-123">The name of the Data Lake Analytics account from which to delete the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="ae55e-124">Der Name der Compute-Richtlinie zu löschen.</span><span class="sxs-lookup"><span data-stu-id="ae55e-124">The name of the compute policy to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ae55e-125">Löscht die angegebene Compute-Richtlinie aus dem angegebenen Data Lake Analytics-Konto</span><span class="sxs-lookup"><span data-stu-id="ae55e-125">Deletes the specified compute policy from the specified Data Lake Analytics account</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, computePolicyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ae55e-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ae55e-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ae55e-127">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="ae55e-127">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="ae55e-128">Der Name des Data Lake Analytics-Kontos aus der die Compute-Richtlinie gelöscht.</span><span class="sxs-lookup"><span data-stu-id="ae55e-128">The name of the Data Lake Analytics account from which to delete the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="ae55e-129">Der Name der Compute-Richtlinie zu löschen.</span><span class="sxs-lookup"><span data-stu-id="ae55e-129">The name of the compute policy to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ae55e-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ae55e-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ae55e-131">Löscht die angegebene Compute-Richtlinie aus dem angegebenen Data Lake Analytics-Konto</span><span class="sxs-lookup"><span data-stu-id="ae55e-131">Deletes the specified compute policy from the specified Data Lake Analytics account</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy Get (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy Get(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IComputePoliciesOperations, resourceGroupName As String, accountName As String, computePolicyName As String) As ComputePolicy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Get (operations, resourceGroupName, accountName, computePolicyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ae55e-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ae55e-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ae55e-133">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="ae55e-133">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="ae55e-134">Der Name des Data Lake Analytics-Kontos aus der zum Abrufen der Compute-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="ae55e-134">The name of the Data Lake Analytics account from which to get the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="ae55e-135">Der Name der abzurufenden Compute-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="ae55e-135">The name of the compute policy to retrieve.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ae55e-136">Ruft die angegebene Data Lake Analytics-Compute-Richtlinie ab.</span><span class="sxs-lookup"><span data-stu-id="ae55e-136">Gets the specified Data Lake Analytics compute policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, computePolicyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ae55e-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ae55e-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ae55e-138">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="ae55e-138">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="ae55e-139">Der Name des Data Lake Analytics-Kontos aus der zum Abrufen der Compute-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="ae55e-139">The name of the Data Lake Analytics account from which to get the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="ae55e-140">Der Name der abzurufenden Compute-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="ae55e-140">The name of the compute policy to retrieve.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ae55e-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ae55e-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ae55e-142">Ruft die angegebene Data Lake Analytics-Compute-Richtlinie ab.</span><span class="sxs-lookup"><span data-stu-id="ae55e-142">Gets the specified Data Lake Analytics compute policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; ListByAccount (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; ListByAccount(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccount(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccount (operations As IComputePoliciesOperations, resourceGroupName As String, accountName As String) As IPage(Of ComputePolicy)" />
      <MemberSignature Language="F#" Value="static member ListByAccount : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccount (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ae55e-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ae55e-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ae55e-144">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="ae55e-144">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="ae55e-145">Der Name des Data Lake Analytics-Konto, von dem die Compute-Richtlinien abgerufen.</span><span class="sxs-lookup"><span data-stu-id="ae55e-145">The name of the Data Lake Analytics account from which to get the compute policies.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ae55e-146">Listet die Data Lake Analytics berechnen Richtlinien in das angegebene Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="ae55e-146">Lists the Data Lake Analytics compute policies within the specified Data Lake Analytics account.</span></span> <span data-ttu-id="ae55e-147">Ein Konto unterstützt höchstens 50-Richtlinien</span><span class="sxs-lookup"><span data-stu-id="ae55e-147">An account supports, at most, 50 policies</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; ListByAccountAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; ListByAccountAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;ListByAccountAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ae55e-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ae55e-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ae55e-149">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="ae55e-149">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="ae55e-150">Der Name des Data Lake Analytics-Konto, von dem die Compute-Richtlinien abgerufen.</span><span class="sxs-lookup"><span data-stu-id="ae55e-150">The name of the Data Lake Analytics account from which to get the compute policies.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ae55e-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ae55e-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ae55e-152">Listet die Data Lake Analytics berechnen Richtlinien in das angegebene Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="ae55e-152">Lists the Data Lake Analytics compute policies within the specified Data Lake Analytics account.</span></span> <span data-ttu-id="ae55e-153">Ein Konto unterstützt höchstens 50-Richtlinien</span><span class="sxs-lookup"><span data-stu-id="ae55e-153">An account supports, at most, 50 policies</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; ListByAccountNext (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; ListByAccountNext(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountNext(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccountNext (operations As IComputePoliciesOperations, nextPageLink As String) As IPage(Of ComputePolicy)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNext : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ae55e-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ae55e-154">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ae55e-155">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ae55e-155">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ae55e-156">Listet die Data Lake Analytics berechnen Richtlinien in das angegebene Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="ae55e-156">Lists the Data Lake Analytics compute policies within the specified Data Lake Analytics account.</span></span> <span data-ttu-id="ae55e-157">Ein Konto unterstützt höchstens 50-Richtlinien</span><span class="sxs-lookup"><span data-stu-id="ae55e-157">An account supports, at most, 50 policies</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; ListByAccountNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; ListByAccountNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;ListByAccountNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ae55e-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ae55e-158">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ae55e-159">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ae55e-159">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ae55e-160">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ae55e-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ae55e-161">Listet die Data Lake Analytics berechnen Richtlinien in das angegebene Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="ae55e-161">Lists the Data Lake Analytics compute policies within the specified Data Lake Analytics account.</span></span> <span data-ttu-id="ae55e-162">Ein Konto unterstützt höchstens 50-Richtlinien</span><span class="sxs-lookup"><span data-stu-id="ae55e-162">An account supports, at most, 50 policies</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy Update (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy Update(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Update(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IComputePoliciesOperations, resourceGroupName As String, accountName As String, computePolicyName As String, Optional parameters As ComputePolicy = null) As ComputePolicy" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Update (operations, resourceGroupName, accountName, computePolicyName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ae55e-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ae55e-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ae55e-164">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="ae55e-164">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="ae55e-165">Der Name des Data Lake Analytics-Kontos, das für die Aktualisierung der Compute-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="ae55e-165">The name of the Data Lake Analytics account to which to update the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="ae55e-166">Der Name der Compute-Richtlinie aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="ae55e-166">The name of the compute policy to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ae55e-167">Parameter, die zum Aktualisieren der Compute-Richtlinie angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="ae55e-167">Parameters supplied to update the compute policy.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ae55e-168">Aktualisiert die angegebene Compute-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="ae55e-168">Updates the specified compute policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; UpdateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; UpdateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, computePolicyName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ae55e-169">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ae55e-169">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ae55e-170">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="ae55e-170">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="ae55e-171">Der Name des Data Lake Analytics-Kontos, das für die Aktualisierung der Compute-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="ae55e-171">The name of the Data Lake Analytics account to which to update the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="ae55e-172">Der Name der Compute-Richtlinie aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="ae55e-172">The name of the compute policy to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ae55e-173">Parameter, die zum Aktualisieren der Compute-Richtlinie angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="ae55e-173">Parameters supplied to update the compute policy.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ae55e-174">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ae55e-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ae55e-175">Aktualisiert die angegebene Compute-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="ae55e-175">Updates the specified compute policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>