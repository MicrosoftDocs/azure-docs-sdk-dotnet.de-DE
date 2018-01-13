<Type Name="OperationStatusExtensions" FullName="Microsoft.Azure.Management.BackupServices.OperationStatusExtensions">
  <TypeSignature Language="C#" Value="public static class OperationStatusExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit OperationStatusExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.OperationStatusExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module OperationStatusExtensions" />
  <TypeSignature Language="F#" Value="type OperationStatusExtensions = class" />
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
    <Member MemberName="CSMGet">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.CSMOperationResult CSMGet (this Microsoft.Azure.Management.BackupServices.IOperationStatus operations, string resourceGroupName, string resourceName, string operationId, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.CSMOperationResult CSMGet(class Microsoft.Azure.Management.BackupServices.IOperationStatus operations, string resourceGroupName, string resourceName, string operationId, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.OperationStatusExtensions.CSMGet(Microsoft.Azure.Management.BackupServices.IOperationStatus,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CSMGet : Microsoft.Azure.Management.BackupServices.IOperationStatus * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.CSMOperationResult" Usage="Microsoft.Azure.Management.BackupServices.OperationStatusExtensions.CSMGet (operations, resourceGroupName, resourceName, operationId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.CSMOperationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IOperationStatus" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b14a1-101">Verweis auf die Microsoft.Azure.Management.BackupServices.IOperationStatus.</span><span class="sxs-lookup"><span data-stu-id="b14a1-101">Reference to the Microsoft.Azure.Management.BackupServices.IOperationStatus.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b14a1-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b14a1-102">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b14a1-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b14a1-103">Required.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="b14a1-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b14a1-104">Required.</span></span> <span data-ttu-id="b14a1-105">OperationId.</span><span class="sxs-lookup"><span data-stu-id="b14a1-105">OperationId.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b14a1-106">Optional.</span><span class="sxs-lookup"><span data-stu-id="b14a1-106">Optional.</span></span> <span data-ttu-id="b14a1-107">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="b14a1-107">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b14a1-108">Vorgangsstatus abrufen.</span><span class="sxs-lookup"><span data-stu-id="b14a1-108">Get the Operation Status.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b14a1-109">Die Definition einer CSMOperationResult.</span><span class="sxs-lookup"><span data-stu-id="b14a1-109">The definition of a CSMOperationResult.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CSMGetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.CSMOperationResult&gt; CSMGetAsync (this Microsoft.Azure.Management.BackupServices.IOperationStatus operations, string resourceGroupName, string resourceName, string operationId, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.CSMOperationResult&gt; CSMGetAsync(class Microsoft.Azure.Management.BackupServices.IOperationStatus operations, string resourceGroupName, string resourceName, string operationId, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.OperationStatusExtensions.CSMGetAsync(Microsoft.Azure.Management.BackupServices.IOperationStatus,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CSMGetAsync : Microsoft.Azure.Management.BackupServices.IOperationStatus * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.CSMOperationResult&gt;" Usage="Microsoft.Azure.Management.BackupServices.OperationStatusExtensions.CSMGetAsync (operations, resourceGroupName, resourceName, operationId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.CSMOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IOperationStatus" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b14a1-110">Verweis auf die Microsoft.Azure.Management.BackupServices.IOperationStatus.</span><span class="sxs-lookup"><span data-stu-id="b14a1-110">Reference to the Microsoft.Azure.Management.BackupServices.IOperationStatus.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b14a1-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b14a1-111">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b14a1-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b14a1-112">Required.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="b14a1-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b14a1-113">Required.</span></span> <span data-ttu-id="b14a1-114">OperationId.</span><span class="sxs-lookup"><span data-stu-id="b14a1-114">OperationId.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b14a1-115">Optional.</span><span class="sxs-lookup"><span data-stu-id="b14a1-115">Optional.</span></span> <span data-ttu-id="b14a1-116">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="b14a1-116">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b14a1-117">Vorgangsstatus abrufen.</span><span class="sxs-lookup"><span data-stu-id="b14a1-117">Get the Operation Status.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b14a1-118">Die Definition einer CSMOperationResult.</span><span class="sxs-lookup"><span data-stu-id="b14a1-118">The definition of a CSMOperationResult.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>