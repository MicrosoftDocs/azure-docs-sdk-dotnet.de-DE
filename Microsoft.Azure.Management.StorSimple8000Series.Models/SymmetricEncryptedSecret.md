<Type Name="SymmetricEncryptedSecret" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret">
  <TypeSignature Language="C#" Value="public class SymmetricEncryptedSecret" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SymmetricEncryptedSecret extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret" />
  <TypeSignature Language="VB.NET" Value="Public Class SymmetricEncryptedSecret" />
  <TypeSignature Language="F#" Value="type SymmetricEncryptedSecret = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt die geheimen Schlüssel, der mit symmetrischen Schlüssel verschlüsselt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SymmetricEncryptedSecret ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SymmetricEncryptedSecret-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SymmetricEncryptedSecret (string value, Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm encryptionAlgorithm, string valueCertificateThumbprint = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string value, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm encryptionAlgorithm, string valueCertificateThumbprint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.#ctor(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret : string * Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret (value, encryptionAlgorithm, valueCertificateThumbprint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="encryptionAlgorithm" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm" />
        <Parameter Name="valueCertificateThumbprint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value">Der Wert des geheimen Schlüssels selbst. Wenn der geheime Schlüssel in nur-Text enthalten oder Null ist, und klicken Sie dann "EncryptionAlgorithm" keine kann.</param>
        <param name="encryptionAlgorithm">Der Algorithmus zum Verschlüsseln der "Value". Folgende Werte sind möglich: "None", "AES256", "RSAES_PKCS1_v_1_5"</param>
        <param name="valueCertificateThumbprint">Der Fingerabdruck des Zertifikats, das zum Verschlüsseln der "Value" verwendet wurde.</param>
        <summary>
            Initialisiert eine neue Instanz der SymmetricEncryptedSecret-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionAlgorithm">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm EncryptionAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm EncryptionAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.EncryptionAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionAlgorithm As EncryptionAlgorithm" />
      <MemberSignature Language="F#" Value="member this.EncryptionAlgorithm : Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.EncryptionAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encryptionAlgorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt der Algorithmus zum Verschlüsseln der "Value" fest. Folgende Werte sind möglich: "None", "AES256", "RSAES_PKCS1_v_1_5"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="symmetricEncryptedSecret.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
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
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt den Wert des geheimen Schlüssels selbst fest. Wenn der geheime Schlüssel in nur-Text enthalten oder Null ist, und klicken Sie dann "EncryptionAlgorithm" keine kann.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValueCertificateThumbprint">
      <MemberSignature Language="C#" Value="public string ValueCertificateThumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ValueCertificateThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.ValueCertificateThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property ValueCertificateThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.ValueCertificateThumbprint : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret.ValueCertificateThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="valueCertificateThumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Fingerabdruck des Zertifikats, das zum Verschlüsseln der "Value" verwendet wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>