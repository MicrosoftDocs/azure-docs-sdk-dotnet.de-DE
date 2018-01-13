<Type Name="SloUsageMetric" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric">
  <TypeSignature Language="C#" Value="public class SloUsageMetric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SloUsageMetric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric" />
  <TypeSignature Language="VB.NET" Value="Public Class SloUsageMetric" />
  <TypeSignature Language="F#" Value="type SloUsageMetric = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Nutzung der Slo-Metrik dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SloUsageMetric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SloUsageMetric-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SloUsageMetric (string serviceLevelObjective = null, Nullable&lt;Guid&gt; serviceLevelObjectiveId = null, Nullable&lt;double&gt; inRangeTimeRatio = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceLevelObjective, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; serviceLevelObjectiveId, valuetype System.Nullable`1&lt;float64&gt; inRangeTimeRatio) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric.#ctor(System.String,System.Nullable{System.Guid},System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceLevelObjective As String = null, Optional serviceLevelObjectiveId As Nullable(Of Guid) = null, Optional inRangeTimeRatio As Nullable(Of Double) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric : string * Nullable&lt;Guid&gt; * Nullable&lt;double&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric (serviceLevelObjective, serviceLevelObjectiveId, inRangeTimeRatio)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceLevelObjective" Type="System.String" />
        <Parameter Name="serviceLevelObjectiveId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="inRangeTimeRatio" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceLevelObjective">Die ServiceLevelObjective für SLO-Metrik "Verwendung". Folgende Werte sind möglich: "Basic", "S0", "S1", "S2", "S3", "P1", "P2", "P3"</param>
        <param name="serviceLevelObjectiveId">Die ServiceLevelObjectiveId für SLO-Metrik "Verwendung".</param>
        <param name="inRangeTimeRatio">Ruft ab, oder legt ihn fest InRangeTimeRatio für SLO-Metrik "Verwendung".</param>
        <summary>
            Initialisiert eine neue Instanz der SloUsageMetric-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InRangeTimeRatio">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; InRangeTimeRatio { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; InRangeTimeRatio" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric.InRangeTimeRatio" />
      <MemberSignature Language="VB.NET" Value="Public Property InRangeTimeRatio As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.InRangeTimeRatio : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric.InRangeTimeRatio" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="inRangeTimeRatio")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest InRangeTimeRatio für SLO-Metrik "Verwendung".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string ServiceLevelObjective { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric.ServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjective : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric.ServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceLevelObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ServiceLevelObjective für SLO-Metrik "Verwendung".
            Folgende Werte sind möglich: "Basic", "S0", "S1", "S2", "S3", "P1", "P2", "P3"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceLevelObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ServiceLevelObjectiveId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ServiceLevelObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric.ServiceLevelObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceLevelObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjectiveId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric.ServiceLevelObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceLevelObjectiveId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ServiceLevelObjectiveId für SLO-Metrik "Verwendung".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>