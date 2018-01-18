<Type Name="IndexerExecutionInfo" FullName="Microsoft.Azure.Search.Models.IndexerExecutionInfo">
  <TypeSignature Language="C#" Value="public class IndexerExecutionInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexerExecutionInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexerExecutionInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexerExecutionInfo" />
  <TypeSignature Language="F#" Value="type IndexerExecutionInfo = class" />
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
            <span data-ttu-id="f2ae5-101">Stellt den aktuellen Status und Ausführungsverlauf eines Indexers dar.</span><span class="sxs-lookup"><span data-stu-id="f2ae5-101">Represents the current status and execution history of an indexer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexerExecutionInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexerExecutionInfo.#ctor" />
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
            <span data-ttu-id="f2ae5-102">Initialisiert eine neue Instanz der "indexerexecutioninfo"-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f2ae5-102">Initializes a new instance of the IndexerExecutionInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexerExecutionInfo (Microsoft.Azure.Search.Models.IndexerStatus status = Microsoft.Azure.Search.Models.IndexerStatus.Unknown, Microsoft.Azure.Search.Models.IndexerExecutionResult lastResult = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexerExecutionResult&gt; executionHistory = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Search.Models.IndexerStatus status, class Microsoft.Azure.Search.Models.IndexerExecutionResult lastResult, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.IndexerExecutionResult&gt; executionHistory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexerExecutionInfo.#ctor(Microsoft.Azure.Search.Models.IndexerStatus,Microsoft.Azure.Search.Models.IndexerExecutionResult,System.Collections.Generic.IList{Microsoft.Azure.Search.Models.IndexerExecutionResult})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional status As IndexerStatus = Microsoft.Azure.Search.Models.IndexerStatus.Unknown, Optional lastResult As IndexerExecutionResult = null, Optional executionHistory As IList(Of IndexerExecutionResult) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexerExecutionInfo : Microsoft.Azure.Search.Models.IndexerStatus * Microsoft.Azure.Search.Models.IndexerExecutionResult * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexerExecutionResult&gt; -&gt; Microsoft.Azure.Search.Models.IndexerExecutionInfo" Usage="new Microsoft.Azure.Search.Models.IndexerExecutionInfo (status, lastResult, executionHistory)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="Microsoft.Azure.Search.Models.IndexerStatus" />
        <Parameter Name="lastResult" Type="Microsoft.Azure.Search.Models.IndexerExecutionResult" />
        <Parameter Name="executionHistory" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexerExecutionResult&gt;" />
      </Parameters>
      <Docs>
        <param name="status"><span data-ttu-id="f2ae5-103">Gesamtstatus des Indexers.</span><span class="sxs-lookup"><span data-stu-id="f2ae5-103">Overall indexer status.</span></span> <span data-ttu-id="f2ae5-104">Folgende Werte sind möglich: "unknown", "Fehler", "wird ausgeführt"</span><span class="sxs-lookup"><span data-stu-id="f2ae5-104">Possible values include: 'unknown', 'error', 'running'</span></span></param>
        <param name="lastResult"><span data-ttu-id="f2ae5-105">Das Ergebnis des letzten oder einer aktiven indexerausführung.</span><span class="sxs-lookup"><span data-stu-id="f2ae5-105">The result of the most recent or an in-progress indexer execution.</span></span></param>
        <param name="executionHistory"><span data-ttu-id="f2ae5-106">Verlauf der letzten indexerausführungen, sortiert in umgekehrter chronologischer Reihenfolge.</span><span class="sxs-lookup"><span data-stu-id="f2ae5-106">History of the recent indexer executions, sorted in reverse chronological order.</span></span></param>
        <summary>
            <span data-ttu-id="f2ae5-107">Initialisiert eine neue Instanz der "indexerexecutioninfo"-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f2ae5-107">Initializes a new instance of the IndexerExecutionInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionHistory">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexerExecutionResult&gt; ExecutionHistory { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.IndexerExecutionResult&gt; ExecutionHistory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexerExecutionInfo.ExecutionHistory" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutionHistory As IList(Of IndexerExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.ExecutionHistory : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexerExecutionResult&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexerExecutionInfo.ExecutionHistory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="executionHistory")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexerExecutionResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2ae5-108">Ruft die Verlauf der letzten indexerausführungen, sortiert in umgekehrter chronologischer Reihenfolge.</span><span class="sxs-lookup"><span data-stu-id="f2ae5-108">Gets history of the recent indexer executions, sorted in reverse chronological order.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastResult">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.IndexerExecutionResult LastResult { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.IndexerExecutionResult LastResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexerExecutionInfo.LastResult" />
      <MemberSignature Language="VB.NET" Value="Public Property LastResult As IndexerExecutionResult" />
      <MemberSignature Language="F#" Value="member this.LastResult : Microsoft.Azure.Search.Models.IndexerExecutionResult with get, set" Usage="Microsoft.Azure.Search.Models.IndexerExecutionInfo.LastResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastResult")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexerExecutionResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2ae5-109">Ruft das Ergebnis des letzten oder einer aktiven indexerausführung ab.</span><span class="sxs-lookup"><span data-stu-id="f2ae5-109">Gets the result of the most recent or an in-progress indexer execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.IndexerStatus Status { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Search.Models.IndexerStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexerExecutionInfo.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As IndexerStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Search.Models.IndexerStatus with get, set" Usage="Microsoft.Azure.Search.Models.IndexerExecutionInfo.Status" />
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
        <ReturnType>Microsoft.Azure.Search.Models.IndexerStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2ae5-110">Ruft die Gesamtstatus des Indexers ab.</span><span class="sxs-lookup"><span data-stu-id="f2ae5-110">Gets overall indexer status.</span></span> <span data-ttu-id="f2ae5-111">Folgende Werte sind möglich: "unknown", "Fehler", "wird ausgeführt"</span><span class="sxs-lookup"><span data-stu-id="f2ae5-111">Possible values include: 'unknown', 'error', 'running'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>