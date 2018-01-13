<Type Name="DomainPatchResource" FullName="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource">
  <TypeSignature Language="C#" Value="public class DomainPatchResource : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DomainPatchResource extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource" />
  <TypeSignature Language="VB.NET" Value="Public Class DomainPatchResource&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type DomainPatchResource = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            ARM-Ressource für eine Domäne.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainPatchResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DomainPatchResource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainPatchResource (string id = null, string name = null, string kind = null, string type = null, Microsoft.Azure.Management.WebSites.Models.Contact contactAdmin = null, Microsoft.Azure.Management.WebSites.Models.Contact contactBilling = null, Microsoft.Azure.Management.WebSites.Models.Contact contactRegistrant = null, Microsoft.Azure.Management.WebSites.Models.Contact contactTech = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainStatus&gt; registrationStatus = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState = null, System.Collections.Generic.IList&lt;string&gt; nameServers = null, Nullable&lt;bool&gt; privacy = null, Nullable&lt;DateTime&gt; createdTime = null, Nullable&lt;DateTime&gt; expirationTime = null, Nullable&lt;DateTime&gt; lastRenewedTime = null, Nullable&lt;bool&gt; autoRenew = null, Nullable&lt;bool&gt; readyForDnsRecordManagement = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostName&gt; managedHostNames = null, Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent consent = null, System.Collections.Generic.IList&lt;string&gt; domainNotRenewableReasons = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt; dnsType = null, string dnsZoneId = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt; targetDnsType = null, string authCode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, class Microsoft.Azure.Management.WebSites.Models.Contact contactAdmin, class Microsoft.Azure.Management.WebSites.Models.Contact contactBilling, class Microsoft.Azure.Management.WebSites.Models.Contact contactRegistrant, class Microsoft.Azure.Management.WebSites.Models.Contact contactTech, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.DomainStatus&gt; registrationStatus, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState, class System.Collections.Generic.IList`1&lt;string&gt; nameServers, valuetype System.Nullable`1&lt;bool&gt; privacy, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expirationTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRenewedTime, valuetype System.Nullable`1&lt;bool&gt; autoRenew, valuetype System.Nullable`1&lt;bool&gt; readyForDnsRecordManagement, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HostName&gt; managedHostNames, class Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent consent, class System.Collections.Generic.IList`1&lt;string&gt; domainNotRenewableReasons, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.DnsType&gt; dnsType, string dnsZoneId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.DnsType&gt; targetDnsType, string authCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.Contact,Microsoft.Azure.Management.WebSites.Models.Contact,Microsoft.Azure.Management.WebSites.Models.Contact,Microsoft.Azure.Management.WebSites.Models.Contact,System.Nullable{Microsoft.Azure.Management.WebSites.Models.DomainStatus},System.Nullable{Microsoft.Azure.Management.WebSites.Models.ProvisioningState},System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.HostName},Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent,System.Collections.Generic.IList{System.String},System.Nullable{Microsoft.Azure.Management.WebSites.Models.DnsType},System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.DnsType},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional contactAdmin As Contact = null, Optional contactBilling As Contact = null, Optional contactRegistrant As Contact = null, Optional contactTech As Contact = null, Optional registrationStatus As Nullable(Of DomainStatus) = null, Optional provisioningState As Nullable(Of ProvisioningState) = null, Optional nameServers As IList(Of String) = null, Optional privacy As Nullable(Of Boolean) = null, Optional createdTime As Nullable(Of DateTime) = null, Optional expirationTime As Nullable(Of DateTime) = null, Optional lastRenewedTime As Nullable(Of DateTime) = null, Optional autoRenew As Nullable(Of Boolean) = null, Optional readyForDnsRecordManagement As Nullable(Of Boolean) = null, Optional managedHostNames As IList(Of HostName) = null, Optional consent As DomainPurchaseConsent = null, Optional domainNotRenewableReasons As IList(Of String) = null, Optional dnsType As Nullable(Of DnsType) = null, Optional dnsZoneId As String = null, Optional targetDnsType As Nullable(Of DnsType) = null, Optional authCode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.DomainPatchResource : string * string * string * string * Microsoft.Azure.Management.WebSites.Models.Contact * Microsoft.Azure.Management.WebSites.Models.Contact * Microsoft.Azure.Management.WebSites.Models.Contact * Microsoft.Azure.Management.WebSites.Models.Contact * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainStatus&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostName&gt; * Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt; * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.DomainPatchResource" Usage="new Microsoft.Azure.Management.WebSites.Models.DomainPatchResource (id, name, kind, type, contactAdmin, contactBilling, contactRegistrant, contactTech, registrationStatus, provisioningState, nameServers, privacy, createdTime, expirationTime, lastRenewedTime, autoRenew, readyForDnsRecordManagement, managedHostNames, consent, domainNotRenewableReasons, dnsType, dnsZoneId, targetDnsType, authCode)" />
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
        <Parameter Name="contactAdmin" Type="Microsoft.Azure.Management.WebSites.Models.Contact" />
        <Parameter Name="contactBilling" Type="Microsoft.Azure.Management.WebSites.Models.Contact" />
        <Parameter Name="contactRegistrant" Type="Microsoft.Azure.Management.WebSites.Models.Contact" />
        <Parameter Name="contactTech" Type="Microsoft.Azure.Management.WebSites.Models.Contact" />
        <Parameter Name="registrationStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainStatus&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" />
        <Parameter Name="nameServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="privacy" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="createdTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="expirationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastRenewedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="autoRenew" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="readyForDnsRecordManagement" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="managedHostNames" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostName&gt;" />
        <Parameter Name="consent" Type="Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent" />
        <Parameter Name="domainNotRenewableReasons" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="dnsType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt;" />
        <Parameter Name="dnsZoneId" Type="System.String" />
        <Parameter Name="targetDnsType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt;" />
        <Parameter Name="authCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id.</param>
        <param name="name">Ressourcenname.</param>
        <param name="kind">Die Art der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="contactAdmin">Administratorkontakt.</param>
        <param name="contactBilling">Abrechnung wenden Sie sich an.</param>
        <param name="contactRegistrant">Registrant wenden Sie sich an.</param>
        <param name="contactTech">Der technische Kontakt.</param>
        <param name="registrationStatus">Registrierungsstatus Domäne.
            Folgende Werte sind möglich: "Aktiv", "Anwendung wartet auf", "Abgebrochen", "Confiscated", "Deaktiviert", "Ausgeschlossen", "Abgelaufen", "Fehlgeschlagen", "Frei", "Gesperrt", "Parked", "Ausstehend", "Reserviert", "Wiederhergestellten", "Angehalten", "Übertragen", "Unknown", "Entsperrt", "Unparked", " Aktualisiert ', 'JsonConverterFailed'</param>
        <param name="provisioningState">Bereitstellungsstatus der Domäne. Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen", "InProgress", "Löschen"</param>
        <param name="nameServers">Namenserver.</param>
        <param name="privacy">&lt;Code&gt;"true"&lt;/code&gt; wenn Domäne Datenschutz für diese Domäne aktiviert ist, andernfalls ist &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <param name="createdTime">Erstellungszeitstempel Domäne.</param>
        <param name="expirationTime">Domäne Ablauf Zeitstempel.</param>
        <param name="lastRenewedTime">Zeitstempel für die Domäne zuletzt erneuert wurde.</param>
        <param name="autoRenew">&lt;Code&gt;"true"&lt;/code&gt; Wenn die Domäne, automatisch erneuert, andernfalls werden sollen &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <param name="readyForDnsRecordManagement">&lt;Code&gt;"true"&lt;/code&gt; Wenn Azure App Service-apps; diese Domäne zuweisen kann, andernfalls &lt;Code&gt;"false"&lt;/code&gt;. Dieser Wert &lt;Code&gt;"true"&lt;/code&gt; wenn Domäne Registrierungsstatus aktiv ist und es auf Azure bietet programmgesteuerten Zugriff auf Namenservern gehostet wird.</param>
        <param name="managedHostNames">Alle Hostnamen abgeleitet aus der Domäne und Azure-Ressourcen zugewiesen werden.</param>
        <param name="consent">Rechtsgültigen Vertrag Zustimmung.</param>
        <param name="domainNotRenewableReasons">Gründe, warum eine Domäne nicht erneuerbar ist.</param>
        <param name="dnsType">Aktuelle DNS-Typ. Folgende Werte sind möglich: "AzureDns", "DefaultDomainRegistrarDns"</param>
        <param name="dnsZoneId">Verwenden von Azure DNS-Zone</param>
        <param name="targetDnsType">DNS-Zieltyp (würden für die Migration verwendet werden). Folgende Werte sind möglich: "AzureDns", "DefaultDomainRegistrarDns"</param>
        <param name="authCode">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der DomainPatchResource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthCode">
      <MemberSignature Language="C#" Value="public string AuthCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.AuthCode" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthCode As String" />
      <MemberSignature Language="F#" Value="member this.AuthCode : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.AuthCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoRenew">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoRenew { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoRenew" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.AutoRenew" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoRenew As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoRenew : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.AutoRenew" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoRenew")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn die Domäne, automatisch erneuert, andernfalls werden sollen &amp;Lt; Code&amp;Gt "false"&amp;Lt; /code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Consent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent Consent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent Consent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.Consent" />
      <MemberSignature Language="VB.NET" Value="Public Property Consent As DomainPurchaseConsent" />
      <MemberSignature Language="F#" Value="member this.Consent : Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.Consent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.consent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.DomainPurchaseConsent</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest rechtsgültigen Vertrag Zustimmung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContactAdmin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.Contact ContactAdmin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.Contact ContactAdmin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.ContactAdmin" />
      <MemberSignature Language="VB.NET" Value="Public Property ContactAdmin As Contact" />
      <MemberSignature Language="F#" Value="member this.ContactAdmin : Microsoft.Azure.Management.WebSites.Models.Contact with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.ContactAdmin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.contactAdmin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Administratorkontakt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContactBilling">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.Contact ContactBilling { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.Contact ContactBilling" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.ContactBilling" />
      <MemberSignature Language="VB.NET" Value="Public Property ContactBilling As Contact" />
      <MemberSignature Language="F#" Value="member this.ContactBilling : Microsoft.Azure.Management.WebSites.Models.Contact with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.ContactBilling" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.contactBilling")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Rechnungskontakt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContactRegistrant">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.Contact ContactRegistrant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.Contact ContactRegistrant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.ContactRegistrant" />
      <MemberSignature Language="VB.NET" Value="Public Property ContactRegistrant As Contact" />
      <MemberSignature Language="F#" Value="member this.ContactRegistrant : Microsoft.Azure.Management.WebSites.Models.Contact with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.ContactRegistrant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.contactRegistrant")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Registrant wenden Sie sich an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContactTech">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.Contact ContactTech { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.Contact ContactTech" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.ContactTech" />
      <MemberSignature Language="VB.NET" Value="Public Property ContactTech As Contact" />
      <MemberSignature Language="F#" Value="member this.ContactTech : Microsoft.Azure.Management.WebSites.Models.Contact with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.ContactTech" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.contactTech")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den technischen Kontakt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.CreatedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.CreatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Domäne Erstellungszeitstempel ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt; DnsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.DnsType&gt; DnsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.DnsType" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsType As Nullable(Of DnsType)" />
      <MemberSignature Language="F#" Value="member this.DnsType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.DnsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der aktuellen DNS-Typ. Folgende Werte sind möglich: "AzureDns", "DefaultDomainRegistrarDns"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsZoneId">
      <MemberSignature Language="C#" Value="public string DnsZoneId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DnsZoneId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.DnsZoneId" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsZoneId As String" />
      <MemberSignature Language="F#" Value="member this.DnsZoneId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.DnsZoneId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsZoneId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Azure DNS-Zone verwenden
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainNotRenewableReasons">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DomainNotRenewableReasons { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DomainNotRenewableReasons" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.DomainNotRenewableReasons" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DomainNotRenewableReasons As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DomainNotRenewableReasons : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.DomainNotRenewableReasons" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.domainNotRenewableReasons")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Gründe, warum eine Domäne nicht erneuerbar ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.expirationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ablaufzeit Zeitstempel Domäne ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRenewedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRenewedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRenewedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.LastRenewedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastRenewedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRenewedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.LastRenewedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastRenewedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Zeitstempel ab, wenn die Domäne zuletzt erneuert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostName&gt; ManagedHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HostName&gt; ManagedHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.ManagedHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ManagedHostNames As IList(Of HostName)" />
      <MemberSignature Language="F#" Value="member this.ManagedHostNames : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostName&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.ManagedHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.managedHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft alle Hostnamen abgeleitet aus der Domäne und Azure-Ressourcen zugewiesen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; NameServers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; NameServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.NameServers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NameServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NameServers : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.NameServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            Ruft die Namenservern ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Privacy">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Privacy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Privacy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.Privacy" />
      <MemberSignature Language="VB.NET" Value="Public Property Privacy As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Privacy : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.Privacy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privacy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn Domäne Datenschutz für diese Domäne aktiviert ist, andernfalls ist &amp;Lt; Code&amp;Gt "false"&amp;Lt; /code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Zustand Domäne bereitgestellt werden. Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen", "InProgress", "Löschen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadyForDnsRecordManagement">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReadyForDnsRecordManagement { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReadyForDnsRecordManagement" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.ReadyForDnsRecordManagement" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadyForDnsRecordManagement As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReadyForDnsRecordManagement : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.ReadyForDnsRecordManagement" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.readyForDnsRecordManagement")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn Azure App Service-apps; diese Domäne zuweisen kann, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; /code&amp;Gt;. Dieser Wert &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn Domäne Registrierungsstatus aktiv ist und es auf Azure bietet programmgesteuerten Zugriff auf Namenservern gehostet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainStatus&gt; RegistrationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.DomainStatus&gt; RegistrationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.RegistrationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegistrationStatus As Nullable(Of DomainStatus)" />
      <MemberSignature Language="F#" Value="member this.RegistrationStatus : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainStatus&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.RegistrationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.registrationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Domäne Registrierungsstatus ab. Folgende Werte sind möglich: "Aktiv", "Anwendung wartet auf", "Abgebrochen", "Confiscated", "Deaktiviert", "Ausgeschlossen", "Abgelaufen", "Fehlgeschlagen", "Frei", "Gesperrt", "Parked", "Ausstehend", "Reserviert", "Wiederhergestellten", "Angehalten", "Übertragen", "Unknown", "Entsperrt", "Unparked", " Aktualisiert ', 'JsonConverterFailed'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDnsType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt; TargetDnsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.DnsType&gt; TargetDnsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.TargetDnsType" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDnsType As Nullable(Of DnsType)" />
      <MemberSignature Language="F#" Value="member this.TargetDnsType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.TargetDnsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetDnsType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest (wird für die Migration verwendet werden) DNS-Zieltyp.
            Folgende Werte sind möglich: "AzureDns", "DefaultDomainRegistrarDns"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.DomainPatchResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="domainPatchResource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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