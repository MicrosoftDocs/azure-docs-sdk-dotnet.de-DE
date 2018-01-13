<Type Name="ApplicationGatewayRedirectConfiguration" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayRedirectConfiguration : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayRedirectConfiguration extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayRedirectConfiguration&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayRedirectConfiguration = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Leiten Sie die Konfiguration eines Gateways für die Anwendung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayRedirectConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ApplicationGatewayRedirectConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayRedirectConfiguration (string id = null, string redirectType = null, Microsoft.Azure.Management.Network.Models.SubResource targetListener = null, string targetUrl = null, Nullable&lt;bool&gt; includePath = null, Nullable&lt;bool&gt; includeQueryString = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; requestRoutingRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; urlPathMaps = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; pathRules = null, string name = null, string etag = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string redirectType, class Microsoft.Azure.Management.Network.Models.SubResource targetListener, string targetUrl, valuetype System.Nullable`1&lt;bool&gt; includePath, valuetype System.Nullable`1&lt;bool&gt; includeQueryString, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; requestRoutingRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; urlPathMaps, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; pathRules, string name, string etag, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.#ctor(System.String,System.String,Microsoft.Azure.Management.Network.Models.SubResource,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.SubResource},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.SubResource},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.SubResource},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional redirectType As String = null, Optional targetListener As SubResource = null, Optional targetUrl As String = null, Optional includePath As Nullable(Of Boolean) = null, Optional includeQueryString As Nullable(Of Boolean) = null, Optional requestRoutingRules As IList(Of SubResource) = null, Optional urlPathMaps As IList(Of SubResource) = null, Optional pathRules As IList(Of SubResource) = null, Optional name As String = null, Optional etag As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration : string * string * Microsoft.Azure.Management.Network.Models.SubResource * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration (id, redirectType, targetListener, targetUrl, includePath, includeQueryString, requestRoutingRules, urlPathMaps, pathRules, name, etag, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="redirectType" Type="System.String" />
        <Parameter Name="targetListener" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="targetUrl" Type="System.String" />
        <Parameter Name="includePath" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="includeQueryString" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="requestRoutingRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;" />
        <Parameter Name="urlPathMaps" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;" />
        <Parameter Name="pathRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-ID</param>
        <param name="redirectType">HTTP-Umleitung Typen - Permanent, temporär, gefunden, SeeOther wird unterstützt. Folgende Werte sind möglich: 'Permanente', "Gefunden", "SeeOther", "Temporär"</param>
        <param name="targetListener">Verweis auf einen Listener, damit die Anforderung umgeleitet.</param>
        <param name="targetUrl">Die URL zum Umleiten der Anforderung an.</param>
        <param name="includePath">Pfad in der umgeleitete Url enthalten sein.</param>
        <param name="includeQueryString">Fügen Sie der umgeleitete Url Abfragezeichenfolge hinzu.</param>
        <param name="requestRoutingRules">Fordern Sie Routingkonfiguration Angabe umleiten.</param>
        <param name="urlPathMaps">URL-Pfad-Zuordnungen angeben standardmäßigen umleiten Konfiguration.</param>
        <param name="pathRules">Pfad Regeln angeben umleitungs-Konfiguration.</param>
        <param name="name">Der Name der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist. Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</param>
        <param name="etag">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</param>
        <param name="type">Der Typ der Ressource.</param>
        <summary>
            Initialisiert eine neue Instanz der ApplicationGatewayRedirectConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludePath">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IncludePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IncludePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.IncludePath" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludePath As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IncludePath : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.IncludePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.includePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Includepfad im umgeleiteten Url ein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeQueryString">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IncludeQueryString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IncludeQueryString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.IncludeQueryString" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludeQueryString As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IncludeQueryString : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.IncludeQueryString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.includeQueryString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt enthalten Abfragezeichenfolge im umgeleiteten Url.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt die Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist. Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; PathRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; PathRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.PathRules" />
      <MemberSignature Language="VB.NET" Value="Public Property PathRules As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.PathRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.PathRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pathRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Pfadregeln Umleitung Konfiguration angeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedirectType">
      <MemberSignature Language="C#" Value="public string RedirectType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RedirectType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.RedirectType" />
      <MemberSignature Language="VB.NET" Value="Public Property RedirectType As String" />
      <MemberSignature Language="F#" Value="member this.RedirectType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.RedirectType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.redirectType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie unterstützten HTTP-Umleitung Typen - Permanent, temporär, gefunden, SeeOther fest. Folgende Werte sind möglich: 'Permanente', "Gefunden", "SeeOther", "Temporär"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestRoutingRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; RequestRoutingRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; RequestRoutingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.RequestRoutingRules" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestRoutingRules As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.RequestRoutingRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.RequestRoutingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestRoutingRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Anforderung angeben Umleitung Routingkonfiguration.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetListener">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource TargetListener { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource TargetListener" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.TargetListener" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetListener As SubResource" />
      <MemberSignature Language="F#" Value="member this.TargetListener : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.TargetListener" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetListener")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Verweis auf einen Listener, damit die Anforderung umgeleitet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetUrl">
      <MemberSignature Language="C#" Value="public string TargetUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.TargetUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetUrl As String" />
      <MemberSignature Language="F#" Value="member this.TargetUrl : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.TargetUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Url für die Anforderung umgeleitet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Ressourcentyp aus.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UrlPathMaps">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; UrlPathMaps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; UrlPathMaps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.UrlPathMaps" />
      <MemberSignature Language="VB.NET" Value="Public Property UrlPathMaps As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.UrlPathMaps : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.UrlPathMaps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.urlPathMaps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Url-Pfad-Zuordnungen Umleitung Standardkonfiguration angeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>