<Type Name="TaskAddResult" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskAddResult">
  <TypeSignature Language="C#" Value="public class TaskAddResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskAddResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskAddResult" />
  <TypeSignature Language="F#" Value="type TaskAddResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Auslöser für eine einzelne Aufgabe, die als Teil einer Auflistung Vorgangs zum Hinzufügen eines Tasks hinzugefügt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskAddResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der TaskAddResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskAddResult (Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus status, string taskId, string eTag = null, Nullable&lt;DateTime&gt; lastModified = null, string location = null, Microsoft.Azure.Batch.Protocol.Models.BatchError error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus status, string taskId, string eTag, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, string location, class Microsoft.Azure.Batch.Protocol.Models.BatchError error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.#ctor(Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus,System.String,System.String,System.Nullable{System.DateTime},System.String,Microsoft.Azure.Batch.Protocol.Models.BatchError)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (status As TaskAddStatus, taskId As String, Optional eTag As String = null, Optional lastModified As Nullable(Of DateTime) = null, Optional location As String = null, Optional error As BatchError = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskAddResult : Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus * string * string * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Batch.Protocol.Models.BatchError -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskAddResult" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskAddResult (status, taskId, eTag, lastModified, location, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="error" Type="Microsoft.Azure.Batch.Protocol.Models.BatchError" />
      </Parameters>
      <Docs>
        <param name="status">Der Status der Anforderung Aufgabe hinzufügen.</param>
        <param name="taskId">Die ID des Tasks "für die dies das Ergebnis ist".</param>
        <param name="eTag">Das ETag der Aufgabe, wenn der Task erfolgreich hinzugefügt wurde.</param>
        <param name="lastModified">Uhrzeit des Tasks werden in der letzten Änderung.</param>
        <param name="location">Die URL der Aufgabe, wenn der Task erfolgreich hinzugefügt wurde.</param>
        <param name="error">Der Fehler bei dem Versuch, um die Aufgabe hinzuzufügen.</param>
        <summary>
            Initialisiert eine neue Instanz der TaskAddResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.BatchError Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.BatchError Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As BatchError" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Batch.Protocol.Models.BatchError with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.BatchError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Fehler beim Versuch, den Task hinzuzufügen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das ETag der Aufgabe, wenn der Task erfolgreich hinzugefügt wurde.
            </summary>
        <value>To be added.</value>
        <remarks>
            Sie können diese verwenden, um zu ermitteln, ob der Task zwischen Anforderungen geändert hat. Insbesondere können werden übergeben das ETag mit einer Anforderung Tasks "Aktualisieren", um anzugeben, dass die Änderungen wirksam werden soll, nur dann, wenn keine andere Person auf der Auftrag in der Zwischenzeit geändert wurde.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastModified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Zeitpunkt der letzten Änderung der Aufgabe.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die URL des Vorgangs fest, ob der Task erfolgreich hinzugefügt wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As TaskAddStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Status der Anforderung zum Hinzufügen eines Vorgangs fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Folgende Werte sind möglich: "Success", "ClientError", "ServerError"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskId">
      <MemberSignature Language="C#" Value="public string TaskId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.TaskId" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskId As String" />
      <MemberSignature Language="F#" Value="member this.TaskId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.TaskId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ID des Tasks für die sieht das Ergebnis fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskAddResult.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>