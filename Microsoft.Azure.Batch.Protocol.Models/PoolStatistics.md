<Type Name="PoolStatistics" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolStatistics">
  <TypeSignature Language="C#" Value="public class PoolStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolStatistics" />
  <TypeSignature Language="F#" Value="type PoolStatistics = class" />
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
            <span data-ttu-id="977dd-101">Enthält Auslastung und Ressource Nutzungsstatistiken für die Lebensdauer eines Pools.</span><span class="sxs-lookup"><span data-stu-id="977dd-101">Contains utilization and resource usage statistics for the lifetime of a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolStatistics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.#ctor" />
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
            <span data-ttu-id="977dd-102">Initialisiert eine neue Instanz der PoolStatistics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="977dd-102">Initializes a new instance of the PoolStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolStatistics (string url, DateTime startTime, DateTime lastUpdateTime, Microsoft.Azure.Batch.Protocol.Models.UsageStatistics usageStats = null, Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics resourceStats = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string url, valuetype System.DateTime startTime, valuetype System.DateTime lastUpdateTime, class Microsoft.Azure.Batch.Protocol.Models.UsageStatistics usageStats, class Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics resourceStats) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.#ctor(System.String,System.DateTime,System.DateTime,Microsoft.Azure.Batch.Protocol.Models.UsageStatistics,Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As String, startTime As DateTime, lastUpdateTime As DateTime, Optional usageStats As UsageStatistics = null, Optional resourceStats As ResourceStatistics = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolStatistics : string * DateTime * DateTime * Microsoft.Azure.Batch.Protocol.Models.UsageStatistics * Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolStatistics" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolStatistics (url, startTime, lastUpdateTime, usageStats, resourceStats)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="lastUpdateTime" Type="System.DateTime" />
        <Parameter Name="usageStats" Type="Microsoft.Azure.Batch.Protocol.Models.UsageStatistics" />
        <Parameter Name="resourceStats" Type="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics" />
      </Parameters>
      <Docs>
        <param name="url"><span data-ttu-id="977dd-103">Die URL für die Statistik.</span><span class="sxs-lookup"><span data-stu-id="977dd-103">The URL for the statistics.</span></span></param>
        <param name="startTime"><span data-ttu-id="977dd-104">Die Startzeit des Zeitraums, der von den Statistiken abgedeckt.</span><span class="sxs-lookup"><span data-stu-id="977dd-104">The start time of the time range covered by the statistics.</span></span></param>
        <param name="lastUpdateTime"><span data-ttu-id="977dd-105">Der Zeitpunkt, an dem die Statistik zuletzt aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="977dd-105">The time at which the statistics were last updated.</span></span> <span data-ttu-id="977dd-106">Alle Statistiken sind beschränkt auf den Bereich zwischen StartTime und LastUpdateTime.</span><span class="sxs-lookup"><span data-stu-id="977dd-106">All statistics are limited to the range between startTime and lastUpdateTime.</span></span></param>
        <param name="usageStats"><span data-ttu-id="977dd-107">Statistik zur Nutzung des Arbeitsthreadpools, z. B. die verstrichene Zeitspanne Core-verwendet.</span><span class="sxs-lookup"><span data-stu-id="977dd-107">Statistics related to pool usage, such as the amount of core-time used.</span></span></param>
        <param name="resourceStats"><span data-ttu-id="977dd-108">Statistiken in Bezug auf den Ressourcenverbrauch durch Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="977dd-108">Statistics related to resource consumption by compute nodes in the pool.</span></span></param>
        <summary>
            <span data-ttu-id="977dd-109">Initialisiert eine neue Instanz der PoolStatistics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="977dd-109">Initializes a new instance of the PoolStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.LastUpdateTime" />
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
            <span data-ttu-id="977dd-110">Ruft ab oder legt die Zeit, an der die Statistik zuletzt aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="977dd-110">Gets or sets the time at which the statistics were last updated.</span></span>
            <span data-ttu-id="977dd-111">Alle Statistiken sind beschränkt auf den Bereich zwischen StartTime und LastUpdateTime.</span><span class="sxs-lookup"><span data-stu-id="977dd-111">All statistics are limited to the range between startTime and lastUpdateTime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceStats">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics ResourceStats { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics ResourceStats" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.ResourceStats" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceStats As ResourceStatistics" />
      <MemberSignature Language="F#" Value="member this.ResourceStats : Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.ResourceStats" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceStats")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="977dd-112">Ruft ab, oder legt ihn fest Statistiken in Bezug auf den Ressourcenverbrauch durch Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="977dd-112">Gets or sets statistics related to resource consumption by compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.StartTime" />
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
            <span data-ttu-id="977dd-113">Ruft ab oder legt die Startzeit des Zeitraums, der von den Statistiken abgedeckt.</span><span class="sxs-lookup"><span data-stu-id="977dd-113">Gets or sets the start time of the time range covered by the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="977dd-114">Ruft ab oder legt die URL für die Statistik.</span><span class="sxs-lookup"><span data-stu-id="977dd-114">Gets or sets the URL for the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageStats">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UsageStatistics UsageStats { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UsageStatistics UsageStats" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.UsageStats" />
      <MemberSignature Language="VB.NET" Value="Public Property UsageStats As UsageStatistics" />
      <MemberSignature Language="F#" Value="member this.UsageStats : Microsoft.Azure.Batch.Protocol.Models.UsageStatistics with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.UsageStats" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="usageStats")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.UsageStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="977dd-115">Ruft ab, oder legt ihn fest Statistiken in Bezug auf die Nutzung des Arbeitsthreadpools, z. B. die verstrichene Zeitspanne Core-verwendet.</span><span class="sxs-lookup"><span data-stu-id="977dd-115">Gets or sets statistics related to pool usage, such as the amount of core-time used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolStatistics.Validate " />
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
            <span data-ttu-id="977dd-116">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="977dd-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="977dd-117">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="977dd-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>