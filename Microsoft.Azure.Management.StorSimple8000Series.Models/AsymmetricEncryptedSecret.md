<Type Name="AsymmetricEncryptedSecret" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret">
  <TypeSignature Language="C#" Value="public class AsymmetricEncryptedSecret" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AsymmetricEncryptedSecret extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" />
  <TypeSignature Language="VB.NET" Value="Public Class AsymmetricEncryptedSecret" />
  <TypeSignature Language="F#" Value="type AsymmetricEncryptedSecret = class" />
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
            <span data-ttu-id="d9741-101">Stellen Sie die geheimen Schlüssel für die Verschlüsselung mit asymmetrischen Schlüsselpaares vorgesehen.</span><span class="sxs-lookup"><span data-stu-id="d9741-101">Represent the secrets intended for encryption with asymmetric key pair.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AsymmetricEncryptedSecret ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d9741-102">Initialisiert eine neue Instanz der AsymmetricEncryptedSecret-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d9741-102">Initializes a new instance of the AsymmetricEncryptedSecret class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AsymmetricEncryptedSecret (string value, Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm encryptionAlgorithm, string encryptionCertThumbprint = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string value, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm encryptionAlgorithm, string encryptionCertThumbprint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.#ctor(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret : string * Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret (value, encryptionAlgorithm, encryptionCertThumbprint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="encryptionAlgorithm" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm" />
        <Parameter Name="encryptionCertThumbprint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="d9741-103">Der Wert des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="d9741-103">The value of the secret.</span></span></param>
        <param name="encryptionAlgorithm"><span data-ttu-id="d9741-104">Der Algorithmus zum Verschlüsseln von "Value".</span><span class="sxs-lookup"><span data-stu-id="d9741-104">The algorithm used to encrypt "Value".</span></span> <span data-ttu-id="d9741-105">Folgende Werte sind möglich: "None", "AES256", "RSAES_PKCS1_v_1_5"</span><span class="sxs-lookup"><span data-stu-id="d9741-105">Possible values include: 'None', 'AES256', 'RSAES_PKCS1_v_1_5'</span></span></param>
        <param name="encryptionCertThumbprint"><span data-ttu-id="d9741-106">Fingerabdruck-Zertifikat, das zum Verschlüsseln der "Value" verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="d9741-106">Thumbprint certificate that was used to encrypt "Value".</span></span> <span data-ttu-id="d9741-107">Wenn der Wert in unverschlüsselt, wird null sein.</span><span class="sxs-lookup"><span data-stu-id="d9741-107">If the value in unencrypted, it will be null.</span></span></param>
        <summary>
            <span data-ttu-id="d9741-108">Initialisiert eine neue Instanz der AsymmetricEncryptedSecret-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d9741-108">Initializes a new instance of the AsymmetricEncryptedSecret class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionAlgorithm">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm EncryptionAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm EncryptionAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.EncryptionAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionAlgorithm As EncryptionAlgorithm" />
      <MemberSignature Language="F#" Value="member this.EncryptionAlgorithm : Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionAlgorithm with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.EncryptionAlgorithm" />
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
            <span data-ttu-id="d9741-109">Ruft ab oder legt der Algorithmus zum Verschlüsseln von "Value" fest.</span><span class="sxs-lookup"><span data-stu-id="d9741-109">Gets or sets the algorithm used to encrypt "Value".</span></span> <span data-ttu-id="d9741-110">Folgende Werte sind möglich: "None", "AES256", "RSAES_PKCS1_v_1_5"</span><span class="sxs-lookup"><span data-stu-id="d9741-110">Possible values include: 'None', 'AES256', 'RSAES_PKCS1_v_1_5'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionCertThumbprint">
      <MemberSignature Language="C#" Value="public string EncryptionCertThumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptionCertThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.EncryptionCertThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionCertThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.EncryptionCertThumbprint : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.EncryptionCertThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encryptionCertThumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d9741-111">Ruft ab, oder legt ihn fest Fingerabdruck-Zertifikat, das zum Verschlüsseln der "Value" verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="d9741-111">Gets or sets thumbprint certificate that was used to encrypt "Value".</span></span> <span data-ttu-id="d9741-112">Wenn der Wert in unverschlüsselt, wird null sein.</span><span class="sxs-lookup"><span data-stu-id="d9741-112">If the value in unencrypted, it will be null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="asymmetricEncryptedSecret.Validate " />
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
            <span data-ttu-id="d9741-113">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="d9741-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d9741-114">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="d9741-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret.Value" />
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
            <span data-ttu-id="d9741-115">Ruft ab oder legt den Wert des geheimen Schlüssels fest.</span><span class="sxs-lookup"><span data-stu-id="d9741-115">Gets or sets the value of the secret.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>