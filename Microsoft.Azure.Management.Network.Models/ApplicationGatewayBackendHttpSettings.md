<Type Name="ApplicationGatewayBackendHttpSettings" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayBackendHttpSettings : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayBackendHttpSettings extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayBackendHttpSettings&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayBackendHttpSettings = class&#xA;    inherit SubResource" />
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
            Back-End-Pool adresseinstellungen eines Gateways für die Anwendung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayBackendHttpSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.#ctor" />
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
            Initialisiert eine neue Instanz der ApplicationGatewayBackendHttpSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayBackendHttpSettings (string id = null, Nullable&lt;int&gt; port = null, string protocol = null, string cookieBasedAffinity = null, Nullable&lt;int&gt; requestTimeout = null, Microsoft.Azure.Management.Network.Models.SubResource probe = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; authenticationCertificates = null, Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining connectionDraining = null, string hostName = null, Nullable&lt;bool&gt; pickHostNameFromBackendAddress = null, string affinityCookieName = null, Nullable&lt;bool&gt; probeEnabled = null, string path = null, string provisioningState = null, string name = null, string etag = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, valuetype System.Nullable`1&lt;int32&gt; port, string protocol, string cookieBasedAffinity, valuetype System.Nullable`1&lt;int32&gt; requestTimeout, class Microsoft.Azure.Management.Network.Models.SubResource probe, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; authenticationCertificates, class Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining connectionDraining, string hostName, valuetype System.Nullable`1&lt;bool&gt; pickHostNameFromBackendAddress, string affinityCookieName, valuetype System.Nullable`1&lt;bool&gt; probeEnabled, string path, string provisioningState, string name, string etag, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.#ctor(System.String,System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Int32},Microsoft.Azure.Management.Network.Models.SubResource,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.SubResource},Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining,System.String,System.Nullable{System.Boolean},System.String,System.Nullable{System.Boolean},System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional port As Nullable(Of Integer) = null, Optional protocol As String = null, Optional cookieBasedAffinity As String = null, Optional requestTimeout As Nullable(Of Integer) = null, Optional probe As SubResource = null, Optional authenticationCertificates As IList(Of SubResource) = null, Optional connectionDraining As ApplicationGatewayConnectionDraining = null, Optional hostName As String = null, Optional pickHostNameFromBackendAddress As Nullable(Of Boolean) = null, Optional affinityCookieName As String = null, Optional probeEnabled As Nullable(Of Boolean) = null, Optional path As String = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings : string * Nullable&lt;int&gt; * string * string * Nullable&lt;int&gt; * Microsoft.Azure.Management.Network.Models.SubResource * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; * Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining * string * Nullable&lt;bool&gt; * string * Nullable&lt;bool&gt; * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings (id, port, protocol, cookieBasedAffinity, requestTimeout, probe, authenticationCertificates, connectionDraining, hostName, pickHostNameFromBackendAddress, affinityCookieName, probeEnabled, path, provisioningState, name, etag, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="port" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="cookieBasedAffinity" Type="System.String" />
        <Parameter Name="requestTimeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="probe" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="authenticationCertificates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;" />
        <Parameter Name="connectionDraining" Type="Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="pickHostNameFromBackendAddress" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="affinityCookieName" Type="System.String" />
        <Parameter Name="probeEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-ID</param>
        <param name="port">Port</param>
        <param name="protocol">Protokoll. Folgende Werte sind möglich: "Http", "Https"</param>
        <param name="cookieBasedAffinity">Affinität für Cookie-basiert. Folgende Werte sind möglich: "Enabled", "Disabled"</param>
        <param name="requestTimeout">Anforderungstimeout in Sekunden.
            Application Gateway wird die Anforderung fehl, wenn keine Antwort innerhalb der RequestTimeout empfangen wird. Die zulässigen Werte reichen von 1 Sekunde bis 86400 Sekunden.</param>
        <param name="probe">Prüfpunkt Ressource eines Gateways für die Anwendung an.</param>
        <param name="authenticationCertificates">Ein Array von Verweisen auf Zertifikate für die Clientauthentifizierung von Application Gateway.</param>
        <param name="connectionDraining">Der Back-End-HTTP-Einstellungsressource durch Verbindung ein.</param>
        <param name="hostName">Hostheader an die Back-End-Server gesendet werden.</param>
        <param name="pickHostNameFromBackendAddress">Ob Hostheader auswählen sollten aus den Hostnamen des Back-End-Servers ausgewählt werden.
            Der Standardwert ist „false“.</param>
        <param name="affinityCookieName">Name des Cookies, die für das Cookie Affinität verwendet.</param>
        <param name="probeEnabled">Gibt an, ob die Überprüfung aktiviert ist. Der Standardwert ist „false“.</param>
        <param name="path">Pfad als Präfix für alle HTTP-Anforderungen verwendet werden soll. NULL bedeutet, dass kein Pfad wird als Präfix verwendet werden. Standardwert ist null.</param>
        <param name="provisioningState">Der Bereitstellungsstatus des Back-End-HTTP-Einstellungsressource. Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</param>
        <param name="name">Der Name der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist. Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</param>
        <param name="etag">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</param>
        <param name="type">Der Typ der Ressource.</param>
        <summary>
            Initialisiert eine neue Instanz der ApplicationGatewayBackendHttpSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityCookieName">
      <MemberSignature Language="C#" Value="public string AffinityCookieName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AffinityCookieName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.AffinityCookieName" />
      <MemberSignature Language="VB.NET" Value="Public Property AffinityCookieName As String" />
      <MemberSignature Language="F#" Value="member this.AffinityCookieName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.AffinityCookieName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.affinityCookieName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Cookienamen, der für das Cookie Affinität verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationCertificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; AuthenticationCertificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; AuthenticationCertificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.AuthenticationCertificates" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationCertificates As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.AuthenticationCertificates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.AuthenticationCertificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authenticationCertificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Array von Verweisen auf Zertifikate für die Clientauthentifizierung von Application Gateway.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionDraining">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining ConnectionDraining { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining ConnectionDraining" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.ConnectionDraining" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionDraining As ApplicationGatewayConnectionDraining" />
      <MemberSignature Language="F#" Value="member this.ConnectionDraining : Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.ConnectionDraining" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.connectionDraining")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie fest, Verbindung durch die Back-End-HTTP-Einstellungen-Ressource ein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CookieBasedAffinity">
      <MemberSignature Language="C#" Value="public string CookieBasedAffinity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CookieBasedAffinity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.CookieBasedAffinity" />
      <MemberSignature Language="VB.NET" Value="Public Property CookieBasedAffinity As String" />
      <MemberSignature Language="F#" Value="member this.CookieBasedAffinity : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.CookieBasedAffinity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cookieBasedAffinity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Affinität Cookie-basiert. Folgende Werte sind möglich: "Enabled", "Disabled"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.Etag" />
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
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.HostName" />
      <MemberSignature Language="VB.NET" Value="Public Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert einen Hostheader an die Back-End-Server gesendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.Name" />
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
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt der Pfad, der als Präfix für alle HTTP-Anforderungen verwendet werden soll. NULL bedeutet, dass kein Pfad wird als Präfix verwendet werden. Standardwert ist null.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PickHostNameFromBackendAddress">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PickHostNameFromBackendAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PickHostNameFromBackendAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.PickHostNameFromBackendAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property PickHostNameFromBackendAddress As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PickHostNameFromBackendAddress : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.PickHostNameFromBackendAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pickHostNameFromBackendAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob der Host auswählen Header aus der Hostname des Back-End-Servers ausgewählt werden soll. Der Standardwert ist „false“.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Port : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Probe">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource Probe { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource Probe" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.Probe" />
      <MemberSignature Language="VB.NET" Value="Public Property Probe As SubResource" />
      <MemberSignature Language="F#" Value="member this.Probe : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.Probe" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.probe")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder Test-Ressourcen eines Gateways für die Anwendung definiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProbeEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ProbeEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ProbeEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.ProbeEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ProbeEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ProbeEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.ProbeEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.probeEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, ob die Überprüfung aktiviert ist. Der Standardwert ist „false“.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest. Folgende Werte sind möglich: "Http", "Https"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie fest, der Bereitstellungsstatus des Back-End-HTTP-Einstellungsressource. Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RequestTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RequestTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.RequestTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RequestTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.RequestTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestTimeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Anforderungstimeout in Sekunden fest. Application Gateway wird die Anforderung fehl, wenn keine Antwort innerhalb der RequestTimeout empfangen wird.
            Die zulässigen Werte reichen von 1 Sekunde bis 86400 Sekunden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.Type" />
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
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationGatewayBackendHttpSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>