<Type Name="MetricAvailability" FullName="Microsoft.Azure.Management.Sql.Models.MetricAvailability">
  <TypeSignature Language="C#" Value="public class MetricAvailability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricAvailability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.MetricAvailability" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricAvailability" />
  <TypeSignature Language="F#" Value="type MetricAvailability = class" />
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
            Ein Verfügbarkeitswert für Metrik.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricAvailability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.MetricAvailability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der MetricAvailability-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricAvailability (string retention = null, string timeGrain = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string retention, string timeGrain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.MetricAvailability.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional retention As String = null, Optional timeGrain As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.MetricAvailability : string * string -&gt; Microsoft.Azure.Management.Sql.Models.MetricAvailability" Usage="new Microsoft.Azure.Management.Sql.Models.MetricAvailability (retention, timeGrain)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retention" Type="System.String" />
        <Parameter Name="timeGrain" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="retention">Die Länge der Beibehaltungsdauer für die Metrik "Datenbank".</param>
        <param name="timeGrain">Die Granularität der Datenbank-Metrik.</param>
        <summary>
            Initialisiert eine neue Instanz der MetricAvailability-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retention">
      <MemberSignature Language="C#" Value="public string Retention { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Retention" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MetricAvailability.Retention" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Retention As String" />
      <MemberSignature Language="F#" Value="member this.Retention : string" Usage="Microsoft.Azure.Management.Sql.Models.MetricAvailability.Retention" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retention")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Länge der Beibehaltungsdauer für die Metrik "Datenbank".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public string TimeGrain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MetricAvailability.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeGrain As String" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : string" Usage="Microsoft.Azure.Management.Sql.Models.MetricAvailability.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeGrain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Granularität der Metrik Datenbank ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>