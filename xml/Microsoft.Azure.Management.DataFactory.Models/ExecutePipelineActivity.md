<Type Name="ExecutePipelineActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.ExecutePipelineActivity">
  <TypeSignature Language="C#" Value="public class ExecutePipelineActivity : Microsoft.Azure.Management.DataFactory.Models.ControlActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExecutePipelineActivity extends Microsoft.Azure.Management.DataFactory.Models.ControlActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.ExecutePipelineActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class ExecutePipelineActivity&#xA;Inherits ControlActivity" />
  <TypeSignature Language="F#" Value="type ExecutePipelineActivity = class&#xA;    inherit ControlActivity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.ControlActivity</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("ExecutePipeline")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f7bd4-101">Führen Sie die pipelineaktivität.</span><span class="sxs-lookup"><span data-stu-id="f7bd4-101">Execute pipeline activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExecutePipelineActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ExecutePipelineActivity.#ctor" />
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
            <span data-ttu-id="f7bd4-102">Initialisiert eine neue Instanz der ExecutePipelineActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f7bd4-102">Initializes a new instance of the ExecutePipelineActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExecutePipelineActivity (string name, Microsoft.Azure.Management.DataFactory.Models.PipelineReference pipeline, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, System.Collections.Generic.IDictionary&lt;string,object&gt; parameters = null, Nullable&lt;bool&gt; waitOnCompletion = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.DataFactory.Models.PipelineReference pipeline, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; parameters, valuetype System.Nullable`1&lt;bool&gt; waitOnCompletion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ExecutePipelineActivity.#ctor(System.String,Microsoft.Azure.Management.DataFactory.Models.PipelineReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},System.Collections.Generic.IDictionary{System.String,System.Object},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, pipeline As PipelineReference, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional parameters As IDictionary(Of String, Object) = null, Optional waitOnCompletion As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.ExecutePipelineActivity : string * Microsoft.Azure.Management.DataFactory.Models.PipelineReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.ExecutePipelineActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.ExecutePipelineActivity (name, pipeline, additionalProperties, description, dependsOn, parameters, waitOnCompletion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="pipeline" Type="Microsoft.Azure.Management.DataFactory.Models.PipelineReference" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="waitOnCompletion" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="f7bd4-103">Der Name der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="f7bd4-103">Activity name.</span></span></param>
        <param name="pipeline"><span data-ttu-id="f7bd4-104">Pipelineverweis.</span><span class="sxs-lookup"><span data-stu-id="f7bd4-104">Pipeline reference.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="f7bd4-105">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="f7bd4-105">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="f7bd4-106">Beschreibung der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="f7bd4-106">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="f7bd4-107">Aktivität hängt vom Zustand ab.</span><span class="sxs-lookup"><span data-stu-id="f7bd4-107">Activity depends on condition.</span></span></param>
        <param name="parameters"><span data-ttu-id="f7bd4-108">Pipeline-Parameter.</span><span class="sxs-lookup"><span data-stu-id="f7bd4-108">Pipeline parameters.</span></span></param>
        <param name="waitOnCompletion"><span data-ttu-id="f7bd4-109">Definiert, ob die Ausführung der abhängigen Pipeline abgeschlossen aktivitätsausführung gewartet wird.</span><span class="sxs-lookup"><span data-stu-id="f7bd4-109">Defines whether activity execution will wait for the dependent pipeline execution to finish.</span></span> <span data-ttu-id="f7bd4-110">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="f7bd4-110">Default is false.</span></span></param>
        <summary>
            <span data-ttu-id="f7bd4-111">Initialisiert eine neue Instanz der ExecutePipelineActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f7bd4-111">Initializes a new instance of the ExecutePipelineActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ExecutePipelineActivity.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ExecutePipelineActivity.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7bd4-112">Ruft ab, oder legt ihn fest Pipeline-Parameter.</span><span class="sxs-lookup"><span data-stu-id="f7bd4-112">Gets or sets pipeline parameters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pipeline">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.PipelineReference Pipeline { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.PipelineReference Pipeline" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ExecutePipelineActivity.Pipeline" />
      <MemberSignature Language="VB.NET" Value="Public Property Pipeline As PipelineReference" />
      <MemberSignature Language="F#" Value="member this.Pipeline : Microsoft.Azure.Management.DataFactory.Models.PipelineReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ExecutePipelineActivity.Pipeline" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.pipeline")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.PipelineReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7bd4-113">Ruft ab, oder legt ihn fest Pipelineverweis.</span><span class="sxs-lookup"><span data-stu-id="f7bd4-113">Gets or sets pipeline reference.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ExecutePipelineActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="executePipelineActivity.Validate " />
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
            <span data-ttu-id="f7bd4-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="f7bd4-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7bd4-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="f7bd4-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WaitOnCompletion">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; WaitOnCompletion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; WaitOnCompletion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ExecutePipelineActivity.WaitOnCompletion" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitOnCompletion As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.WaitOnCompletion : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ExecutePipelineActivity.WaitOnCompletion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.waitOnCompletion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7bd4-116">Ruft ab oder legt ihn fest definiert, ob die Ausführung der abhängigen Pipeline abgeschlossen aktivitätsausführung gewartet wird.</span><span class="sxs-lookup"><span data-stu-id="f7bd4-116">Gets or sets defines whether activity execution will wait for the dependent pipeline execution to finish.</span></span> <span data-ttu-id="f7bd4-117">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="f7bd4-117">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>