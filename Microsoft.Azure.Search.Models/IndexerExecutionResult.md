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
            Stellt das Ergebnis einer einzelnen indexerausführung dar.
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
            Initialisiert eine neue Instanz der "indexerexecutionresult"-Klasse.
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
        <param name="status">Das Ergebnis dieser indexerausführung.
            Folgende Werte sind möglich: "TransientFailure", "Success", "InProgress", "Zurücksetzen"</param>
        <param name="errorMessage">Die Fehlermeldung, der angibt, die Fehlers des obersten Ebene, sofern vorhanden.</param>
        <param name="startTime">Die Startzeit dieser indexerausführung.</param>
        <param name="endTime">Die Endzeit dieser indexerausführung, wenn die Ausführung bereits abgeschlossen wurde.</param>
        <param name="errors">Die Indizierung auf Elementebene-Fehler.</param>
        <param name="itemCount">Die Anzahl der Elemente, die während dieser indexerausführung verarbeitet wurden. Dies schließt sowohl erfolgreich verarbeitete Elemente und Elemente, in denen die Indizierung versucht aber fehlgeschlagen ist.</param>
        <param name="failedItemCount">Die Anzahl der Elemente, die während dieser indexerausführung indiziert werden konnten.</param>
        <param name="initialTrackingState">Ändern Sie Nachverfolgungsstatus mit dem eine indexerausführung gestartet.</param>
        <param name="finalTrackingState">Ändern Sie Nachverfolgungsstatus mit dem eine indexerausführung abgeschlossen.</param>
        <summary>
            Initialisiert eine neue Instanz der "indexerexecutionresult"-Klasse.
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
            Ruft die Endzeit dieser indexerausführung ab, wenn die Ausführung bereits abgeschlossen wurde.
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
            Ruft die Fehlermeldung ab, der angibt, die Fehlers des obersten Ebene, sofern vorhanden.
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
            Ruft die Elementebene Fehler indizieren.
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
            Ruft die Anzahl der Elemente, die während dieser indexerausführung indiziert werden konnten.
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
            Ruft ändern Nachverfolgungsstatus mit dem eine indexerausführung abgeschlossen.
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
            Ruft ändern Nachverfolgungsstatus mit dem eine indexerausführung gestartet.
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
            Ruft die Anzahl der Elemente, die während dieser indexerausführung verarbeitet wurden. Dies schließt sowohl erfolgreich verarbeitete Elemente und Elemente, in denen die Indizierung versucht aber fehlgeschlagen ist.
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
            Ruft die Startzeit dieser indexerausführung ab.
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
            Ruft das Ergebnis dieser indexerausführung ab. Folgende Werte sind möglich: "TransientFailure", "Success", "InProgress", "Zurücksetzen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>