<Type Name="MaxSizeCapability" FullName="Microsoft.Azure.Management.Sql.Models.MaxSizeCapability">
  <TypeSignature Language="C#" Value="public class MaxSizeCapability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MaxSizeCapability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.MaxSizeCapability" />
  <TypeSignature Language="VB.NET" Value="Public Class MaxSizeCapability" />
  <TypeSignature Language="F#" Value="type MaxSizeCapability = class" />
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
            Der maximal zulässigen Größe für eine Datenbank.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MaxSizeCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.MaxSizeCapability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der MaxSizeCapability-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MaxSizeCapability (long limit = 0, Nullable&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeUnits&gt; unit = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 limit, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.MaxSizeUnits&gt; unit, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.MaxSizeCapability.#ctor(System.Int64,System.Nullable{Microsoft.Azure.Management.Sql.Models.MaxSizeUnits},System.Nullable{Microsoft.Azure.Management.Sql.Models.CapabilityStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional limit As Long = 0, Optional unit As Nullable(Of MaxSizeUnits) = null, Optional status As Nullable(Of CapabilityStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.MaxSizeCapability : int64 * Nullable&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeUnits&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; -&gt; Microsoft.Azure.Management.Sql.Models.MaxSizeCapability" Usage="new Microsoft.Azure.Management.Sql.Models.MaxSizeCapability (limit, unit, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="limit" Type="System.Int64" />
        <Parameter Name="unit" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeUnits&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="limit">Die maximale Größe der Datenbank (siehe "Einheit" für die Einheiten).</param>
        <param name="unit">Die Einheiten, denen der Grenzwert ausgedrückt wird.
            Folgende Werte sind möglich: "MB", "GB", "TB", "Petabytes"</param>
        <param name="status">Der Status der Maximalgröße-Funktion.
            Folgende Werte sind möglich: "Sichtbar", "Verfügbar", "Default", "Deaktiviert"</param>
        <summary>
            Initialisiert eine neue Instanz der MaxSizeCapability-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public long Limit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MaxSizeCapability.Limit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Limit As Long" />
      <MemberSignature Language="F#" Value="member this.Limit : int64" Usage="Microsoft.Azure.Management.Sql.Models.MaxSizeCapability.Limit" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die maximale Größe der Datenbank (siehe "Einheit" für die Einheiten).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MaxSizeCapability.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of CapabilityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" Usage="Microsoft.Azure.Management.Sql.Models.MaxSizeCapability.Status" />
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
            Ruft den Status der Funktion für die maximale Größe ab. Folgende Werte sind möglich: "Sichtbar", "Verfügbar", "Default", "Deaktiviert"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeUnits&gt; Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.MaxSizeUnits&gt; Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MaxSizeCapability.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As Nullable(Of MaxSizeUnits)" />
      <MemberSignature Language="F#" Value="member this.Unit : Nullable&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeUnits&gt;" Usage="Microsoft.Azure.Management.Sql.Models.MaxSizeCapability.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeUnits&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Einheiten, denen der Grenzwert ausgedrückt wird. Folgende Werte sind möglich: "MB", "GB", "TB", "Petabytes"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>