<Type Name="DatabaseMetric" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric">
  <TypeSignature Language="C#" Value="public class DatabaseMetric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DatabaseMetric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric" />
  <TypeSignature Language="VB.NET" Value="Public Class DatabaseMetric" />
  <TypeSignature Language="F#" Value="type DatabaseMetric = class" />
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
            Stellt Metriken für Azure SQL-Datenbank dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseMetric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DatabaseMetric-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseMetric (string resourceName = null, string displayName = null, Nullable&lt;double&gt; currentValue = null, Nullable&lt;double&gt; limit = null, string unit = null, Nullable&lt;DateTime&gt; nextResetTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string resourceName, string displayName, valuetype System.Nullable`1&lt;float64&gt; currentValue, valuetype System.Nullable`1&lt;float64&gt; limit, string unit, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; nextResetTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric.#ctor(System.String,System.String,System.Nullable{System.Double},System.Nullable{System.Double},System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resourceName As String = null, Optional displayName As String = null, Optional currentValue As Nullable(Of Double) = null, Optional limit As Nullable(Of Double) = null, Optional unit As String = null, Optional nextResetTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric : string * string * Nullable&lt;double&gt; * Nullable&lt;double&gt; * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric (resourceName, displayName, currentValue, limit, unit, nextResetTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="currentValue" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="limit" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="nextResetTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="resourceName">Der Name der Ressource.</param>
        <param name="displayName">Der Metrik Anzeigename.</param>
        <param name="currentValue">Der aktuelle Wert der Metrik.</param>
        <param name="limit">Der aktuelle Grenzwert für die Metrik.</param>
        <param name="unit">Die Einheiten der Metrik.</param>
        <param name="nextResetTime">Das nächste zurückgesetzt Mal für die Metrik (ISO8601-Format).</param>
        <summary>
            Initialisiert eine neue Instanz der DatabaseMetric-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; CurrentValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentValue As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den aktuellen Wert der Eigenschaft ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Metrik Anzeigenamen ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Limit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric.Limit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Limit As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Limit : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="limit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die aktuelle Grenze für die Metrik ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextResetTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NextResetTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NextResetTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric.NextResetTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextResetTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NextResetTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric.NextResetTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextResetTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft der nächsten zurücksetzen Zeit für die Metrik (ISO8601-Format).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceName">
      <MemberSignature Language="C#" Value="public string ResourceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric.ResourceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceName As String" />
      <MemberSignature Language="F#" Value="member this.ResourceName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric.ResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen der Ressource ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Einheiten der Metrik an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>