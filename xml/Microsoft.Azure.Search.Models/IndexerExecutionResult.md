<Type Name="IndexerExecutionResult" FullName="Microsoft.Azure.Search.Models.IndexerExecutionResult">
  <TypeSignature Language="C#" Value="public class IndexerExecutionResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexerExecutionResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexerExecutionResult" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexerExecutionResult" />
  <TypeSignature Language="F#" Value="type IndexerExecutionResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bb404-101">Stellt das Ergebnis einer einzelnen indexerausführung dar.</span><span class="sxs-lookup"><span data-stu-id="bb404-101">Represents the result of an individual indexer execution.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexerExecutionResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexerExecutionResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bb404-102">Initialisiert eine neue Instanz der "indexerexecutionresult"-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bb404-102">Initializes a new instance of the IndexerExecutionResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexerExecutionResult (Microsoft.Azure.Search.Models.IndexerExecutionStatus status = Microsoft.Azure.Search.Models.IndexerExecutionStatus.TransientFailure, string errorMessage = null, Nullable&lt;DateTimeOffset&gt; startTime = null, Nullable&lt;DateTimeOffset&gt; endTime = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ItemError&gt; errors = null, int itemCount = 0, int failedItemCount = 0, string initialTrackingState = null, string finalTrackingState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Search.Models.IndexerExecutionStatus status, string errorMessage, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.ItemError&gt; errors, int32 itemCount, int32 failedItemCount, string initialTrackingState, string finalTrackingState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexerExecutionResult.#ctor(Microsoft.Azure.Search.Models.IndexerExecutionStatus,System.String,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Collections.Generic.IList{Microsoft.Azure.Search.Models.ItemError},System.Int32,System.Int32,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional status As IndexerExecutionStatus = Microsoft.Azure.Search.Models.IndexerExecutionStatus.TransientFailure, Optional errorMessage As String = null, Optional startTime As Nullable(Of DateTimeOffset) = null, Optional endTime As Nullable(Of DateTimeOffset) = null, Optional errors As IList(Of ItemError) = null, Optional itemCount As Integer = 0, Optional failedItemCount As Integer = 0, Optional initialTrackingState As String = null, Optional finalTrackingState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexerExecutionResult : Microsoft.Azure.Search.Models.IndexerExecutionStatus * string * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ItemError&gt; * int * int * string * string -&gt; Microsoft.Azure.Search.Models.IndexerExecutionResult" Usage="new Microsoft.Azure.Search.Models.IndexerExecutionResult (status, errorMessage, startTime, endTime, errors, itemCount, failedItemCount, initialTrackingState, finalTrackingState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="Microsoft.Azure.Search.Models.IndexerExecutionStatus" />
        <Parameter Name="errorMessage" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="errors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ItemError&gt;" />
        <Parameter Name="itemCount" Type="System.Int32" />
        <Parameter Name="failedItemCount" Type="System.Int32" />
        <Parameter Name="initialTrackingState" Type="System.String" />
        <Parameter Name="finalTrackingState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="status"><span data-ttu-id="bb404-103">Das Ergebnis dieser indexerausführung.</span><span class="sxs-lookup"><span data-stu-id="bb404-103">The outcome of this indexer execution.</span></span>
            <span data-ttu-id="bb404-104">Folgende Werte sind möglich: "TransientFailure", "Success", "InProgress", "Zurücksetzen"</span><span class="sxs-lookup"><span data-stu-id="bb404-104">Possible values include: 'transientFailure', 'success', 'inProgress', 'reset'</span></span></param>
        <param name="errorMessage"><span data-ttu-id="bb404-105">Die Fehlermeldung, der angibt, die Fehlers des obersten Ebene, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="bb404-105">The error message indicating the top-level error, if any.</span></span></param>
        <param name="startTime"><span data-ttu-id="bb404-106">Die Startzeit dieser indexerausführung.</span><span class="sxs-lookup"><span data-stu-id="bb404-106">The start time of this indexer execution.</span></span></param>
        <param name="endTime"><span data-ttu-id="bb404-107">Die Endzeit dieser indexerausführung, wenn die Ausführung bereits abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="bb404-107">The end time of this indexer execution, if the execution has already completed.</span></span></param>
        <param name="errors"><span data-ttu-id="bb404-108">Die Indizierung auf Elementebene-Fehler.</span><span class="sxs-lookup"><span data-stu-id="bb404-108">The item-level indexing errors.</span></span></param>
        <param name="itemCount"><span data-ttu-id="bb404-109">Die Anzahl der Elemente, die während dieser indexerausführung verarbeitet wurden.</span><span class="sxs-lookup"><span data-stu-id="bb404-109">The number of items that were processed during this indexer execution.</span></span> <span data-ttu-id="bb404-110">Dies schließt sowohl erfolgreich verarbeitete Elemente und Elemente, in denen die Indizierung versucht aber fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="bb404-110">This includes both successfully processed items and items where indexing was attempted but failed.</span></span></param>
        <param name="failedItemCount"><span data-ttu-id="bb404-111">Die Anzahl der Elemente, die während dieser indexerausführung indiziert werden konnten.</span><span class="sxs-lookup"><span data-stu-id="bb404-111">The number of items that failed to be indexed during this indexer execution.</span></span></param>
        <param name="initialTrackingState"><span data-ttu-id="bb404-112">Ändern Sie Nachverfolgungsstatus mit dem eine indexerausführung gestartet.</span><span class="sxs-lookup"><span data-stu-id="bb404-112">Change tracking state with which an indexer execution started.</span></span></param>
        <param name="finalTrackingState"><span data-ttu-id="bb404-113">Ändern Sie Nachverfolgungsstatus mit dem eine indexerausführung abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="bb404-113">Change tracking state with which an indexer execution finished.</span></span></param>
        <summary>
            <span data-ttu-id="bb404-114">Initialisiert eine neue Instanz der "indexerexecutionresult"-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bb404-114">Initializes a new instance of the IndexerExecutionResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; EndTime { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexerExecutionResult.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexerExecutionResult.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb404-115">Ruft die Endzeit dieser indexerausführung ab, wenn die Ausführung bereits abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="bb404-115">Gets the end time of this indexer execution, if the execution has already completed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexerExecutionResult.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string with get, set" Usage="Microsoft.Azure.Search.Models.IndexerExecutionResult.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb404-116">Ruft die Fehlermeldung ab, der angibt, die Fehlers des obersten Ebene, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="bb404-116">Gets the error message indicating the top-level error, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ItemError&gt; Errors { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.ItemError&gt; Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexerExecutionResult.Errors" />
      <MemberSignature Language="VB.NET" Value="Public Property Errors As IList(Of ItemError)" />
      <MemberSignature Language="F#" Value="member this.Errors : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ItemError&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexerExecutionResult.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ItemError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb404-117">Ruft die Elementebene Fehler indizieren.</span><span class="sxs-lookup"><span data-stu-id="bb404-117">Gets the item-level indexing errors.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailedItemCount">
      <MemberSignature Language="C#" Value="public int FailedItemCount { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FailedItemCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexerExecutionResult.FailedItemCount" />
      <MemberSignature Language="VB.NET" Value="Public Property FailedItemCount As Integer" />
      <MemberSignature Language="F#" Value="member this.FailedItemCount : int with get, set" Usage="Microsoft.Azure.Search.Models.IndexerExecutionResult.FailedItemCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="itemsFailed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb404-118">Ruft die Anzahl der Elemente, die während dieser indexerausführung indiziert werden konnten.</span><span class="sxs-lookup"><span data-stu-id="bb404-118">Gets the number of items that failed to be indexed during this indexer execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FinalTrackingState">
      <MemberSignature Language="C#" Value="public string FinalTrackingState { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FinalTrackingState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexerExecutionResult.FinalTrackingState" />
      <MemberSignature Language="VB.NET" Value="Public Property FinalTrackingState As String" />
      <MemberSignature Language="F#" Value="member this.FinalTrackingState : string with get, set" Usage="Microsoft.Azure.Search.Models.IndexerExecutionResult.FinalTrackingState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="finalTrackingState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb404-119">Ruft ändern Nachverfolgungsstatus mit dem eine indexerausführung abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="bb404-119">Gets change tracking state with which an indexer execution finished.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialTrackingState">
      <MemberSignature Language="C#" Value="public string InitialTrackingState { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InitialTrackingState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexerExecutionResult.InitialTrackingState" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialTrackingState As String" />
      <MemberSignature Language="F#" Value="member this.InitialTrackingState : string with get, set" Usage="Microsoft.Azure.Search.Models.IndexerExecutionResult.InitialTrackingState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="initialTrackingState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb404-120">Ruft ändern Nachverfolgungsstatus mit dem eine indexerausführung gestartet.</span><span class="sxs-lookup"><span data-stu-id="bb404-120">Gets change tracking state with which an indexer execution started.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ItemCount">
      <MemberSignature Language="C#" Value="public int ItemCount { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ItemCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexerExecutionResult.ItemCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ItemCount As Integer" />
      <MemberSignature Language="F#" Value="member this.ItemCount : int with get, set" Usage="Microsoft.Azure.Search.Models.IndexerExecutionResult.ItemCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="itemsProcessed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb404-121">Ruft die Anzahl der Elemente, die während dieser indexerausführung verarbeitet wurden.</span><span class="sxs-lookup"><span data-stu-id="bb404-121">Gets the number of items that were processed during this indexer execution.</span></span> <span data-ttu-id="bb404-122">Dies schließt sowohl erfolgreich verarbeitete Elemente und Elemente, in denen die Indizierung versucht aber fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="bb404-122">This includes both successfully processed items and items where indexing was attempted but failed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; StartTime { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexerExecutionResult.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexerExecutionResult.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb404-123">Ruft die Startzeit dieser indexerausführung ab.</span><span class="sxs-lookup"><span data-stu-id="bb404-123">Gets the start time of this indexer execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.IndexerExecutionStatus Status { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Search.Models.IndexerExecutionStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexerExecutionResult.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As IndexerExecutionStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Search.Models.IndexerExecutionStatus with get, set" Usage="Microsoft.Azure.Search.Models.IndexerExecutionResult.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexerExecutionStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb404-124">Ruft das Ergebnis dieser indexerausführung ab.</span><span class="sxs-lookup"><span data-stu-id="bb404-124">Gets the outcome of this indexer execution.</span></span> <span data-ttu-id="bb404-125">Folgende Werte sind möglich: "TransientFailure", "Success", "InProgress", "Zurücksetzen"</span><span class="sxs-lookup"><span data-stu-id="bb404-125">Possible values include: 'transientFailure', 'success', 'inProgress', 'reset'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>