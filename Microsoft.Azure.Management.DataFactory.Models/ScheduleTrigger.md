<Type Name="ScheduleTrigger" FullName="Microsoft.Azure.Management.DataFactory.Models.ScheduleTrigger">
  <TypeSignature Language="C#" Value="public class ScheduleTrigger : Microsoft.Azure.Management.DataFactory.Models.MultiplePipelineTrigger" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScheduleTrigger extends Microsoft.Azure.Management.DataFactory.Models.MultiplePipelineTrigger" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.ScheduleTrigger" />
  <TypeSignature Language="VB.NET" Value="Public Class ScheduleTrigger&#xA;Inherits MultiplePipelineTrigger" />
  <TypeSignature Language="F#" Value="type ScheduleTrigger = class&#xA;    inherit MultiplePipelineTrigger" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.Trigger</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.DataFactory.Models.MultiplePipelineTrigger</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Trigger, die Pipeline erstellt wird in regelmäßigen Abständen nach Zeitplan ausgeführt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleTrigger ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ScheduleTrigger.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ScheduleTrigger-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleTrigger (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, string runtimeState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference&gt; pipelines = null, Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence recurrence = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, string runtimeState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference&gt; pipelines, class Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence recurrence) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ScheduleTrigger.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference},Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional runtimeState As String = null, Optional pipelines As IList(Of TriggerPipelineReference) = null, Optional recurrence As ScheduleTriggerRecurrence = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.ScheduleTrigger : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference&gt; * Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence -&gt; Microsoft.Azure.Management.DataFactory.Models.ScheduleTrigger" Usage="new Microsoft.Azure.Management.DataFactory.Models.ScheduleTrigger (additionalProperties, description, runtimeState, pipelines, recurrence)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="runtimeState" Type="System.String" />
        <Parameter Name="pipelines" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference&gt;" />
        <Parameter Name="recurrence" Type="Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="description">Beschreibung des Triggers.</param>
        <param name="runtimeState">Gibt an, ob Trigger oder nicht ausgeführt wird.
            Aktualisiert, wenn der Start/Stopp-APIs für den Trigger aufgerufen werden. Folgende Werte sind möglich: "Gestartet", "Angehalten", "Disabled"</param>
        <param name="pipelines">Pipelines, die gestartet werden müssen.</param>
        <param name="recurrence">Konfiguration für Wiederholungen des Zeitplans.</param>
        <summary>
            Initialisiert eine neue Instanz der ScheduleTrigger-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recurrence">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence Recurrence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence Recurrence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ScheduleTrigger.Recurrence" />
      <MemberSignature Language="VB.NET" Value="Public Property Recurrence As ScheduleTriggerRecurrence" />
      <MemberSignature Language="F#" Value="member this.Recurrence : Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ScheduleTrigger.Recurrence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.recurrence")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Konfiguration Wiederholung des Zeitplans.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>