<Type Name="TriggerRun" FullName="Microsoft.Azure.Management.DataFactory.Models.TriggerRun">
  <TypeSignature Language="C#" Value="public class TriggerRun" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TriggerRun extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.TriggerRun" />
  <TypeSignature Language="VB.NET" Value="Public Class TriggerRun" />
  <TypeSignature Language="F#" Value="type TriggerRun = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5c023-101">Trigger ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="5c023-101">Trigger runs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TriggerRun ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.#ctor" />
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
            <span data-ttu-id="5c023-102">Initialisiert eine neue Instanz der TriggerRun-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5c023-102">Initializes a new instance of the TriggerRun class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TriggerRun (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string triggerRunId = null, string triggerName = null, string triggerType = null, Nullable&lt;DateTime&gt; triggerRunTimestamp = null, string status = null, string message = null, System.Collections.Generic.IDictionary&lt;string,string&gt; properties = null, System.Collections.Generic.IDictionary&lt;string,string&gt; triggeredPipelines = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string triggerRunId, string triggerName, string triggerType, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; triggerRunTimestamp, string status, string message, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; triggeredPipelines) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.String,System.Nullable{System.DateTime},System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional triggerRunId As String = null, Optional triggerName As String = null, Optional triggerType As String = null, Optional triggerRunTimestamp As Nullable(Of DateTime) = null, Optional status As String = null, Optional message As String = null, Optional properties As IDictionary(Of String, String) = null, Optional triggeredPipelines As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.TriggerRun : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * string * Nullable&lt;DateTime&gt; * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.TriggerRun" Usage="new Microsoft.Azure.Management.DataFactory.Models.TriggerRun (additionalProperties, triggerRunId, triggerName, triggerType, triggerRunTimestamp, status, message, properties, triggeredPipelines)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="triggerRunId" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="triggerType" Type="System.String" />
        <Parameter Name="triggerRunTimestamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="triggeredPipelines" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="5c023-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="5c023-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="triggerRunId"><span data-ttu-id="5c023-104">Trigger Id ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="5c023-104">Trigger run id.</span></span></param>
        <param name="triggerName"><span data-ttu-id="5c023-105">Triggername.</span><span class="sxs-lookup"><span data-stu-id="5c023-105">Trigger name.</span></span></param>
        <param name="triggerType"><span data-ttu-id="5c023-106">Triggertyp.</span><span class="sxs-lookup"><span data-stu-id="5c023-106">Trigger type.</span></span></param>
        <param name="triggerRunTimestamp"><span data-ttu-id="5c023-107">Startzeit der Trigger ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="5c023-107">Trigger run start time.</span></span></param>
        <param name="status"><span data-ttu-id="5c023-108">Trigger, der Status der Ausführung.</span><span class="sxs-lookup"><span data-stu-id="5c023-108">Trigger run status.</span></span> <span data-ttu-id="5c023-109">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Inprogress"</span><span class="sxs-lookup"><span data-stu-id="5c023-109">Possible values include: 'Succeeded', 'Failed', 'Inprogress'</span></span></param>
        <param name="message"><span data-ttu-id="5c023-110">Trigger-Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="5c023-110">Trigger error message.</span></span></param>
        <param name="properties"><span data-ttu-id="5c023-111">Liste von Eigenschaftennamen und-Wert im Zusammenhang mit der Trigger ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="5c023-111">List of property name and value related to trigger run.</span></span> <span data-ttu-id="5c023-112">Name-Wert-Paar hängt Typ des Triggers ab.</span><span class="sxs-lookup"><span data-stu-id="5c023-112">Name, value pair depends on type of trigger.</span></span></param>
        <param name="triggeredPipelines"><span data-ttu-id="5c023-113">Liste der pipelinenamen, und führen Sie die Id, die ausgelöst wird, durch den Trigger ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="5c023-113">List of pipeline name and run Id triggered by the trigger run.</span></span></param>
        <summary>
            <span data-ttu-id="5c023-114">Initialisiert eine neue Instanz der TriggerRun-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5c023-114">Initializes a new instance of the TriggerRun class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c023-115">Ruft ab oder legt ihn fest, die nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="5c023-115">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c023-116">Ruft auslösen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="5c023-116">Gets trigger error message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c023-117">Ruft die Liste der Eigenschaftennamen und-Wert im Zusammenhang mit der Trigger ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="5c023-117">Gets list of property name and value related to trigger run.</span></span> <span data-ttu-id="5c023-118">Name-Wert-Paar hängt Typ des Triggers ab.</span><span class="sxs-lookup"><span data-stu-id="5c023-118">Name, value pair depends on type of trigger.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c023-119">Ruft auslösen Ausführungsstatus.</span><span class="sxs-lookup"><span data-stu-id="5c023-119">Gets trigger run status.</span></span> <span data-ttu-id="5c023-120">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Inprogress"</span><span class="sxs-lookup"><span data-stu-id="5c023-120">Possible values include: 'Succeeded', 'Failed', 'Inprogress'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggeredPipelines">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; TriggeredPipelines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; TriggeredPipelines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggeredPipelines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggeredPipelines As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.TriggeredPipelines : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggeredPipelines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="triggeredPipelines")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c023-121">Ruft die Liste der pipelinenamen und Testlauf-Id ausgelöst durch den Trigger ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="5c023-121">Gets list of pipeline name and run Id triggered by the trigger run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerName">
      <MemberSignature Language="C#" Value="public string TriggerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TriggerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggerName As String" />
      <MemberSignature Language="F#" Value="member this.TriggerName : string" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="triggerName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c023-122">Ruft auslösen Name.</span><span class="sxs-lookup"><span data-stu-id="5c023-122">Gets trigger name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerRunId">
      <MemberSignature Language="C#" Value="public string TriggerRunId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TriggerRunId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggerRunId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggerRunId As String" />
      <MemberSignature Language="F#" Value="member this.TriggerRunId : string" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggerRunId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="triggerRunId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c023-123">Ruft auslösen Testlauf-Id an.</span><span class="sxs-lookup"><span data-stu-id="5c023-123">Gets trigger run id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerRunTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; TriggerRunTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; TriggerRunTimestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggerRunTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggerRunTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.TriggerRunTimestamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggerRunTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="triggerRunTimestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c023-124">Ruft auslösen zur Startzeit an.</span><span class="sxs-lookup"><span data-stu-id="5c023-124">Gets trigger run start time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerType">
      <MemberSignature Language="C#" Value="public string TriggerType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TriggerType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggerType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggerType As String" />
      <MemberSignature Language="F#" Value="member this.TriggerType : string" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggerType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="triggerType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c023-125">Ruft die Triggertyp an.</span><span class="sxs-lookup"><span data-stu-id="5c023-125">Gets trigger type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>