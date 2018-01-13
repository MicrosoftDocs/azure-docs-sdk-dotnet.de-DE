<Type Name="CertificateIssuerSetParameters" FullName="Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters">
  <TypeSignature Language="C#" Value="public class CertificateIssuerSetParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateIssuerSetParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateIssuerSetParameters" />
  <TypeSignature Language="F#" Value="type CertificateIssuerSetParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Der Aussteller des Zertifikats festlegen Parameter.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateIssuerSetParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CertificateIssuerSetParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateIssuerSetParameters (string provider, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.#ctor(System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters : string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes -&gt; Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters" Usage="new Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters (provider, credentials, organizationDetails, attributes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
      </Parameters>
      <Docs>
        <param name="provider">Der Aussteller-Anbieter.</param>
        <param name="credentials">Die Anmeldeinformationen für den Aussteller verwendet werden soll.</param>
        <param name="organizationDetails">Details der Organisation wie an den Aussteller angegeben.</param>
        <param name="attributes">Attribute des Ausstellers-Objekts.</param>
        <summary>
            Initialisiert eine neue Instanz der CertificateIssuerSetParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Attributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.IssuerAttributes Attributes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.IssuerAttributes Attributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.Attributes" />
      <MemberSignature Language="VB.NET" Value="Public Property Attributes As IssuerAttributes" />
      <MemberSignature Language="F#" Value="member this.Attributes : Microsoft.Azure.KeyVault.Models.IssuerAttributes with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.Attributes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="attributes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.IssuerAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Attribute des Ausstellers-Objekts.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.IssuerCredentials Credentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.IssuerCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public Property Credentials As IssuerCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.KeyVault.Models.IssuerCredentials with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="credentials")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.IssuerCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anmeldeinformationen für den Aussteller zu verwendende fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrganizationDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.OrganizationDetails OrganizationDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.OrganizationDetails OrganizationDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.OrganizationDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property OrganizationDetails As OrganizationDetails" />
      <MemberSignature Language="F#" Value="member this.OrganizationDetails : Microsoft.Azure.KeyVault.Models.OrganizationDetails with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.OrganizationDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="org_details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.OrganizationDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert die Details der Organisation wie an den Aussteller angegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen des Ausstellers-Anbieters.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateIssuerSetParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateIssuerSetParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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