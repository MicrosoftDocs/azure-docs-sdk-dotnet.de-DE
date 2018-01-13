<Type Name="JobPropertiesExecutionInfo" FullName="Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo">
  <TypeSignature Language="C#" Value="public class JobPropertiesExecutionInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPropertiesExecutionInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPropertiesExecutionInfo" />
  <TypeSignature Language="F#" Value="type JobPropertiesExecutionInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Enthält Informationen zur Ausführung eines Auftrags in der Azure Batch-Dienst an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPropertiesExecutionInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der JobPropertiesExecutionInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPropertiesExecutionInfo (Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Nullable&lt;int&gt; exitCode = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; errors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, valuetype System.Nullable`1&lt;int32&gt; exitCode, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; errors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo.#ctor(System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.BatchAIError})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional exitCode As Nullable(Of Integer) = null, Optional errors As IList(Of BatchAIError) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo : Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo" Usage="new Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo (startTime, endTime, exitCode, errors)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="exitCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="errors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt;" />
      </Parameters>
      <Docs>
        <param name="startTime">Der Zeitpunkt, an dem der Auftrag gestartet wurde.</param>
        <param name="endTime">Der Zeitpunkt, an dem der Auftrag abgeschlossen war.</param>
        <param name="exitCode">Der Exitcode des Auftrags.</param>
        <param name="errors">Enthält Details zu verschiedenen Fehlern, die vom Dienst gefunden wird, während der Ausführung eines Auftrags</param>
        <summary>
            Initialisiert eine neue Instanz der JobPropertiesExecutionInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit, zu der der Auftrag abgeschlossen wurde.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird nur zurückgegeben, wenn der Auftrag in Zustand "abgeschlossen" befindet.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; Errors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo.Errors" />
      <MemberSignature Language="VB.NET" Value="Public Property Errors As IList(Of BatchAIError)" />
      <MemberSignature Language="F#" Value="member this.Errors : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt enthält Details zu verschiedenen Fehlern, die vom Dienst gefunden wird, während der Ausführung eines Auftrags
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo.ExitCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Exitcode des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird nur zurückgegeben, wenn der Auftrag in Zustand "abgeschlossen" befindet.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit, an dem der Auftrag gestartet wurde.
            </summary>
        <value>To be added.</value>
        <remarks>
            "Wird ausgeführt" entspricht den Ausführungsstatus. Wenn der Auftrag neu gestartet oder wiederholt wurde, ist dies der letzte Zeitpunkt, an dem der Auftrag gestartet wurde. Diese Eigenschaft ist nur für den Auftrag, der in der laufenden oder abgeschlossenen Zustand befinden.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>