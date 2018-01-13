<Type Name="ElasticPoolEditionCapability" FullName="Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability">
  <TypeSignature Language="C#" Value="public class ElasticPoolEditionCapability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ElasticPoolEditionCapability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability" />
  <TypeSignature Language="VB.NET" Value="Public Class ElasticPoolEditionCapability" />
  <TypeSignature Language="F#" Value="type ElasticPoolEditionCapability = class" />
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
            Die Funktionen für den elastischen Pool-Edition.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolEditionCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ElasticPoolEditionCapability-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolEditionCapability (string name = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability&gt; supportedElasticPoolDtus = null, Nullable&lt;bool&gt; zoneRedundant = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability&gt; supportedElasticPoolDtus, valuetype System.Nullable`1&lt;bool&gt; zoneRedundant) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.CapabilityStatus},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional status As Nullable(Of CapabilityStatus) = null, Optional supportedElasticPoolDtus As IList(Of ElasticPoolDtuCapability) = null, Optional zoneRedundant As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability : string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability" Usage="new Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability (name, status, supportedElasticPoolDtus, zoneRedundant)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" />
        <Parameter Name="supportedElasticPoolDtus" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability&gt;" />
        <Parameter Name="zoneRedundant" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des elastischen Pools Edition.</param>
        <param name="status">Der Status der Edition des elastischen Pools.
            Folgende Werte sind möglich: "Sichtbar", "Verfügbar", "Default", "Deaktiviert"</param>
        <param name="supportedElasticPoolDtus">Die Liste der unterstützten elastischen Pool-dtu-Schwellenwert für die Edition.</param>
        <param name="zoneRedundant">Und zwar unabhängig davon, ob die Zonenredundanz für die Edition unterstützt wird.</param>
        <summary>
            Initialisiert eine neue Instanz der ElasticPoolEditionCapability-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen des elastischen Pools Edition.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of CapabilityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.Status" />
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
            Ruft den Status der Edition des elastischen Pools ab. Folgende Werte sind möglich: "Sichtbar", "Verfügbar", "Default", "Deaktiviert"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedElasticPoolDtus">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability&gt; SupportedElasticPoolDtus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability&gt; SupportedElasticPoolDtus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.SupportedElasticPoolDtus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportedElasticPoolDtus As IList(Of ElasticPoolDtuCapability)" />
      <MemberSignature Language="F#" Value="member this.SupportedElasticPoolDtus : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.SupportedElasticPoolDtus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="supportedElasticPoolDtus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der unterstützten elastischen Pool-dtu-Ebenen für die Edition ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ZoneRedundant">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ZoneRedundant { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ZoneRedundant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.ZoneRedundant" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ZoneRedundant As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ZoneRedundant : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.ZoneRedundant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="zoneRedundant")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, und zwar unabhängig davon, ob Zonenredundanz für die Edition unterstützt wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>