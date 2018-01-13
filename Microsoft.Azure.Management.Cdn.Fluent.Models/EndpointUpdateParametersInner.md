<Type Name="EndpointUpdateParametersInner" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner">
  <TypeSignature Language="C#" Value="public class EndpointUpdateParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EndpointUpdateParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class EndpointUpdateParametersInner" />
  <TypeSignature Language="F#" Value="type EndpointUpdateParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Eigenschaften, die erforderlich, um einen neuen Endpunkt zu erstellen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EndpointUpdateParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der EndpointUpdateParametersInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EndpointUpdateParametersInner (System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string originHostHeader = null, string originPath = null, System.Collections.Generic.IList&lt;string&gt; contentTypesToCompress = null, Nullable&lt;bool&gt; isCompressionEnabled = null, Nullable&lt;bool&gt; isHttpAllowed = null, Nullable&lt;bool&gt; isHttpsAllowed = null, Nullable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; queryStringCachingBehavior = null, string optimizationType = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; geoFilters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string originHostHeader, string originPath, class System.Collections.Generic.IList`1&lt;string&gt; contentTypesToCompress, valuetype System.Nullable`1&lt;bool&gt; isCompressionEnabled, valuetype System.Nullable`1&lt;bool&gt; isHttpAllowed, valuetype System.Nullable`1&lt;bool&gt; isHttpsAllowed, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; queryStringCachingBehavior, string optimizationType, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; geoFilters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional tags As IDictionary(Of String, String) = null, Optional originHostHeader As String = null, Optional originPath As String = null, Optional contentTypesToCompress As IList(Of String) = null, Optional isCompressionEnabled As Nullable(Of Boolean) = null, Optional isHttpAllowed As Nullable(Of Boolean) = null, Optional isHttpsAllowed As Nullable(Of Boolean) = null, Optional queryStringCachingBehavior As Nullable(Of QueryStringCachingBehavior) = null, Optional optimizationType As String = null, Optional geoFilters As IList(Of GeoFilter) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner : System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner (tags, originHostHeader, originPath, contentTypesToCompress, isCompressionEnabled, isHttpAllowed, isHttpsAllowed, queryStringCachingBehavior, optimizationType, geoFilters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="originHostHeader" Type="System.String" />
        <Parameter Name="originPath" Type="System.String" />
        <Parameter Name="contentTypesToCompress" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="isCompressionEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isHttpAllowed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isHttpsAllowed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="queryStringCachingBehavior" Type="System.Nullable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt;" />
        <Parameter Name="optimizationType" Type="System.String" />
        <Parameter Name="geoFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="tags">Endpunkt-Tags.</param>
        <param name="originHostHeader">Der Hostheader CDN sendet zusammen mit inhaltsanforderungen Ursprung. Der Standardwert ist der Hostname des Ursprungs.</param>
        <param name="originPath">Der Pfad verwendet, wenn das CDN Anforderung an den Ursprung gesendet wird.</param>
        <param name="contentTypesToCompress">Liste der Inhaltstypen, die für die Komprimierung angewendet wird. Der Wert muss ein gültiger MIME-Typ.</param>
        <param name="isCompressionEnabled">Gibt an, ob Komprimierung Inhalte auf CDN aktiviert ist. Der Standardwert ist „false“. Wenn die Komprimierung aktiviert ist, wird Inhalt als bedient werden komprimiert, wenn der Benutzer eine komprimierte Version anfordert. Inhalt wird nicht auf CDN komprimiert werden, wenn angeforderten Inhalt 1 Byte kleiner oder größer als 1 MB ist.</param>
        <param name="isHttpAllowed">Gibt an, ob HTTP-Datenverkehr für den Endpunkt zulässig ist. Standardwert ist "true". Es muss mindestens ein Protokoll (HTTP oder HTTPS) zulässig sein.</param>
        <param name="isHttpsAllowed">Gibt an, ob HTTPS-Datenverkehr für den Endpunkt zulässig ist. Standardwert ist "true". Es muss mindestens ein Protokoll (HTTP oder HTTPS) zulässig sein.</param>
        <param name="queryStringCachingBehavior">Definiert die Zeichenfolge der Abfrage, die Verhalten beim Zwischenspeichern. Folgende Werte sind möglich: 'IgnoreQueryString', 'BypassCaching', 'UseQueryString', 'NotSet'</param>
        <param name="optimizationType">Kunden kann angeben, welches Szenario diesem CDN-Endpunkt zu optimieren, z. B. herunterladen, Media Services werden soll. Mit diesen Informationen können Szenario driven Optimierung angewendet werden.</param>
        <param name="geoFilters">Liste der Regeln, die geografische Benutzerzugriff in einem CDN-Endpunkt zu definieren. Jede geografische Filter definiert eine Regel auf, zu einem angegebenen Pfad oder den Inhalt, z. B. Block APAC für Pfad /pictures/</param>
        <summary>
            Initialisiert eine neue Instanz der EndpointUpdateParametersInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentTypesToCompress">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ContentTypesToCompress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ContentTypesToCompress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.ContentTypesToCompress" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentTypesToCompress As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ContentTypesToCompress : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.ContentTypesToCompress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.contentTypesToCompress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Inhaltstypen für die Komprimierung angewendet wird.
            Der Wert muss ein gültiger MIME-Typ.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; GeoFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; GeoFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.GeoFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property GeoFilters As IList(Of GeoFilter)" />
      <MemberSignature Language="F#" Value="member this.GeoFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.GeoFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.geoFilters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Regeln, die geografische Benutzerzugriff in einem CDN-Endpunkt zu definieren. Jede geografische Filter definiert eine Regel auf, zu einem angegebenen Pfad oder den Inhalt, z. B. Block APAC für Pfad /pictures/
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsCompressionEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsCompressionEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsCompressionEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.IsCompressionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsCompressionEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsCompressionEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.IsCompressionEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isCompressionEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob es sich bei inhaltskomprimierung auf CDN aktiviert ist, ruft ab oder legt ihn fest. Der Standardwert ist „false“. Wenn die Komprimierung aktiviert ist, wird Inhalt als bedient werden komprimiert, wenn der Benutzer eine komprimierte Version anfordert. Inhalt wird nicht auf CDN komprimiert werden, wenn angeforderten Inhalt 1 Byte kleiner oder größer als 1 MB ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsHttpAllowed">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsHttpAllowed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsHttpAllowed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.IsHttpAllowed" />
      <MemberSignature Language="VB.NET" Value="Public Property IsHttpAllowed As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsHttpAllowed : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.IsHttpAllowed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isHttpAllowed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob es sich bei HTTP-Datenverkehr auf dem Endpunkt zulässig ist, ruft ab oder legt ihn fest. Standardwert ist "true". Es muss mindestens ein Protokoll (HTTP oder HTTPS) zulässig sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsHttpsAllowed">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsHttpsAllowed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsHttpsAllowed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.IsHttpsAllowed" />
      <MemberSignature Language="VB.NET" Value="Public Property IsHttpsAllowed As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsHttpsAllowed : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.IsHttpsAllowed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isHttpsAllowed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob es sich bei HTTPS-Datenverkehr auf dem Endpunkt zulässig ist, ruft ab oder legt ihn fest. Standardwert ist "true". Es muss mindestens ein Protokoll (HTTP oder HTTPS) zulässig sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OptimizationType">
      <MemberSignature Language="C#" Value="public string OptimizationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OptimizationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.OptimizationType" />
      <MemberSignature Language="VB.NET" Value="Public Property OptimizationType As String" />
      <MemberSignature Language="F#" Value="member this.OptimizationType : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.OptimizationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.optimizationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Kunden kann angeben, welches Szenario diesem CDN-Endpunkt zu optimieren, z. B. herunterladen, Media Services werden soll. Mit diesen Informationen können Szenario driven Optimierung angewendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginHostHeader">
      <MemberSignature Language="C#" Value="public string OriginHostHeader { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OriginHostHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.OriginHostHeader" />
      <MemberSignature Language="VB.NET" Value="Public Property OriginHostHeader As String" />
      <MemberSignature Language="F#" Value="member this.OriginHostHeader : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.OriginHostHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.originHostHeader")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Host-Header, die, den zusammen mit inhaltsanforderungen Ursprung CDN sendet. Der Standardwert ist der Hostname des Ursprungs.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginPath">
      <MemberSignature Language="C#" Value="public string OriginPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OriginPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.OriginPath" />
      <MemberSignature Language="VB.NET" Value="Public Property OriginPath As String" />
      <MemberSignature Language="F#" Value="member this.OriginPath : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.OriginPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.originPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Pfad verwendet, wenn das CDN Anforderung an den Ursprung gesendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryStringCachingBehavior">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; QueryStringCachingBehavior { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; QueryStringCachingBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.QueryStringCachingBehavior" />
      <MemberSignature Language="VB.NET" Value="Public Property QueryStringCachingBehavior As Nullable(Of QueryStringCachingBehavior)" />
      <MemberSignature Language="F#" Value="member this.QueryStringCachingBehavior : Nullable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.QueryStringCachingBehavior" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.queryStringCachingBehavior")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest definiert die Zeichenfolge der Abfrage, die Verhalten beim Zwischenspeichern. Folgende Werte sind möglich: 'IgnoreQueryString', 'BypassCaching', 'UseQueryString', 'NotSet'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Endpunkt Tags.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>