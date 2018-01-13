<Type Name="CertificateImportParameters" FullName="Microsoft.Azure.KeyVault.Models.CertificateImportParameters">
  <TypeSignature Language="C#" Value="public class CertificateImportParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateImportParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.CertificateImportParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateImportParameters" />
  <TypeSignature Language="F#" Value="type CertificateImportParameters = class" />
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
            Die Zertifikat-Import-Parameter.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateImportParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateImportParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CertificateImportParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateImportParameters (string base64EncodedCertificate, string password = null, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string base64EncodedCertificate, string password, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateImportParameters.#ctor(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.CertificateImportParameters : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.KeyVault.Models.CertificateImportParameters" Usage="new Microsoft.Azure.KeyVault.Models.CertificateImportParameters (base64EncodedCertificate, password, certificatePolicy, certificateAttributes, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="base64EncodedCertificate" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="base64EncodedCertificate">Base64-codierte Darstellung des Objekts Zertifikat zu importieren. Dieses Zertifikat muss den privaten Schlüssel enthalten.</param>
        <param name="password">Wenn der private Schlüssel im base64EncodedCertificate verschlüsselt ist, können Sie das Kennwort für die Verschlüsselung verwendete.</param>
        <param name="certificatePolicy">Die Richtlinie für das Zertifikat.</param>
        <param name="certificateAttributes">Die Attribute des Zertifikats (optional).</param>
        <param name="tags">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</param>
        <summary>
            Initialisiert eine neue Instanz der CertificateImportParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Base64EncodedCertificate">
      <MemberSignature Language="C#" Value="public string Base64EncodedCertificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Base64EncodedCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateImportParameters.Base64EncodedCertificate" />
      <MemberSignature Language="VB.NET" Value="Public Property Base64EncodedCertificate As String" />
      <MemberSignature Language="F#" Value="member this.Base64EncodedCertificate : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateImportParameters.Base64EncodedCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest base64-codierte Darstellung des zu importierenden Objekts Zertifikat. Dieses Zertifikat muss den privaten Schlüssel enthalten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateAttributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.CertificateAttributes CertificateAttributes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.CertificateAttributes CertificateAttributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateImportParameters.CertificateAttributes" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateAttributes As CertificateAttributes" />
      <MemberSignature Language="F#" Value="member this.CertificateAttributes : Microsoft.Azure.KeyVault.Models.CertificateAttributes with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateImportParameters.CertificateAttributes" />
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
        <ReturnType>Microsoft.Azure.KeyVault.Models.CertificateAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Attribute des Zertifikats (optional).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificatePolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.CertificatePolicy CertificatePolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.CertificatePolicy CertificatePolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateImportParameters.CertificatePolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificatePolicy As CertificatePolicy" />
      <MemberSignature Language="F#" Value="member this.CertificatePolicy : Microsoft.Azure.KeyVault.Models.CertificatePolicy with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateImportParameters.CertificatePolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="policy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.CertificatePolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Verwaltungsrichtlinie für das Zertifikat.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateImportParameters.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateImportParameters.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pwd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob der private Schlüssel im base64EncodedCertificate verschlüsselt ist, verwendet das Kennwort für die Verschlüsselung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateImportParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateImportParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateImportParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateImportParameters.Validate " />
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