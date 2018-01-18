<Type Name="CertificateOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CertificateOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CertificateOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CertificateOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CertificateOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="89ec8-101">Erweiterungsmethoden für CertificateOperations.</span><span class="sxs-lookup"><span data-stu-id="89ec8-101">Extension methods for CertificateOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate BeginCreate (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate BeginCreate(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginCreate(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String, parameters As CertificateCreateOrUpdateParameters, Optional ifMatch As String = null, Optional ifNoneMatch As String = null) As Certificate" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginCreate (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89ec8-103">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="89ec8-103">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="89ec8-104">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-104">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="89ec8-105">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-105">The identifier for the certificate.</span></span> <span data-ttu-id="89ec8-106">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-106">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="89ec8-107">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="89ec8-107">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="89ec8-108">Zusätzliche Parameter für die zertifikaterstellung.</span><span class="sxs-lookup"><span data-stu-id="89ec8-108">Additional parameters for certificate creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="89ec8-109">Die entitätszustandsversion (ETag) das Zertifikat zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="89ec8-109">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="89ec8-110">Der Wert "\*" können verwendet werden, um die Operation angewendet werden, wenn das Zertifikat bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="89ec8-110">A value of "\*" can be used to apply the operation only if the certificate already exists.</span></span> <span data-ttu-id="89ec8-111">Wenn nicht angegeben, wird dieser Vorgang immer angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="89ec8-111">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="89ec8-112">Legen Sie auf "\*" um ein neues Zertifikat erstellt werden, sondern um zu verhindern, aktualisieren ein vorhandenes Zertifikat zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-112">Set to '\*' to allow a new certificate to be created, but to prevent updating an existing certificate.</span></span> <span data-ttu-id="89ec8-113">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="89ec8-113">Other values will be ignored.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-114">Erstellt ein neues Zertifikat in das angegebene Konto an.</span><span class="sxs-lookup"><span data-stu-id="89ec8-114">Creates a new certificate inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; BeginCreateAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; BeginCreateAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;BeginCreateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89ec8-116">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="89ec8-116">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="89ec8-117">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-117">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="89ec8-118">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-118">The identifier for the certificate.</span></span> <span data-ttu-id="89ec8-119">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-119">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="89ec8-120">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="89ec8-120">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="89ec8-121">Zusätzliche Parameter für die zertifikaterstellung.</span><span class="sxs-lookup"><span data-stu-id="89ec8-121">Additional parameters for certificate creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="89ec8-122">Die entitätszustandsversion (ETag) das Zertifikat zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="89ec8-122">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="89ec8-123">Der Wert "\*" können verwendet werden, um die Operation angewendet werden, wenn das Zertifikat bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="89ec8-123">A value of "\*" can be used to apply the operation only if the certificate already exists.</span></span> <span data-ttu-id="89ec8-124">Wenn nicht angegeben, wird dieser Vorgang immer angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="89ec8-124">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="89ec8-125">Legen Sie auf "\*" um ein neues Zertifikat erstellt werden, sondern um zu verhindern, aktualisieren ein vorhandenes Zertifikat zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-125">Set to '\*' to allow a new certificate to be created, but to prevent updating an existing certificate.</span></span> <span data-ttu-id="89ec8-126">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="89ec8-126">Other values will be ignored.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="89ec8-127">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="89ec8-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-128">Erstellt ein neues Zertifikat in das angegebene Konto an.</span><span class="sxs-lookup"><span data-stu-id="89ec8-128">Creates a new certificate inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders BeginDelete (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders BeginDelete(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String) As CertificateDeleteHeaders" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginDelete (operations, resourceGroupName, accountName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-129">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89ec8-130">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="89ec8-130">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="89ec8-131">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-131">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="89ec8-132">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-132">The identifier for the certificate.</span></span> <span data-ttu-id="89ec8-133">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-133">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="89ec8-134">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="89ec8-134">For example SHA1-a3d1c5.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-135">Löscht das angegebene Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-135">Deletes the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, accountName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;BeginDeleteAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89ec8-137">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="89ec8-137">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="89ec8-138">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-138">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="89ec8-139">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-139">The identifier for the certificate.</span></span> <span data-ttu-id="89ec8-140">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-140">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="89ec8-141">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="89ec8-141">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="89ec8-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="89ec8-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-143">Löscht das angegebene Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-143">Deletes the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletion">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate CancelDeletion (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate CancelDeletion(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CancelDeletion(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CancelDeletion (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String) As Certificate" />
      <MemberSignature Language="F#" Value="static member CancelDeletion : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CancelDeletion (operations, resourceGroupName, accountName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89ec8-145">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="89ec8-145">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="89ec8-146">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-146">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="89ec8-147">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-147">The identifier for the certificate.</span></span> <span data-ttu-id="89ec8-148">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-148">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="89ec8-149">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="89ec8-149">For example SHA1-a3d1c5.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-150">Bricht einen fehlerhaften Löschvorgang eines Zertifikats aus dem angegebenen Konto ab.</span><span class="sxs-lookup"><span data-stu-id="89ec8-150">Cancels a failed deletion of a certificate from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="89ec8-151">Wenn Sie versuchen, löschen ein Zertifikat, das von einem Pool verwendet wird oder compute-Knoten, ändert den Status des Zertifikats in DeleteFailed aus.</span><span class="sxs-lookup"><span data-stu-id="89ec8-151">If you try to delete a certificate that is being used by a pool or compute node, the status of the certificate changes to deleteFailed.</span></span> <span data-ttu-id="89ec8-152">Wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten, können Sie diesen Vorgang verwenden, um den Status des Zertifikats erneut auf aktiv festzulegen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-152">If you decide that you want to continue using the certificate, you can use this operation to set the status of the certificate back to active.</span></span> <span data-ttu-id="89ec8-153">Wenn Sie das Zertifikat löschen möchten, müssen Sie nicht, diesen Vorgang auszuführen, nach dem fehlerhaften Löschvorgang.</span><span class="sxs-lookup"><span data-stu-id="89ec8-153">If you intend to delete the certificate, you do not need to run this operation after the deletion failed.</span></span> <span data-ttu-id="89ec8-154">Sie müssen sicherstellen, dass das Zertifikat nicht von Ressourcen verwendet wird, und klicken Sie dann Sie es beim Löschen des Zertifikats versuchen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-154">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; CancelDeletionAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; CancelDeletionAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CancelDeletionAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelDeletionAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CancelDeletionAsync (operations, resourceGroupName, accountName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;CancelDeletionAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89ec8-156">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="89ec8-156">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="89ec8-157">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-157">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="89ec8-158">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-158">The identifier for the certificate.</span></span> <span data-ttu-id="89ec8-159">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-159">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="89ec8-160">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="89ec8-160">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="89ec8-161">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="89ec8-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-162">Bricht einen fehlerhaften Löschvorgang eines Zertifikats aus dem angegebenen Konto ab.</span><span class="sxs-lookup"><span data-stu-id="89ec8-162">Cancels a failed deletion of a certificate from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="89ec8-163">Wenn Sie versuchen, löschen ein Zertifikat, das von einem Pool verwendet wird oder compute-Knoten, ändert den Status des Zertifikats in DeleteFailed aus.</span><span class="sxs-lookup"><span data-stu-id="89ec8-163">If you try to delete a certificate that is being used by a pool or compute node, the status of the certificate changes to deleteFailed.</span></span> <span data-ttu-id="89ec8-164">Wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten, können Sie diesen Vorgang verwenden, um den Status des Zertifikats erneut auf aktiv festzulegen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-164">If you decide that you want to continue using the certificate, you can use this operation to set the status of the certificate back to active.</span></span> <span data-ttu-id="89ec8-165">Wenn Sie das Zertifikat löschen möchten, müssen Sie nicht, diesen Vorgang auszuführen, nach dem fehlerhaften Löschvorgang.</span><span class="sxs-lookup"><span data-stu-id="89ec8-165">If you intend to delete the certificate, you do not need to run this operation after the deletion failed.</span></span> <span data-ttu-id="89ec8-166">Sie müssen sicherstellen, dass das Zertifikat nicht von Ressourcen verwendet wird, und klicken Sie dann Sie es beim Löschen des Zertifikats versuchen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-166">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate Create (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate Create(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Create(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String, parameters As CertificateCreateOrUpdateParameters, Optional ifMatch As String = null, Optional ifNoneMatch As String = null) As Certificate" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Create (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89ec8-168">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="89ec8-168">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="89ec8-169">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-169">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="89ec8-170">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-170">The identifier for the certificate.</span></span> <span data-ttu-id="89ec8-171">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-171">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="89ec8-172">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="89ec8-172">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="89ec8-173">Zusätzliche Parameter für die zertifikaterstellung.</span><span class="sxs-lookup"><span data-stu-id="89ec8-173">Additional parameters for certificate creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="89ec8-174">Die entitätszustandsversion (ETag) das Zertifikat zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="89ec8-174">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="89ec8-175">Der Wert "\*" können verwendet werden, um die Operation angewendet werden, wenn das Zertifikat bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="89ec8-175">A value of "\*" can be used to apply the operation only if the certificate already exists.</span></span> <span data-ttu-id="89ec8-176">Wenn nicht angegeben, wird dieser Vorgang immer angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="89ec8-176">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="89ec8-177">Legen Sie auf "\*" um ein neues Zertifikat erstellt werden, sondern um zu verhindern, aktualisieren ein vorhandenes Zertifikat zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-177">Set to '\*' to allow a new certificate to be created, but to prevent updating an existing certificate.</span></span> <span data-ttu-id="89ec8-178">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="89ec8-178">Other values will be ignored.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-179">Erstellt ein neues Zertifikat in das angegebene Konto an.</span><span class="sxs-lookup"><span data-stu-id="89ec8-179">Creates a new certificate inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; CreateAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; CreateAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-180">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-180">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89ec8-181">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="89ec8-181">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="89ec8-182">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-182">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="89ec8-183">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-183">The identifier for the certificate.</span></span> <span data-ttu-id="89ec8-184">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-184">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="89ec8-185">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="89ec8-185">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="89ec8-186">Zusätzliche Parameter für die zertifikaterstellung.</span><span class="sxs-lookup"><span data-stu-id="89ec8-186">Additional parameters for certificate creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="89ec8-187">Die entitätszustandsversion (ETag) das Zertifikat zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="89ec8-187">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="89ec8-188">Der Wert "\*" können verwendet werden, um die Operation angewendet werden, wenn das Zertifikat bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="89ec8-188">A value of "\*" can be used to apply the operation only if the certificate already exists.</span></span> <span data-ttu-id="89ec8-189">Wenn nicht angegeben, wird dieser Vorgang immer angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="89ec8-189">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="89ec8-190">Legen Sie auf "\*" um ein neues Zertifikat erstellt werden, sondern um zu verhindern, aktualisieren ein vorhandenes Zertifikat zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-190">Set to '\*' to allow a new certificate to be created, but to prevent updating an existing certificate.</span></span> <span data-ttu-id="89ec8-191">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="89ec8-191">Other values will be ignored.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="89ec8-192">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="89ec8-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-193">Erstellt ein neues Zertifikat in das angegebene Konto an.</span><span class="sxs-lookup"><span data-stu-id="89ec8-193">Creates a new certificate inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders Delete (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders Delete(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Delete(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String) As CertificateDeleteHeaders" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Delete (operations, resourceGroupName, accountName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-194">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-194">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89ec8-195">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="89ec8-195">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="89ec8-196">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-196">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="89ec8-197">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-197">The identifier for the certificate.</span></span> <span data-ttu-id="89ec8-198">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-198">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="89ec8-199">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="89ec8-199">For example SHA1-a3d1c5.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-200">Löscht das angegebene Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-200">Deletes the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-201">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89ec8-202">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="89ec8-202">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="89ec8-203">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-203">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="89ec8-204">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-204">The identifier for the certificate.</span></span> <span data-ttu-id="89ec8-205">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-205">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="89ec8-206">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="89ec8-206">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="89ec8-207">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="89ec8-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-208">Löscht das angegebene Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-208">Deletes the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate Get (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate Get(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Get(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String) As Certificate" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Get (operations, resourceGroupName, accountName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-209">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-209">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89ec8-210">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="89ec8-210">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="89ec8-211">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-211">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="89ec8-212">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-212">The identifier for the certificate.</span></span> <span data-ttu-id="89ec8-213">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-213">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="89ec8-214">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="89ec8-214">For example SHA1-a3d1c5.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-215">Ruft Informationen über das angegebene Zertifikat ab.</span><span class="sxs-lookup"><span data-stu-id="89ec8-215">Gets information about the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; GetAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; GetAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.GetAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-216">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-216">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89ec8-217">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="89ec8-217">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="89ec8-218">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-218">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="89ec8-219">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-219">The identifier for the certificate.</span></span> <span data-ttu-id="89ec8-220">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-220">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="89ec8-221">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="89ec8-221">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="89ec8-222">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="89ec8-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-223">Ruft Informationen über das angegebene Zertifikat ab.</span><span class="sxs-lookup"><span data-stu-id="89ec8-223">Gets information about the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; ListByBatchAccount (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, string select = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; ListByBatchAccount(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, string select, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccount(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByBatchAccount (operations As ICertificateOperations, resourceGroupName As String, accountName As String, Optional maxresults As Nullable(Of Integer) = null, Optional select As String = null, Optional filter As String = null) As IPage(Of Certificate)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccount : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * Nullable&lt;int&gt; * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccount (operations, resourceGroupName, accountName, maxresults, select, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-224">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-224">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89ec8-225">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="89ec8-225">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="89ec8-226">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-226">The name of the Batch account.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="89ec8-227">Die maximale Anzahl von Elementen, die in der Antwort zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="89ec8-227">The maximum number of items to return in the response.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="89ec8-228">Durch Trennzeichen getrennte Liste von Eigenschaften, die zurückgegeben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-228">Comma separated list of properties that should be returned.</span></span> <span data-ttu-id="89ec8-229">z. B. "Eigenschaften/ProvisioningState".</span><span class="sxs-lookup"><span data-stu-id="89ec8-229">e.g. "properties/provisioningState".</span></span> <span data-ttu-id="89ec8-230">Nur die ersten Ebene unter Eigenschaften Eigenschaften / zur Auswahl gültig sind.</span><span class="sxs-lookup"><span data-stu-id="89ec8-230">Only top level properties under properties/ are valid for selection.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="89ec8-231">OData-Filterausdruck.</span><span class="sxs-lookup"><span data-stu-id="89ec8-231">OData filter expression.</span></span> <span data-ttu-id="89ec8-232">Gültige Eigenschaften für die Filterung sind "Eigenschaften/ProvisioningState", "Eigenschaften/ProvisioningStateTransitionTime", "Name".</span><span class="sxs-lookup"><span data-stu-id="89ec8-232">Valid properties for filtering are "properties/provisioningState", "properties/provisioningStateTransitionTime", "name".</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-233">Zeigt eine Liste aller Zertifikate in das angegebene Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-233">Lists all of the certificates in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt; ListByBatchAccountAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, string select = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt; ListByBatchAccountAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, string select, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * Nullable&lt;int&gt; * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountAsync (operations, resourceGroupName, accountName, maxresults, select, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;ListByBatchAccountAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-234">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-234">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89ec8-235">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="89ec8-235">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="89ec8-236">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-236">The name of the Batch account.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="89ec8-237">Die maximale Anzahl von Elementen, die in der Antwort zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="89ec8-237">The maximum number of items to return in the response.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="89ec8-238">Durch Trennzeichen getrennte Liste von Eigenschaften, die zurückgegeben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-238">Comma separated list of properties that should be returned.</span></span> <span data-ttu-id="89ec8-239">z. B. "Eigenschaften/ProvisioningState".</span><span class="sxs-lookup"><span data-stu-id="89ec8-239">e.g. "properties/provisioningState".</span></span> <span data-ttu-id="89ec8-240">Nur die ersten Ebene unter Eigenschaften Eigenschaften / zur Auswahl gültig sind.</span><span class="sxs-lookup"><span data-stu-id="89ec8-240">Only top level properties under properties/ are valid for selection.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="89ec8-241">OData-Filterausdruck.</span><span class="sxs-lookup"><span data-stu-id="89ec8-241">OData filter expression.</span></span> <span data-ttu-id="89ec8-242">Gültige Eigenschaften für die Filterung sind "Eigenschaften/ProvisioningState", "Eigenschaften/ProvisioningStateTransitionTime", "Name".</span><span class="sxs-lookup"><span data-stu-id="89ec8-242">Valid properties for filtering are "properties/provisioningState", "properties/provisioningStateTransitionTime", "name".</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="89ec8-243">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="89ec8-243">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-244">Zeigt eine Liste aller Zertifikate in das angegebene Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-244">Lists all of the certificates in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; ListByBatchAccountNext (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; ListByBatchAccountNext(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountNext(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByBatchAccountNext (operations As ICertificateOperations, nextPageLink As String) As IPage(Of Certificate)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountNext : Microsoft.Azure.Management.Batch.ICertificateOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-245">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-245">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="89ec8-246">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="89ec8-246">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-247">Zeigt eine Liste aller Zertifikate in das angegebene Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-247">Lists all of the certificates in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt; ListByBatchAccountNextAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt; ListByBatchAccountNextAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountNextAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountNextAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;ListByBatchAccountNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-248">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-248">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="89ec8-249">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="89ec8-249">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="89ec8-250">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="89ec8-250">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-251">Zeigt eine Liste aller Zertifikate in das angegebene Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-251">Lists all of the certificates in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate Update (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate Update(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Update(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String, parameters As CertificateCreateOrUpdateParameters, Optional ifMatch As String = null) As Certificate" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Update (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-252">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-252">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89ec8-253">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="89ec8-253">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="89ec8-254">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-254">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="89ec8-255">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-255">The identifier for the certificate.</span></span> <span data-ttu-id="89ec8-256">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-256">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="89ec8-257">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="89ec8-257">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="89ec8-258">Das Zertifikat zu aktualisierenden Entität.</span><span class="sxs-lookup"><span data-stu-id="89ec8-258">Certificate entity to update.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="89ec8-259">Die entitätszustandsversion (ETag) das Zertifikat zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="89ec8-259">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="89ec8-260">Dieser Wert ausgelassen oder auf festgelegt werden kann "\*" um den Vorgang ohne Bedingung anzuwenden.</span><span class="sxs-lookup"><span data-stu-id="89ec8-260">This value can be omitted or set to "\*" to apply the operation unconditionally.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-261">Aktualisiert die Eigenschaften eines vorhandenen Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="89ec8-261">Updates the properties of an existing certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; UpdateAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; UpdateAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;UpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89ec8-262">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="89ec8-262">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89ec8-263">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="89ec8-263">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="89ec8-264">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="89ec8-264">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="89ec8-265">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="89ec8-265">The identifier for the certificate.</span></span> <span data-ttu-id="89ec8-266">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="89ec8-266">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="89ec8-267">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="89ec8-267">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="89ec8-268">Das Zertifikat zu aktualisierenden Entität.</span><span class="sxs-lookup"><span data-stu-id="89ec8-268">Certificate entity to update.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="89ec8-269">Die entitätszustandsversion (ETag) das Zertifikat zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="89ec8-269">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="89ec8-270">Dieser Wert ausgelassen oder auf festgelegt werden kann "\*" um den Vorgang ohne Bedingung anzuwenden.</span><span class="sxs-lookup"><span data-stu-id="89ec8-270">This value can be omitted or set to "\*" to apply the operation unconditionally.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="89ec8-271">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="89ec8-271">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89ec8-272">Aktualisiert die Eigenschaften eines vorhandenen Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="89ec8-272">Updates the properties of an existing certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>