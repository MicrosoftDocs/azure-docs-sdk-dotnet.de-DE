<Type Name="X509CertificateProperties" FullName="Microsoft.Azure.KeyVault.Models.X509CertificateProperties">
  <TypeSignature Language="C#" Value="public class X509CertificateProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit X509CertificateProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.X509CertificateProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class X509CertificateProperties" />
  <TypeSignature Language="F#" Value="type X509CertificateProperties = class" />
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
            <span data-ttu-id="33c62-101">Eigenschaften der X509 Komponente eines Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="33c62-101">Properties of the X509 component of a certificate.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public X509CertificateProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.X509CertificateProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="33c62-102">Initialisiert eine neue Instanz der X509CertificateProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="33c62-102">Initializes a new instance of the X509CertificateProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public X509CertificateProperties (string subject = null, System.Collections.Generic.IList&lt;string&gt; ekus = null, Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames subjectAlternativeNames = null, System.Collections.Generic.IList&lt;string&gt; keyUsage = null, Nullable&lt;int&gt; validityInMonths = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string subject, class System.Collections.Generic.IList`1&lt;string&gt; ekus, class Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames subjectAlternativeNames, class System.Collections.Generic.IList`1&lt;string&gt; keyUsage, valuetype System.Nullable`1&lt;int32&gt; validityInMonths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.X509CertificateProperties.#ctor(System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames,System.Collections.Generic.IList{System.String},System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.X509CertificateProperties : string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.KeyVault.Models.X509CertificateProperties" Usage="new Microsoft.Azure.KeyVault.Models.X509CertificateProperties (subject, ekus, subjectAlternativeNames, keyUsage, validityInMonths)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="subject" Type="System.String" />
        <Parameter Name="ekus" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="subjectAlternativeNames" Type="Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames" />
        <Parameter Name="keyUsage" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="validityInMonths" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="subject"><span data-ttu-id="33c62-103">Der Name des Subjekts.</span><span class="sxs-lookup"><span data-stu-id="33c62-103">The subject name.</span></span> <span data-ttu-id="33c62-104">Sollte sein, dass eine gültige X509 Namen unterschieden.</span><span class="sxs-lookup"><span data-stu-id="33c62-104">Should be a valid X509 distinguished Name.</span></span></param>
        <param name="ekus"><span data-ttu-id="33c62-105">Die erweiterte Schlüsselverwendung.</span><span class="sxs-lookup"><span data-stu-id="33c62-105">The enhanced key usage.</span></span></param>
        <param name="subjectAlternativeNames"><span data-ttu-id="33c62-106">Die alternativen Antragstellernamen.</span><span class="sxs-lookup"><span data-stu-id="33c62-106">The subject alternative names.</span></span></param>
        <param name="keyUsage"><span data-ttu-id="33c62-107">Liste der Schlüsselverwendungen.</span><span class="sxs-lookup"><span data-stu-id="33c62-107">List of key usages.</span></span></param>
        <param name="validityInMonths"><span data-ttu-id="33c62-108">Die Dauer, die die Ceritifcate in Monaten gültig ist.</span><span class="sxs-lookup"><span data-stu-id="33c62-108">The duration that the ceritifcate is valid in months.</span></span></param>
        <summary>
            <span data-ttu-id="33c62-109">Initialisiert eine neue Instanz der X509CertificateProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="33c62-109">Initializes a new instance of the X509CertificateProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ekus">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Ekus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Ekus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.X509CertificateProperties.Ekus" />
      <MemberSignature Language="VB.NET" Value="Public Property Ekus As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Ekus : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.X509CertificateProperties.Ekus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ekus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="33c62-110">Ruft ab oder legt die Verbesserte Schlüsselverwendung.</span><span class="sxs-lookup"><span data-stu-id="33c62-110">Gets or sets the enhanced key usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyUsage">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; KeyUsage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; KeyUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.X509CertificateProperties.KeyUsage" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyUsage As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.KeyUsage : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.X509CertificateProperties.KeyUsage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="key_usage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="33c62-111">Ruft ab oder legt die Liste der Schlüsselverwendungen.</span><span class="sxs-lookup"><span data-stu-id="33c62-111">Gets or sets list of key usages.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subject">
      <MemberSignature Language="C#" Value="public string Subject { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Subject" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.X509CertificateProperties.Subject" />
      <MemberSignature Language="VB.NET" Value="Public Property Subject As String" />
      <MemberSignature Language="F#" Value="member this.Subject : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.X509CertificateProperties.Subject" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subject")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="33c62-112">Ruft ab oder legt den Antragstellernamen.</span><span class="sxs-lookup"><span data-stu-id="33c62-112">Gets or sets the subject name.</span></span> <span data-ttu-id="33c62-113">Sollte sein, dass eine gültige X509 Namen unterschieden.</span><span class="sxs-lookup"><span data-stu-id="33c62-113">Should be a valid X509 distinguished Name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubjectAlternativeNames">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames SubjectAlternativeNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames SubjectAlternativeNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.X509CertificateProperties.SubjectAlternativeNames" />
      <MemberSignature Language="VB.NET" Value="Public Property SubjectAlternativeNames As SubjectAlternativeNames" />
      <MemberSignature Language="F#" Value="member this.SubjectAlternativeNames : Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames with get, set" Usage="Microsoft.Azure.KeyVault.Models.X509CertificateProperties.SubjectAlternativeNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sans")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="33c62-114">Ruft ab oder legt die alternativen Antragstellernamen.</span><span class="sxs-lookup"><span data-stu-id="33c62-114">Gets or sets the subject alternative names.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.X509CertificateProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="x509CertificateProperties.Validate " />
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
            <span data-ttu-id="33c62-115">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="33c62-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="33c62-116">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="33c62-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ValidityInMonths">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ValidityInMonths { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ValidityInMonths" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.X509CertificateProperties.ValidityInMonths" />
      <MemberSignature Language="VB.NET" Value="Public Property ValidityInMonths As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ValidityInMonths : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.X509CertificateProperties.ValidityInMonths" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="validity_months")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="33c62-117">Ruft ab oder legt die Dauer, die die Ceritifcate in Monaten gültig ist.</span><span class="sxs-lookup"><span data-stu-id="33c62-117">Gets or sets the duration that the ceritifcate is valid in months.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>