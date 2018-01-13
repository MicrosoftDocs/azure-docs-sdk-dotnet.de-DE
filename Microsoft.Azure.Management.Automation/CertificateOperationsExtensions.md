<Type Name="CertificateOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.CertificateOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CertificateOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CertificateOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.CertificateOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CertificateOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CertificateOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.ICertificateOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ICertificateOperations, resourceGroupName As String, automationAccount As String, parameters As CertificateCreateOrUpdateParameters) As CertificateCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.ICertificateOperations * string * string * Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0667e-101">Verweis auf die Microsoft.Azure.Management.Automation.ICertificateOperations.</span><span class="sxs-lookup"><span data-stu-id="0667e-101">Reference to the Microsoft.Azure.Management.Automation.ICertificateOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0667e-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-102">Required.</span></span> <span data-ttu-id="0667e-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="0667e-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="0667e-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-104">Required.</span></span> <span data-ttu-id="0667e-105">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="0667e-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0667e-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-106">Required.</span></span> <span data-ttu-id="0667e-107">Die Parameter für das Zertifikat erstellen oder Aktualisieren zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="0667e-107">The parameters supplied to the create or update certificate operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0667e-108">Erstellen Sie ein Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="0667e-108">Create a certificate.</span></span>  <span data-ttu-id="0667e-109">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="0667e-109">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0667e-110">Das Antwort-Modell für den Vorgang der Zertifikat erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="0667e-110">The response model for the create or update certificate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.ICertificateOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As ICertificateOperations, resourceGroupName As String, automationAccount As String, parameters As CertificateCreateOrUpdateParameters) As Task(Of CertificateCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.ICertificateOperations * string * string * Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0667e-111">Verweis auf die Microsoft.Azure.Management.Automation.ICertificateOperations.</span><span class="sxs-lookup"><span data-stu-id="0667e-111">Reference to the Microsoft.Azure.Management.Automation.ICertificateOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0667e-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-112">Required.</span></span> <span data-ttu-id="0667e-113">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="0667e-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="0667e-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-114">Required.</span></span> <span data-ttu-id="0667e-115">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="0667e-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0667e-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-116">Required.</span></span> <span data-ttu-id="0667e-117">Die Parameter für das Zertifikat erstellen oder Aktualisieren zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="0667e-117">The parameters supplied to the create or update certificate operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0667e-118">Erstellen Sie ein Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="0667e-118">Create a certificate.</span></span>  <span data-ttu-id="0667e-119">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="0667e-119">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0667e-120">Das Antwort-Modell für den Vorgang der Zertifikat erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="0667e-120">The response model for the create or update certificate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As ICertificateOperations, resourceGroupName As String, automationAccount As String, certificateName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0667e-121">Verweis auf die Microsoft.Azure.Management.Automation.ICertificateOperations.</span><span class="sxs-lookup"><span data-stu-id="0667e-121">Reference to the Microsoft.Azure.Management.Automation.ICertificateOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0667e-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-122">Required.</span></span> <span data-ttu-id="0667e-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="0667e-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="0667e-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-124">Required.</span></span> <span data-ttu-id="0667e-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="0667e-125">The automation account name.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="0667e-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-126">Required.</span></span> <span data-ttu-id="0667e-127">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="0667e-127">The name of certificate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0667e-128">Löschen Sie das Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="0667e-128">Delete the certificate.</span></span>  <span data-ttu-id="0667e-129">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="0667e-129">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0667e-130">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="0667e-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As ICertificateOperations, resourceGroupName As String, automationAccount As String, certificateName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.ICertificateOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0667e-131">Verweis auf die Microsoft.Azure.Management.Automation.ICertificateOperations.</span><span class="sxs-lookup"><span data-stu-id="0667e-131">Reference to the Microsoft.Azure.Management.Automation.ICertificateOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0667e-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-132">Required.</span></span> <span data-ttu-id="0667e-133">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="0667e-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="0667e-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-134">Required.</span></span> <span data-ttu-id="0667e-135">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="0667e-135">The automation account name.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="0667e-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-136">Required.</span></span> <span data-ttu-id="0667e-137">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="0667e-137">The name of certificate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0667e-138">Löschen Sie das Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="0667e-138">Delete the certificate.</span></span>  <span data-ttu-id="0667e-139">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="0667e-139">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0667e-140">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="0667e-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.CertificateGetResponse Get (this Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.CertificateGetResponse Get(class Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.Get(Microsoft.Azure.Management.Automation.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ICertificateOperations, resourceGroupName As String, automationAccount As String, certificateName As String) As CertificateGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.CertificateGetResponse" Usage="Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.Get (operations, resourceGroupName, automationAccount, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.CertificateGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0667e-141">Verweis auf die Microsoft.Azure.Management.Automation.ICertificateOperations.</span><span class="sxs-lookup"><span data-stu-id="0667e-141">Reference to the Microsoft.Azure.Management.Automation.ICertificateOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0667e-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-142">Required.</span></span> <span data-ttu-id="0667e-143">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="0667e-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="0667e-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-144">Required.</span></span> <span data-ttu-id="0667e-145">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="0667e-145">The automation account name.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="0667e-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-146">Required.</span></span> <span data-ttu-id="0667e-147">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="0667e-147">The name of certificate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0667e-148">Rufen Sie das Zertifikat, das Zertifikat namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="0667e-148">Retrieve the certificate identified by certificate name.</span></span>  <span data-ttu-id="0667e-149">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="0667e-149">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0667e-150">Das Antwort-Modell für den Abrufvorgang für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="0667e-150">The response model for the get certificate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CertificateGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As ICertificateOperations, resourceGroupName As String, automationAccount As String, certificateName As String) As Task(Of CertificateGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.ICertificateOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0667e-151">Verweis auf die Microsoft.Azure.Management.Automation.ICertificateOperations.</span><span class="sxs-lookup"><span data-stu-id="0667e-151">Reference to the Microsoft.Azure.Management.Automation.ICertificateOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0667e-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-152">Required.</span></span> <span data-ttu-id="0667e-153">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="0667e-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="0667e-154">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-154">Required.</span></span> <span data-ttu-id="0667e-155">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="0667e-155">The automation account name.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="0667e-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-156">Required.</span></span> <span data-ttu-id="0667e-157">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="0667e-157">The name of certificate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0667e-158">Rufen Sie das Zertifikat, das Zertifikat namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="0667e-158">Retrieve the certificate identified by certificate name.</span></span>  <span data-ttu-id="0667e-159">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="0667e-159">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0667e-160">Das Antwort-Modell für den Abrufvorgang für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="0667e-160">The response model for the get certificate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.CertificateListResponse List (this Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.CertificateListResponse List(class Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.List(Microsoft.Azure.Management.Automation.ICertificateOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ICertificateOperations, resourceGroupName As String, automationAccount As String) As CertificateListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.ICertificateOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.CertificateListResponse" Usage="Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.List (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.CertificateListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0667e-161">Verweis auf die Microsoft.Azure.Management.Automation.ICertificateOperations.</span><span class="sxs-lookup"><span data-stu-id="0667e-161">Reference to the Microsoft.Azure.Management.Automation.ICertificateOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0667e-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-162">Required.</span></span> <span data-ttu-id="0667e-163">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="0667e-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="0667e-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-164">Required.</span></span> <span data-ttu-id="0667e-165">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="0667e-165">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0667e-166">Rufen Sie eine Liste von Zertifikaten.</span><span class="sxs-lookup"><span data-stu-id="0667e-166">Retrieve a list of certificates.</span></span>  <span data-ttu-id="0667e-167">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="0667e-167">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0667e-168">Das Antwort-Modell für den Auflistungsvorgang für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="0667e-168">The response model for the list certificate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.ICertificateOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As ICertificateOperations, resourceGroupName As String, automationAccount As String) As Task(Of CertificateListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.ICertificateOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0667e-169">Verweis auf die Microsoft.Azure.Management.Automation.ICertificateOperations.</span><span class="sxs-lookup"><span data-stu-id="0667e-169">Reference to the Microsoft.Azure.Management.Automation.ICertificateOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0667e-170">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-170">Required.</span></span> <span data-ttu-id="0667e-171">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="0667e-171">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="0667e-172">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-172">Required.</span></span> <span data-ttu-id="0667e-173">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="0667e-173">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0667e-174">Rufen Sie eine Liste von Zertifikaten.</span><span class="sxs-lookup"><span data-stu-id="0667e-174">Retrieve a list of certificates.</span></span>  <span data-ttu-id="0667e-175">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="0667e-175">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0667e-176">Das Antwort-Modell für den Auflistungsvorgang für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="0667e-176">The response model for the list certificate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.CertificateListResponse ListNext (this Microsoft.Azure.Management.Automation.ICertificateOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.CertificateListResponse ListNext(class Microsoft.Azure.Management.Automation.ICertificateOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.ICertificateOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ICertificateOperations, nextLink As String) As CertificateListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.ICertificateOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.CertificateListResponse" Usage="Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.CertificateListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICertificateOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0667e-177">Verweis auf die Microsoft.Azure.Management.Automation.ICertificateOperations.</span><span class="sxs-lookup"><span data-stu-id="0667e-177">Reference to the Microsoft.Azure.Management.Automation.ICertificateOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="0667e-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-178">Required.</span></span> <span data-ttu-id="0667e-179">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="0667e-179">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0667e-180">Abgerufen Sie weitere Liste der Zertifikate werden.</span><span class="sxs-lookup"><span data-stu-id="0667e-180">Retrieve next list of certificates.</span></span>  <span data-ttu-id="0667e-181">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="0667e-181">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0667e-182">Das Antwort-Modell für den Auflistungsvorgang für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="0667e-182">The response model for the list certificate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.ICertificateOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.ICertificateOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.ICertificateOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As ICertificateOperations, nextLink As String) As Task(Of CertificateListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.ICertificateOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICertificateOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0667e-183">Verweis auf die Microsoft.Azure.Management.Automation.ICertificateOperations.</span><span class="sxs-lookup"><span data-stu-id="0667e-183">Reference to the Microsoft.Azure.Management.Automation.ICertificateOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="0667e-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-184">Required.</span></span> <span data-ttu-id="0667e-185">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="0667e-185">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0667e-186">Abgerufen Sie weitere Liste der Zertifikate werden.</span><span class="sxs-lookup"><span data-stu-id="0667e-186">Retrieve next list of certificates.</span></span>  <span data-ttu-id="0667e-187">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="0667e-187">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0667e-188">Das Antwort-Modell für den Auflistungsvorgang für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="0667e-188">The response model for the list certificate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Patch (this Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Patch(class Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.ICertificateOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As ICertificateOperations, resourceGroupName As String, automationAccount As String, parameters As CertificatePatchParameters) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.ICertificateOperations * string * string * Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.Patch (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0667e-189">Verweis auf die Microsoft.Azure.Management.Automation.ICertificateOperations.</span><span class="sxs-lookup"><span data-stu-id="0667e-189">Reference to the Microsoft.Azure.Management.Automation.ICertificateOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0667e-190">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-190">Required.</span></span> <span data-ttu-id="0667e-191">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="0667e-191">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="0667e-192">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-192">Required.</span></span> <span data-ttu-id="0667e-193">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="0667e-193">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0667e-194">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-194">Required.</span></span> <span data-ttu-id="0667e-195">Die Parameter für den Patch-Vorgang Zertifikat bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="0667e-195">The parameters supplied to the patch certificate operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0667e-196">Aktualisieren eines Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="0667e-196">Update a certificate.</span></span>  <span data-ttu-id="0667e-197">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="0667e-197">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0667e-198">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="0667e-198">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.ICertificateOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.ICertificateOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As ICertificateOperations, resourceGroupName As String, automationAccount As String, parameters As CertificatePatchParameters) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.ICertificateOperations * string * string * Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.CertificateOperationsExtensions.PatchAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0667e-199">Verweis auf die Microsoft.Azure.Management.Automation.ICertificateOperations.</span><span class="sxs-lookup"><span data-stu-id="0667e-199">Reference to the Microsoft.Azure.Management.Automation.ICertificateOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0667e-200">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-200">Required.</span></span> <span data-ttu-id="0667e-201">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="0667e-201">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="0667e-202">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-202">Required.</span></span> <span data-ttu-id="0667e-203">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="0667e-203">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0667e-204">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0667e-204">Required.</span></span> <span data-ttu-id="0667e-205">Die Parameter für den Patch-Vorgang Zertifikat bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="0667e-205">The parameters supplied to the patch certificate operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0667e-206">Aktualisieren eines Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="0667e-206">Update a certificate.</span></span>  <span data-ttu-id="0667e-207">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="0667e-207">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0667e-208">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="0667e-208">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>