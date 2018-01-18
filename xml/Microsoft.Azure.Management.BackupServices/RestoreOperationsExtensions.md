<Type Name="RestoreOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RestoreOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RestoreOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RestoreOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RestoreOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Member MemberName="TriggerResotre">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse TriggerResotre (this Microsoft.Azure.Management.BackupServices.IRestoreOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse TriggerResotre(class Microsoft.Azure.Management.BackupServices.IRestoreOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, class Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions.TriggerResotre(Microsoft.Azure.Management.BackupServices.IRestoreOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest)" />
      <MemberSignature Language="F#" Value="static member TriggerResotre : Microsoft.Azure.Management.BackupServices.IRestoreOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions.TriggerResotre (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, recoveryPointName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IRestoreOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="recoveryPointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e865b-101">Verweis auf die Microsoft.Azure.Management.BackupServices.IRestoreOperations.</span><span class="sxs-lookup"><span data-stu-id="e865b-101">Reference to the Microsoft.Azure.Management.BackupServices.IRestoreOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e865b-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e865b-102">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="e865b-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e865b-103">Required.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="e865b-104">Optional.</span><span class="sxs-lookup"><span data-stu-id="e865b-104">Optional.</span></span> <span data-ttu-id="e865b-105">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="e865b-105">Request header parameters.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="e865b-106">Optional.</span><span class="sxs-lookup"><span data-stu-id="e865b-106">Optional.</span></span>
            </param>
        <param name="itemName">
            <span data-ttu-id="e865b-107">Optional.</span><span class="sxs-lookup"><span data-stu-id="e865b-107">Optional.</span></span>
            </param>
        <param name="recoveryPointName">
            <span data-ttu-id="e865b-108">Optional.</span><span class="sxs-lookup"><span data-stu-id="e865b-108">Optional.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e865b-109">Optional.</span><span class="sxs-lookup"><span data-stu-id="e865b-109">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e865b-110">Stellen Sie die Azure-BackUpItem wieder her.</span><span class="sxs-lookup"><span data-stu-id="e865b-110">Restore Azure BackUpItem.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e865b-111">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="e865b-111">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerResotreAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; TriggerResotreAsync (this Microsoft.Azure.Management.BackupServices.IRestoreOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; TriggerResotreAsync(class Microsoft.Azure.Management.BackupServices.IRestoreOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, class Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions.TriggerResotreAsync(Microsoft.Azure.Management.BackupServices.IRestoreOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest)" />
      <MemberSignature Language="F#" Value="static member TriggerResotreAsync : Microsoft.Azure.Management.BackupServices.IRestoreOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions.TriggerResotreAsync (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, recoveryPointName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IRestoreOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="recoveryPointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e865b-112">Verweis auf die Microsoft.Azure.Management.BackupServices.IRestoreOperations.</span><span class="sxs-lookup"><span data-stu-id="e865b-112">Reference to the Microsoft.Azure.Management.BackupServices.IRestoreOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e865b-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e865b-113">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="e865b-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e865b-114">Required.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="e865b-115">Optional.</span><span class="sxs-lookup"><span data-stu-id="e865b-115">Optional.</span></span> <span data-ttu-id="e865b-116">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="e865b-116">Request header parameters.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="e865b-117">Optional.</span><span class="sxs-lookup"><span data-stu-id="e865b-117">Optional.</span></span>
            </param>
        <param name="itemName">
            <span data-ttu-id="e865b-118">Optional.</span><span class="sxs-lookup"><span data-stu-id="e865b-118">Optional.</span></span>
            </param>
        <param name="recoveryPointName">
            <span data-ttu-id="e865b-119">Optional.</span><span class="sxs-lookup"><span data-stu-id="e865b-119">Optional.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e865b-120">Optional.</span><span class="sxs-lookup"><span data-stu-id="e865b-120">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e865b-121">Stellen Sie die Azure-BackUpItem wieder her.</span><span class="sxs-lookup"><span data-stu-id="e865b-121">Restore Azure BackUpItem.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e865b-122">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="e865b-122">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>