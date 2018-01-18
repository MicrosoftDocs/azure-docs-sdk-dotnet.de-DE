<Type Name="VirtualDiskOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualDiskOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualDiskOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualDiskOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualDiskOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9090e-101">Dies ist eine RESTFul-API, um Sie StorSimple-Objekte zu verwalten</span><span class="sxs-lookup"><span data-stu-id="9090e-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreating">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginCreating (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginCreating(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginCreating(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreating : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginCreating (operations, deviceId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9090e-102">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span><span class="sxs-lookup"><span data-stu-id="9090e-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="9090e-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-103">Required.</span></span> <span data-ttu-id="9090e-104">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="9090e-104">device id</span></span>
            </param>
        <param name="diskDetails">
            <span data-ttu-id="9090e-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-105">Required.</span></span> <span data-ttu-id="9090e-106">Parameter, die auf den Erstellungsvorgang für die virtuelle Festplatte angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9090e-106">Parameters supplied to the Create virtual disk operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9090e-107">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-107">Required.</span></span> <span data-ttu-id="9090e-108">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="9090e-108">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9090e-109">Der Vorgang beginnen erstellen-Datenträger wird ein neues Volume erstellt.</span><span class="sxs-lookup"><span data-stu-id="9090e-109">The Begin Creating Volume operation creates a new volume.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9090e-110">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="9090e-110">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreatingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginCreatingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginCreatingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginCreatingAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginCreatingAsync (operations, deviceId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9090e-111">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span><span class="sxs-lookup"><span data-stu-id="9090e-111">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="9090e-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-112">Required.</span></span> <span data-ttu-id="9090e-113">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="9090e-113">device id</span></span>
            </param>
        <param name="diskDetails">
            <span data-ttu-id="9090e-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-114">Required.</span></span> <span data-ttu-id="9090e-115">Parameter, die auf den Erstellungsvorgang für die virtuelle Festplatte angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9090e-115">Parameters supplied to the Create virtual disk operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9090e-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-116">Required.</span></span> <span data-ttu-id="9090e-117">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="9090e-117">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9090e-118">Der Vorgang beginnen erstellen-Datenträger wird ein neues Volume erstellt.</span><span class="sxs-lookup"><span data-stu-id="9090e-118">The Begin Creating Volume operation creates a new volume.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9090e-119">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="9090e-119">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleting">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginDeleting (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginDeleting(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginDeleting(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeleting : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginDeleting (operations, deviceId, diskId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9090e-120">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span><span class="sxs-lookup"><span data-stu-id="9090e-120">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="9090e-121">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-121">Required.</span></span> <span data-ttu-id="9090e-122">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="9090e-122">device id</span></span>
            </param>
        <param name="diskId">
            <span data-ttu-id="9090e-123">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-123">Required.</span></span> <span data-ttu-id="9090e-124">Instanz-Id des virtuellen Datenträgers gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="9090e-124">Instance id of the virtual disk to be deleted.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9090e-125">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-125">Required.</span></span> <span data-ttu-id="9090e-126">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="9090e-126">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9090e-127">Das Löschen des Datenträgers beginnen-Vorgang löscht das angegebene Volume.</span><span class="sxs-lookup"><span data-stu-id="9090e-127">The Begin Deleteing Volume operation deletes the specified volume.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9090e-128">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="9090e-128">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeletingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginDeletingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginDeletingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginDeletingAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeletingAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginDeletingAsync (operations, deviceId, diskId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9090e-129">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span><span class="sxs-lookup"><span data-stu-id="9090e-129">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="9090e-130">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-130">Required.</span></span> <span data-ttu-id="9090e-131">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="9090e-131">device id</span></span>
            </param>
        <param name="diskId">
            <span data-ttu-id="9090e-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-132">Required.</span></span> <span data-ttu-id="9090e-133">Instanz-Id des virtuellen Datenträgers gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="9090e-133">Instance id of the virtual disk to be deleted.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9090e-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-134">Required.</span></span> <span data-ttu-id="9090e-135">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="9090e-135">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9090e-136">Das Löschen des Datenträgers beginnen-Vorgang löscht das angegebene Volume.</span><span class="sxs-lookup"><span data-stu-id="9090e-136">The Begin Deleteing Volume operation deletes the specified volume.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9090e-137">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="9090e-137">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdating">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdating (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdating(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginUpdating(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdating : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginUpdating (operations, deviceId, diskId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9090e-138">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span><span class="sxs-lookup"><span data-stu-id="9090e-138">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="9090e-139">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-139">Required.</span></span> <span data-ttu-id="9090e-140">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="9090e-140">device id</span></span>
            </param>
        <param name="diskId">
            <span data-ttu-id="9090e-141">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-141">Required.</span></span> <span data-ttu-id="9090e-142">Datenträger-id</span><span class="sxs-lookup"><span data-stu-id="9090e-142">disk id</span></span>
            </param>
        <param name="diskDetails">
            <span data-ttu-id="9090e-143">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-143">Required.</span></span> <span data-ttu-id="9090e-144">Parameter, die auf den Updatevorgang für die virtuelle Festplatte angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9090e-144">Parameters supplied to the update virtual disk operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9090e-145">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-145">Required.</span></span> <span data-ttu-id="9090e-146">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="9090e-146">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9090e-147">Das Aktualisieren der Volume-Vorgang beginnen aktualisiert ein vorhandenes Volume an.</span><span class="sxs-lookup"><span data-stu-id="9090e-147">The Begin updating Volume operation updates an existing volume.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9090e-148">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="9090e-148">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdatingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdatingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdatingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginUpdatingAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdatingAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginUpdatingAsync (operations, deviceId, diskId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9090e-149">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span><span class="sxs-lookup"><span data-stu-id="9090e-149">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="9090e-150">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-150">Required.</span></span> <span data-ttu-id="9090e-151">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="9090e-151">device id</span></span>
            </param>
        <param name="diskId">
            <span data-ttu-id="9090e-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-152">Required.</span></span> <span data-ttu-id="9090e-153">Datenträger-id</span><span class="sxs-lookup"><span data-stu-id="9090e-153">disk id</span></span>
            </param>
        <param name="diskDetails">
            <span data-ttu-id="9090e-154">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-154">Required.</span></span> <span data-ttu-id="9090e-155">Parameter, die auf den Updatevorgang für die virtuelle Festplatte angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9090e-155">Parameters supplied to the update virtual disk operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9090e-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-156">Required.</span></span> <span data-ttu-id="9090e-157">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="9090e-157">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9090e-158">Das Aktualisieren der Volume-Vorgang beginnen aktualisiert ein vorhandenes Volume an.</span><span class="sxs-lookup"><span data-stu-id="9090e-158">The Begin updating Volume operation updates an existing volume.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9090e-159">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="9090e-159">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Create(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Create (operations, deviceId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9090e-160">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span><span class="sxs-lookup"><span data-stu-id="9090e-160">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="9090e-161">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-161">Required.</span></span> <span data-ttu-id="9090e-162">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="9090e-162">device id</span></span>
            </param>
        <param name="diskDetails">
            <span data-ttu-id="9090e-163">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-163">Required.</span></span> <span data-ttu-id="9090e-164">Parameter, die auf den Erstellungsvorgang für die virtuelle Festplatte angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9090e-164">Parameters supplied to the Create virtual disk operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9090e-165">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-165">Required.</span></span> <span data-ttu-id="9090e-166">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="9090e-166">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="9090e-167">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="9090e-167">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.CreateAsync (operations, deviceId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9090e-168">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span><span class="sxs-lookup"><span data-stu-id="9090e-168">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="9090e-169">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-169">Required.</span></span> <span data-ttu-id="9090e-170">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="9090e-170">device id</span></span>
            </param>
        <param name="diskDetails">
            <span data-ttu-id="9090e-171">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-171">Required.</span></span> <span data-ttu-id="9090e-172">Parameter, die auf den Erstellungsvorgang für die virtuelle Festplatte angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9090e-172">Parameters supplied to the Create virtual disk operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9090e-173">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-173">Required.</span></span> <span data-ttu-id="9090e-174">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="9090e-174">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="9090e-175">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="9090e-175">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Delete(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Delete (operations, deviceId, diskId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9090e-176">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span><span class="sxs-lookup"><span data-stu-id="9090e-176">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="9090e-177">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-177">Required.</span></span> <span data-ttu-id="9090e-178">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="9090e-178">device id</span></span>
            </param>
        <param name="diskId">
            <span data-ttu-id="9090e-179">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-179">Required.</span></span> <span data-ttu-id="9090e-180">Datenträger-id</span><span class="sxs-lookup"><span data-stu-id="9090e-180">disk id</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9090e-181">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-181">Required.</span></span> <span data-ttu-id="9090e-182">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="9090e-182">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="9090e-183">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="9090e-183">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.DeleteAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.DeleteAsync (operations, deviceId, diskId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9090e-184">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span><span class="sxs-lookup"><span data-stu-id="9090e-184">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="9090e-185">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-185">Required.</span></span> <span data-ttu-id="9090e-186">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="9090e-186">device id</span></span>
            </param>
        <param name="diskId">
            <span data-ttu-id="9090e-187">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-187">Required.</span></span> <span data-ttu-id="9090e-188">Datenträger-id</span><span class="sxs-lookup"><span data-stu-id="9090e-188">disk id</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9090e-189">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-189">Required.</span></span> <span data-ttu-id="9090e-190">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="9090e-190">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="9090e-191">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="9090e-191">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByName">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse GetByName (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse GetByName(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.GetByName(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetByName : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.GetByName (operations, deviceId, diskName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9090e-192">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span><span class="sxs-lookup"><span data-stu-id="9090e-192">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="9090e-193">Optional.</span><span class="sxs-lookup"><span data-stu-id="9090e-193">Optional.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="9090e-194">Optional.</span><span class="sxs-lookup"><span data-stu-id="9090e-194">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9090e-195">Optional.</span><span class="sxs-lookup"><span data-stu-id="9090e-195">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="9090e-196">Das Antwort-Modell für das Abrufen des virtuellen Datenträgers.</span><span class="sxs-lookup"><span data-stu-id="9090e-196">The response model for the get of virtual disk.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByNameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse&gt; GetByNameAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse&gt; GetByNameAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.GetByNameAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetByNameAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.GetByNameAsync (operations, deviceId, diskName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9090e-197">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span><span class="sxs-lookup"><span data-stu-id="9090e-197">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="9090e-198">Optional.</span><span class="sxs-lookup"><span data-stu-id="9090e-198">Optional.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="9090e-199">Optional.</span><span class="sxs-lookup"><span data-stu-id="9090e-199">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9090e-200">Optional.</span><span class="sxs-lookup"><span data-stu-id="9090e-200">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="9090e-201">Das Antwort-Modell für das Abrufen des virtuellen Datenträgers.</span><span class="sxs-lookup"><span data-stu-id="9090e-201">The response model for the get of virtual disk.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse List (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse List(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.List(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.List (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9090e-202">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span><span class="sxs-lookup"><span data-stu-id="9090e-202">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="9090e-203">Optional.</span><span class="sxs-lookup"><span data-stu-id="9090e-203">Optional.</span></span>
            </param>
        <param name="dataContainerId">
            <span data-ttu-id="9090e-204">Optional.</span><span class="sxs-lookup"><span data-stu-id="9090e-204">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9090e-205">Optional.</span><span class="sxs-lookup"><span data-stu-id="9090e-205">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="9090e-206">Das Antwort-Modell für die Liste der virtuellen Datenträger für einen angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="9090e-206">The response model for the list of virtual disks for a given data container.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse&gt; ListAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse&gt; ListAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.ListAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.ListAsync (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9090e-207">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span><span class="sxs-lookup"><span data-stu-id="9090e-207">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="9090e-208">Optional.</span><span class="sxs-lookup"><span data-stu-id="9090e-208">Optional.</span></span>
            </param>
        <param name="dataContainerId">
            <span data-ttu-id="9090e-209">Optional.</span><span class="sxs-lookup"><span data-stu-id="9090e-209">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9090e-210">Optional.</span><span class="sxs-lookup"><span data-stu-id="9090e-210">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="9090e-211">Das Antwort-Modell für die Liste der virtuellen Datenträger für einen angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="9090e-211">The response model for the list of virtual disks for a given data container.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Update (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Update(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Update(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Update (operations, deviceId, diskId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9090e-212">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span><span class="sxs-lookup"><span data-stu-id="9090e-212">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="9090e-213">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-213">Required.</span></span> <span data-ttu-id="9090e-214">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="9090e-214">device id</span></span>
            </param>
        <param name="diskId">
            <span data-ttu-id="9090e-215">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-215">Required.</span></span> <span data-ttu-id="9090e-216">Datenträger-id</span><span class="sxs-lookup"><span data-stu-id="9090e-216">disk id</span></span>
            </param>
        <param name="diskDetails">
            <span data-ttu-id="9090e-217">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-217">Required.</span></span> <span data-ttu-id="9090e-218">Parameter, die auf den Updatevorgang für die virtuelle Festplatte angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9090e-218">Parameters supplied to the update virtual disk operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9090e-219">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-219">Required.</span></span> <span data-ttu-id="9090e-220">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="9090e-220">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="9090e-221">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="9090e-221">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.UpdateAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.UpdateAsync (operations, deviceId, diskId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9090e-222">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span><span class="sxs-lookup"><span data-stu-id="9090e-222">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="9090e-223">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-223">Required.</span></span> <span data-ttu-id="9090e-224">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="9090e-224">device id</span></span>
            </param>
        <param name="diskId">
            <span data-ttu-id="9090e-225">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-225">Required.</span></span> <span data-ttu-id="9090e-226">Datenträger-id</span><span class="sxs-lookup"><span data-stu-id="9090e-226">disk id</span></span>
            </param>
        <param name="diskDetails">
            <span data-ttu-id="9090e-227">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-227">Required.</span></span> <span data-ttu-id="9090e-228">Parameter, die auf den Updatevorgang für die virtuelle Festplatte angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9090e-228">Parameters supplied to the update virtual disk operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9090e-229">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9090e-229">Required.</span></span> <span data-ttu-id="9090e-230">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="9090e-230">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="9090e-231">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="9090e-231">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>