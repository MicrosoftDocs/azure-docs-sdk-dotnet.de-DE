<Type Name="JobStatistics" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics">
  <TypeSignature Language="C#" Value="public class JobStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class JobStatistics" />
  <TypeSignature Language="F#" Value="type JobStatistics = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="160c3-101">Die Ausführungsstatistik für den Data Lake Analytics-Auftrag.</span><span class="sxs-lookup"><span data-stu-id="160c3-101">The Data Lake Analytics job execution statistics.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobStatistics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="160c3-102">Initialisiert eine neue Instanz der JobStatistics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="160c3-102">Initializes a new instance of the JobStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobStatistics (Nullable&lt;DateTimeOffset&gt; lastUpdateTimeUtc = null, Nullable&lt;DateTimeOffset&gt; finalizingTimeUtc = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage&gt; stages = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; lastUpdateTimeUtc, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; finalizingTimeUtc, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage&gt; stages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics.#ctor(System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional lastUpdateTimeUtc As Nullable(Of DateTimeOffset) = null, Optional finalizingTimeUtc As Nullable(Of DateTimeOffset) = null, Optional stages As IList(Of JobStatisticsVertexStage) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics : Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics (lastUpdateTimeUtc, finalizingTimeUtc, stages)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lastUpdateTimeUtc" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="finalizingTimeUtc" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="stages" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage&gt;" />
      </Parameters>
      <Docs>
        <param name="lastUpdateTimeUtc"><span data-ttu-id="160c3-103">Aktualisierungszeit der letzten der Statistik.</span><span class="sxs-lookup"><span data-stu-id="160c3-103">the last update time for the statistics.</span></span></param>
        <param name="finalizingTimeUtc"><span data-ttu-id="160c3-104">der Auftrag abgeschlossen Startzeit.</span><span class="sxs-lookup"><span data-stu-id="160c3-104">the job finalizing start time.</span></span></param>
        <param name="stages"><span data-ttu-id="160c3-105">die Liste der Stufen für den Auftrag.</span><span class="sxs-lookup"><span data-stu-id="160c3-105">the list of stages for the job.</span></span></param>
        <summary>
            <span data-ttu-id="160c3-106">Initialisiert eine neue Instanz der JobStatistics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="160c3-106">Initializes a new instance of the JobStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FinalizingTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; FinalizingTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; FinalizingTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics.FinalizingTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FinalizingTimeUtc As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.FinalizingTimeUtc : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics.FinalizingTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="finalizingTimeUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="160c3-107">Ruft den Auftrag abschließen Startzeit ab.</span><span class="sxs-lookup"><span data-stu-id="160c3-107">Gets the job finalizing start time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; LastUpdateTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; LastUpdateTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics.LastUpdateTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastUpdateTimeUtc As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTimeUtc : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics.LastUpdateTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastUpdateTimeUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="160c3-108">Ruft die letzte Aktualisierungszeit für die Statistik.</span><span class="sxs-lookup"><span data-stu-id="160c3-108">Gets the last update time for the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage&gt; Stages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage&gt; Stages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics.Stages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Stages As IList(Of JobStatisticsVertexStage)" />
      <MemberSignature Language="F#" Value="member this.Stages : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics.Stages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stages")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="160c3-109">Ruft die Liste der Phasen für den Auftrag ab.</span><span class="sxs-lookup"><span data-stu-id="160c3-109">Gets the list of stages for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>