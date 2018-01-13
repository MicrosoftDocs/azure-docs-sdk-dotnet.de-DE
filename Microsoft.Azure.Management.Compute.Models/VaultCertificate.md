<Type Name="VaultCertificate" FullName="Microsoft.Azure.Management.Compute.Models.VaultCertificate">
  <TypeSignature Language="C#" Value="public class VaultCertificate" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VaultCertificate extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VaultCertificate" />
  <TypeSignature Language="VB.NET" Value="Public Class VaultCertificate" />
  <TypeSignature Language="F#" Value="type VaultCertificate = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Beschreibt einen Verweis auf ein einzelnes Zertifikat in einem Schlüsseltresor und, in dem das Zertifikat muss auf dem virtuellen Computer befinden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultCertificate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VaultCertificate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VaultCertificate-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultCertificate (string certificateUrl = null, string certificateStore = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string certificateUrl, string certificateStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VaultCertificate.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional certificateUrl As String = null, Optional certificateStore As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VaultCertificate : string * string -&gt; Microsoft.Azure.Management.Compute.Models.VaultCertificate" Usage="new Microsoft.Azure.Management.Compute.Models.VaultCertificate (certificateUrl, certificateStore)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="certificateUrl" Type="System.String" />
        <Parameter Name="certificateStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="certificateUrl">Dies ist die URL eines Zertifikats, das in den Key Vault als ein geheimer Schlüssel hochgeladen wurde. Der Schlüsseltresor einen geheimer Schlüssel hinzufügen, finden Sie unter [Hinzufügen eines Schlüssels oder den geheimen Schlüssel für den schlüsseltresor](https://docs.microsoft.com/azure/key-vault/key-vault-get-started/#add).
            In diesem Fall ist die Base64-Codierung der folgenden JSON-Objekt, das Ihrem Zertifikat muss in UTF-8 codiert ist: &lt;Br&gt;&lt;Br&gt; {&lt;Br&gt; "Daten": "&lt; Base64-codierten Zertifikats&gt;",&lt;Br&gt; "DataType":"Pfx",&lt;Br&gt; "Password":"&lt;Pfx-Datei-Password&gt;"&lt;Br&gt;}</param>
        <param name="certificateStore">Für Windows-VMs gibt den Zertifikatspeicher auf dem virtuellen Computer, der das Zertifikat hinzugefügt werden soll. Der angegebene Zertifikatspeicher ist implizit im LocalMachine-Konto. &lt;Brasilien&gt;&lt;Br&gt;für virtuelle Linux-Computer befindet sich die Zertifikatdatei /var/lib/waagent im Verzeichnis, mit dem Dateinamen &lt;UppercaseThumbprint&gt;CRT für die X509 Datei und desZertifikats&lt; UppercaseThumbpring&gt;.prv für privaten Schlüssel. Beide Dateien sind PEM formatiert.</param>
        <summary>
            Initialisiert eine neue Instanz der VaultCertificate-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateStore">
      <MemberSignature Language="C#" Value="public string CertificateStore { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateStore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VaultCertificate.CertificateStore" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateStore As String" />
      <MemberSignature Language="F#" Value="member this.CertificateStore : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VaultCertificate.CertificateStore" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateStore")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, für die Windows-VMs, gibt den Zertifikatspeicher auf dem virtuellen Computer, der das Zertifikat hinzugefügt werden soll. Der angegebene Zertifikatspeicher ist implizit im LocalMachine-Konto. &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Für virtuelle Linux-Computer befindet sich die Zertifikatdatei /var/lib/waagent im Verzeichnis, mit dem Dateinamen &amp;Lt; UppercaseThumbprint&amp;Gt;. CRT für die X509 Zertifikatsdatei und &amp;Lt; UppercaseThumbpring&amp;Gt;. Prv für privaten Schlüssel. Beide Dateien sind PEM formatiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateUrl">
      <MemberSignature Language="C#" Value="public string CertificateUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VaultCertificate.CertificateUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateUrl As String" />
      <MemberSignature Language="F#" Value="member this.CertificateUrl : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VaultCertificate.CertificateUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, ist dies die URL eines Zertifikats, das in den Key Vault als ein geheimer Schlüssel hochgeladen wurde. Der Schlüsseltresor einen geheimer Schlüssel hinzufügen, finden Sie unter [Hinzufügen eines Schlüssels oder den geheimen Schlüssel für den schlüsseltresor](https://docs.microsoft.com/azure/key-vault/key-vault-get-started/#add).
            In diesem Fall ist die Base64-Codierung der folgenden JSON-Objekt, das Ihrem Zertifikat muss in UTF-8 codiert ist: &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; {&amp;Lt; Br&amp;Gt; "Daten": "&amp;Lt; Base64-codierten Zertifikats&amp;Gt; ",&amp;Lt; Br&amp;Gt; "DataType": "Pfx",&amp;Lt; Br&amp;Gt; "Password": "&amp;Lt; Pfx-Datei-Password&amp;Gt;" &amp;Lt; Br&amp;Gt;}
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>