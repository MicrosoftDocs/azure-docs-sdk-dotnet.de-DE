<Type Name="UsageStatistics" FullName="Microsoft.Azure.Batch.Protocol.Models.UsageStatistics">
  <TypeSignature Language="C#" Value="public class UsageStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UsageStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.UsageStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class UsageStatistics" />
  <TypeSignature Language="F#" Value="type UsageStatistics = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="df16e-101">Statistik zu Verwendungsinformationen Anwendungspool.</span><span class="sxs-lookup"><span data-stu-id="df16e-101">Statistics related to pool usage information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UsageStatistics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="df16e-102">Initialisiert eine neue Instanz der UsageStatistics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="df16e-102">Initializes a new instance of the UsageStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UsageStatistics (DateTime startTime, DateTime lastUpdateTime, TimeSpan dedicatedCoreTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime startTime, valuetype System.DateTime lastUpdateTime, valuetype System.TimeSpan dedicatedCoreTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.#ctor(System.DateTime,System.DateTime,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startTime As DateTime, lastUpdateTime As DateTime, dedicatedCoreTime As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.UsageStatistics : DateTime * DateTime * TimeSpan -&gt; Microsoft.Azure.Batch.Protocol.Models.UsageStatistics" Usage="new Microsoft.Azure.Batch.Protocol.Models.UsageStatistics (startTime, lastUpdateTime, dedicatedCoreTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="lastUpdateTime" Type="System.DateTime" />
        <Parameter Name="dedicatedCoreTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="startTime"><span data-ttu-id="df16e-103">Die Startzeit des Zeitraums, der von den Statistiken abgedeckt.</span><span class="sxs-lookup"><span data-stu-id="df16e-103">The start time of the time range covered by the statistics.</span></span></param>
        <param name="lastUpdateTime"><span data-ttu-id="df16e-104">Der Zeitpunkt, an dem die Statistik zuletzt aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="df16e-104">The time at which the statistics were last updated.</span></span> <span data-ttu-id="df16e-105">Alle Statistiken sind beschränkt auf den Bereich zwischen StartTime und LastUpdateTime.</span><span class="sxs-lookup"><span data-stu-id="df16e-105">All statistics are limited to the range between startTime and lastUpdateTime.</span></span></param>
        <param name="dedicatedCoreTime"><span data-ttu-id="df16e-106">Berechnen Sie der aggregierte wanduhrzeit für die dedizierte Knoten Kerne, die Teil des Pools wird.</span><span class="sxs-lookup"><span data-stu-id="df16e-106">The aggregated wall-clock time of the dedicated compute node cores being part of the pool.</span></span></param>
        <summary>
            <span data-ttu-id="df16e-107">Initialisiert eine neue Instanz der UsageStatistics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="df16e-107">Initializes a new instance of the UsageStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DedicatedCoreTime">
      <MemberSignature Language="C#" Value="public TimeSpan DedicatedCoreTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DedicatedCoreTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.DedicatedCoreTime" />
      <MemberSignature Language="VB.NET" Value="Public Property DedicatedCoreTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DedicatedCoreTime : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.DedicatedCoreTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dedicatedCoreTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="df16e-108">Abrufen oder Festlegen der aggregierten wanduhrzeit der dedizierten Compute Knoten Kerne, die Teil des Pools wird.</span><span class="sxs-lookup"><span data-stu-id="df16e-108">Gets or sets the aggregated wall-clock time of the dedicated compute node cores being part of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.LastUpdateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastUpdateTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="df16e-109">Ruft ab oder legt die Zeit, an der die Statistik zuletzt aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="df16e-109">Gets or sets the time at which the statistics were last updated.</span></span>
            <span data-ttu-id="df16e-110">Alle Statistiken sind beschränkt auf den Bereich zwischen StartTime und LastUpdateTime.</span><span class="sxs-lookup"><span data-stu-id="df16e-110">All statistics are limited to the range between startTime and lastUpdateTime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="df16e-111">Ruft ab oder legt die Startzeit des Zeitraums, der von den Statistiken abgedeckt.</span><span class="sxs-lookup"><span data-stu-id="df16e-111">Gets or sets the start time of the time range covered by the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="usageStatistics.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="df16e-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="df16e-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="df16e-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="df16e-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>