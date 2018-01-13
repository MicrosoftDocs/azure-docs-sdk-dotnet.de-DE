<Type Name="CertificateAddParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter">
  <TypeSignature Language="C#" Value="public class CertificateAddParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateAddParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateAddParameter" />
  <TypeSignature Language="F#" Value="type CertificateAddParameter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Ein Zertifikat, das auf installiert werden kann, Serverknoten und können verwendet werden, um Vorgänge auf dem Computer zu authentifizieren.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateAddParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CertificateAddParameter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateAddParameter (string thumbprint, string thumbprintAlgorithm, string data, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateFormat&gt; certificateFormat = null, string password = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string thumbprint, string thumbprintAlgorithm, string data, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateFormat&gt; certificateFormat, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.#ctor(System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.CertificateFormat},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (thumbprint As String, thumbprintAlgorithm As String, data As String, Optional certificateFormat As Nullable(Of CertificateFormat) = null, Optional password As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter : string * string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateFormat&gt; * string -&gt; Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter (thumbprint, thumbprintAlgorithm, data, certificateFormat, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="data" Type="System.String" />
        <Parameter Name="certificateFormat" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateFormat&gt;" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="thumbprint">Der x. 509-Fingerabdruck des Zertifikats.
            Dies ist eine Sequenz von bis zu 40 hexadezimale Ziffern (es kann Leerzeichen enthalten, aber diese entfernt werden).</param>
        <param name="thumbprintAlgorithm">Der Algorithmus, der zum Ableiten des Fingerabdrucks verwendet wird. Diese Angabe muss sha1.</param>
        <param name="data">Die base64-codierte Inhalt des Zertifikats.
            Die maximale Größe beträgt 10KB.</param>
        <param name="certificateFormat">Das Format der Zertifikatdaten.</param>
        <param name="password">Das Kennwort für privaten Schlüssel des Zertifikats zugreifen.</param>
        <summary>
            Initialisiert eine neue Instanz der CertificateAddParameter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateFormat">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateFormat&gt; CertificateFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateFormat&gt; CertificateFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.CertificateFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateFormat As Nullable(Of CertificateFormat)" />
      <MemberSignature Language="F#" Value="member this.CertificateFormat : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateFormat&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.CertificateFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateFormat&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Format der Zertifikatdaten.
            </summary>
        <value>To be added.</value>
        <remarks>
            Folgende Werte sind möglich: "Pfx", ". Cer"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public string Data { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Data" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.Data" />
      <MemberSignature Language="VB.NET" Value="Public Property Data As String" />
      <MemberSignature Language="F#" Value="member this.Data : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="data")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den base64-codierten Inhalt des Zertifikats fest. Die maximale Größe beträgt 10KB.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Kennwort für privaten Schlüssel des Zertifikats zugreifen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies ist erforderlich, wenn das Format des Zertifikats Pfx ist. Es sollte weggelassen werden, wenn das Format des Zertifikats Cer ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den x. 509-Fingerabdruck des Zertifikats. Dies ist eine Sequenz von bis zu 40 hexadezimale Ziffern (es kann Leerzeichen enthalten, aber diese entfernt werden).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintAlgorithm">
      <MemberSignature Language="C#" Value="public string ThumbprintAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.ThumbprintAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property ThumbprintAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintAlgorithm : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.ThumbprintAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="thumbprintAlgorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Hashalgorithmus, der zum Ableiten des Fingerabdrucks verwendet. Diese Angabe muss sha1.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateAddParameter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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