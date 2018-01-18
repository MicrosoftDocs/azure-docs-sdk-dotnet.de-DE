<Type Name="DataContainerOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataContainerOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataContainerOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataContainerOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataContainerOperationsExtensions = class" />
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
            <span data-ttu-id="4a688-101">Dies ist eine RESTFul-API, um Sie StorSimple-Objekte zu verwalten</span><span class="sxs-lookup"><span data-stu-id="4a688-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreating">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreating (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreating(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginCreating(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreating : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginCreating (operations, deviceId, containerDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="containerDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4a688-102">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="4a688-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4a688-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-103">Required.</span></span> <span data-ttu-id="4a688-104">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="4a688-104">device id</span></span>
            </param>
        <param name="containerDetails">
            <span data-ttu-id="4a688-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-105">Required.</span></span> <span data-ttu-id="4a688-106">Parameter für das Erstellen von Volume-Container starten zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="4a688-106">Parameters supplied to the Begin Creating Volume Container operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4a688-107">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-107">Required.</span></span> <span data-ttu-id="4a688-108">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="4a688-108">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4a688-109">Das Erstellen von Volume-Container starten-Vorgang erstellt einen neuen volumecontainer.</span><span class="sxs-lookup"><span data-stu-id="4a688-109">The Begin Creating Volume Container operation creates a new volume container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4a688-110">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="4a688-110">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreatingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginCreatingAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginCreatingAsync (operations, deviceId, containerDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="containerDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4a688-111">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="4a688-111">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4a688-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-112">Required.</span></span> <span data-ttu-id="4a688-113">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="4a688-113">device id</span></span>
            </param>
        <param name="containerDetails">
            <span data-ttu-id="4a688-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-114">Required.</span></span> <span data-ttu-id="4a688-115">Parameter für das Erstellen von Volume-Container starten zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="4a688-115">Parameters supplied to the Begin Creating Volume Container operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4a688-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-116">Required.</span></span> <span data-ttu-id="4a688-117">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="4a688-117">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4a688-118">Das Erstellen von Volume-Container starten-Vorgang erstellt einen neuen volumecontainer.</span><span class="sxs-lookup"><span data-stu-id="4a688-118">The Begin Creating Volume Container operation creates a new volume container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4a688-119">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="4a688-119">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleting">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginDeleting (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginDeleting(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginDeleting(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeleting : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginDeleting (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4a688-120">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="4a688-120">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4a688-121">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-121">Required.</span></span> <span data-ttu-id="4a688-122">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="4a688-122">device id</span></span>
            </param>
        <param name="dataContainerId">
            <span data-ttu-id="4a688-123">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-123">Required.</span></span> <span data-ttu-id="4a688-124">ID des Containers, der gelöscht werden muss</span><span class="sxs-lookup"><span data-stu-id="4a688-124">id of data container which needs to be deleted</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4a688-125">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-125">Required.</span></span> <span data-ttu-id="4a688-126">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="4a688-126">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4a688-127">Das Löschen von Volumecontainer beginnen-Vorgang löscht den angegebenen Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="4a688-127">The Begin Deleting Volume Container operation deletes the specified volume container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4a688-128">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="4a688-128">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeletingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginDeletingAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeletingAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginDeletingAsync (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4a688-129">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="4a688-129">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4a688-130">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-130">Required.</span></span> <span data-ttu-id="4a688-131">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="4a688-131">device id</span></span>
            </param>
        <param name="dataContainerId">
            <span data-ttu-id="4a688-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-132">Required.</span></span> <span data-ttu-id="4a688-133">ID des Containers, der gelöscht werden muss</span><span class="sxs-lookup"><span data-stu-id="4a688-133">id of data container which needs to be deleted</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4a688-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-134">Required.</span></span> <span data-ttu-id="4a688-135">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="4a688-135">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4a688-136">Das Löschen von Volumecontainer beginnen-Vorgang löscht den angegebenen Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="4a688-136">The Begin Deleting Volume Container operation deletes the specified volume container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4a688-137">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="4a688-137">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Create(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Create (operations, deviceId, containerDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="containerDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4a688-138">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="4a688-138">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4a688-139">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-139">Required.</span></span> <span data-ttu-id="4a688-140">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="4a688-140">device id</span></span>
            </param>
        <param name="containerDetails">
            <span data-ttu-id="4a688-141">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-141">Required.</span></span> <span data-ttu-id="4a688-142">Parameter für den Volumecontainer erstellen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="4a688-142">Parameters supplied to the Create Volume Container operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4a688-143">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-143">Required.</span></span> <span data-ttu-id="4a688-144">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="4a688-144">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="4a688-145">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="4a688-145">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.CreateAsync (operations, deviceId, containerDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="containerDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4a688-146">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="4a688-146">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4a688-147">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-147">Required.</span></span> <span data-ttu-id="4a688-148">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="4a688-148">device id</span></span>
            </param>
        <param name="containerDetails">
            <span data-ttu-id="4a688-149">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-149">Required.</span></span> <span data-ttu-id="4a688-150">Parameter für den Volumecontainer erstellen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="4a688-150">Parameters supplied to the Create Volume Container operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4a688-151">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-151">Required.</span></span> <span data-ttu-id="4a688-152">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="4a688-152">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="4a688-153">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="4a688-153">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Delete(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Delete (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4a688-154">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="4a688-154">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4a688-155">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-155">Required.</span></span> <span data-ttu-id="4a688-156">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="4a688-156">device id</span></span>
            </param>
        <param name="dataContainerId">
            <span data-ttu-id="4a688-157">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-157">Required.</span></span> <span data-ttu-id="4a688-158">ID des Containers, der gelöscht werden muss</span><span class="sxs-lookup"><span data-stu-id="4a688-158">id of data container which needs to be deleted</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4a688-159">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-159">Required.</span></span> <span data-ttu-id="4a688-160">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="4a688-160">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="4a688-161">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="4a688-161">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.DeleteAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.DeleteAsync (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4a688-162">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="4a688-162">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4a688-163">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-163">Required.</span></span> <span data-ttu-id="4a688-164">Geräte-id</span><span class="sxs-lookup"><span data-stu-id="4a688-164">device id</span></span>
            </param>
        <param name="dataContainerId">
            <span data-ttu-id="4a688-165">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-165">Required.</span></span> <span data-ttu-id="4a688-166">ID des Containers, der gelöscht werden muss</span><span class="sxs-lookup"><span data-stu-id="4a688-166">id of data container which needs to be deleted</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4a688-167">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a688-167">Required.</span></span> <span data-ttu-id="4a688-168">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="4a688-168">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="4a688-169">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="4a688-169">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Get (operations, deviceId, dataContainerName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4a688-170">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="4a688-170">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4a688-171">Optional.</span><span class="sxs-lookup"><span data-stu-id="4a688-171">Optional.</span></span>
            </param>
        <param name="dataContainerName">
            <span data-ttu-id="4a688-172">Optional.</span><span class="sxs-lookup"><span data-stu-id="4a688-172">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4a688-173">Optional.</span><span class="sxs-lookup"><span data-stu-id="4a688-173">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="4a688-174">Das Antwort-Modell für das Abrufen von Containern.</span><span class="sxs-lookup"><span data-stu-id="4a688-174">The response model for the get of data containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.GetAsync (operations, deviceId, dataContainerName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4a688-175">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="4a688-175">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4a688-176">Optional.</span><span class="sxs-lookup"><span data-stu-id="4a688-176">Optional.</span></span>
            </param>
        <param name="dataContainerName">
            <span data-ttu-id="4a688-177">Optional.</span><span class="sxs-lookup"><span data-stu-id="4a688-177">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4a688-178">Optional.</span><span class="sxs-lookup"><span data-stu-id="4a688-178">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="4a688-179">Das Antwort-Modell für das Abrufen von Containern.</span><span class="sxs-lookup"><span data-stu-id="4a688-179">The response model for the get of data containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse List (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse List(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.List(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.List (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4a688-180">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="4a688-180">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4a688-181">Optional.</span><span class="sxs-lookup"><span data-stu-id="4a688-181">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4a688-182">Optional.</span><span class="sxs-lookup"><span data-stu-id="4a688-182">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="4a688-183">Das Antwort-Modell für die Liste der Datencontainer.</span><span class="sxs-lookup"><span data-stu-id="4a688-183">The response model for the list of data containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse&gt; ListAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse&gt; ListAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.ListAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.ListAsync (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4a688-184">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span><span class="sxs-lookup"><span data-stu-id="4a688-184">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4a688-185">Optional.</span><span class="sxs-lookup"><span data-stu-id="4a688-185">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4a688-186">Optional.</span><span class="sxs-lookup"><span data-stu-id="4a688-186">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="4a688-187">Das Antwort-Modell für die Liste der Datencontainer.</span><span class="sxs-lookup"><span data-stu-id="4a688-187">The response model for the list of data containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>