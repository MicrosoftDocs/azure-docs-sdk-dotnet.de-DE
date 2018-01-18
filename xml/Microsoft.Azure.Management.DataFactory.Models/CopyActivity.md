<Type Name="CopyActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.CopyActivity">
  <TypeSignature Language="C#" Value="public class CopyActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CopyActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.CopyActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class CopyActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type CopyActivity = class&#xA;    inherit ExecutionActivity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Copy")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c654c-101">Kopieren Sie-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="c654c-101">Copy activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CopyActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.#ctor" />
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
            <span data-ttu-id="c654c-102">Initialisiert eine neue Instanz der CopyActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c654c-102">Initializes a new instance of the CopyActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CopyActivity (string name, Microsoft.Azure.Management.DataFactory.Models.CopySource source, Microsoft.Azure.Management.DataFactory.Models.CopySink sink, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, Microsoft.Azure.Management.DataFactory.Models.CopyTranslator translator = null, object enableStaging = null, Microsoft.Azure.Management.DataFactory.Models.StagingSettings stagingSettings = null, object parallelCopies = null, object cloudDataMovementUnits = null, object enableSkipIncompatibleRow = null, Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings redirectIncompatibleRowSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; inputs = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; outputs = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.DataFactory.Models.CopySource source, class Microsoft.Azure.Management.DataFactory.Models.CopySink sink, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, class Microsoft.Azure.Management.DataFactory.Models.CopyTranslator translator, object enableStaging, class Microsoft.Azure.Management.DataFactory.Models.StagingSettings stagingSettings, object parallelCopies, object cloudDataMovementUnits, object enableSkipIncompatibleRow, class Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings redirectIncompatibleRowSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; inputs, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; outputs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.#ctor(System.String,Microsoft.Azure.Management.DataFactory.Models.CopySource,Microsoft.Azure.Management.DataFactory.Models.CopySink,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,Microsoft.Azure.Management.DataFactory.Models.CopyTranslator,System.Object,Microsoft.Azure.Management.DataFactory.Models.StagingSettings,System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.DatasetReference},System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.DatasetReference})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.CopyActivity : string * Microsoft.Azure.Management.DataFactory.Models.CopySource * Microsoft.Azure.Management.DataFactory.Models.CopySink * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * Microsoft.Azure.Management.DataFactory.Models.CopyTranslator * obj * Microsoft.Azure.Management.DataFactory.Models.StagingSettings * obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.CopyActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.CopyActivity (name, source, sink, additionalProperties, description, dependsOn, linkedServiceName, policy, translator, enableStaging, stagingSettings, parallelCopies, cloudDataMovementUnits, enableSkipIncompatibleRow, redirectIncompatibleRowSettings, inputs, outputs)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="source" Type="Microsoft.Azure.Management.DataFactory.Models.CopySource" />
        <Parameter Name="sink" Type="Microsoft.Azure.Management.DataFactory.Models.CopySink" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="translator" Type="Microsoft.Azure.Management.DataFactory.Models.CopyTranslator" />
        <Parameter Name="enableStaging" Type="System.Object" />
        <Parameter Name="stagingSettings" Type="Microsoft.Azure.Management.DataFactory.Models.StagingSettings" />
        <Parameter Name="parallelCopies" Type="System.Object" />
        <Parameter Name="cloudDataMovementUnits" Type="System.Object" />
        <Parameter Name="enableSkipIncompatibleRow" Type="System.Object" />
        <Parameter Name="redirectIncompatibleRowSettings" Type="Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings" />
        <Parameter Name="inputs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt;" />
        <Parameter Name="outputs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c654c-103">Der Name der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="c654c-103">Activity name.</span></span></param>
        <param name="source"><span data-ttu-id="c654c-104">Kopiequelle der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="c654c-104">Copy activity source.</span></span></param>
        <param name="sink"><span data-ttu-id="c654c-105">Kopieren Sie die Aktivität Senke.</span><span class="sxs-lookup"><span data-stu-id="c654c-105">Copy activity sink.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="c654c-106">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="c654c-106">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="c654c-107">Beschreibung der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="c654c-107">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="c654c-108">Aktivität hängt vom Zustand ab.</span><span class="sxs-lookup"><span data-stu-id="c654c-108">Activity depends on condition.</span></span></param>
        <param name="linkedServiceName"><span data-ttu-id="c654c-109">Verknüpften Dienst verweisen.</span><span class="sxs-lookup"><span data-stu-id="c654c-109">Linked service reference.</span></span></param>
        <param name="policy"><span data-ttu-id="c654c-110">"Aktivitätsrichtlinie".</span><span class="sxs-lookup"><span data-stu-id="c654c-110">Activity policy.</span></span></param>
        <param name="translator"><span data-ttu-id="c654c-111">Kopieren Sie die Aktivität Konvertierungsprogramm.</span><span class="sxs-lookup"><span data-stu-id="c654c-111">Copy activity translator.</span></span> <span data-ttu-id="c654c-112">Wenn keine angegebene, tabellarische Konvertierer verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="c654c-112">If not specificed, tabular translator is used.</span></span></param>
        <param name="enableStaging"><span data-ttu-id="c654c-113">Gibt an, ob Sie Daten über eine vorläufige Staging kopiert.</span><span class="sxs-lookup"><span data-stu-id="c654c-113">Specifies whether to copy data via an interim staging.</span></span> <span data-ttu-id="c654c-114">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="c654c-114">Default value is false.</span></span> <span data-ttu-id="c654c-115">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="c654c-115">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <param name="stagingSettings"><span data-ttu-id="c654c-116">Gibt interim staging Einstellungen an, wenn EnableStaging "true" ist.</span><span class="sxs-lookup"><span data-stu-id="c654c-116">Specifies interim staging settings when EnableStaging is true.</span></span></param>
        <param name="parallelCopies"><span data-ttu-id="c654c-117">Maximale Anzahl gleichzeitiger Sitzungen für die Quelle oder Senke, vermeiden Sie das überlasten Datenspeicher geöffnet.</span><span class="sxs-lookup"><span data-stu-id="c654c-117">Maximum number of concurrent sessions opened on the source or sink to avoid overloading the data store.</span></span>
            <span data-ttu-id="c654c-118">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimale:</span><span class="sxs-lookup"><span data-stu-id="c654c-118">Type: integer (or Expression with resultType integer), minimum:</span></span>
            0.</param>
        <param name="cloudDataMovementUnits"><span data-ttu-id="c654c-119">Maximale Anzahl der Cloud Daten Bewegung Einheiten, die zum Ausführen dieser datenverschiebung verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="c654c-119">Maximum number of cloud data movement units that can be used to perform this data movement.</span></span>
            <span data-ttu-id="c654c-120">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimale:</span><span class="sxs-lookup"><span data-stu-id="c654c-120">Type: integer (or Expression with resultType integer), minimum:</span></span>
            0.</param>
        <param name="enableSkipIncompatibleRow"><span data-ttu-id="c654c-121">Ob inkompatible Zeile übersprungen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c654c-121">Whether to skip incompatible row.</span></span> <span data-ttu-id="c654c-122">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="c654c-122">Default value is false.</span></span> <span data-ttu-id="c654c-123">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="c654c-123">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <param name="redirectIncompatibleRowSettings"><span data-ttu-id="c654c-124">Leiten Sie inkompatible Zeile Einstellungen, wenn EnableSkipIncompatibleRow "true" ist.</span><span class="sxs-lookup"><span data-stu-id="c654c-124">Redirect incompatible row settings when EnableSkipIncompatibleRow is true.</span></span></param>
        <param name="inputs"><span data-ttu-id="c654c-125">Die Liste der Eingaben für die Aktivität definiert.</span><span class="sxs-lookup"><span data-stu-id="c654c-125">List of inputs for the activity.</span></span></param>
        <param name="outputs"><span data-ttu-id="c654c-126">Liste der Ausgaben für die Aktivität definiert.</span><span class="sxs-lookup"><span data-stu-id="c654c-126">List of outputs for the activity.</span></span></param>
        <summary>
            <span data-ttu-id="c654c-127">Initialisiert eine neue Instanz der CopyActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c654c-127">Initializes a new instance of the CopyActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudDataMovementUnits">
      <MemberSignature Language="C#" Value="public object CloudDataMovementUnits { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object CloudDataMovementUnits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.CloudDataMovementUnits" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudDataMovementUnits As Object" />
      <MemberSignature Language="F#" Value="member this.CloudDataMovementUnits : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.CloudDataMovementUnits" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.cloudDataMovementUnits")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c654c-128">Ruft ab oder legt die maximale Anzahl der Cloud Daten Bewegung Einheiten, die zum Ausführen dieser datenverschiebung verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="c654c-128">Gets or sets maximum number of cloud data movement units that can be used to perform this data movement.</span></span> <span data-ttu-id="c654c-129">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="c654c-129">Type: integer (or Expression with resultType integer), minimum: 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSkipIncompatibleRow">
      <MemberSignature Language="C#" Value="public object EnableSkipIncompatibleRow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableSkipIncompatibleRow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.EnableSkipIncompatibleRow" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableSkipIncompatibleRow As Object" />
      <MemberSignature Language="F#" Value="member this.EnableSkipIncompatibleRow : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.EnableSkipIncompatibleRow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.enableSkipIncompatibleRow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c654c-130">Ruft ab oder legt fest, ob nicht kompatible Zeile überspringen.</span><span class="sxs-lookup"><span data-stu-id="c654c-130">Gets or sets whether to skip incompatible row.</span></span> <span data-ttu-id="c654c-131">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="c654c-131">Default value is false.</span></span> <span data-ttu-id="c654c-132">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="c654c-132">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableStaging">
      <MemberSignature Language="C#" Value="public object EnableStaging { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableStaging" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.EnableStaging" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableStaging As Object" />
      <MemberSignature Language="F#" Value="member this.EnableStaging : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.EnableStaging" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.enableStaging")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c654c-133">Gibt an, ob Kopieren von Daten über eine vorläufige Staging, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="c654c-133">Gets or sets specifies whether to copy data via an interim staging.</span></span>
            <span data-ttu-id="c654c-134">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="c654c-134">Default value is false.</span></span> <span data-ttu-id="c654c-135">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="c654c-135">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Inputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; Inputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; Inputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Inputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Inputs As IList(Of DatasetReference)" />
      <MemberSignature Language="F#" Value="member this.Inputs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Inputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="inputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c654c-136">Ruft ab oder legt die Liste der Eingaben für die Aktivität definiert.</span><span class="sxs-lookup"><span data-stu-id="c654c-136">Gets or sets list of inputs for the activity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Outputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; Outputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; Outputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Outputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Outputs As IList(Of DatasetReference)" />
      <MemberSignature Language="F#" Value="member this.Outputs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Outputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c654c-137">Ruft ab oder legt die Liste der Ausgaben für die Aktivität definiert.</span><span class="sxs-lookup"><span data-stu-id="c654c-137">Gets or sets list of outputs for the activity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParallelCopies">
      <MemberSignature Language="C#" Value="public object ParallelCopies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ParallelCopies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.ParallelCopies" />
      <MemberSignature Language="VB.NET" Value="Public Property ParallelCopies As Object" />
      <MemberSignature Language="F#" Value="member this.ParallelCopies : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.ParallelCopies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.parallelCopies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c654c-138">Ruft ab oder legt die maximale Anzahl gleichzeitiger Sitzungen für die Quelle oder Senke, vermeiden Sie das überlasten Datenspeicher geöffnet.</span><span class="sxs-lookup"><span data-stu-id="c654c-138">Gets or sets maximum number of concurrent sessions opened on the source or sink to avoid overloading the data store.</span></span> <span data-ttu-id="c654c-139">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="c654c-139">Type: integer (or Expression with resultType integer), minimum: 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedirectIncompatibleRowSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings RedirectIncompatibleRowSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings RedirectIncompatibleRowSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.RedirectIncompatibleRowSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property RedirectIncompatibleRowSettings As RedirectIncompatibleRowSettings" />
      <MemberSignature Language="F#" Value="member this.RedirectIncompatibleRowSettings : Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.RedirectIncompatibleRowSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.redirectIncompatibleRowSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c654c-140">Ermittelt oder inkompatible Zeile umleitungseinstellungen definiert, wenn EnableSkipIncompatibleRow "true" ist.</span><span class="sxs-lookup"><span data-stu-id="c654c-140">Gets or sets redirect incompatible row settings when EnableSkipIncompatibleRow is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.CopySink Sink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.CopySink Sink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Sink" />
      <MemberSignature Language="VB.NET" Value="Public Property Sink As CopySink" />
      <MemberSignature Language="F#" Value="member this.Sink : Microsoft.Azure.Management.DataFactory.Models.CopySink with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Sink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.sink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.CopySink</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c654c-141">Ruft ab, oder legt ihn fest Senke der kopieren-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="c654c-141">Gets or sets copy activity sink.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.CopySource Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.CopySource Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As CopySource" />
      <MemberSignature Language="F#" Value="member this.Source : Microsoft.Azure.Management.DataFactory.Models.CopySource with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.CopySource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c654c-142">Ruft ab, oder legt ihn fest Kopiequelle-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="c654c-142">Gets or sets copy activity source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StagingSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.StagingSettings StagingSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.StagingSettings StagingSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.StagingSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property StagingSettings As StagingSettings" />
      <MemberSignature Language="F#" Value="member this.StagingSettings : Microsoft.Azure.Management.DataFactory.Models.StagingSettings with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.StagingSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.stagingSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.StagingSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c654c-143">Ruft ab oder legt gibt interim staging-Einstellungen auf, wenn EnableStaging "true" ist.</span><span class="sxs-lookup"><span data-stu-id="c654c-143">Gets or sets specifies interim staging settings when EnableStaging is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Translator">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.CopyTranslator Translator { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.CopyTranslator Translator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Translator" />
      <MemberSignature Language="VB.NET" Value="Public Property Translator As CopyTranslator" />
      <MemberSignature Language="F#" Value="member this.Translator : Microsoft.Azure.Management.DataFactory.Models.CopyTranslator with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Translator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.translator")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.CopyTranslator</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c654c-144">Ruft ab, oder legt ihn fest Konvertierer der kopieren-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="c654c-144">Gets or sets copy activity translator.</span></span> <span data-ttu-id="c654c-145">Wenn keine angegebene, tabellarische Konvertierer verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="c654c-145">If not specificed, tabular translator is used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="copyActivity.Validate " />
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
            <span data-ttu-id="c654c-146">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="c654c-146">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c654c-147">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="c654c-147">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>