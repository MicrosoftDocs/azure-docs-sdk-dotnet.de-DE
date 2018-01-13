<Type Name="HostNameBinding" FullName="Microsoft.Azure.Management.WebSites.Models.HostNameBinding">
  <TypeSignature Language="C#" Value="public class HostNameBinding : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HostNameBinding extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.HostNameBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class HostNameBinding&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type HostNameBinding = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Hostname Binding-Objekt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HostNameBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der HostNameBinding-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HostNameBinding (string id = null, string name = null, string kind = null, string type = null, string siteName = null, string domainId = null, string azureResourceName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AzureResourceType&gt; azureResourceType = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType&gt; customHostNameDnsRecordType = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostNameType&gt; hostNameType = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt; sslState = null, string thumbprint = null, string virtualIP = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string siteName, string domainId, string azureResourceName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.AzureResourceType&gt; azureResourceType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType&gt; customHostNameDnsRecordType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.HostNameType&gt; hostNameType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.SslState&gt; sslState, string thumbprint, string virtualIP) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.AzureResourceType},System.Nullable{Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType},System.Nullable{Microsoft.Azure.Management.WebSites.Models.HostNameType},System.Nullable{Microsoft.Azure.Management.WebSites.Models.SslState},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional siteName As String = null, Optional domainId As String = null, Optional azureResourceName As String = null, Optional azureResourceType As Nullable(Of AzureResourceType) = null, Optional customHostNameDnsRecordType As Nullable(Of CustomHostNameDnsRecordType) = null, Optional hostNameType As Nullable(Of HostNameType) = null, Optional sslState As Nullable(Of SslState) = null, Optional thumbprint As String = null, Optional virtualIP As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.HostNameBinding : string * string * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AzureResourceType&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostNameType&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt; * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.HostNameBinding" Usage="new Microsoft.Azure.Management.WebSites.Models.HostNameBinding (id, name, kind, type, siteName, domainId, azureResourceName, azureResourceType, customHostNameDnsRecordType, hostNameType, sslState, thumbprint, virtualIP)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="domainId" Type="System.String" />
        <Parameter Name="azureResourceName" Type="System.String" />
        <Parameter Name="azureResourceType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AzureResourceType&gt;" />
        <Parameter Name="customHostNameDnsRecordType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType&gt;" />
        <Parameter Name="hostNameType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostNameType&gt;" />
        <Parameter Name="sslState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt;" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="virtualIP" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id.</param>
        <param name="name">Ressourcenname.</param>
        <param name="kind">Die Art der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="siteName">App Service-app-Name.</param>
        <param name="domainId">Vollqualifizierte ARM-Domänenressource URI.</param>
        <param name="azureResourceName">Name des Azure-Ressource.</param>
        <param name="azureResourceType">Azure-Ressource-Typ. Folgende Werte sind möglich: "Website", "TrafficManager"</param>
        <param name="customHostNameDnsRecordType">Benutzerdefinierte DNS-Datensatztyp.
            Folgende Werte sind möglich: "CName", "A"</param>
        <param name="hostNameType">Hostname-Typ. Folgende Werte sind möglich: "Überprüft", "Verwaltet"</param>
        <param name="sslState">SSL-Typ. Folgende Werte sind möglich: "Deaktiviert", "SniEnabled", "IpBasedEnabled"</param>
        <param name="thumbprint">Fingerabdruck des SSL-Zertifikats</param>
        <param name="virtualIP">Virtuelle IP-Adresse, den Hostnamen zugewiesen, wenn die IP-basiertes SSL aktiviert ist.</param>
        <summary>
            Initialisiert eine neue Instanz der HostNameBinding-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureResourceName">
      <MemberSignature Language="C#" Value="public string AzureResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzureResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.AzureResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureResourceName As String" />
      <MemberSignature Language="F#" Value="member this.AzureResourceName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.AzureResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.azureResourceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Azure-Ressourcennamen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureResourceType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AzureResourceType&gt; AzureResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.AzureResourceType&gt; AzureResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.AzureResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureResourceType As Nullable(Of AzureResourceType)" />
      <MemberSignature Language="F#" Value="member this.AzureResourceType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AzureResourceType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.AzureResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.azureResourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AzureResourceType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Azure-Ressource. Folgende Werte sind möglich: "Website", "TrafficManager"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomHostNameDnsRecordType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType&gt; CustomHostNameDnsRecordType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType&gt; CustomHostNameDnsRecordType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.CustomHostNameDnsRecordType" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomHostNameDnsRecordType As Nullable(Of CustomHostNameDnsRecordType)" />
      <MemberSignature Language="F#" Value="member this.CustomHostNameDnsRecordType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.CustomHostNameDnsRecordType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customHostNameDnsRecordType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest benutzerdefinierten DNS-Eintragstyp. Folgende Werte sind möglich: "CName", "A"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainId">
      <MemberSignature Language="C#" Value="public string DomainId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.DomainId" />
      <MemberSignature Language="VB.NET" Value="Public Property DomainId As String" />
      <MemberSignature Language="F#" Value="member this.DomainId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.DomainId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.domainId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest vollqualifizierten ARM Domänenressource URI.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostNameType&gt; HostNameType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.HostNameType&gt; HostNameType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.HostNameType" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameType As Nullable(Of HostNameType)" />
      <MemberSignature Language="F#" Value="member this.HostNameType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostNameType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.HostNameType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNameType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostNameType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Hostname. Folgende Werte sind möglich: "Überprüft", "Verwaltet"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteName">
      <MemberSignature Language="C#" Value="public string SiteName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.SiteName" />
      <MemberSignature Language="VB.NET" Value="Public Property SiteName As String" />
      <MemberSignature Language="F#" Value="member this.SiteName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.SiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.siteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Name des app Service-app.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SslState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt; SslState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.SslState&gt; SslState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.SslState" />
      <MemberSignature Language="VB.NET" Value="Public Property SslState As Nullable(Of SslState)" />
      <MemberSignature Language="F#" Value="member this.SslState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.SslState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sslState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest SSL. Folgende Werte sind möglich: "Deaktiviert", "SniEnabled", "IpBasedEnabled"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Fingerabdruck des SSL-Zertifikats
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualIP">
      <MemberSignature Language="C#" Value="public string VirtualIP { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.VirtualIP" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualIP As String" />
      <MemberSignature Language="F#" Value="member this.VirtualIP : string" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.VirtualIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualIP")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft virtuelle IP-Adresse, den Hostnamen zugewiesen, wenn die IP-basiertes SSL aktiviert ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>