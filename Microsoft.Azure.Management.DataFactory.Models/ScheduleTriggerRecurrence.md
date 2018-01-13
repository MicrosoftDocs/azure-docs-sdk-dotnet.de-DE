<Type Name="ScheduleTriggerRecurrence" FullName="Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence">
  <TypeSignature Language="C#" Value="public class ScheduleTriggerRecurrence" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScheduleTriggerRecurrence extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence" />
  <TypeSignature Language="VB.NET" Value="Public Class ScheduleTriggerRecurrence" />
  <TypeSignature Language="F#" Value="type ScheduleTriggerRecurrence = class" />
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
            <span data-ttu-id="11ae0-101">Die Wiederholung des Workflow-Trigger.</span><span class="sxs-lookup"><span data-stu-id="11ae0-101">The workflow trigger recurrence.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleTriggerRecurrence ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence.#ctor" />
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
            <span data-ttu-id="11ae0-102">Initialisiert eine neue Instanz der ScheduleTriggerRecurrence-Klasse.</span><span class="sxs-lookup"><span data-stu-id="11ae0-102">Initializes a new instance of the ScheduleTriggerRecurrence class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleTriggerRecurrence (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string frequency = null, Nullable&lt;int&gt; interval = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, string timeZone = null, Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule schedule = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string frequency, valuetype System.Nullable`1&lt;int32&gt; interval, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string timeZone, class Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule schedule) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Nullable{System.Int32},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional frequency As String = null, Optional interval As Nullable(Of Integer) = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional timeZone As String = null, Optional schedule As RecurrenceSchedule = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * Nullable&lt;int&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule -&gt; Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence" Usage="new Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence (additionalProperties, frequency, interval, startTime, endTime, timeZone, schedule)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="frequency" Type="System.String" />
        <Parameter Name="interval" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="timeZone" Type="System.String" />
        <Parameter Name="schedule" Type="Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="11ae0-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="11ae0-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="frequency"><span data-ttu-id="11ae0-104">Die Häufigkeit.</span><span class="sxs-lookup"><span data-stu-id="11ae0-104">The frequency.</span></span> <span data-ttu-id="11ae0-105">Folgende Werte sind möglich: "NotSpecified" "", "Minute", 'Hour', 'Day', 'Week', 'Month', 'Year'</span><span class="sxs-lookup"><span data-stu-id="11ae0-105">Possible values include: 'NotSpecified', 'Minute', 'Hour', 'Day', 'Week', 'Month', 'Year'</span></span></param>
        <param name="interval"><span data-ttu-id="11ae0-106">Das Intervall.</span><span class="sxs-lookup"><span data-stu-id="11ae0-106">The interval.</span></span></param>
        <param name="startTime"><span data-ttu-id="11ae0-107">Die Startzeit.</span><span class="sxs-lookup"><span data-stu-id="11ae0-107">The start time.</span></span></param>
        <param name="endTime"><span data-ttu-id="11ae0-108">Die Endzeit.</span><span class="sxs-lookup"><span data-stu-id="11ae0-108">The end time.</span></span></param>
        <param name="timeZone"><span data-ttu-id="11ae0-109">Die Zeitzone.</span><span class="sxs-lookup"><span data-stu-id="11ae0-109">The time zone.</span></span></param>
        <param name="schedule"><span data-ttu-id="11ae0-110">Die Wiederholung des Zeitplans.</span><span class="sxs-lookup"><span data-stu-id="11ae0-110">The recurrence schedule.</span></span></param>
        <summary>
            <span data-ttu-id="11ae0-111">Initialisiert eine neue Instanz der ScheduleTriggerRecurrence-Klasse.</span><span class="sxs-lookup"><span data-stu-id="11ae0-111">Initializes a new instance of the ScheduleTriggerRecurrence class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence.AdditionalProperties" />
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
            <span data-ttu-id="11ae0-112">Ruft ab oder legt ihn fest, die nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="11ae0-112">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="11ae0-113">Ruft ab oder legt die Endzeit.</span><span class="sxs-lookup"><span data-stu-id="11ae0-113">Gets or sets the end time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Frequency">
      <MemberSignature Language="C#" Value="public string Frequency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Frequency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence.Frequency" />
      <MemberSignature Language="VB.NET" Value="Public Property Frequency As String" />
      <MemberSignature Language="F#" Value="member this.Frequency : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence.Frequency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="frequency")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11ae0-114">Ruft ab oder legt die Häufigkeit fest.</span><span class="sxs-lookup"><span data-stu-id="11ae0-114">Gets or sets the frequency.</span></span> <span data-ttu-id="11ae0-115">Folgende Werte sind möglich: "NotSpecified" "", "Minute", 'Hour', 'Day', 'Week', 'Month', 'Year'</span><span class="sxs-lookup"><span data-stu-id="11ae0-115">Possible values include: 'NotSpecified', 'Minute', 'Hour', 'Day', 'Week', 'Month', 'Year'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Interval">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Interval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Interval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence.Interval" />
      <MemberSignature Language="VB.NET" Value="Public Property Interval As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Interval : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence.Interval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="interval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11ae0-116">Ruft ab oder legt das Zeitintervall fest.</span><span class="sxs-lookup"><span data-stu-id="11ae0-116">Gets or sets the interval.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule Schedule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule Schedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence.Schedule" />
      <MemberSignature Language="VB.NET" Value="Public Property Schedule As RecurrenceSchedule" />
      <MemberSignature Language="F#" Value="member this.Schedule : Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence.Schedule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schedule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11ae0-117">Ruft ab oder legt die Wiederholung des Zeitplans.</span><span class="sxs-lookup"><span data-stu-id="11ae0-117">Gets or sets the recurrence schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="11ae0-118">Ruft ab oder legt die Startzeit.</span><span class="sxs-lookup"><span data-stu-id="11ae0-118">Gets or sets the start time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeZone">
      <MemberSignature Language="C#" Value="public string TimeZone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence.TimeZone" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeZone As String" />
      <MemberSignature Language="F#" Value="member this.TimeZone : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ScheduleTriggerRecurrence.TimeZone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeZone")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11ae0-119">Ruft ab oder legt die Zeitzone.</span><span class="sxs-lookup"><span data-stu-id="11ae0-119">Gets or sets the time zone.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>