<Type Name="RecurrenceOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecurrenceOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecurrenceOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecurrenceOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecurrenceOperationsExtensions = class" />
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
            <span data-ttu-id="3f796-101">Erweiterungsmethoden für RecurrenceOperations.</span><span class="sxs-lookup"><span data-stu-id="3f796-101">Extension methods for RecurrenceOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation Get (this Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations operations, string accountName, Guid recurrenceIdentity, Nullable&lt;DateTimeOffset&gt; startDateTime = null, Nullable&lt;DateTimeOffset&gt; endDateTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation Get(class Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations operations, string accountName, valuetype System.Guid recurrenceIdentity, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startDateTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endDateTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations,System.String,System.Guid,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRecurrenceOperations, accountName As String, recurrenceIdentity As Guid, Optional startDateTime As Nullable(Of DateTimeOffset) = null, Optional endDateTime As Nullable(Of DateTimeOffset) = null) As JobRecurrenceInformation" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations * string * Guid * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation" Usage="Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions.Get (operations, accountName, recurrenceIdentity, startDateTime, endDateTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="recurrenceIdentity" Type="System.Guid" />
        <Parameter Name="startDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f796-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f796-102">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="3f796-103">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="3f796-103">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="recurrenceIdentity">
            <span data-ttu-id="3f796-104">Wiederholung-ID.</span><span class="sxs-lookup"><span data-stu-id="3f796-104">Recurrence ID.</span></span>
            </param>
        <param name="startDateTime">
            <span data-ttu-id="3f796-105">Das Startdatum für die die Wiederholung abrufen und seine Daten aggregieren.</span><span class="sxs-lookup"><span data-stu-id="3f796-105">The start date for when to get the recurrence and aggregate its data.</span></span> <span data-ttu-id="3f796-106">Die %StartDateTime;) und EndDateTime können nicht mehr als 30 Tage auseinander sein.</span><span class="sxs-lookup"><span data-stu-id="3f796-106">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="endDateTime">
            <span data-ttu-id="3f796-107">Das Enddatum für die Wiederholung erhalten und ihre Daten zu aggregieren.</span><span class="sxs-lookup"><span data-stu-id="3f796-107">The end date for when to get recurrence and aggregate its data.</span></span> <span data-ttu-id="3f796-108">Die %StartDateTime;) und EndDateTime können nicht mehr als 30 Tage auseinander sein.</span><span class="sxs-lookup"><span data-stu-id="3f796-108">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f796-109">Ruft die Wiederholungsinformationen für die angegebene Serie-ID.</span><span class="sxs-lookup"><span data-stu-id="3f796-109">Gets the recurrence information for the specified recurrence ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations operations, string accountName, Guid recurrenceIdentity, Nullable&lt;DateTimeOffset&gt; startDateTime = null, Nullable&lt;DateTimeOffset&gt; endDateTime = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations operations, string accountName, valuetype System.Guid recurrenceIdentity, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startDateTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endDateTime, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations,System.String,System.Guid,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations * string * Guid * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions.GetAsync (operations, accountName, recurrenceIdentity, startDateTime, endDateTime, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="recurrenceIdentity" Type="System.Guid" />
        <Parameter Name="startDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f796-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f796-110">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="3f796-111">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="3f796-111">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="recurrenceIdentity">
            <span data-ttu-id="3f796-112">Wiederholung-ID.</span><span class="sxs-lookup"><span data-stu-id="3f796-112">Recurrence ID.</span></span>
            </param>
        <param name="startDateTime">
            <span data-ttu-id="3f796-113">Das Startdatum für die die Wiederholung abrufen und seine Daten aggregieren.</span><span class="sxs-lookup"><span data-stu-id="3f796-113">The start date for when to get the recurrence and aggregate its data.</span></span> <span data-ttu-id="3f796-114">Die %StartDateTime;) und EndDateTime können nicht mehr als 30 Tage auseinander sein.</span><span class="sxs-lookup"><span data-stu-id="3f796-114">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="endDateTime">
            <span data-ttu-id="3f796-115">Das Enddatum für die Wiederholung erhalten und ihre Daten zu aggregieren.</span><span class="sxs-lookup"><span data-stu-id="3f796-115">The end date for when to get recurrence and aggregate its data.</span></span> <span data-ttu-id="3f796-116">Die %StartDateTime;) und EndDateTime können nicht mehr als 30 Tage auseinander sein.</span><span class="sxs-lookup"><span data-stu-id="3f796-116">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f796-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f796-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f796-118">Ruft die Wiederholungsinformationen für die angegebene Serie-ID.</span><span class="sxs-lookup"><span data-stu-id="3f796-118">Gets the recurrence information for the specified recurrence ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt; List (this Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations operations, string accountName, Nullable&lt;DateTimeOffset&gt; startDateTime = null, Nullable&lt;DateTimeOffset&gt; endDateTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt; List(class Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations operations, string accountName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startDateTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endDateTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions.List(Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations,System.String,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IRecurrenceOperations, accountName As String, Optional startDateTime As Nullable(Of DateTimeOffset) = null, Optional endDateTime As Nullable(Of DateTimeOffset) = null) As IPage(Of JobRecurrenceInformation)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations * string * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions.List (operations, accountName, startDateTime, endDateTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="startDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f796-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f796-119">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="3f796-120">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="3f796-120">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="startDateTime">
            <span data-ttu-id="3f796-121">Das Startdatum für die Ausführung zum Abrufen der Liste der Wiederholungen.</span><span class="sxs-lookup"><span data-stu-id="3f796-121">The start date for when to get the list of recurrences.</span></span> <span data-ttu-id="3f796-122">Die %StartDateTime;) und EndDateTime können nicht mehr als 30 Tage auseinander sein.</span><span class="sxs-lookup"><span data-stu-id="3f796-122">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="endDateTime">
            <span data-ttu-id="3f796-123">Das Enddatum für den Fall zum Abrufen der Liste der Wiederholungen.</span><span class="sxs-lookup"><span data-stu-id="3f796-123">The end date for when to get the list of recurrences.</span></span> <span data-ttu-id="3f796-124">Die %StartDateTime;) und EndDateTime können nicht mehr als 30 Tage auseinander sein.</span><span class="sxs-lookup"><span data-stu-id="3f796-124">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f796-125">Listet alle Wiederholungen an.</span><span class="sxs-lookup"><span data-stu-id="3f796-125">Lists all recurrences.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt; ListAsync (this Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations operations, string accountName, Nullable&lt;DateTimeOffset&gt; startDateTime = null, Nullable&lt;DateTimeOffset&gt; endDateTime = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt; ListAsync(class Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations operations, string accountName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startDateTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endDateTime, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations,System.String,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations * string * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions.ListAsync (operations, accountName, startDateTime, endDateTime, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="startDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f796-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f796-126">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="3f796-127">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="3f796-127">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="startDateTime">
            <span data-ttu-id="3f796-128">Das Startdatum für die Ausführung zum Abrufen der Liste der Wiederholungen.</span><span class="sxs-lookup"><span data-stu-id="3f796-128">The start date for when to get the list of recurrences.</span></span> <span data-ttu-id="3f796-129">Die %StartDateTime;) und EndDateTime können nicht mehr als 30 Tage auseinander sein.</span><span class="sxs-lookup"><span data-stu-id="3f796-129">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="endDateTime">
            <span data-ttu-id="3f796-130">Das Enddatum für den Fall zum Abrufen der Liste der Wiederholungen.</span><span class="sxs-lookup"><span data-stu-id="3f796-130">The end date for when to get the list of recurrences.</span></span> <span data-ttu-id="3f796-131">Die %StartDateTime;) und EndDateTime können nicht mehr als 30 Tage auseinander sein.</span><span class="sxs-lookup"><span data-stu-id="3f796-131">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f796-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f796-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f796-133">Listet alle Wiederholungen an.</span><span class="sxs-lookup"><span data-stu-id="3f796-133">Lists all recurrences.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt; ListNext (this Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt; ListNext(class Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions.ListNext(Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IRecurrenceOperations, nextPageLink As String) As IPage(Of JobRecurrenceInformation)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f796-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f796-134">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3f796-135">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3f796-135">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f796-136">Listet alle Wiederholungen an.</span><span class="sxs-lookup"><span data-stu-id="3f796-136">Lists all recurrences.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.RecurrenceOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f796-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f796-137">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3f796-138">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3f796-138">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f796-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f796-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f796-140">Listet alle Wiederholungen an.</span><span class="sxs-lookup"><span data-stu-id="3f796-140">Lists all recurrences.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>