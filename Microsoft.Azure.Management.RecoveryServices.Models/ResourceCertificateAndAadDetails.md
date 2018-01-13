<Type Name="ResourceCertificateAndAadDetails" FullName="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails">
  <TypeSignature Language="C#" Value="public class ResourceCertificateAndAadDetails : Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceCertificateAndAadDetails extends Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceCertificateAndAadDetails&#xA;Inherits ResourceCertificateDetails" />
  <TypeSignature Language="F#" Value="type ResourceCertificateAndAadDetails = class&#xA;    inherit ResourceCertificateDetails" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("AzureActiveDirectory")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Details des Zertifikats, das die tresoranmeldeinformationen für AAD darstellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceCertificateAndAadDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ResourceCertificateAndAadDetails-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceCertificateAndAadDetails (string aadAuthority, string aadTenantId, string servicePrincipalClientId, string servicePrincipalObjectId, string azureManagementEndpointAudience, byte[] certificate = null, string friendlyName = null, string issuer = null, Nullable&lt;long&gt; resourceId = null, string subject = null, string thumbprint = null, Nullable&lt;DateTime&gt; validFrom = null, Nullable&lt;DateTime&gt; validTo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string aadAuthority, string aadTenantId, string servicePrincipalClientId, string servicePrincipalObjectId, string azureManagementEndpointAudience, unsigned int8[] certificate, string friendlyName, string issuer, valuetype System.Nullable`1&lt;int64&gt; resourceId, string subject, string thumbprint, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; validFrom, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; validTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.#ctor(System.String,System.String,System.String,System.String,System.String,System.Byte[],System.String,System.String,System.Nullable{System.Int64},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (aadAuthority As String, aadTenantId As String, servicePrincipalClientId As String, servicePrincipalObjectId As String, azureManagementEndpointAudience As String, Optional certificate As Byte() = null, Optional friendlyName As String = null, Optional issuer As String = null, Optional resourceId As Nullable(Of Long) = null, Optional subject As String = null, Optional thumbprint As String = null, Optional validFrom As Nullable(Of DateTime) = null, Optional validTo As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails : string * string * string * string * string * byte[] * string * string * Nullable&lt;int64&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails (aadAuthority, aadTenantId, servicePrincipalClientId, servicePrincipalObjectId, azureManagementEndpointAudience, certificate, friendlyName, issuer, resourceId, subject, thumbprint, validFrom, validTo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="aadAuthority" Type="System.String" />
        <Parameter Name="aadTenantId" Type="System.String" />
        <Parameter Name="servicePrincipalClientId" Type="System.String" />
        <Parameter Name="servicePrincipalObjectId" Type="System.String" />
        <Parameter Name="azureManagementEndpointAudience" Type="System.String" />
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
        <param name="aadAuthority">Autorität für AAD-Mandanten.</param>
        <param name="aadTenantId">AAD-Mandanten-Id.</param>
        <param name="servicePrincipalClientId">Principal ClientId des AAD-Dienst.</param>
        <param name="servicePrincipalObjectId">AAD service principal ObjectId.</param>
        <param name="azureManagementEndpointAudience">Zielgruppe für Azure Management-Endpunkt.</param>
        <param name="certificate">Die base64-codierte Zertifikat Rohdaten Zeichenfolge.</param>
        <param name="friendlyName">Friendlyname-Zertifikat.</param>
        <param name="issuer">Aussteller des Zertifikats.</param>
        <param name="resourceId">Ressourcen-ID des Tresors.</param>
        <param name="subject">Zertifikatsantragsteller.</param>
        <param name="thumbprint">Fingerabdruck des Zertifikats.</param>
        <param name="validFrom">Startzeit der Gültigkeit des Zertifikats.</param>
        <param name="validTo">Enddatum für die Gültigkeit des Zertifikatzeit.</param>
        <summary>
            Initialisiert eine neue Instanz der ResourceCertificateAndAadDetails-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AadAuthority">
      <MemberSignature Language="C#" Value="public string AadAuthority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AadAuthority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.AadAuthority" />
      <MemberSignature Language="VB.NET" Value="Public Property AadAuthority As String" />
      <MemberSignature Language="F#" Value="member this.AadAuthority : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.AadAuthority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aadAuthority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Autorität für die AAD-Mandanten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AadTenantId">
      <MemberSignature Language="C#" Value="public string AadTenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AadTenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.AadTenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property AadTenantId As String" />
      <MemberSignature Language="F#" Value="member this.AadTenantId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.AadTenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aadTenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest AAD-Mandanten-Id.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureManagementEndpointAudience">
      <MemberSignature Language="C#" Value="public string AzureManagementEndpointAudience { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzureManagementEndpointAudience" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.AzureManagementEndpointAudience" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureManagementEndpointAudience As String" />
      <MemberSignature Language="F#" Value="member this.AzureManagementEndpointAudience : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.AzureManagementEndpointAudience" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureManagementEndpointAudience")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Azure Management Endpunkt Zielgruppe.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalClientId">
      <MemberSignature Language="C#" Value="public string ServicePrincipalClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePrincipalClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.ServicePrincipalClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalClientId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalClientId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.ServicePrincipalClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="servicePrincipalClientId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest AAD Service principal ClientId.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalObjectId">
      <MemberSignature Language="C#" Value="public string ServicePrincipalObjectId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePrincipalObjectId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.ServicePrincipalObjectId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalObjectId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalObjectId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.ServicePrincipalObjectId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="servicePrincipalObjectId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt AAD service principal ObjectId auf.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateAndAadDetails.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceCertificateAndAadDetails.Validate " />
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