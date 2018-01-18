<Type Name="HDInsightSparkActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity">
  <TypeSignature Language="C#" Value="public class HDInsightSparkActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HDInsightSparkActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class HDInsightSparkActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type HDInsightSparkActivity = class&#xA;    inherit ExecutionActivity" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("HDInsightSpark")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="cc4cb-101">HDInsight Spark-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-101">HDInsight Spark activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightSparkActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.#ctor" />
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
            <span data-ttu-id="cc4cb-102">Initialisiert eine neue Instanz der HDInsightSparkActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-102">Initializes a new instance of the HDInsightSparkActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightSparkActivity (string name, object rootPath, object entryFilePath, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, System.Collections.Generic.IList&lt;object&gt; arguments = null, string getDebugInfo = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference sparkJobLinkedService = null, string className = null, object proxyUser = null, System.Collections.Generic.IDictionary&lt;string,object&gt; sparkConfig = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object rootPath, object entryFilePath, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, class System.Collections.Generic.IList`1&lt;object&gt; arguments, string getDebugInfo, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference sparkJobLinkedService, string className, object proxyUser, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; sparkConfig) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.#ctor(System.String,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,System.Collections.Generic.IList{System.Object},System.String,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.String,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, rootPath As Object, entryFilePath As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional arguments As IList(Of Object) = null, Optional getDebugInfo As String = null, Optional sparkJobLinkedService As LinkedServiceReference = null, Optional className As String = null, Optional proxyUser As Object = null, Optional sparkConfig As IDictionary(Of String, Object) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity : string * obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * System.Collections.Generic.IList&lt;obj&gt; * string * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * string * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity (name, rootPath, entryFilePath, additionalProperties, description, dependsOn, linkedServiceName, policy, arguments, getDebugInfo, sparkJobLinkedService, className, proxyUser, sparkConfig)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="rootPath" Type="System.Object" />
        <Parameter Name="entryFilePath" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="arguments" Type="System.Collections.Generic.IList&lt;System.Object&gt;" />
        <Parameter Name="getDebugInfo" Type="System.String" />
        <Parameter Name="sparkJobLinkedService" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="className" Type="System.String" />
        <Parameter Name="proxyUser" Type="System.Object" />
        <Parameter Name="sparkConfig" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="cc4cb-103">Der Name der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-103">Activity name.</span></span></param>
        <param name="rootPath"><span data-ttu-id="cc4cb-104">Der Stammpfad in "SparkJobLinkedService" für die Dateien des Projekts.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-104">The root path in 'sparkJobLinkedService' for all the job’s files.</span></span> <span data-ttu-id="cc4cb-105">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="cc4cb-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="entryFilePath"><span data-ttu-id="cc4cb-106">Der relative Pfad zum Stammordner, der das Codepaket ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-106">The relative path to the root folder of the code/package to be executed.</span></span> <span data-ttu-id="cc4cb-107">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="cc4cb-107">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="cc4cb-108">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="cc4cb-108">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="cc4cb-109">Beschreibung der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-109">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="cc4cb-110">Aktivität hängt vom Zustand ab.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-110">Activity depends on condition.</span></span></param>
        <param name="linkedServiceName"><span data-ttu-id="cc4cb-111">Verknüpften Dienst verweisen.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-111">Linked service reference.</span></span></param>
        <param name="policy"><span data-ttu-id="cc4cb-112">"Aktivitätsrichtlinie".</span><span class="sxs-lookup"><span data-stu-id="cc4cb-112">Activity policy.</span></span></param>
        <param name="arguments"><span data-ttu-id="cc4cb-113">Die benutzerdefinierten Argumente HDInsightSparkActivity.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-113">The user-specified arguments to HDInsightSparkActivity.</span></span></param>
        <param name="getDebugInfo"><span data-ttu-id="cc4cb-114">Debuggen Sie ParameterInfo (Option).</span><span class="sxs-lookup"><span data-stu-id="cc4cb-114">Debug info option.</span></span> <span data-ttu-id="cc4cb-115">Folgende Werte sind möglich: "None", "Immer", "Fehler"</span><span class="sxs-lookup"><span data-stu-id="cc4cb-115">Possible values include: 'None', 'Always', 'Failure'</span></span></param>
        <param name="sparkJobLinkedService"><span data-ttu-id="cc4cb-116">Der Speicher verknüpfter Dienst zum Hochladen der Datei Eintrag und Abhängigkeiten sowie zum Empfangen von Protokollen.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-116">The storage linked service for uploading the entry file and dependencies, and for receiving logs.</span></span></param>
        <param name="className"><span data-ttu-id="cc4cb-117">Hauptfenster der Anwendung Java/Spark-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-117">The application's Java/Spark main class.</span></span></param>
        <param name="proxyUser"><span data-ttu-id="cc4cb-118">Der Benutzer für den Identitätswechsel, der den Auftrag ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-118">The user to impersonate that will execute the job.</span></span> <span data-ttu-id="cc4cb-119">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="cc4cb-119">Type: string (or Expression with resultType string).</span></span></param>
        <param name="sparkConfig"><span data-ttu-id="cc4cb-120">Spark-Konfigurationseigenschaft.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-120">Spark configuration property.</span></span></param>
        <summary>
            <span data-ttu-id="cc4cb-121">Initialisiert eine neue Instanz der HDInsightSparkActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-121">Initializes a new instance of the HDInsightSparkActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Arguments">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;object&gt; Arguments { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;object&gt; Arguments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.Arguments" />
      <MemberSignature Language="VB.NET" Value="Public Property Arguments As IList(Of Object)" />
      <MemberSignature Language="F#" Value="member this.Arguments : System.Collections.Generic.IList&lt;obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.Arguments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.arguments")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc4cb-122">Ruft ab oder legt die benutzerdefinierten Argumente auf HDInsightSparkActivity fest.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-122">Gets or sets the user-specified arguments to HDInsightSparkActivity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClassName">
      <MemberSignature Language="C#" Value="public string ClassName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClassName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.ClassName" />
      <MemberSignature Language="VB.NET" Value="Public Property ClassName As String" />
      <MemberSignature Language="F#" Value="member this.ClassName : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.ClassName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.className")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc4cb-123">Ruft ab, oder legt ihn fest Java/Spark-Hauptklasse der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-123">Gets or sets the application's Java/Spark main class.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntryFilePath">
      <MemberSignature Language="C#" Value="public object EntryFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EntryFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.EntryFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property EntryFilePath As Object" />
      <MemberSignature Language="F#" Value="member this.EntryFilePath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.EntryFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.entryFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc4cb-124">Ruft ab oder legt den relativen Pfad zum Stammordner, der das Codepaket ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-124">Gets or sets the relative path to the root folder of the code/package to be executed.</span></span> <span data-ttu-id="cc4cb-125">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="cc4cb-125">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDebugInfo">
      <MemberSignature Language="C#" Value="public string GetDebugInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GetDebugInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.GetDebugInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property GetDebugInfo As String" />
      <MemberSignature Language="F#" Value="member this.GetDebugInfo : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.GetDebugInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.getDebugInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc4cb-126">Ruft ab, oder legt ihn fest Debug ParameterInfo (Option).</span><span class="sxs-lookup"><span data-stu-id="cc4cb-126">Gets or sets debug info option.</span></span> <span data-ttu-id="cc4cb-127">Folgende Werte sind möglich: "None", "Immer", "Fehler"</span><span class="sxs-lookup"><span data-stu-id="cc4cb-127">Possible values include: 'None', 'Always', 'Failure'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyUser">
      <MemberSignature Language="C#" Value="public object ProxyUser { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ProxyUser" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.ProxyUser" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyUser As Object" />
      <MemberSignature Language="F#" Value="member this.ProxyUser : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.ProxyUser" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.proxyUser")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc4cb-128">Abrufen oder festlegen den Benutzer für den Identitätswechsel an, der den Auftrag ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-128">Gets or sets the user to impersonate that will execute the job.</span></span>
            <span data-ttu-id="cc4cb-129">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="cc4cb-129">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RootPath">
      <MemberSignature Language="C#" Value="public object RootPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RootPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.RootPath" />
      <MemberSignature Language="VB.NET" Value="Public Property RootPath As Object" />
      <MemberSignature Language="F#" Value="member this.RootPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.RootPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.rootPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc4cb-130">Im abruft oder festlegt Stammpfad "SparkJobLinkedService" für die Dateien des Projekts.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-130">Gets or sets the root path in 'sparkJobLinkedService' for all the job’s files.</span></span> <span data-ttu-id="cc4cb-131">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="cc4cb-131">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SparkConfig">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; SparkConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; SparkConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.SparkConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property SparkConfig As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.SparkConfig : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.SparkConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.sparkConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc4cb-132">Ruft ab, oder legt ihn fest Spark-Konfigurationseigenschaft.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-132">Gets or sets spark configuration property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SparkJobLinkedService">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference SparkJobLinkedService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference SparkJobLinkedService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.SparkJobLinkedService" />
      <MemberSignature Language="VB.NET" Value="Public Property SparkJobLinkedService As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.SparkJobLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.SparkJobLinkedService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.sparkJobLinkedService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc4cb-133">Ruft ab, oder legt ihn fest-Speicher verknüpften Dienst zum Hochladen der Datei Eintrag und Abhängigkeiten für den Empfang von Protokollen.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-133">Gets or sets the storage linked service for uploading the entry file and dependencies, and for receiving logs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="hDInsightSparkActivity.Validate " />
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
            <span data-ttu-id="cc4cb-134">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="cc4cb-134">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cc4cb-135">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="cc4cb-135">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>