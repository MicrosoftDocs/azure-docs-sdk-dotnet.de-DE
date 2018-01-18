<Type Name="BatchAccountOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BatchAccountOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BatchAccountOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BatchAccountOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BatchAccountOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="246ab-101">Erweiterungsmethoden für BatchAccountOperations.</span><span class="sxs-lookup"><span data-stu-id="246ab-101">Extension methods for BatchAccountOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchAccount BeginCreate (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchAccount BeginCreate(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.BeginCreate(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String, parameters As BatchAccountCreateParameters) As BatchAccount" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccount" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.BeginCreate (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-103">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-103">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-104">Ein Name für das Batch-Konto muss innerhalb des Bereichs eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="246ab-104">A name for the Batch account which must be unique within the region.</span></span> <span data-ttu-id="246ab-105">Batch-Kontonamen müssen zwischen 3 und 24 Zeichen lang sein und müssen nur aus Ziffern und Kleinbuchstaben verwenden.</span><span class="sxs-lookup"><span data-stu-id="246ab-105">Batch account names must be between 3 and 24 characters in length and must use only numbers and lowercase letters.</span></span> <span data-ttu-id="246ab-106">Dieser Name wird als Teil der DNS-Name verwendet, der verwendet wird, auf die Batch-Dienst in der Region, in dem das Konto erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="246ab-106">This name is used as part of the DNS name that is used to access the Batch service in the region in which the account is created.</span></span> <span data-ttu-id="246ab-107">Zum Beispiel: http://accountname.region.batch.azure.com/.</span><span class="sxs-lookup"><span data-stu-id="246ab-107">For example: http://accountname.region.batch.azure.com/.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="246ab-108">Zusätzliche Parameter für die Erstellung von Benutzerkonten.</span><span class="sxs-lookup"><span data-stu-id="246ab-108">Additional parameters for account creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-109">Erstellt ein neues Batch-Konto mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="246ab-109">Creates a new Batch account with the specified parameters.</span></span> <span data-ttu-id="246ab-110">Vorhandene Konten können nicht mit dieser API aktualisiert werden, und es stattdessen mit der Update-Batch-Konto-API aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="246ab-110">Existing accounts cannot be updated with this API and should instead be updated with the Update Batch Account API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; BeginCreateAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; BeginCreateAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;BeginCreateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-112">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-112">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-113">Ein Name für das Batch-Konto muss innerhalb des Bereichs eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="246ab-113">A name for the Batch account which must be unique within the region.</span></span> <span data-ttu-id="246ab-114">Batch-Kontonamen müssen zwischen 3 und 24 Zeichen lang sein und müssen nur aus Ziffern und Kleinbuchstaben verwenden.</span><span class="sxs-lookup"><span data-stu-id="246ab-114">Batch account names must be between 3 and 24 characters in length and must use only numbers and lowercase letters.</span></span> <span data-ttu-id="246ab-115">Dieser Name wird als Teil der DNS-Name verwendet, der verwendet wird, auf die Batch-Dienst in der Region, in dem das Konto erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="246ab-115">This name is used as part of the DNS name that is used to access the Batch service in the region in which the account is created.</span></span> <span data-ttu-id="246ab-116">Zum Beispiel: http://accountname.region.batch.azure.com/.</span><span class="sxs-lookup"><span data-stu-id="246ab-116">For example: http://accountname.region.batch.azure.com/.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="246ab-117">Zusätzliche Parameter für die Erstellung von Benutzerkonten.</span><span class="sxs-lookup"><span data-stu-id="246ab-117">Additional parameters for account creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="246ab-118">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="246ab-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-119">Erstellt ein neues Batch-Konto mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="246ab-119">Creates a new Batch account with the specified parameters.</span></span> <span data-ttu-id="246ab-120">Vorhandene Konten können nicht mit dieser API aktualisiert werden, und es stattdessen mit der Update-Batch-Konto-API aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="246ab-120">Existing accounts cannot be updated with this API and should instead be updated with the Update Batch Account API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders BeginDelete (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders BeginDelete(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String) As BatchAccountDeleteHeaders" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.BeginDelete (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-122">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-122">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-123">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-123">The name of the Batch account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-124">Löscht das angegebene Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-124">Deletes the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;BeginDeleteAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-126">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-126">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-127">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-127">The name of the Batch account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="246ab-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="246ab-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-129">Löscht das angegebene Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-129">Deletes the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchAccount Create (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchAccount Create(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.Create(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String, parameters As BatchAccountCreateParameters) As BatchAccount" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccount" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.Create (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-131">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-131">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-132">Ein Name für das Batch-Konto muss innerhalb des Bereichs eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="246ab-132">A name for the Batch account which must be unique within the region.</span></span> <span data-ttu-id="246ab-133">Batch-Kontonamen müssen zwischen 3 und 24 Zeichen lang sein und müssen nur aus Ziffern und Kleinbuchstaben verwenden.</span><span class="sxs-lookup"><span data-stu-id="246ab-133">Batch account names must be between 3 and 24 characters in length and must use only numbers and lowercase letters.</span></span> <span data-ttu-id="246ab-134">Dieser Name wird als Teil der DNS-Name verwendet, der verwendet wird, auf die Batch-Dienst in der Region, in dem das Konto erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="246ab-134">This name is used as part of the DNS name that is used to access the Batch service in the region in which the account is created.</span></span> <span data-ttu-id="246ab-135">Zum Beispiel: http://accountname.region.batch.azure.com/.</span><span class="sxs-lookup"><span data-stu-id="246ab-135">For example: http://accountname.region.batch.azure.com/.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="246ab-136">Zusätzliche Parameter für die Erstellung von Benutzerkonten.</span><span class="sxs-lookup"><span data-stu-id="246ab-136">Additional parameters for account creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-137">Erstellt ein neues Batch-Konto mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="246ab-137">Creates a new Batch account with the specified parameters.</span></span> <span data-ttu-id="246ab-138">Vorhandene Konten können nicht mit dieser API aktualisiert werden, und es stattdessen mit der Update-Batch-Konto-API aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="246ab-138">Existing accounts cannot be updated with this API and should instead be updated with the Update Batch Account API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; CreateAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; CreateAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-140">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-140">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-141">Ein Name für das Batch-Konto muss innerhalb des Bereichs eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="246ab-141">A name for the Batch account which must be unique within the region.</span></span> <span data-ttu-id="246ab-142">Batch-Kontonamen müssen zwischen 3 und 24 Zeichen lang sein und müssen nur aus Ziffern und Kleinbuchstaben verwenden.</span><span class="sxs-lookup"><span data-stu-id="246ab-142">Batch account names must be between 3 and 24 characters in length and must use only numbers and lowercase letters.</span></span> <span data-ttu-id="246ab-143">Dieser Name wird als Teil der DNS-Name verwendet, der verwendet wird, auf die Batch-Dienst in der Region, in dem das Konto erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="246ab-143">This name is used as part of the DNS name that is used to access the Batch service in the region in which the account is created.</span></span> <span data-ttu-id="246ab-144">Zum Beispiel: http://accountname.region.batch.azure.com/.</span><span class="sxs-lookup"><span data-stu-id="246ab-144">For example: http://accountname.region.batch.azure.com/.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="246ab-145">Zusätzliche Parameter für die Erstellung von Benutzerkonten.</span><span class="sxs-lookup"><span data-stu-id="246ab-145">Additional parameters for account creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="246ab-146">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="246ab-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-147">Erstellt ein neues Batch-Konto mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="246ab-147">Creates a new Batch account with the specified parameters.</span></span> <span data-ttu-id="246ab-148">Vorhandene Konten können nicht mit dieser API aktualisiert werden, und es stattdessen mit der Update-Batch-Konto-API aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="246ab-148">Existing accounts cannot be updated with this API and should instead be updated with the Update Batch Account API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders Delete (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders Delete(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.Delete(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String) As BatchAccountDeleteHeaders" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.Delete (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-149">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-150">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-150">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-151">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-151">The name of the Batch account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-152">Löscht das angegebene Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-152">Deletes the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-154">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-154">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-155">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-155">The name of the Batch account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="246ab-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="246ab-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-157">Löscht das angegebene Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-157">Deletes the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchAccount Get (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchAccount Get(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.Get(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String) As BatchAccount" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccount" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.Get (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-159">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-159">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-160">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-160">The name of the Batch account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-161">Ruft Informationen über den angegebenen Batch-Konto ab.</span><span class="sxs-lookup"><span data-stu-id="246ab-161">Gets information about the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; GetAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; GetAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.GetAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-163">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-163">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-164">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-164">The name of the Batch account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="246ab-165">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="246ab-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-166">Ruft Informationen über den angegebenen Batch-Konto ab.</span><span class="sxs-lookup"><span data-stu-id="246ab-166">Gets information about the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchAccountKeys GetKeys (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchAccountKeys GetKeys(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.GetKeys(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetKeys (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String) As BatchAccountKeys" />
      <MemberSignature Language="F#" Value="static member GetKeys : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccountKeys" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.GetKeys (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchAccountKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-168">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-168">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-169">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-169">The name of the Batch account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-170">Ruft den kontoschlüssel für das angegebene Batch-Konto ab.</span><span class="sxs-lookup"><span data-stu-id="246ab-170">Gets the account keys for the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="246ab-171">Dieser Vorgang gilt nur für Batch-Konten, die mit einem PoolAllocationMode von "BatchService" erstellt.</span><span class="sxs-lookup"><span data-stu-id="246ab-171">This operation applies only to Batch accounts created with a poolAllocationMode of 'BatchService'.</span></span> <span data-ttu-id="246ab-172">Wenn der Batch-Konto mit einem PoolAllocationMode von "UserSubscription" erstellt wurde, können nicht Clients Zugriff auf Schlüssel verwenden, um zu authentifizieren, und müssen stattdessen Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="246ab-172">If the Batch account was created with a poolAllocationMode of 'UserSubscription', clients cannot use access to keys to authenticate, and must use Azure Active Directory instead.</span></span> <span data-ttu-id="246ab-173">In diesem Fall wird das Abrufen von den Schlüsseln fehl.</span><span class="sxs-lookup"><span data-stu-id="246ab-173">In this case, getting the keys will fail.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountKeys&gt; GetKeysAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccountKeys&gt; GetKeysAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.GetKeysAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeysAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountKeys&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.GetKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;GetKeysAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-174">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-174">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-175">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-175">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-176">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-176">The name of the Batch account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="246ab-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="246ab-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-178">Ruft den kontoschlüssel für das angegebene Batch-Konto ab.</span><span class="sxs-lookup"><span data-stu-id="246ab-178">Gets the account keys for the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="246ab-179">Dieser Vorgang gilt nur für Batch-Konten, die mit einem PoolAllocationMode von "BatchService" erstellt.</span><span class="sxs-lookup"><span data-stu-id="246ab-179">This operation applies only to Batch accounts created with a poolAllocationMode of 'BatchService'.</span></span> <span data-ttu-id="246ab-180">Wenn der Batch-Konto mit einem PoolAllocationMode von "UserSubscription" erstellt wurde, können nicht Clients Zugriff auf Schlüssel verwenden, um zu authentifizieren, und müssen stattdessen Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="246ab-180">If the Batch account was created with a poolAllocationMode of 'UserSubscription', clients cannot use access to keys to authenticate, and must use Azure Active Directory instead.</span></span> <span data-ttu-id="246ab-181">In diesem Fall wird das Abrufen von den Schlüsseln fehl.</span><span class="sxs-lookup"><span data-stu-id="246ab-181">In this case, getting the keys will fail.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; List (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; List(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.List(Microsoft.Azure.Management.Batch.IBatchAccountOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IBatchAccountOperations) As IPage(Of BatchAccount)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Batch.IBatchAccountOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-182">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-183">Ruft Informationen zu den Batch-Konten, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="246ab-183">Gets information about the Batch accounts associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt; ListAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt; ListAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-184">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-184">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="246ab-185">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="246ab-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-186">Ruft Informationen zu den Batch-Konten, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="246ab-186">Gets information about the Batch accounts associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; ListByResourceGroup (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; ListByResourceGroup(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IBatchAccountOperations, resourceGroupName As String) As IPage(Of BatchAccount)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-187">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-187">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-188">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-188">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-189">Ruft Informationen zu den Batch-Konten, die der angegebenen Ressourcengruppe zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="246ab-189">Gets information about the Batch accounts associated with the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-191">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-191">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="246ab-192">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="246ab-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-193">Ruft Informationen zu den Batch-Konten, die der angegebenen Ressourcengruppe zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="246ab-193">Gets information about the Batch accounts associated with the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IBatchAccountOperations, nextPageLink As String) As IPage(Of BatchAccount)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-194">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-194">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="246ab-195">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="246ab-195">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-196">Ruft Informationen zu den Batch-Konten, die der angegebenen Ressourcengruppe zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="246ab-196">Gets information about the Batch accounts associated with the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-197">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-197">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="246ab-198">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="246ab-198">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="246ab-199">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="246ab-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-200">Ruft Informationen zu den Batch-Konten, die der angegebenen Ressourcengruppe zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="246ab-200">Gets information about the Batch accounts associated with the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; ListNext (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; ListNext(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListNext(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IBatchAccountOperations, nextPageLink As String) As IPage(Of BatchAccount)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-201">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-201">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="246ab-202">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="246ab-202">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-203">Ruft Informationen zu den Batch-Konten, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="246ab-203">Gets information about the Batch accounts associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;ListNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-204">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="246ab-205">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="246ab-205">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="246ab-206">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="246ab-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-207">Ruft Informationen zu den Batch-Konten, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="246ab-207">Gets information about the Batch accounts associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchAccountKeys RegenerateKey (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Models.AccountKeyType keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchAccountKeys RegenerateKey(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype Microsoft.Azure.Management.Batch.Models.AccountKeyType keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.RegenerateKey(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Models.AccountKeyType)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKey (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String, keyName As AccountKeyType) As BatchAccountKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateKey : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Models.AccountKeyType -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccountKeys" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.RegenerateKey (operations, resourceGroupName, accountName, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchAccountKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyName" Type="Microsoft.Azure.Management.Batch.Models.AccountKeyType" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-208">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-209">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-209">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-210">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-210">The name of the Batch account.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="246ab-211">Der Typ des kontoschlüssel erneut generiert.</span><span class="sxs-lookup"><span data-stu-id="246ab-211">The type of account key to regenerate.</span></span> <span data-ttu-id="246ab-212">Folgende Werte sind möglich: 'Primary', 'Sekundären'</span><span class="sxs-lookup"><span data-stu-id="246ab-212">Possible values include: 'Primary', 'Secondary'</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-213">Generiert einen neuen Schlüssel angegebene Konto für die Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-213">Regenerates the specified account key for the Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountKeys&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Models.AccountKeyType keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccountKeys&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype Microsoft.Azure.Management.Batch.Models.AccountKeyType keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Models.AccountKeyType,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Models.AccountKeyType * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountKeys&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, accountName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyName" Type="Microsoft.Azure.Management.Batch.Models.AccountKeyType" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-214">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-215">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-215">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-216">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-216">The name of the Batch account.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="246ab-217">Der Typ des kontoschlüssel erneut generiert.</span><span class="sxs-lookup"><span data-stu-id="246ab-217">The type of account key to regenerate.</span></span> <span data-ttu-id="246ab-218">Folgende Werte sind möglich: 'Primary', 'Sekundären'</span><span class="sxs-lookup"><span data-stu-id="246ab-218">Possible values include: 'Primary', 'Secondary'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="246ab-219">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="246ab-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-220">Generiert einen neuen Schlüssel angegebene Konto für die Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-220">Regenerates the specified account key for the Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SynchronizeAutoStorageKeys">
      <MemberSignature Language="C#" Value="public static void SynchronizeAutoStorageKeys (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SynchronizeAutoStorageKeys(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.SynchronizeAutoStorageKeys(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SynchronizeAutoStorageKeys (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String)" />
      <MemberSignature Language="F#" Value="static member SynchronizeAutoStorageKeys : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.SynchronizeAutoStorageKeys (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-221">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-222">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-222">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-223">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-223">The name of the Batch account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-224">Synchronisiert die Zugriffsschlüssel für das automatische Speicherkonto für das angegebene Batch-Konto konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="246ab-224">Synchronizes access keys for the auto-storage account configured for the specified Batch account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SynchronizeAutoStorageKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SynchronizeAutoStorageKeysAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SynchronizeAutoStorageKeysAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.SynchronizeAutoStorageKeysAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SynchronizeAutoStorageKeysAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.SynchronizeAutoStorageKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;SynchronizeAutoStorageKeysAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-225">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-225">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-226">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-226">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-227">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-227">The name of the Batch account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="246ab-228">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="246ab-228">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-229">Synchronisiert die Zugriffsschlüssel für das automatische Speicherkonto für das angegebene Batch-Konto konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="246ab-229">Synchronizes access keys for the auto-storage account configured for the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchAccount Update (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchAccount Update(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.Update(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String, parameters As BatchAccountUpdateParameters) As BatchAccount" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccount" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.Update (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-230">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-230">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-231">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-231">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-232">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-232">The name of the Batch account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="246ab-233">Zusätzliche Parameter für das Konto aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="246ab-233">Additional parameters for account update.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-234">Aktualisiert die Eigenschaften eines vorhandenen Batch-Kontos.</span><span class="sxs-lookup"><span data-stu-id="246ab-234">Updates the properties of an existing Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; UpdateAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; UpdateAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="246ab-235">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="246ab-235">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="246ab-236">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="246ab-236">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="246ab-237">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="246ab-237">The name of the Batch account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="246ab-238">Zusätzliche Parameter für das Konto aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="246ab-238">Additional parameters for account update.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="246ab-239">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="246ab-239">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="246ab-240">Aktualisiert die Eigenschaften eines vorhandenen Batch-Kontos.</span><span class="sxs-lookup"><span data-stu-id="246ab-240">Updates the properties of an existing Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>