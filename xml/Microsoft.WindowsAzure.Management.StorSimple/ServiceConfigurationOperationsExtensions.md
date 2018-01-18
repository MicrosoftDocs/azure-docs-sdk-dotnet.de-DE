<Type Name="ServiceConfigurationOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServiceConfigurationOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServiceConfigurationOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServiceConfigurationOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServiceConfigurationOperationsExtensions = class" />
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
            <span data-ttu-id="f7065-101">Dies ist eine RESTFul-API, um Sie StorSimple-Objekte zu verwalten</span><span class="sxs-lookup"><span data-stu-id="f7065-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreating">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreating (this Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreating(class Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.BeginCreating(Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreating : Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.BeginCreating (operations, serviceConfiguration, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations" RefType="this" />
        <Parameter Name="serviceConfiguration" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7065-102">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="f7065-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span></span>
            </param>
        <param name="serviceConfiguration">
            <span data-ttu-id="f7065-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7065-103">Required.</span></span> <span data-ttu-id="f7065-104">Parameter für das Erstellen von Speicherkonto beginnen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="f7065-104">Parameters supplied to the Begin Creating Storage Account operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f7065-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7065-105">Required.</span></span> <span data-ttu-id="f7065-106">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="f7065-106">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7065-107">Der beginnen Erstellen von Speicherkonto-Vorgang erstellt ein neues Speicherkonto in Azure.</span><span class="sxs-lookup"><span data-stu-id="f7065-107">The Begin Creating Storage Account operation creates a new storage account in Azure.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f7065-108">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="f7065-108">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreatingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.BeginCreatingAsync(Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingAsync : Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.BeginCreatingAsync (operations, serviceConfiguration, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations" RefType="this" />
        <Parameter Name="serviceConfiguration" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7065-109">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="f7065-109">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span></span>
            </param>
        <param name="serviceConfiguration">
            <span data-ttu-id="f7065-110">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7065-110">Required.</span></span> <span data-ttu-id="f7065-111">Parameter für das Erstellen von Speicherkonto beginnen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="f7065-111">Parameters supplied to the Begin Creating Storage Account operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f7065-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7065-112">Required.</span></span> <span data-ttu-id="f7065-113">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="f7065-113">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7065-114">Der beginnen Erstellen von Speicherkonto-Vorgang erstellt ein neues Speicherkonto in Azure.</span><span class="sxs-lookup"><span data-stu-id="f7065-114">The Begin Creating Storage Account operation creates a new storage account in Azure.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f7065-115">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="f7065-115">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create (this Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create(class Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.Create(Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.Create (operations, serviceConfiguration, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations" RefType="this" />
        <Parameter Name="serviceConfiguration" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7065-116">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="f7065-116">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span></span>
            </param>
        <param name="serviceConfiguration">
            <span data-ttu-id="f7065-117">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7065-117">Required.</span></span> <span data-ttu-id="f7065-118">Parameter für das Speicherkonto erstellen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="f7065-118">Parameters supplied to the Create Storage Account operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f7065-119">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7065-119">Required.</span></span> <span data-ttu-id="f7065-120">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="f7065-120">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="f7065-121">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="f7065-121">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.CreateAsync (operations, serviceConfiguration, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations" RefType="this" />
        <Parameter Name="serviceConfiguration" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7065-122">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="f7065-122">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span></span>
            </param>
        <param name="serviceConfiguration">
            <span data-ttu-id="f7065-123">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7065-123">Required.</span></span> <span data-ttu-id="f7065-124">Parameter für das Speicherkonto erstellen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="f7065-124">Parameters supplied to the Create Storage Account operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f7065-125">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f7065-125">Required.</span></span> <span data-ttu-id="f7065-126">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="f7065-126">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="f7065-127">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="f7065-127">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customeRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customeRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IServiceConfigurationOperations, customeRequestHeaders As CustomRequestHeaders) As ServiceConfigurationResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.Get (operations, customeRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations" RefType="this" />
        <Parameter Name="customeRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7065-128">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="f7065-128">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span></span>
            </param>
        <param name="customeRequestHeaders">
            <span data-ttu-id="f7065-129">Optional.</span><span class="sxs-lookup"><span data-stu-id="f7065-129">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="f7065-130">Informationen über die Konfiguration des Diensts für die Ressource</span><span class="sxs-lookup"><span data-stu-id="f7065-130">Info about the service configuration regarding the resource</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customeRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customeRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IServiceConfigurationOperations, customeRequestHeaders As CustomRequestHeaders) As Task(Of ServiceConfigurationResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.GetAsync (operations, customeRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations" RefType="this" />
        <Parameter Name="customeRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7065-131">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="f7065-131">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span></span>
            </param>
        <param name="customeRequestHeaders">
            <span data-ttu-id="f7065-132">Optional.</span><span class="sxs-lookup"><span data-stu-id="f7065-132">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="f7065-133">Informationen über die Konfiguration des Diensts für die Ressource</span><span class="sxs-lookup"><span data-stu-id="f7065-133">Info about the service configuration regarding the resource</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>