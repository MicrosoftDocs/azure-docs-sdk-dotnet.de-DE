<Type Name="ForEachActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.ForEachActivity">
  <TypeSignature Language="C#" Value="public class ForEachActivity : Microsoft.Azure.Management.DataFactory.Models.ControlActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ForEachActivity extends Microsoft.Azure.Management.DataFactory.Models.ControlActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.ForEachActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class ForEachActivity&#xA;Inherits ControlActivity" />
  <TypeSignature Language="F#" Value="type ForEachActivity = class&#xA;    inherit ControlActivity" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("ForEach")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="aaa29-101">Diese Aktivität wird zum Durchlaufen einer Auflistung und der angegebene Aktivitäten ausführen.</span><span class="sxs-lookup"><span data-stu-id="aaa29-101">This activity is used for iterating over a collection and execute given activities.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ForEachActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ForEachActivity.#ctor" />
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
            <span data-ttu-id="aaa29-102">Initialisiert eine neue Instanz der ForEachActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="aaa29-102">Initializes a new instance of the ForEachActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ForEachActivity (string name, Microsoft.Azure.Management.DataFactory.Models.Expression items, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; activities, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Nullable&lt;bool&gt; isSequential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.DataFactory.Models.Expression items, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Activity&gt; activities, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, valuetype System.Nullable`1&lt;bool&gt; isSequential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ForEachActivity.#ctor(System.String,Microsoft.Azure.Management.DataFactory.Models.Expression,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.Activity},System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, items As Expression, activities As IList(Of Activity), Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional isSequential As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.ForEachActivity : string * Microsoft.Azure.Management.DataFactory.Models.Expression * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.ForEachActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.ForEachActivity (name, items, activities, additionalProperties, description, dependsOn, isSequential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="items" Type="Microsoft.Azure.Management.DataFactory.Models.Expression" />
        <Parameter Name="activities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt;" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="isSequential" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="aaa29-103">Der Name der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="aaa29-103">Activity name.</span></span></param>
        <param name="items"><span data-ttu-id="aaa29-104">Die Auflistung durchlaufen werden kann.</span><span class="sxs-lookup"><span data-stu-id="aaa29-104">Collection to iterate.</span></span></param>
        <param name="activities"><span data-ttu-id="aaa29-105">Liste der Aktivitäten, ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="aaa29-105">List of activities to execute .</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="aaa29-106">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="aaa29-106">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="aaa29-107">Beschreibung der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="aaa29-107">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="aaa29-108">Aktivität hängt vom Zustand ab.</span><span class="sxs-lookup"><span data-stu-id="aaa29-108">Activity depends on condition.</span></span></param>
        <param name="isSequential"><span data-ttu-id="aaa29-109">Die Schleife nacheinander oder parallel (max. 20) ausgeführt werden soll</span><span class="sxs-lookup"><span data-stu-id="aaa29-109">Should the loop be executed in sequence or in parallel (max 20)</span></span></param>
        <summary>
            <span data-ttu-id="aaa29-110">Initialisiert eine neue Instanz der ForEachActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="aaa29-110">Initializes a new instance of the ForEachActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Activities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; Activities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Activity&gt; Activities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ForEachActivity.Activities" />
      <MemberSignature Language="VB.NET" Value="Public Property Activities As IList(Of Activity)" />
      <MemberSignature Language="F#" Value="member this.Activities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ForEachActivity.Activities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.activities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aaa29-111">Ruft ab oder legt die Liste der auszuführenden Aktivitäten.</span><span class="sxs-lookup"><span data-stu-id="aaa29-111">Gets or sets list of activities to execute .</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSequential">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsSequential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsSequential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ForEachActivity.IsSequential" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSequential As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsSequential : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ForEachActivity.IsSequential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.isSequential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aaa29-112">Ruft ab oder legt ihn fest sollte die Schleife ausgeführt werden nacheinander oder parallel (max. 20)</span><span class="sxs-lookup"><span data-stu-id="aaa29-112">Gets or sets should the loop be executed in sequence or in parallel (max 20)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Items">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.Expression Items { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.Expression Items" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ForEachActivity.Items" />
      <MemberSignature Language="VB.NET" Value="Public Property Items As Expression" />
      <MemberSignature Language="F#" Value="member this.Items : Microsoft.Azure.Management.DataFactory.Models.Expression with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ForEachActivity.Items" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.items")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.Expression</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aaa29-113">Ruft ab oder legt die Auflistung durchlaufen werden kann.</span><span class="sxs-lookup"><span data-stu-id="aaa29-113">Gets or sets collection to iterate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ForEachActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="forEachActivity.Validate " />
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
            <span data-ttu-id="aaa29-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="aaa29-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="aaa29-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="aaa29-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>