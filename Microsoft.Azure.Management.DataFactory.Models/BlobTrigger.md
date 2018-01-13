<Type Name="BlobTrigger" FullName="Microsoft.Azure.Management.DataFactory.Models.BlobTrigger">
  <TypeSignature Language="C#" Value="public class BlobTrigger : Microsoft.Azure.Management.DataFactory.Models.MultiplePipelineTrigger" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BlobTrigger extends Microsoft.Azure.Management.DataFactory.Models.MultiplePipelineTrigger" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.BlobTrigger" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobTrigger&#xA;Inherits MultiplePipelineTrigger" />
  <TypeSignature Language="F#" Value="type BlobTrigger = class&#xA;    inherit MultiplePipelineTrigger" />
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
            Trigger, der Zählers die ausgewählten Blob-Container-Änderungen ausgeführt wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobTrigger ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.BlobTrigger.#ctor" />
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
            Initialisiert eine neue Instanz der BlobTrigger-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobTrigger (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, string runtimeState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference&gt; pipelines = null, string folderPath = null, Nullable&lt;int&gt; maxConcurrency = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedService = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, string runtimeState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference&gt; pipelines, string folderPath, valuetype System.Nullable`1&lt;int32&gt; maxConcurrency, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.BlobTrigger.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference},System.String,System.Nullable{System.Int32},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional runtimeState As String = null, Optional pipelines As IList(Of TriggerPipelineReference) = null, Optional folderPath As String = null, Optional maxConcurrency As Nullable(Of Integer) = null, Optional linkedService As LinkedServiceReference = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.BlobTrigger : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference&gt; * string * Nullable&lt;int&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference -&gt; Microsoft.Azure.Management.DataFactory.Models.BlobTrigger" Usage="new Microsoft.Azure.Management.DataFactory.Models.BlobTrigger (additionalProperties, description, runtimeState, pipelines, folderPath, maxConcurrency, linkedService)" />
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
        <Parameter Name="folderPath" Type="System.String" />
        <Parameter Name="maxConcurrency" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="linkedService" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="description">Beschreibung des Triggers.</param>
        <param name="runtimeState">Gibt an, ob Trigger oder nicht ausgeführt wird.
            Aktualisiert, wenn der Start/Stopp-APIs für den Trigger aufgerufen werden. Folgende Werte sind möglich: "Gestartet", "Angehalten", "Disabled"</param>
        <param name="pipelines">Pipelines, die gestartet werden müssen.</param>
        <param name="folderPath">Der Pfad der Ordner "Container /", die die Pipeline auslösen.</param>
        <param name="maxConcurrency">Die maximale Anzahl von parallelen Dateien behandelt werden, wenn es ausgelöst wird.</param>
        <param name="linkedService">Die verknüpften Azure Storage-Dienst verweisen.</param>
        <summary>
            Initialisiert eine neue Instanz der BlobTrigger-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FolderPath">
      <MemberSignature Language="C#" Value="public string FolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobTrigger.FolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property FolderPath As String" />
      <MemberSignature Language="F#" Value="member this.FolderPath : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobTrigger.FolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.folderPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Pfad der Ordner "Container /", die die Pipeline auslösen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedService">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference LinkedService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference LinkedService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobTrigger.LinkedService" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedService As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.LinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobTrigger.LinkedService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.linkedService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen des Dienstverweises verknüpften Azure Storage.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrency">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxConcurrency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxConcurrency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobTrigger.MaxConcurrency" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrency As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrency : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobTrigger.MaxConcurrency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.maxConcurrency")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl von parallelen Dateien behandelt werden, wenn es ausgelöst wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.BlobTrigger.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="blobTrigger.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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