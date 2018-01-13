<Type Name="ZoneInner" FullName="Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner">
  <TypeSignature Language="C#" Value="public class ZoneInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ZoneInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ZoneInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ZoneInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Beschreibt eine DNS-Zone.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ZoneInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ZoneInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ZoneInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string etag = null, Nullable&lt;long&gt; maxNumberOfRecordSets = null, Nullable&lt;long&gt; numberOfRecordSets = null, System.Collections.Generic.IList&lt;string&gt; nameServers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string etag, valuetype System.Nullable`1&lt;int64&gt; maxNumberOfRecordSets, valuetype System.Nullable`1&lt;int64&gt; numberOfRecordSets, class System.Collections.Generic.IList`1&lt;string&gt; nameServers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional etag As String = null, Optional maxNumberOfRecordSets As Nullable(Of Long) = null, Optional numberOfRecordSets As Nullable(Of Long) = null, Optional nameServers As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner" Usage="new Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner (location, id, name, type, tags, etag, maxNumberOfRecordSets, numberOfRecordSets, nameServers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="maxNumberOfRecordSets" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="numberOfRecordSets" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="nameServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="etag">Das Etag der Zone.</param>
        <param name="maxNumberOfRecordSets">Die maximale Anzahl von Datensatzgruppen, die in dieser DNS-Zone erstellt werden können.  Dies ist eine schreibgeschützte Eigenschaft, und jeder Versuch zum Festlegen dieses Werts werden ignoriert.</param>
        <param name="numberOfRecordSets">Die aktuelle Anzahl der Datensatz wird in dieser DNS-Zone.  Dies ist eine schreibgeschützte Eigenschaft, und jeder Versuch zum Festlegen dieses Werts werden ignoriert.</param>
        <param name="nameServers">Der Namenserver für diese DNS-Zone. Dies ist eine schreibgeschützte Eigenschaft, und jeder Versuch zum Festlegen dieses Werts werden ignoriert.</param>
        <summary>
            Initialisiert eine neue Instanz der ZoneInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Etag der Zone fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxNumberOfRecordSets">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxNumberOfRecordSets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxNumberOfRecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner.MaxNumberOfRecordSets" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxNumberOfRecordSets As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxNumberOfRecordSets : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner.MaxNumberOfRecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxNumberOfRecordSets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl von Datensatzgruppen, die in dieser DNS-Zone erstellt werden können.  Dies ist eine schreibgeschützte Eigenschaft, und jeder Versuch zum Festlegen dieses Werts werden ignoriert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; NameServers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; NameServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner.NameServers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NameServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NameServers : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner.NameServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nameServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namenserver für diese DNS-Zone. Dies ist eine schreibgeschützte Eigenschaft, und jeder Versuch zum Festlegen dieses Werts werden ignoriert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfRecordSets">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; NumberOfRecordSets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; NumberOfRecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner.NumberOfRecordSets" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfRecordSets As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.NumberOfRecordSets : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner.NumberOfRecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberOfRecordSets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die aktuelle Anzahl der Datensätze in dieser DNS-Zone.
            Dies ist eine schreibgeschützte Eigenschaft, und jeder Versuch zum Festlegen dieses Werts werden ignoriert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>