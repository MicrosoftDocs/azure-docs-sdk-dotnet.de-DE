<Type Name="ResourceCertificateAndAcsDetails" FullName="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails">
  <TypeSignature Language="C#" Value="public class ResourceCertificateAndAcsDetails : Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceCertificateAndAcsDetails extends Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceCertificateAndAcsDetails&#xA;Inherits ResourceCertificateDetails" />
  <TypeSignature Language="F#" Value="type ResourceCertificateAndAcsDetails = class&#xA;    inherit ResourceCertificateDetails" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("AccessControlService")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Details des Zertifikats, das die tresoranmeldeinformationen für ACS darstellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceCertificateAndAcsDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ResourceCertificateAndAcsDetails-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceCertificateAndAcsDetails (string globalAcsNamespace, string globalAcsHostName, string globalAcsRPRealm, byte[] certificate = null, string friendlyName = null, string issuer = null, Nullable&lt;long&gt; resourceId = null, string subject = null, string thumbprint = null, Nullable&lt;DateTime&gt; validFrom = null, Nullable&lt;DateTime&gt; validTo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string globalAcsNamespace, string globalAcsHostName, string globalAcsRPRealm, unsigned int8[] certificate, string friendlyName, string issuer, valuetype System.Nullable`1&lt;int64&gt; resourceId, string subject, string thumbprint, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; validFrom, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; validTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.#ctor(System.String,System.String,System.String,System.Byte[],System.String,System.String,System.Nullable{System.Int64},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (globalAcsNamespace As String, globalAcsHostName As String, globalAcsRPRealm As String, Optional certificate As Byte() = null, Optional friendlyName As String = null, Optional issuer As String = null, Optional resourceId As Nullable(Of Long) = null, Optional subject As String = null, Optional thumbprint As String = null, Optional validFrom As Nullable(Of DateTime) = null, Optional validTo As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails : string * string * string * byte[] * string * string * Nullable&lt;int64&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails (globalAcsNamespace, globalAcsHostName, globalAcsRPRealm, certificate, friendlyName, issuer, resourceId, subject, thumbprint, validFrom, validTo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="globalAcsNamespace" Type="System.String" />
        <Parameter Name="globalAcsHostName" Type="System.String" />
        <Parameter Name="globalAcsRPRealm" Type="System.String" />
        <Parameter Name="certificate" Type="System.Byte[]" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="issuer" Type="System.String" />
        <Parameter Name="resourceId" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="subject" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="validFrom" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="validTo" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="globalAcsNamespace">ACS-Namespacenamen - Mandanten für den Dienst.</param>
        <param name="globalAcsHostName">ACS-Mgmt-Hostnamen für die Verbindung.</param>
        <param name="globalAcsRPRealm">Globale RP-Bereich des ACS-Namespace.</param>
        <param name="certificate">Die base64-codierte Zertifikat Rohdaten Zeichenfolge.</param>
        <param name="friendlyName">Friendlyname-Zertifikat.</param>
        <param name="issuer">Aussteller des Zertifikats.</param>
        <param name="resourceId">Ressourcen-ID des Tresors.</param>
        <param name="subject">Zertifikatsantragsteller.</param>
        <param name="thumbprint">Fingerabdruck des Zertifikats.</param>
        <param name="validFrom">Startzeit der Gültigkeit des Zertifikats.</param>
        <param name="validTo">Enddatum für die Gültigkeit des Zertifikatzeit.</param>
        <summary>
            Initialisiert eine neue Instanz der ResourceCertificateAndAcsDetails-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalAcsHostName">
      <MemberSignature Language="C#" Value="public string GlobalAcsHostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GlobalAcsHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.GlobalAcsHostName" />
      <MemberSignature Language="VB.NET" Value="Public Property GlobalAcsHostName As String" />
      <MemberSignature Language="F#" Value="member this.GlobalAcsHostName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.GlobalAcsHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="globalAcsHostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt Sie acs-Mgmt-Hostnamen für die Verbindung fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalAcsNamespace">
      <MemberSignature Language="C#" Value="public string GlobalAcsNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GlobalAcsNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.GlobalAcsNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property GlobalAcsNamespace As String" />
      <MemberSignature Language="F#" Value="member this.GlobalAcsNamespace : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.GlobalAcsNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="globalAcsNamespace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt Sie ACS-Namespacenamen - Mandanten für den Dienst fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalAcsRPRealm">
      <MemberSignature Language="C#" Value="public string GlobalAcsRPRealm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GlobalAcsRPRealm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.GlobalAcsRPRealm" />
      <MemberSignature Language="VB.NET" Value="Public Property GlobalAcsRPRealm As String" />
      <MemberSignature Language="F#" Value="member this.GlobalAcsRPRealm : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.GlobalAcsRPRealm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="globalAcsRPRealm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest globale ACS-Namespace RP-Bereich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAcsDetails.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceCertificateAndAcsDetails.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
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