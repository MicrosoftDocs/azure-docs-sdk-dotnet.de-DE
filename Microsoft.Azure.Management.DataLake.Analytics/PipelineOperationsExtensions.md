<Type Name="PipelineOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PipelineOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PipelineOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PipelineOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PipelineOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f1248-101">Erweiterungsmethoden für PipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="f1248-101">Extension methods for PipelineOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation Get (this Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string accountName, Guid pipelineIdentity, Nullable&lt;DateTimeOffset&gt; startDateTime = null, Nullable&lt;DateTimeOffset&gt; endDateTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation Get(class Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string accountName, valuetype System.Guid pipelineIdentity, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startDateTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endDateTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations,System.String,System.Guid,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPipelineOperations, accountName As String, pipelineIdentity As Guid, Optional startDateTime As Nullable(Of DateTimeOffset) = null, Optional endDateTime As Nullable(Of DateTimeOffset) = null) As JobPipelineInformation" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations * string * Guid * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation" Usage="Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.Get (operations, accountName, pipelineIdentity, startDateTime, endDateTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="pipelineIdentity" Type="System.Guid" />
        <Parameter Name="startDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f1248-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f1248-102">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f1248-103">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f1248-103">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="pipelineIdentity">
            <span data-ttu-id="f1248-104">Pipeline-ID.</span><span class="sxs-lookup"><span data-stu-id="f1248-104">Pipeline ID.</span></span>
            </param>
        <param name="startDateTime">
            <span data-ttu-id="f1248-105">Das Startdatum für die Ausführung die Pipeline abgerufen und seine Daten aggregieren.</span><span class="sxs-lookup"><span data-stu-id="f1248-105">The start date for when to get the pipeline and aggregate its data.</span></span> <span data-ttu-id="f1248-106">Die %StartDateTime;) und EndDateTime können nicht mehr als 30 Tage auseinander sein.</span><span class="sxs-lookup"><span data-stu-id="f1248-106">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="endDateTime">
            <span data-ttu-id="f1248-107">Das Enddatum für die Ausführung die Pipeline abgerufen und seine Daten aggregieren.</span><span class="sxs-lookup"><span data-stu-id="f1248-107">The end date for when to get the pipeline and aggregate its data.</span></span> <span data-ttu-id="f1248-108">Die %StartDateTime;) und EndDateTime können nicht mehr als 30 Tage auseinander sein.</span><span class="sxs-lookup"><span data-stu-id="f1248-108">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f1248-109">Ruft die Pipeline-Informationen für die angegebene Pipeline-ID.</span><span class="sxs-lookup"><span data-stu-id="f1248-109">Gets the Pipeline information for the specified pipeline ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string accountName, Guid pipelineIdentity, Nullable&lt;DateTimeOffset&gt; startDateTime = null, Nullable&lt;DateTimeOffset&gt; endDateTime = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string accountName, valuetype System.Guid pipelineIdentity, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startDateTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endDateTime, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations,System.String,System.Guid,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations * string * Guid * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.GetAsync (operations, accountName, pipelineIdentity, startDateTime, endDateTime, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="pipelineIdentity" Type="System.Guid" />
        <Parameter Name="startDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f1248-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f1248-110">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f1248-111">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f1248-111">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="pipelineIdentity">
            <span data-ttu-id="f1248-112">Pipeline-ID.</span><span class="sxs-lookup"><span data-stu-id="f1248-112">Pipeline ID.</span></span>
            </param>
        <param name="startDateTime">
            <span data-ttu-id="f1248-113">Das Startdatum für die Ausführung die Pipeline abgerufen und seine Daten aggregieren.</span><span class="sxs-lookup"><span data-stu-id="f1248-113">The start date for when to get the pipeline and aggregate its data.</span></span> <span data-ttu-id="f1248-114">Die %StartDateTime;) und EndDateTime können nicht mehr als 30 Tage auseinander sein.</span><span class="sxs-lookup"><span data-stu-id="f1248-114">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="endDateTime">
            <span data-ttu-id="f1248-115">Das Enddatum für die Ausführung die Pipeline abgerufen und seine Daten aggregieren.</span><span class="sxs-lookup"><span data-stu-id="f1248-115">The end date for when to get the pipeline and aggregate its data.</span></span> <span data-ttu-id="f1248-116">Die %StartDateTime;) und EndDateTime können nicht mehr als 30 Tage auseinander sein.</span><span class="sxs-lookup"><span data-stu-id="f1248-116">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f1248-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f1248-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f1248-118">Ruft die Pipeline-Informationen für die angegebene Pipeline-ID.</span><span class="sxs-lookup"><span data-stu-id="f1248-118">Gets the Pipeline information for the specified pipeline ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt; List (this Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string accountName, Nullable&lt;DateTimeOffset&gt; startDateTime = null, Nullable&lt;DateTimeOffset&gt; endDateTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt; List(class Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string accountName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startDateTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endDateTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.List(Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations,System.String,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IPipelineOperations, accountName As String, Optional startDateTime As Nullable(Of DateTimeOffset) = null, Optional endDateTime As Nullable(Of DateTimeOffset) = null) As IPage(Of JobPipelineInformation)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations * string * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.List (operations, accountName, startDateTime, endDateTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="startDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f1248-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f1248-119">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f1248-120">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f1248-120">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="startDateTime">
            <span data-ttu-id="f1248-121">Das Startdatum für die Ausführung zum Abrufen der Liste der Pipelines.</span><span class="sxs-lookup"><span data-stu-id="f1248-121">The start date for when to get the list of pipelines.</span></span> <span data-ttu-id="f1248-122">Die %StartDateTime;) und EndDateTime können nicht mehr als 30 Tage auseinander sein.</span><span class="sxs-lookup"><span data-stu-id="f1248-122">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="endDateTime">
            <span data-ttu-id="f1248-123">Das Enddatum für den Fall zum Abrufen der Liste der Pipelines.</span><span class="sxs-lookup"><span data-stu-id="f1248-123">The end date for when to get the list of pipelines.</span></span> <span data-ttu-id="f1248-124">Die %StartDateTime;) und EndDateTime können nicht mehr als 30 Tage auseinander sein.</span><span class="sxs-lookup"><span data-stu-id="f1248-124">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f1248-125">Listet alle Pipelines.</span><span class="sxs-lookup"><span data-stu-id="f1248-125">Lists all pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;&gt; ListAsync (this Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string accountName, Nullable&lt;DateTimeOffset&gt; startDateTime = null, Nullable&lt;DateTimeOffset&gt; endDateTime = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;&gt; ListAsync(class Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string accountName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startDateTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endDateTime, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations,System.String,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations * string * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.ListAsync (operations, accountName, startDateTime, endDateTime, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="startDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f1248-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f1248-126">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f1248-127">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f1248-127">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="startDateTime">
            <span data-ttu-id="f1248-128">Das Startdatum für die Ausführung zum Abrufen der Liste der Pipelines.</span><span class="sxs-lookup"><span data-stu-id="f1248-128">The start date for when to get the list of pipelines.</span></span> <span data-ttu-id="f1248-129">Die %StartDateTime;) und EndDateTime können nicht mehr als 30 Tage auseinander sein.</span><span class="sxs-lookup"><span data-stu-id="f1248-129">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="endDateTime">
            <span data-ttu-id="f1248-130">Das Enddatum für den Fall zum Abrufen der Liste der Pipelines.</span><span class="sxs-lookup"><span data-stu-id="f1248-130">The end date for when to get the list of pipelines.</span></span> <span data-ttu-id="f1248-131">Die %StartDateTime;) und EndDateTime können nicht mehr als 30 Tage auseinander sein.</span><span class="sxs-lookup"><span data-stu-id="f1248-131">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f1248-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f1248-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f1248-133">Listet alle Pipelines.</span><span class="sxs-lookup"><span data-stu-id="f1248-133">Lists all pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt; ListNext (this Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt; ListNext(class Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.ListNext(Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IPipelineOperations, nextPageLink As String) As IPage(Of JobPipelineInformation)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f1248-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f1248-134">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f1248-135">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f1248-135">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f1248-136">Listet alle Pipelines.</span><span class="sxs-lookup"><span data-stu-id="f1248-136">Lists all pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f1248-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f1248-137">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f1248-138">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f1248-138">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f1248-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f1248-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f1248-140">Listet alle Pipelines.</span><span class="sxs-lookup"><span data-stu-id="f1248-140">Lists all pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>