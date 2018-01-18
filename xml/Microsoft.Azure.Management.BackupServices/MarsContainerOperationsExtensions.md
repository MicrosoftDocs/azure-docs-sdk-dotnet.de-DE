<Type Name="MarsContainerOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class MarsContainerOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MarsContainerOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MarsContainerOperationsExtensions" />
  <TypeSignature Language="F#" Value="type MarsContainerOperationsExtensions = class" />
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
    <Member MemberName="EnableMarsContainerReregistration">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse EnableMarsContainerReregistration (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest enableReregistrationRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse EnableMarsContainerReregistration(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, class Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest enableReregistrationRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.EnableMarsContainerReregistration(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member EnableMarsContainerReregistration : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.EnableMarsContainerReregistration (operations, resourceGroupName, resourceName, containerId, enableReregistrationRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="enableReregistrationRequest" Type="Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bbc56-101">Verweis auf die Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="bbc56-101">Reference to the Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bbc56-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-102">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="bbc56-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-103">Required.</span></span>
            </param>
        <param name="containerId">
            <span data-ttu-id="bbc56-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-104">Required.</span></span> <span data-ttu-id="bbc56-105">MARS-Container-ID.</span><span class="sxs-lookup"><span data-stu-id="bbc56-105">MARS container ID.</span></span>
            </param>
        <param name="enableReregistrationRequest">
            <span data-ttu-id="bbc56-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-106">Required.</span></span> <span data-ttu-id="bbc56-107">Aktivieren Sie die Anforderung für eine erneute Registrierung.</span><span class="sxs-lookup"><span data-stu-id="bbc56-107">Enable Reregistration Request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="bbc56-108">Optional.</span><span class="sxs-lookup"><span data-stu-id="bbc56-108">Optional.</span></span> <span data-ttu-id="bbc56-109">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="bbc56-109">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bbc56-110">Der Container eine erneute Registrierung zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="bbc56-110">Enable the container reregistration.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bbc56-111">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="bbc56-111">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableMarsContainerReregistrationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; EnableMarsContainerReregistrationAsync (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest enableReregistrationRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; EnableMarsContainerReregistrationAsync(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, class Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest enableReregistrationRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.EnableMarsContainerReregistrationAsync(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member EnableMarsContainerReregistrationAsync : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.EnableMarsContainerReregistrationAsync (operations, resourceGroupName, resourceName, containerId, enableReregistrationRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="enableReregistrationRequest" Type="Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bbc56-112">Verweis auf die Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="bbc56-112">Reference to the Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bbc56-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-113">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="bbc56-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-114">Required.</span></span>
            </param>
        <param name="containerId">
            <span data-ttu-id="bbc56-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-115">Required.</span></span> <span data-ttu-id="bbc56-116">MARS-Container-ID.</span><span class="sxs-lookup"><span data-stu-id="bbc56-116">MARS container ID.</span></span>
            </param>
        <param name="enableReregistrationRequest">
            <span data-ttu-id="bbc56-117">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-117">Required.</span></span> <span data-ttu-id="bbc56-118">Aktivieren Sie die Anforderung für eine erneute Registrierung.</span><span class="sxs-lookup"><span data-stu-id="bbc56-118">Enable Reregistration Request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="bbc56-119">Optional.</span><span class="sxs-lookup"><span data-stu-id="bbc56-119">Optional.</span></span> <span data-ttu-id="bbc56-120">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="bbc56-120">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bbc56-121">Der Container eine erneute Registrierung zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="bbc56-121">Enable the container reregistration.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bbc56-122">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="bbc56-122">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMarsContainersByType">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse ListMarsContainersByType (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse ListMarsContainersByType(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, valuetype Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByType(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.MarsContainerType,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListMarsContainersByType : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.MarsContainerType * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByType (operations, resourceGroupName, resourceName, containerType, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerType" Type="Microsoft.Azure.Management.BackupServices.Models.MarsContainerType" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bbc56-123">Verweis auf die Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="bbc56-123">Reference to the Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bbc56-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-124">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="bbc56-125">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-125">Required.</span></span>
            </param>
        <param name="containerType">
            <span data-ttu-id="bbc56-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-126">Required.</span></span> <span data-ttu-id="bbc56-127">Der Typ des Containers.</span><span class="sxs-lookup"><span data-stu-id="bbc56-127">Type of container.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="bbc56-128">Optional.</span><span class="sxs-lookup"><span data-stu-id="bbc56-128">Optional.</span></span> <span data-ttu-id="bbc56-129">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="bbc56-129">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bbc56-130">Ruft die Liste der alle Container, die anhand der angegebenen Abfragezeichenfolge für den Filter.</span><span class="sxs-lookup"><span data-stu-id="bbc56-130">Get the list of all container based on the given query filter string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bbc56-131">Die Liste der Microsoft Azure Recovery Services (MARS)-Container.</span><span class="sxs-lookup"><span data-stu-id="bbc56-131">List of Microsoft Azure Recovery Services (MARS) containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMarsContainersByTypeAndFriendlyName">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse ListMarsContainersByTypeAndFriendlyName (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, string friendlyName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse ListMarsContainersByTypeAndFriendlyName(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, valuetype Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, string friendlyName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAndFriendlyName(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.MarsContainerType,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListMarsContainersByTypeAndFriendlyName : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.MarsContainerType * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAndFriendlyName (operations, resourceGroupName, resourceName, containerType, friendlyName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerType" Type="Microsoft.Azure.Management.BackupServices.Models.MarsContainerType" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bbc56-132">Verweis auf die Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="bbc56-132">Reference to the Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bbc56-133">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-133">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="bbc56-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-134">Required.</span></span>
            </param>
        <param name="containerType">
            <span data-ttu-id="bbc56-135">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-135">Required.</span></span> <span data-ttu-id="bbc56-136">Der Typ des Containers.</span><span class="sxs-lookup"><span data-stu-id="bbc56-136">Type of container.</span></span>
            </param>
        <param name="friendlyName">
            <span data-ttu-id="bbc56-137">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-137">Required.</span></span> <span data-ttu-id="bbc56-138">Anzeigename des Containers.</span><span class="sxs-lookup"><span data-stu-id="bbc56-138">Friendly name of container.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="bbc56-139">Optional.</span><span class="sxs-lookup"><span data-stu-id="bbc56-139">Optional.</span></span> <span data-ttu-id="bbc56-140">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="bbc56-140">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bbc56-141">Ruft die Liste der alle Container, die anhand der angegebenen Abfragezeichenfolge für den Filter.</span><span class="sxs-lookup"><span data-stu-id="bbc56-141">Get the list of all container based on the given query filter string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bbc56-142">Die Liste der Microsoft Azure Recovery Services (MARS)-Container.</span><span class="sxs-lookup"><span data-stu-id="bbc56-142">List of Microsoft Azure Recovery Services (MARS) containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMarsContainersByTypeAndFriendlyNameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAndFriendlyNameAsync (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, string friendlyName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAndFriendlyNameAsync(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, valuetype Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, string friendlyName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAndFriendlyNameAsync(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.MarsContainerType,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListMarsContainersByTypeAndFriendlyNameAsync : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.MarsContainerType * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAndFriendlyNameAsync (operations, resourceGroupName, resourceName, containerType, friendlyName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerType" Type="Microsoft.Azure.Management.BackupServices.Models.MarsContainerType" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bbc56-143">Verweis auf die Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="bbc56-143">Reference to the Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bbc56-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-144">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="bbc56-145">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-145">Required.</span></span>
            </param>
        <param name="containerType">
            <span data-ttu-id="bbc56-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-146">Required.</span></span> <span data-ttu-id="bbc56-147">Der Typ des Containers.</span><span class="sxs-lookup"><span data-stu-id="bbc56-147">Type of container.</span></span>
            </param>
        <param name="friendlyName">
            <span data-ttu-id="bbc56-148">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-148">Required.</span></span> <span data-ttu-id="bbc56-149">Anzeigename des Containers.</span><span class="sxs-lookup"><span data-stu-id="bbc56-149">Friendly name of container.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="bbc56-150">Optional.</span><span class="sxs-lookup"><span data-stu-id="bbc56-150">Optional.</span></span> <span data-ttu-id="bbc56-151">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="bbc56-151">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bbc56-152">Ruft die Liste der alle Container, die anhand der angegebenen Abfragezeichenfolge für den Filter.</span><span class="sxs-lookup"><span data-stu-id="bbc56-152">Get the list of all container based on the given query filter string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bbc56-153">Die Liste der Microsoft Azure Recovery Services (MARS)-Container.</span><span class="sxs-lookup"><span data-stu-id="bbc56-153">List of Microsoft Azure Recovery Services (MARS) containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMarsContainersByTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAsync (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAsync(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, valuetype Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAsync(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.MarsContainerType,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListMarsContainersByTypeAsync : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.MarsContainerType * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAsync (operations, resourceGroupName, resourceName, containerType, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerType" Type="Microsoft.Azure.Management.BackupServices.Models.MarsContainerType" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bbc56-154">Verweis auf die Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="bbc56-154">Reference to the Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bbc56-155">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-155">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="bbc56-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-156">Required.</span></span>
            </param>
        <param name="containerType">
            <span data-ttu-id="bbc56-157">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-157">Required.</span></span> <span data-ttu-id="bbc56-158">Der Typ des Containers.</span><span class="sxs-lookup"><span data-stu-id="bbc56-158">Type of container.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="bbc56-159">Optional.</span><span class="sxs-lookup"><span data-stu-id="bbc56-159">Optional.</span></span> <span data-ttu-id="bbc56-160">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="bbc56-160">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bbc56-161">Ruft die Liste der alle Container, die anhand der angegebenen Abfragezeichenfolge für den Filter.</span><span class="sxs-lookup"><span data-stu-id="bbc56-161">Get the list of all container based on the given query filter string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bbc56-162">Die Liste der Microsoft Azure Recovery Services (MARS)-Container.</span><span class="sxs-lookup"><span data-stu-id="bbc56-162">List of Microsoft Azure Recovery Services (MARS) containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterMarsContainer">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse UnregisterMarsContainer (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse UnregisterMarsContainer(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.UnregisterMarsContainer(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UnregisterMarsContainer : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.UnregisterMarsContainer (operations, resourceGroupName, resourceName, containerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bbc56-163">Verweis auf die Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="bbc56-163">Reference to the Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bbc56-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-164">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="bbc56-165">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-165">Required.</span></span>
            </param>
        <param name="containerId">
            <span data-ttu-id="bbc56-166">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-166">Required.</span></span> <span data-ttu-id="bbc56-167">MARS-Container-ID.</span><span class="sxs-lookup"><span data-stu-id="bbc56-167">MARS container ID.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="bbc56-168">Optional.</span><span class="sxs-lookup"><span data-stu-id="bbc56-168">Optional.</span></span> <span data-ttu-id="bbc56-169">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="bbc56-169">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bbc56-170">Aufheben der Registrierung des Containers.</span><span class="sxs-lookup"><span data-stu-id="bbc56-170">Unregister the container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bbc56-171">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="bbc56-171">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterMarsContainerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterMarsContainerAsync (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterMarsContainerAsync(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.UnregisterMarsContainerAsync(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UnregisterMarsContainerAsync : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.UnregisterMarsContainerAsync (operations, resourceGroupName, resourceName, containerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bbc56-172">Verweis auf die Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="bbc56-172">Reference to the Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bbc56-173">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-173">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="bbc56-174">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-174">Required.</span></span>
            </param>
        <param name="containerId">
            <span data-ttu-id="bbc56-175">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="bbc56-175">Required.</span></span> <span data-ttu-id="bbc56-176">MARS-Container-ID.</span><span class="sxs-lookup"><span data-stu-id="bbc56-176">MARS container ID.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="bbc56-177">Optional.</span><span class="sxs-lookup"><span data-stu-id="bbc56-177">Optional.</span></span> <span data-ttu-id="bbc56-178">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="bbc56-178">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bbc56-179">Aufheben der Registrierung des Containers.</span><span class="sxs-lookup"><span data-stu-id="bbc56-179">Unregister the container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bbc56-180">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="bbc56-180">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>