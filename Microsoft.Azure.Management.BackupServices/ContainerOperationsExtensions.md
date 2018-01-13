<Type Name="ContainerOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ContainerOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ContainerOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ContainerOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ContainerOperationsExtensions = class" />
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
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse List (this Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse List(class Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.List(Microsoft.Azure.Management.BackupServices.IContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.BackupServices.IContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.List (operations, resourceGroupName, resourceName, parameters, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e75a1-101">Verweis auf die Microsoft.Azure.Management.BackupServices.IContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="e75a1-101">Reference to the Microsoft.Azure.Management.BackupServices.IContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e75a1-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-102">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="e75a1-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-103">Required.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e75a1-104">Optional.</span><span class="sxs-lookup"><span data-stu-id="e75a1-104">Optional.</span></span> <span data-ttu-id="e75a1-105">Container-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="e75a1-105">Container query parameters.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="e75a1-106">Optional.</span><span class="sxs-lookup"><span data-stu-id="e75a1-106">Optional.</span></span> <span data-ttu-id="e75a1-107">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="e75a1-107">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e75a1-108">Ruft die Liste der alle Container, die anhand der angegebenen Abfragezeichenfolge für den Filter.</span><span class="sxs-lookup"><span data-stu-id="e75a1-108">Get the list of all container based on the given query filter string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e75a1-109">Die Definition einer CSMContainerListOperationResponse.</span><span class="sxs-lookup"><span data-stu-id="e75a1-109">The definition of a CSMContainerListOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt; ListAsync (this Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt; ListAsync(class Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.ListAsync(Microsoft.Azure.Management.BackupServices.IContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.BackupServices.IContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.ListAsync (operations, resourceGroupName, resourceName, parameters, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e75a1-110">Verweis auf die Microsoft.Azure.Management.BackupServices.IContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="e75a1-110">Reference to the Microsoft.Azure.Management.BackupServices.IContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e75a1-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-111">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="e75a1-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-112">Required.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e75a1-113">Optional.</span><span class="sxs-lookup"><span data-stu-id="e75a1-113">Optional.</span></span> <span data-ttu-id="e75a1-114">Container-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="e75a1-114">Container query parameters.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="e75a1-115">Optional.</span><span class="sxs-lookup"><span data-stu-id="e75a1-115">Optional.</span></span> <span data-ttu-id="e75a1-116">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="e75a1-116">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e75a1-117">Ruft die Liste der alle Container, die anhand der angegebenen Abfragezeichenfolge für den Filter.</span><span class="sxs-lookup"><span data-stu-id="e75a1-117">Get the list of all container based on the given query filter string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e75a1-118">Die Definition einer CSMContainerListOperationResponse.</span><span class="sxs-lookup"><span data-stu-id="e75a1-118">The definition of a CSMContainerListOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse Refresh (this Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse Refresh(class Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.Refresh(Microsoft.Azure.Management.BackupServices.IContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Refresh : Microsoft.Azure.Management.BackupServices.IContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.Refresh (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e75a1-119">Verweis auf die Microsoft.Azure.Management.BackupServices.IContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="e75a1-119">Reference to the Microsoft.Azure.Management.BackupServices.IContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e75a1-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-120">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="e75a1-121">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-121">Required.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="e75a1-122">Optional.</span><span class="sxs-lookup"><span data-stu-id="e75a1-122">Optional.</span></span> <span data-ttu-id="e75a1-123">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="e75a1-123">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e75a1-124">Lösen Sie die Ermittlung an.</span><span class="sxs-lookup"><span data-stu-id="e75a1-124">Trigger the Discovery.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e75a1-125">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="e75a1-125">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RefreshAsync (this Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RefreshAsync(class Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.RefreshAsync(Microsoft.Azure.Management.BackupServices.IContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member RefreshAsync : Microsoft.Azure.Management.BackupServices.IContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.RefreshAsync (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e75a1-126">Verweis auf die Microsoft.Azure.Management.BackupServices.IContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="e75a1-126">Reference to the Microsoft.Azure.Management.BackupServices.IContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e75a1-127">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-127">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="e75a1-128">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-128">Required.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="e75a1-129">Optional.</span><span class="sxs-lookup"><span data-stu-id="e75a1-129">Optional.</span></span> <span data-ttu-id="e75a1-130">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="e75a1-130">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e75a1-131">Lösen Sie die Ermittlung an.</span><span class="sxs-lookup"><span data-stu-id="e75a1-131">Trigger the Discovery.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e75a1-132">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="e75a1-132">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Register">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse Register (this Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, string containerName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse Register(class Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, string containerName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.Register(Microsoft.Azure.Management.BackupServices.IContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Register : Microsoft.Azure.Management.BackupServices.IContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.Register (operations, resourceGroupName, resourceName, containerName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e75a1-133">Verweis auf die Microsoft.Azure.Management.BackupServices.IContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="e75a1-133">Reference to the Microsoft.Azure.Management.BackupServices.IContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e75a1-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-134">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="e75a1-135">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-135">Required.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="e75a1-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-136">Required.</span></span> <span data-ttu-id="e75a1-137">Container werden registriert.</span><span class="sxs-lookup"><span data-stu-id="e75a1-137">Container to be register.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="e75a1-138">Optional.</span><span class="sxs-lookup"><span data-stu-id="e75a1-138">Optional.</span></span> <span data-ttu-id="e75a1-139">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="e75a1-139">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e75a1-140">Registrieren Sie den Container.</span><span class="sxs-lookup"><span data-stu-id="e75a1-140">Register the container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e75a1-141">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="e75a1-141">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RegisterAsync (this Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, string containerName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RegisterAsync(class Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, string containerName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.RegisterAsync(Microsoft.Azure.Management.BackupServices.IContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member RegisterAsync : Microsoft.Azure.Management.BackupServices.IContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.RegisterAsync (operations, resourceGroupName, resourceName, containerName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e75a1-142">Verweis auf die Microsoft.Azure.Management.BackupServices.IContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="e75a1-142">Reference to the Microsoft.Azure.Management.BackupServices.IContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e75a1-143">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-143">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="e75a1-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-144">Required.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="e75a1-145">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-145">Required.</span></span> <span data-ttu-id="e75a1-146">Container werden registriert.</span><span class="sxs-lookup"><span data-stu-id="e75a1-146">Container to be register.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="e75a1-147">Optional.</span><span class="sxs-lookup"><span data-stu-id="e75a1-147">Optional.</span></span> <span data-ttu-id="e75a1-148">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="e75a1-148">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e75a1-149">Registrieren Sie den Container.</span><span class="sxs-lookup"><span data-stu-id="e75a1-149">Register the container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e75a1-150">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="e75a1-150">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unregister">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse Unregister (this Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, string containerName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse Unregister(class Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, string containerName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.Unregister(Microsoft.Azure.Management.BackupServices.IContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Unregister : Microsoft.Azure.Management.BackupServices.IContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.Unregister (operations, resourceGroupName, resourceName, containerName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e75a1-151">Verweis auf die Microsoft.Azure.Management.BackupServices.IContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="e75a1-151">Reference to the Microsoft.Azure.Management.BackupServices.IContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e75a1-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-152">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="e75a1-153">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-153">Required.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="e75a1-154">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-154">Required.</span></span> <span data-ttu-id="e75a1-155">Container, der Registrierung aufgehoben werden soll.</span><span class="sxs-lookup"><span data-stu-id="e75a1-155">Container which we want to unregister.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="e75a1-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-156">Required.</span></span> <span data-ttu-id="e75a1-157">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="e75a1-157">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e75a1-158">Aufheben der Registrierung des Containers.</span><span class="sxs-lookup"><span data-stu-id="e75a1-158">Unregister the container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e75a1-159">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="e75a1-159">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterAsync (this Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, string containerName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterAsync(class Microsoft.Azure.Management.BackupServices.IContainerOperations operations, string resourceGroupName, string resourceName, string containerName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.UnregisterAsync(Microsoft.Azure.Management.BackupServices.IContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UnregisterAsync : Microsoft.Azure.Management.BackupServices.IContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.ContainerOperationsExtensions.UnregisterAsync (operations, resourceGroupName, resourceName, containerName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e75a1-160">Verweis auf die Microsoft.Azure.Management.BackupServices.IContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="e75a1-160">Reference to the Microsoft.Azure.Management.BackupServices.IContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e75a1-161">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-161">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="e75a1-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-162">Required.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="e75a1-163">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-163">Required.</span></span> <span data-ttu-id="e75a1-164">Container, der Registrierung aufgehoben werden soll.</span><span class="sxs-lookup"><span data-stu-id="e75a1-164">Container which we want to unregister.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="e75a1-165">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e75a1-165">Required.</span></span> <span data-ttu-id="e75a1-166">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="e75a1-166">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e75a1-167">Aufheben der Registrierung des Containers.</span><span class="sxs-lookup"><span data-stu-id="e75a1-167">Unregister the container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e75a1-168">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="e75a1-168">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>