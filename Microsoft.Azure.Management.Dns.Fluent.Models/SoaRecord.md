<Type Name="SoaRecord" FullName="Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord">
  <TypeSignature Language="C#" Value="public class SoaRecord" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SoaRecord extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord" />
  <TypeSignature Language="VB.NET" Value="Public Class SoaRecord" />
  <TypeSignature Language="F#" Value="type SoaRecord = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Ein SOA-Datensatz.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SoaRecord ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SoaRecord-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SoaRecord (string host = null, string email = null, Nullable&lt;long&gt; serialNumber = null, Nullable&lt;long&gt; refreshTime = null, Nullable&lt;long&gt; retryTime = null, Nullable&lt;long&gt; expireTime = null, Nullable&lt;long&gt; minimumTtl = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string host, string email, valuetype System.Nullable`1&lt;int64&gt; serialNumber, valuetype System.Nullable`1&lt;int64&gt; refreshTime, valuetype System.Nullable`1&lt;int64&gt; retryTime, valuetype System.Nullable`1&lt;int64&gt; expireTime, valuetype System.Nullable`1&lt;int64&gt; minimumTtl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord.#ctor(System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional host As String = null, Optional email As String = null, Optional serialNumber As Nullable(Of Long) = null, Optional refreshTime As Nullable(Of Long) = null, Optional retryTime As Nullable(Of Long) = null, Optional expireTime As Nullable(Of Long) = null, Optional minimumTtl As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord : string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord" Usage="new Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord (host, email, serialNumber, refreshTime, retryTime, expireTime, minimumTtl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="host" Type="System.String" />
        <Parameter Name="email" Type="System.String" />
        <Parameter Name="serialNumber" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="refreshTime" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="retryTime" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="expireTime" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="minimumTtl" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="host">Der Domänenname der autorisierende Namenserver für diesen SOA-Datensatz.</param>
        <param name="email">Die e-Mail-Adresse für diesen SOA-Datensatz.</param>
        <param name="serialNumber">Die Seriennummer für diesen SOA-Datensatz.</param>
        <param name="refreshTime">Der Wert der datenaktualisierung für diesen SOA-Datensatz.</param>
        <param name="retryTime">Die Wiederholungszeit für diesen SOA-Datensatz.</param>
        <param name="expireTime">Der Zeitpunkt der Ablauf für diesen SOA-Datensatz.</param>
        <param name="minimumTtl">Der Mindestwert für diesen SOA-Datensatz. Gemäß der Konvention wird dies verwendet, um zu bestimmen, die negative Zwischenspeichern Dauer.</param>
        <summary>
            Initialisiert eine neue Instanz der SoaRecord-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Email">
      <MemberSignature Language="C#" Value="public string Email { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Email" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord.Email" />
      <MemberSignature Language="VB.NET" Value="Public Property Email As String" />
      <MemberSignature Language="F#" Value="member this.Email : string with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord.Email" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="email")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die e-Mail-Adresse für diesen SOA-Datensatz.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpireTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ExpireTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ExpireTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord.ExpireTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpireTime As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ExpireTime : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord.ExpireTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="expireTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit ablaufen für diesen SOA-Datensatz fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public string Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As String" />
      <MemberSignature Language="F#" Value="member this.Host : string with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord.Host" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="host")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Domänennamen von der autorisierende Namenserver für diesen SOA-Datensatz.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumTtl">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MinimumTtl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MinimumTtl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord.MinimumTtl" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumTtl As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MinimumTtl : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord.MinimumTtl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minimumTTL")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den minimalen Wert für diesen SOA-Datensatz. Gemäß der Konvention wird dies verwendet, um zu bestimmen, die negative Zwischenspeichern Dauer.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; RefreshTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; RefreshTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord.RefreshTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RefreshTime As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RefreshTime : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord.RefreshTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="refreshTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Aktualisierungswert "für diesen SOA-Datensatz.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; RetryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; RetryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord.RetryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryTime As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RetryTime : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord.RetryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retryTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Wiederholungszeit für diesen SOA-Datensatz.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerialNumber">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SerialNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SerialNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord.SerialNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SerialNumber As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SerialNumber : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord.SerialNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serialNumber")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Seriennummer für diesen SOA-Datensatz.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>