<Type Name="CertificatesOperationsExtensions" FullName="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CertificatesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CertificatesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CertificatesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CertificatesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b4061-101">Erweiterungsmethoden für CertificatesOperations.</span><span class="sxs-lookup"><span data-stu-id="b4061-101">Extension methods for CertificatesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.CertificateDescription CreateOrUpdate (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription certificateDescription, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.CertificateDescription CreateOrUpdate(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription certificateDescription, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription * string -&gt; Microsoft.Azure.Management.IotHub.Models.CertificateDescription" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, resourceName, certificateName, certificateDescription, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.CertificateDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateDescription" Type="Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4061-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4061-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b4061-103">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="b4061-103">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b4061-104">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="b4061-104">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="b4061-105">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="b4061-105">The name of the certificate</span></span>
            </param>
        <param name="certificateDescription">
            <span data-ttu-id="b4061-106">Der Text des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="b4061-106">The certificate body.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="b4061-107">ETag des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="b4061-107">ETag of the Certificate.</span></span> <span data-ttu-id="b4061-108">Geben Sie zum Erstellen eines neuen Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="b4061-108">Do not specify for creating a brand new certificate.</span></span> <span data-ttu-id="b4061-109">Zum Aktualisieren eines vorhandenen Zertifikats erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b4061-109">Required to update an existing certificate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4061-110">Hochladen des Zertifikats mit dem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="b4061-110">Upload the certificate to the IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b4061-111">Fügt die neuen oder vorhandenen Zertifikats ersetzt.</span><span class="sxs-lookup"><span data-stu-id="b4061-111">Adds new or replaces existing certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription certificateDescription, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription certificateDescription, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, resourceName, certificateName, certificateDescription, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateDescription" Type="Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4061-112">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4061-112">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b4061-113">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="b4061-113">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b4061-114">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="b4061-114">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="b4061-115">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="b4061-115">The name of the certificate</span></span>
            </param>
        <param name="certificateDescription">
            <span data-ttu-id="b4061-116">Der Text des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="b4061-116">The certificate body.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="b4061-117">ETag des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="b4061-117">ETag of the Certificate.</span></span> <span data-ttu-id="b4061-118">Geben Sie zum Erstellen eines neuen Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="b4061-118">Do not specify for creating a brand new certificate.</span></span> <span data-ttu-id="b4061-119">Zum Aktualisieren eines vorhandenen Zertifikats erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b4061-119">Required to update an existing certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b4061-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b4061-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4061-121">Hochladen des Zertifikats mit dem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="b4061-121">Upload the certificate to the IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b4061-122">Fügt die neuen oder vorhandenen Zertifikats ersetzt.</span><span class="sxs-lookup"><span data-stu-id="b4061-122">Adds new or replaces existing certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, string ifMatch);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.Delete(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ICertificatesOperations, resourceGroupName As String, resourceName As String, certificateName As String, ifMatch As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.Delete (operations, resourceGroupName, resourceName, certificateName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4061-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4061-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b4061-124">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="b4061-124">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b4061-125">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="b4061-125">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="b4061-126">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="b4061-126">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="b4061-127">ETag des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="b4061-127">ETag of the Certificate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4061-128">Löschen einer X509 Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="b4061-128">Delete an X509 certificate.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="b4061-129">Löscht ein vorhandenes X509 Zertifikat oder bewirkt nichts, wenn er nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b4061-129">Deletes an existing X509 certificate or does nothing if it does not exist.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, string ifMatch, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.DeleteAsync (operations, resourceGroupName, resourceName, certificateName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4061-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4061-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b4061-131">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="b4061-131">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b4061-132">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="b4061-132">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="b4061-133">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="b4061-133">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="b4061-134">ETag des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="b4061-134">ETag of the Certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b4061-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b4061-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4061-136">Löschen einer X509 Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="b4061-136">Delete an X509 certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b4061-137">Löscht ein vorhandenes X509 Zertifikat oder bewirkt nichts, wenn er nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b4061-137">Deletes an existing X509 certificate or does nothing if it does not exist.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateVerificationCode">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription GenerateVerificationCode (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, string ifMatch);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription GenerateVerificationCode(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.GenerateVerificationCode(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateVerificationCode (operations As ICertificatesOperations, resourceGroupName As String, resourceName As String, certificateName As String, ifMatch As String) As CertificateWithNonceDescription" />
      <MemberSignature Language="F#" Value="static member GenerateVerificationCode : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.GenerateVerificationCode (operations, resourceGroupName, resourceName, certificateName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4061-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4061-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b4061-139">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="b4061-139">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b4061-140">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="b4061-140">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="b4061-141">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="b4061-141">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="b4061-142">ETag des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="b4061-142">ETag of the Certificate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4061-143">Überprüfungscode für den Nachweis des rechtmäßigen Besitzes Flusses zu generieren.</span><span class="sxs-lookup"><span data-stu-id="b4061-143">Generate verification code for proof of possession flow.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b4061-144">Generiert Überprüfungscode für den Nachweis des rechtmäßigen Besitzes Flusses.</span><span class="sxs-lookup"><span data-stu-id="b4061-144">Generates verification code for proof of possession flow.</span></span> <span data-ttu-id="b4061-145">Der Überprüfungscode dienen zum Generieren eines Zertifikats Endknoten.</span><span class="sxs-lookup"><span data-stu-id="b4061-145">The verification code will be used to generate a leaf certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateVerificationCodeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt; GenerateVerificationCodeAsync (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, string ifMatch, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt; GenerateVerificationCodeAsync(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.GenerateVerificationCodeAsync(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateVerificationCodeAsync : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.GenerateVerificationCodeAsync (operations, resourceGroupName, resourceName, certificateName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions/&lt;GenerateVerificationCodeAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4061-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4061-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b4061-147">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="b4061-147">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b4061-148">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="b4061-148">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="b4061-149">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="b4061-149">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="b4061-150">ETag des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="b4061-150">ETag of the Certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b4061-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b4061-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4061-152">Überprüfungscode für den Nachweis des rechtmäßigen Besitzes Flusses zu generieren.</span><span class="sxs-lookup"><span data-stu-id="b4061-152">Generate verification code for proof of possession flow.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b4061-153">Generiert Überprüfungscode für den Nachweis des rechtmäßigen Besitzes Flusses.</span><span class="sxs-lookup"><span data-stu-id="b4061-153">Generates verification code for proof of possession flow.</span></span> <span data-ttu-id="b4061-154">Der Überprüfungscode dienen zum Generieren eines Zertifikats Endknoten.</span><span class="sxs-lookup"><span data-stu-id="b4061-154">The verification code will be used to generate a leaf certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.CertificateDescription Get (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.CertificateDescription Get(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.Get(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ICertificatesOperations, resourceGroupName As String, resourceName As String, certificateName As String) As CertificateDescription" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.CertificateDescription" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.Get (operations, resourceGroupName, resourceName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.CertificateDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4061-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4061-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b4061-156">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="b4061-156">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b4061-157">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="b4061-157">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="b4061-158">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="b4061-158">The name of the certificate</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4061-159">Abrufen des Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="b4061-159">Get the certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b4061-160">Gibt das Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="b4061-160">Returns the certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt; GetAsync (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt; GetAsync(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.GetAsync(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.GetAsync (operations, resourceGroupName, resourceName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4061-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4061-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b4061-162">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="b4061-162">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b4061-163">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="b4061-163">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="b4061-164">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="b4061-164">The name of the certificate</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b4061-165">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b4061-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4061-166">Abrufen des Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="b4061-166">Get the certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b4061-167">Gibt das Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="b4061-167">Returns the certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByIotHub">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.CertificateListDescription ListByIotHub (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.CertificateListDescription ListByIotHub(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.ListByIotHub(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByIotHub (operations As ICertificatesOperations, resourceGroupName As String, resourceName As String) As CertificateListDescription" />
      <MemberSignature Language="F#" Value="static member ListByIotHub : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.CertificateListDescription" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.ListByIotHub (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.CertificateListDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4061-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4061-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b4061-169">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="b4061-169">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b4061-170">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="b4061-170">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4061-171">Rufen Sie die Zertifikatliste.</span><span class="sxs-lookup"><span data-stu-id="b4061-171">Get the certificate list.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b4061-172">Gibt die Liste der Zertifikate.</span><span class="sxs-lookup"><span data-stu-id="b4061-172">Returns the list of certificates.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByIotHubAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt; ListByIotHubAsync (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt; ListByIotHubAsync(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.ListByIotHubAsync(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByIotHubAsync : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.ListByIotHubAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions/&lt;ListByIotHubAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4061-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4061-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b4061-174">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="b4061-174">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b4061-175">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="b4061-175">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b4061-176">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b4061-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4061-177">Rufen Sie die Zertifikatliste.</span><span class="sxs-lookup"><span data-stu-id="b4061-177">Get the certificate list.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b4061-178">Gibt die Liste der Zertifikate.</span><span class="sxs-lookup"><span data-stu-id="b4061-178">Returns the list of certificates.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Verify">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.CertificateDescription Verify (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription certificateVerificationBody, string ifMatch);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.CertificateDescription Verify(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription certificateVerificationBody, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.Verify(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Verify (operations As ICertificatesOperations, resourceGroupName As String, resourceName As String, certificateName As String, certificateVerificationBody As CertificateVerificationDescription, ifMatch As String) As CertificateDescription" />
      <MemberSignature Language="F#" Value="static member Verify : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription * string -&gt; Microsoft.Azure.Management.IotHub.Models.CertificateDescription" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.Verify (operations, resourceGroupName, resourceName, certificateName, certificateVerificationBody, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.CertificateDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVerificationBody" Type="Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4061-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4061-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b4061-180">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="b4061-180">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b4061-181">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="b4061-181">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="b4061-182">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="b4061-182">The name of the certificate</span></span>
            </param>
        <param name="certificateVerificationBody">
            <span data-ttu-id="b4061-183">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="b4061-183">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="b4061-184">ETag des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="b4061-184">ETag of the Certificate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4061-185">Überprüfen des Zertifikats privaten Schlüssel besitzt.</span><span class="sxs-lookup"><span data-stu-id="b4061-185">Verify certificate's private key possession.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b4061-186">Überprüft das Zertifikat privaten Schlüssel besitzt durch Bereitstellen der Blattebene des Zertifikats durch das überprüft, ob vor hochgeladene Zertifikat ausgestellt.</span><span class="sxs-lookup"><span data-stu-id="b4061-186">Verifies the certificate's private key possession by providing the leaf cert issued by the verifying pre uploaded certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt; VerifyAsync (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription certificateVerificationBody, string ifMatch, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt; VerifyAsync(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription certificateVerificationBody, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.VerifyAsync(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyAsync : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.VerifyAsync (operations, resourceGroupName, resourceName, certificateName, certificateVerificationBody, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions/&lt;VerifyAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVerificationBody" Type="Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4061-187">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4061-187">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b4061-188">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="b4061-188">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b4061-189">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="b4061-189">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="b4061-190">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="b4061-190">The name of the certificate</span></span>
            </param>
        <param name="certificateVerificationBody">
            <span data-ttu-id="b4061-191">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="b4061-191">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="b4061-192">ETag des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="b4061-192">ETag of the Certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b4061-193">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b4061-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4061-194">Überprüfen des Zertifikats privaten Schlüssel besitzt.</span><span class="sxs-lookup"><span data-stu-id="b4061-194">Verify certificate's private key possession.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b4061-195">Überprüft das Zertifikat privaten Schlüssel besitzt durch Bereitstellen der Blattebene des Zertifikats durch das überprüft, ob vor hochgeladene Zertifikat ausgestellt.</span><span class="sxs-lookup"><span data-stu-id="b4061-195">Verifies the certificate's private key possession by providing the leaf cert issued by the verifying pre uploaded certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>