<Type Name="VpnClientParameters" FullName="Microsoft.Azure.Management.Network.Models.VpnClientParameters">
  <TypeSignature Language="C#" Value="public class VpnClientParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VpnClientParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class VpnClientParameters" />
  <TypeSignature Language="F#" Value="type VpnClientParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            VPN-Client-Parameter für die Erstellung eines Clientpakets
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VpnClientParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VpnClientParameters.#ctor" />
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
            Initialisiert eine neue Instanz der VpnClientParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VpnClientParameters (string processorArchitecture = null, string authenticationMethod = null, string radiusServerAuthCertificate = null, System.Collections.Generic.IList&lt;string&gt; clientRootCertificates = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string processorArchitecture, string authenticationMethod, string radiusServerAuthCertificate, class System.Collections.Generic.IList`1&lt;string&gt; clientRootCertificates) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VpnClientParameters.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional processorArchitecture As String = null, Optional authenticationMethod As String = null, Optional radiusServerAuthCertificate As String = null, Optional clientRootCertificates As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.VpnClientParameters : string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Models.VpnClientParameters" Usage="new Microsoft.Azure.Management.Network.Models.VpnClientParameters (processorArchitecture, authenticationMethod, radiusServerAuthCertificate, clientRootCertificates)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="processorArchitecture" Type="System.String" />
        <Parameter Name="authenticationMethod" Type="System.String" />
        <Parameter Name="radiusServerAuthCertificate" Type="System.String" />
        <Parameter Name="clientRootCertificates" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="processorArchitecture">VPN-Client-Architektur des Prozessors. Mögliche Werte sind: "AMD64" "X86". Folgende Werte sind möglich: "Amd64", "X86"</param>
        <param name="authenticationMethod">VPN-Client Authentifizierungsmethode. Mögliche Werte sind: "EAPTLS" und "EAPMSCHAPv2". Folgende Werte sind möglich: "EAPTLS", "EAPMSCHAPv2"</param>
        <param name="radiusServerAuthCertificate">Die öffentlichen Daten für das Radius-Serverzertifikat Authentifizierung als Base-64-codierte Zeichenfolge. Nur erforderlich, wenn externe Radius-Authentifizierung mit EAPTLS-Authentifizierung konfiguriert wurde.</param>
        <param name="clientRootCertificates">Eine Liste der Zertifikate öffentliches Zertifikat des Clients Stammdaten codiert als Base64-Zeichenfolgen.
            Ein optionaler Parameter für externe Radius-basierte Authentifizierung mit EAPTLS.</param>
        <summary>
            Initialisiert eine neue Instanz der VpnClientParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationMethod">
      <MemberSignature Language="C#" Value="public string AuthenticationMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientParameters.AuthenticationMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationMethod As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationMethod : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientParameters.AuthenticationMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authenticationMethod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-VPN-Client Authentifizierungsmethode. Mögliche Werte sind: "EAPTLS" und "EAPMSCHAPv2". Folgende Werte sind möglich: "EAPTLS", "EAPMSCHAPv2"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRootCertificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ClientRootCertificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ClientRootCertificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientParameters.ClientRootCertificates" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRootCertificates As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ClientRootCertificates : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientParameters.ClientRootCertificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="clientRootCertificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der clientstammzertifikate Zertifikat für Öffentliche Daten als Base64-Zeichenfolgen codiert. Ein optionaler Parameter für externe Radius-basierte Authentifizierung mit EAPTLS.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessorArchitecture">
      <MemberSignature Language="C#" Value="public string ProcessorArchitecture { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProcessorArchitecture" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientParameters.ProcessorArchitecture" />
      <MemberSignature Language="VB.NET" Value="Public Property ProcessorArchitecture As String" />
      <MemberSignature Language="F#" Value="member this.ProcessorArchitecture : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientParameters.ProcessorArchitecture" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="processorArchitecture")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-VPN-Client Prozessorarchitektur. Mögliche Werte sind: "AMD64" "X86". Folgende Werte sind möglich: "Amd64", "X86"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RadiusServerAuthCertificate">
      <MemberSignature Language="C#" Value="public string RadiusServerAuthCertificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RadiusServerAuthCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientParameters.RadiusServerAuthCertificate" />
      <MemberSignature Language="VB.NET" Value="Public Property RadiusServerAuthCertificate As String" />
      <MemberSignature Language="F#" Value="member this.RadiusServerAuthCertificate : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientParameters.RadiusServerAuthCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="radiusServerAuthCertificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft oder legt die öffentlichen Daten für den Radius-Server Authentifizierungszertifikat als Base64-codierte Zeichenfolge. Nur erforderlich, wenn externe Radius-Authentifizierung mit EAPTLS-Authentifizierung konfiguriert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>