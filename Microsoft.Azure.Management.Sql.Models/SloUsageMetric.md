<Type Name="SloUsageMetric" FullName="Microsoft.Azure.Management.Sql.Models.SloUsageMetric">
  <TypeSignature Language="C#" Value="public class SloUsageMetric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SloUsageMetric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SloUsageMetric" />
  <TypeSignature Language="VB.NET" Value="Public Class SloUsageMetric" />
  <TypeSignature Language="F#" Value="type SloUsageMetric = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine Verwendung Slo-Metrik.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SloUsageMetric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SloUsageMetric.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public SloUsageMetric (string serviceLevelObjective = null, Guid serviceLevelObjectiveId = null, double inRangeTimeRatio = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceLevelObjective, valuetype System.Guid serviceLevelObjectiveId, float64 inRangeTimeRatio) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SloUsageMetric.#ctor(System.String,System.Guid,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceLevelObjective As String = null, Optional serviceLevelObjectiveId As Guid = null, Optional inRangeTimeRatio As Double = 0)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SloUsageMetric : string * Guid * double -&gt; Microsoft.Azure.Management.Sql.Models.SloUsageMetric" Usage="new Microsoft.Azure.Management.Sql.Models.SloUsageMetric (serviceLevelObjective, serviceLevelObjectiveId, inRangeTimeRatio)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceLevelObjective" Type="System.String" />
        <Parameter Name="serviceLevelObjectiveId" Type="System.Guid" />
        <Parameter Name="inRangeTimeRatio" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="serviceLevelObjective">Die ServiceLevelObjective für SLO-Metrik "Verwendung". Folgende Werte sind möglich: "Basic", "S0", "S1", "S2", "S3", "P1", "P2", "P3", "P4", "P6", "P11", "P15", "System", "System 2", "ElasticPool"</param>
        <param name="serviceLevelObjectiveId">Die ServiceLevelObjectiveId für SLO-Metrik "Verwendung".</param>
        <param name="inRangeTimeRatio">Ruft ab, oder legt ihn fest InRangeTimeRatio für SLO-Metrik "Verwendung".</param>
        <summary>
            Initialisiert eine neue Instanz der SloUsageMetric-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InRangeTimeRatio">
      <MemberSignature Language="C#" Value="public double InRangeTimeRatio { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 InRangeTimeRatio" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SloUsageMetric.InRangeTimeRatio" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InRangeTimeRatio As Double" />
      <MemberSignature Language="F#" Value="member this.InRangeTimeRatio : double" Usage="Microsoft.Azure.Management.Sql.Models.SloUsageMetric.InRangeTimeRatio" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="inRangeTimeRatio")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
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
      <MemberSignature Language="C#" Value="public string ServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SloUsageMetric.ServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.SloUsageMetric.ServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            Ruft die ServiceLevelObjective für SLO-Metrik "Verwendung". Folgende Werte sind möglich: "Basic", "S0", "S1", "S2", "S3", "P1", "P2", "P3", "P4", "P6", "P11", "P15", "System", "System 2", "ElasticPool"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceLevelObjectiveId">
      <MemberSignature Language="C#" Value="public Guid ServiceLevelObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid ServiceLevelObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SloUsageMetric.ServiceLevelObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceLevelObjectiveId As Guid" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjectiveId : Guid" Usage="Microsoft.Azure.Management.Sql.Models.SloUsageMetric.ServiceLevelObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceLevelObjectiveId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die ServiceLevelObjectiveId für SLO-Metrik "Verwendung".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>