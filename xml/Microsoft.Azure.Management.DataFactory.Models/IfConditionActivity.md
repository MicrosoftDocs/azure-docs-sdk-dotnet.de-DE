<Type Name="IfConditionActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity">
  <TypeSignature Language="C#" Value="public class IfConditionActivity : Microsoft.Azure.Management.DataFactory.Models.ControlActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IfConditionActivity extends Microsoft.Azure.Management.DataFactory.Models.ControlActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class IfConditionActivity&#xA;Inherits ControlActivity" />
  <TypeSignature Language="F#" Value="type IfConditionActivity = class&#xA;    inherit ControlActivity" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("IfCondition")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5631f-101">Diese Aktivität wertet einen booleschen Ausdruck und führt Aktivitäten unter der IfTrueActivities-Eigenschaft oder die IfFalseActivities Eigenschaft abhängig vom Ergebnis des Ausdrucks.</span><span class="sxs-lookup"><span data-stu-id="5631f-101">This activity evaluates a boolean expression and executes either the activities under the ifTrueActivities property or the ifFalseActivities property depending on the result of the expression.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IfConditionActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.#ctor" />
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
            <span data-ttu-id="5631f-102">Initialisiert eine neue Instanz der IfConditionActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5631f-102">Initializes a new instance of the IfConditionActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IfConditionActivity (string name, Microsoft.Azure.Management.DataFactory.Models.Expression expression, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; ifTrueActivities = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; ifFalseActivities = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.DataFactory.Models.Expression expression, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Activity&gt; ifTrueActivities, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Activity&gt; ifFalseActivities) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.#ctor(System.String,Microsoft.Azure.Management.DataFactory.Models.Expression,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.Activity},System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.Activity})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity : string * Microsoft.Azure.Management.DataFactory.Models.Expression * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity (name, expression, additionalProperties, description, dependsOn, ifTrueActivities, ifFalseActivities)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="expression" Type="Microsoft.Azure.Management.DataFactory.Models.Expression" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="ifTrueActivities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt;" />
        <Parameter Name="ifFalseActivities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5631f-103">Der Name der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="5631f-103">Activity name.</span></span></param>
        <param name="expression"><span data-ttu-id="5631f-104">Ein Ausdruck, der in einen booleschen Wert ausgewertet wird.</span><span class="sxs-lookup"><span data-stu-id="5631f-104">An expression that would evaluate to Boolean.</span></span> <span data-ttu-id="5631f-105">Hiermit wird den Block von Aktivitäten (IfTrueActivities oder IfFalseActivities) zu bestimmen, die ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="5631f-105">This is used to determine the block of activities (ifTrueActivities or ifFalseActivities) that will be executed.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="5631f-106">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="5631f-106">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="5631f-107">Beschreibung der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="5631f-107">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="5631f-108">Aktivität hängt vom Zustand ab.</span><span class="sxs-lookup"><span data-stu-id="5631f-108">Activity depends on condition.</span></span></param>
        <param name="ifTrueActivities"><span data-ttu-id="5631f-109">Liste der Aktivitäten ausführt, wenn der Ausdruck ausgewertet wird auf "true".</span><span class="sxs-lookup"><span data-stu-id="5631f-109">List of activities to execute if expression is evaluated to true.</span></span> <span data-ttu-id="5631f-110">Dies ist eine optionale Eigenschaft, und wenn nicht angegeben ist, wird die Aktivität beendet, ohne Eingreifen.</span><span class="sxs-lookup"><span data-stu-id="5631f-110">This is an optional property and if not provided, the activity will exit without any action.</span></span></param>
        <param name="ifFalseActivities"><span data-ttu-id="5631f-111">Liste der Aktivitäten ausführt, wenn der Ausdruck auf "false" ausgewertet wird.</span><span class="sxs-lookup"><span data-stu-id="5631f-111">List of activities to execute if expression is evaluated to false.</span></span> <span data-ttu-id="5631f-112">Dies ist eine optionale Eigenschaft, und wenn nicht angegeben ist, wird die Aktivität beendet, ohne Eingreifen.</span><span class="sxs-lookup"><span data-stu-id="5631f-112">This is an optional property and if not provided, the activity will exit without any action.</span></span></param>
        <summary>
            <span data-ttu-id="5631f-113">Initialisiert eine neue Instanz der IfConditionActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5631f-113">Initializes a new instance of the IfConditionActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expression">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.Expression Expression { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.Expression Expression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.Expression" />
      <MemberSignature Language="VB.NET" Value="Public Property Expression As Expression" />
      <MemberSignature Language="F#" Value="member this.Expression : Microsoft.Azure.Management.DataFactory.Models.Expression with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.Expression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.expression")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.Expression</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5631f-114">Ruft ab oder legt einen Ausdruck, der ausgewertet wird, würde in einen booleschen Wert.</span><span class="sxs-lookup"><span data-stu-id="5631f-114">Gets or sets an expression that would evaluate to Boolean.</span></span> <span data-ttu-id="5631f-115">Hiermit wird den Block von Aktivitäten (IfTrueActivities oder IfFalseActivities) zu bestimmen, die ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="5631f-115">This is used to determine the block of activities (ifTrueActivities or ifFalseActivities) that will be executed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfFalseActivities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; IfFalseActivities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Activity&gt; IfFalseActivities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.IfFalseActivities" />
      <MemberSignature Language="VB.NET" Value="Public Property IfFalseActivities As IList(Of Activity)" />
      <MemberSignature Language="F#" Value="member this.IfFalseActivities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.IfFalseActivities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.ifFalseActivities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5631f-116">Ruft ab oder legt die Liste der Aktivitäten ausführt, wenn der Ausdruck auf "false" ausgewertet wird.</span><span class="sxs-lookup"><span data-stu-id="5631f-116">Gets or sets list of activities to execute if expression is evaluated to false.</span></span> <span data-ttu-id="5631f-117">Dies ist eine optionale Eigenschaft, und wenn nicht angegeben ist, wird die Aktivität beendet, ohne Eingreifen.</span><span class="sxs-lookup"><span data-stu-id="5631f-117">This is an optional property and if not provided, the activity will exit without any action.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfTrueActivities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; IfTrueActivities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Activity&gt; IfTrueActivities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.IfTrueActivities" />
      <MemberSignature Language="VB.NET" Value="Public Property IfTrueActivities As IList(Of Activity)" />
      <MemberSignature Language="F#" Value="member this.IfTrueActivities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.IfTrueActivities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.ifTrueActivities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5631f-118">Ruft ab oder legt die Liste der Aktivitäten ausführt, wenn der Ausdruck ausgewertet wird auf "true".</span><span class="sxs-lookup"><span data-stu-id="5631f-118">Gets or sets list of activities to execute if expression is evaluated to true.</span></span> <span data-ttu-id="5631f-119">Dies ist eine optionale Eigenschaft, und wenn nicht angegeben ist, wird die Aktivität beendet, ohne Eingreifen.</span><span class="sxs-lookup"><span data-stu-id="5631f-119">This is an optional property and if not provided, the activity will exit without any action.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="ifConditionActivity.Validate " />
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
            <span data-ttu-id="5631f-120">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="5631f-120">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5631f-121">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="5631f-121">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>