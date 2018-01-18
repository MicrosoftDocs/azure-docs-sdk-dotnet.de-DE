<Type Name="DataLakeAnalyticsUSQLActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsUSQLActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsUSQLActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsUSQLActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsUSQLActivity = class&#xA;    inherit ExecutionActivity" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("DataLakeAnalyticsU-SQL")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3b172-101">Data Lake Analytics-U-SQL-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="3b172-101">Data Lake Analytics U-SQL activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsUSQLActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.#ctor" />
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
            <span data-ttu-id="3b172-102">Initialisiert eine neue Instanz der DataLakeAnalyticsUSQLActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3b172-102">Initializes a new instance of the DataLakeAnalyticsUSQLActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsUSQLActivity (string name, object scriptPath, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference scriptLinkedService, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, object degreeOfParallelism = null, object priority = null, System.Collections.Generic.IDictionary&lt;string,object&gt; parameters = null, object runtimeVersion = null, object compilationMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object scriptPath, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference scriptLinkedService, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, object degreeOfParallelism, object priority, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; parameters, object runtimeVersion, object compilationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.#ctor(System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, scriptPath As Object, scriptLinkedService As LinkedServiceReference, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional degreeOfParallelism As Object = null, Optional priority As Object = null, Optional parameters As IDictionary(Of String, Object) = null, Optional runtimeVersion As Object = null, Optional compilationMode As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity : string * obj * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity (name, scriptPath, scriptLinkedService, additionalProperties, description, dependsOn, linkedServiceName, policy, degreeOfParallelism, priority, parameters, runtimeVersion, compilationMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="scriptPath" Type="System.Object" />
        <Parameter Name="scriptLinkedService" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="degreeOfParallelism" Type="System.Object" />
        <Parameter Name="priority" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="runtimeVersion" Type="System.Object" />
        <Parameter Name="compilationMode" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="3b172-103">Der Name der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="3b172-103">Activity name.</span></span></param>
        <param name="scriptPath"><span data-ttu-id="3b172-104">Groß-/Kleinschreibung Pfad zum Ordner, der das U-SQL-Skript enthält.</span><span class="sxs-lookup"><span data-stu-id="3b172-104">Case-sensitive path to folder that contains the U-SQL script.</span></span> <span data-ttu-id="3b172-105">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="3b172-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="scriptLinkedService"><span data-ttu-id="3b172-106">Dienstverweis Skript verknüpft.</span><span class="sxs-lookup"><span data-stu-id="3b172-106">Script linked service reference.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="3b172-107">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="3b172-107">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="3b172-108">Beschreibung der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="3b172-108">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="3b172-109">Aktivität hängt vom Zustand ab.</span><span class="sxs-lookup"><span data-stu-id="3b172-109">Activity depends on condition.</span></span></param>
        <param name="linkedServiceName"><span data-ttu-id="3b172-110">Verknüpften Dienst verweisen.</span><span class="sxs-lookup"><span data-stu-id="3b172-110">Linked service reference.</span></span></param>
        <param name="policy"><span data-ttu-id="3b172-111">"Aktivitätsrichtlinie".</span><span class="sxs-lookup"><span data-stu-id="3b172-111">Activity policy.</span></span></param>
        <param name="degreeOfParallelism"><span data-ttu-id="3b172-112">Die maximale Anzahl von Knoten, die zum Ausführen des Auftrags gleichzeitig verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="3b172-112">The maximum number of nodes simultaneously used to run the job.</span></span> <span data-ttu-id="3b172-113">Der Standardwert ist 1.</span><span class="sxs-lookup"><span data-stu-id="3b172-113">Default value is 1.</span></span> <span data-ttu-id="3b172-114">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimale:</span><span class="sxs-lookup"><span data-stu-id="3b172-114">Type: integer (or Expression with resultType integer), minimum:</span></span>
            1.</param>
        <param name="priority"><span data-ttu-id="3b172-115">Bestimmt, welche der in der Warteschlange befindlichen Aufträge als erstes ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="3b172-115">Determines which jobs out of all that are queued should be selected to run first.</span></span> <span data-ttu-id="3b172-116">Je niedriger die Zahl, desto höher die Priorität.</span><span class="sxs-lookup"><span data-stu-id="3b172-116">The lower the number, the higher the priority.</span></span> <span data-ttu-id="3b172-117">Der Standardwert ist 1000.</span><span class="sxs-lookup"><span data-stu-id="3b172-117">Default value is 1000.</span></span> <span data-ttu-id="3b172-118">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 1.</span><span class="sxs-lookup"><span data-stu-id="3b172-118">Type: integer (or Expression with resultType integer), minimum: 1.</span></span></param>
        <param name="parameters"><span data-ttu-id="3b172-119">Parameter für die Anforderung der U-SQL-Auftrag.</span><span class="sxs-lookup"><span data-stu-id="3b172-119">Parameters for U-SQL job request.</span></span></param>
        <param name="runtimeVersion"><span data-ttu-id="3b172-120">Common Language Runtime-Version des Moduls U-SQL verwenden.</span><span class="sxs-lookup"><span data-stu-id="3b172-120">Runtime version of the U-SQL engine to use.</span></span> <span data-ttu-id="3b172-121">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="3b172-121">Type: string (or Expression with resultType string).</span></span></param>
        <param name="compilationMode"><span data-ttu-id="3b172-122">Der Kompilierungsmodus von U-SQL.</span><span class="sxs-lookup"><span data-stu-id="3b172-122">Compilation mode of U-SQL.</span></span> <span data-ttu-id="3b172-123">Muss einen der folgenden Werte sein: semantische, vollständige Installation und SingleBox.</span><span class="sxs-lookup"><span data-stu-id="3b172-123">Must be one of these values : Semantic, Full and SingleBox.</span></span> <span data-ttu-id="3b172-124">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="3b172-124">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="3b172-125">Initialisiert eine neue Instanz der DataLakeAnalyticsUSQLActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3b172-125">Initializes a new instance of the DataLakeAnalyticsUSQLActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompilationMode">
      <MemberSignature Language="C#" Value="public object CompilationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object CompilationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.CompilationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property CompilationMode As Object" />
      <MemberSignature Language="F#" Value="member this.CompilationMode : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.CompilationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.compilationMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b172-126">Ruft ab, oder legt ihn fest Kompilierungsmodus U-SQL.</span><span class="sxs-lookup"><span data-stu-id="3b172-126">Gets or sets compilation mode of U-SQL.</span></span> <span data-ttu-id="3b172-127">Muss einen der folgenden Werte sein: semantische, vollständige Installation und SingleBox.</span><span class="sxs-lookup"><span data-stu-id="3b172-127">Must be one of these values : Semantic, Full and SingleBox.</span></span> <span data-ttu-id="3b172-128">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="3b172-128">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DegreeOfParallelism">
      <MemberSignature Language="C#" Value="public object DegreeOfParallelism { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object DegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.DegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public Property DegreeOfParallelism As Object" />
      <MemberSignature Language="F#" Value="member this.DegreeOfParallelism : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.DegreeOfParallelism" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.degreeOfParallelism")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b172-129">Ruft ab oder legt die maximale Anzahl von Knoten, die zum Ausführen des Auftrags gleichzeitig verwendet.</span><span class="sxs-lookup"><span data-stu-id="3b172-129">Gets or sets the maximum number of nodes simultaneously used to run the job.</span></span> <span data-ttu-id="3b172-130">Der Standardwert ist 1.</span><span class="sxs-lookup"><span data-stu-id="3b172-130">Default value is 1.</span></span> <span data-ttu-id="3b172-131">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 1.</span><span class="sxs-lookup"><span data-stu-id="3b172-131">Type: integer (or Expression with resultType integer), minimum: 1.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Parameters" />
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
            <span data-ttu-id="3b172-132">Ruft ab oder legt Parameter für die Anforderung der U-SQL-Auftrag fest.</span><span class="sxs-lookup"><span data-stu-id="3b172-132">Gets or sets parameters for U-SQL job request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public object Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Object" />
      <MemberSignature Language="F#" Value="member this.Priority : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b172-133">Ruft ab oder legt bestimmt, welche in der Warteschlange eingereihten Aufträge zuerst ausgeführt ausgewählt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="3b172-133">Gets or sets determines which jobs out of all that are queued should be selected to run first.</span></span> <span data-ttu-id="3b172-134">Je niedriger die Zahl, desto höher die Priorität.</span><span class="sxs-lookup"><span data-stu-id="3b172-134">The lower the number, the higher the priority.</span></span> <span data-ttu-id="3b172-135">Der Standardwert ist 1000.</span><span class="sxs-lookup"><span data-stu-id="3b172-135">Default value is 1000.</span></span> <span data-ttu-id="3b172-136">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 1.</span><span class="sxs-lookup"><span data-stu-id="3b172-136">Type: integer (or Expression with resultType integer), minimum: 1.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeVersion">
      <MemberSignature Language="C#" Value="public object RuntimeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RuntimeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.RuntimeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property RuntimeVersion As Object" />
      <MemberSignature Language="F#" Value="member this.RuntimeVersion : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.RuntimeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.runtimeVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b172-137">Ruft ab, oder legt ihn fest Laufzeitversion von das U-SQL-Datenbankmodul verwenden.</span><span class="sxs-lookup"><span data-stu-id="3b172-137">Gets or sets runtime version of the U-SQL engine to use.</span></span> <span data-ttu-id="3b172-138">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="3b172-138">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptLinkedService">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference ScriptLinkedService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference ScriptLinkedService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptLinkedService As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.ScriptLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.scriptLinkedService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b172-139">Ruft ab, oder legt ihn fest Dienstverweis Skript verknüpft.</span><span class="sxs-lookup"><span data-stu-id="3b172-139">Gets or sets script linked service reference.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptPath">
      <MemberSignature Language="C#" Value="public object ScriptPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ScriptPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptPath As Object" />
      <MemberSignature Language="F#" Value="member this.ScriptPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.scriptPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b172-140">Ruft ab oder legt Groß-/Kleinschreibung Pfad zum Ordner, der das U-SQL-Skript enthält.</span><span class="sxs-lookup"><span data-stu-id="3b172-140">Gets or sets case-sensitive path to folder that contains the U-SQL script.</span></span> <span data-ttu-id="3b172-141">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="3b172-141">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="dataLakeAnalyticsUSQLActivity.Validate " />
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
            <span data-ttu-id="3b172-142">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="3b172-142">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3b172-143">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="3b172-143">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>