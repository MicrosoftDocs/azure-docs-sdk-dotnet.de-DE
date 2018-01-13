<Type Name="CertificateOperation" FullName="Microsoft.Azure.KeyVault.Models.CertificateOperation">
  <TypeSignature Language="C#" Value="public class CertificateOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateOperation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.CertificateOperation" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateOperation" />
  <TypeSignature Language="F#" Value="type CertificateOperation = class" />
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
            Ein Zertifikat-Vorgang ist bei asynchronen Anforderungen zurückgegeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateOperation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateOperation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CertificateOperation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateOperation (string id = null, Microsoft.Azure.KeyVault.Models.IssuerParameters issuerParameters = null, byte[] csr = null, Nullable&lt;bool&gt; cancellationRequested = null, string status = null, string statusDetails = null, Microsoft.Azure.KeyVault.Models.Error error = null, string target = null, string requestId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class Microsoft.Azure.KeyVault.Models.IssuerParameters issuerParameters, unsigned int8[] csr, valuetype System.Nullable`1&lt;bool&gt; cancellationRequested, string status, string statusDetails, class Microsoft.Azure.KeyVault.Models.Error error, string target, string requestId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateOperation.#ctor(System.String,Microsoft.Azure.KeyVault.Models.IssuerParameters,System.Byte[],System.Nullable{System.Boolean},System.String,System.String,Microsoft.Azure.KeyVault.Models.Error,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.CertificateOperation : string * Microsoft.Azure.KeyVault.Models.IssuerParameters * byte[] * Nullable&lt;bool&gt; * string * string * Microsoft.Azure.KeyVault.Models.Error * string * string -&gt; Microsoft.Azure.KeyVault.Models.CertificateOperation" Usage="new Microsoft.Azure.KeyVault.Models.CertificateOperation (id, issuerParameters, csr, cancellationRequested, status, statusDetails, error, target, requestId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="issuerParameters" Type="Microsoft.Azure.KeyVault.Models.IssuerParameters" />
        <Parameter Name="csr" Type="System.Byte[]" />
        <Parameter Name="cancellationRequested" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="statusDetails" Type="System.String" />
        <Parameter Name="error" Type="Microsoft.Azure.KeyVault.Models.Error" />
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="requestId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Die Zertifikat-ID.</param>
        <param name="issuerParameters">Parameter für den Aussteller der X509 Komponente eines Zertifikats.</param>
        <param name="csr">Die zertifikatsignieranforderung (CSR), die in den Zertifikat-Vorgang verwendet wird.</param>
        <param name="cancellationRequested">Gibt an, ob für den Zertifikat-Vorgang ein Abbruch angefordert wurde.</param>
        <param name="status">Status des Zertifikats an.</param>
        <param name="statusDetails">Die Statusdetails des Zertifikat-Vorgangs.</param>
        <param name="error">Ein Fehler aufgetreten, sofern vorhanden, während des Vorgangs Zertifikat.</param>
        <param name="target">An der sich das Ergebnis des Vorgangs Zertifikat enthält.</param>
        <param name="requestId">Der Bezeichner für den Zertifikat-Vorgang.</param>
        <summary>
            Initialisiert eine neue Instanz der CertificateOperation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancellationRequested">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CancellationRequested { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CancellationRequested" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.CancellationRequested" />
      <MemberSignature Language="VB.NET" Value="Public Property CancellationRequested As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CancellationRequested : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.CancellationRequested" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cancellation_requested")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt an, ob für den Zertifikat-Vorgang ein Abbruch angefordert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateOperationIdentifier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.CertificateOperationIdentifier CertificateOperationIdentifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.CertificateOperationIdentifier CertificateOperationIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.CertificateOperationIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CertificateOperationIdentifier As CertificateOperationIdentifier" />
      <MemberSignature Language="F#" Value="member this.CertificateOperationIdentifier : Microsoft.Azure.KeyVault.CertificateOperationIdentifier" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.CertificateOperationIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.CertificateOperationIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Zertifikat-Vorgangs-ID
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Csr">
      <MemberSignature Language="C#" Value="public byte[] Csr { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Csr" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.Csr" />
      <MemberSignature Language="VB.NET" Value="Public Property Csr As Byte()" />
      <MemberSignature Language="F#" Value="member this.Csr : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.Csr" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="csr")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die zertifikatsignieranforderung (CSR), die in den Zertifikat-Vorgang verwendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.Error Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.Error Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As Error" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.KeyVault.Models.Error with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.Error</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert ein Fehler aufgetreten ist, sofern vorhanden, während des Vorgangs Zertifikat.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Zertifikat-Id ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssuerParameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.IssuerParameters IssuerParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.IssuerParameters IssuerParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.IssuerParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property IssuerParameters As IssuerParameters" />
      <MemberSignature Language="F#" Value="member this.IssuerParameters : Microsoft.Azure.KeyVault.Models.IssuerParameters with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.IssuerParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="issuer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.IssuerParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Parameter für den Aussteller der X509 Komponente eines Zertifikats.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public string RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As String" />
      <MemberSignature Language="F#" Value="member this.RequestId : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.RequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="request_id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Bezeichner für den Zertifikat-Vorgang.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen des Status des Zertifikats an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusDetails">
      <MemberSignature Language="C#" Value="public string StatusDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.StatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.StatusDetails : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.StatusDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status_details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Statusdetails des Zertifikat-Vorgangs.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="target")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Speicherort, der das Ergebnis des Vorgangs Zertifikat enthält.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>