<Type Name="ElasticPoolPerDatabaseMinDtuCapability" FullName="Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability">
  <TypeSignature Language="C#" Value="public class ElasticPoolPerDatabaseMinDtuCapability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ElasticPoolPerDatabaseMinDtuCapability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability" />
  <TypeSignature Language="VB.NET" Value="Public Class ElasticPoolPerDatabaseMinDtuCapability" />
  <TypeSignature Language="F#" Value="type ElasticPoolPerDatabaseMinDtuCapability = class" />
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
            Die minimalen pro Datenbank DTU-Funktion.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolPerDatabaseMinDtuCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ElasticPoolPerDatabaseMinDtuCapability-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolPerDatabaseMinDtuCapability (Nullable&lt;long&gt; limit = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; limit, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability.#ctor(System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.Sql.Models.CapabilityStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional limit As Nullable(Of Long) = null, Optional status As Nullable(Of CapabilityStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability : Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability" Usage="new Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability (limit, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="limit" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="limit">Die maximale dtu-Anzahl pro Datenbank.</param>
        <param name="status">Der Status der Funktion. Folgende Werte sind möglich: "Sichtbar", "Verfügbar", "Default", "Deaktiviert"</param>
        <summary>
            Initialisiert eine neue Instanz der ElasticPoolPerDatabaseMinDtuCapability-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Limit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability.Limit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Limit As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Limit : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="limit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die maximale dtu-Anzahl pro Datenbank ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of CapabilityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status der Funktion ab. Folgende Werte sind möglich: "Sichtbar", "Verfügbar", "Default", "Deaktiviert"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>