<Type Name="CertificateCreateOrUpdateParameters" FullName="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters">
  <TypeSignature Language="C#" Value="public class CertificateCreateOrUpdateParameters : Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateCreateOrUpdateParameters extends Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateCreateOrUpdateParameters&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type CertificateCreateOrUpdateParameters = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Batch.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a6fc3-101">Enthält Informationen über ein Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-101">Contains information about a certificate.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateCreateOrUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a6fc3-102">Initialisiert eine neue Instanz der CertificateCreateOrUpdateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-102">Initializes a new instance of the CertificateCreateOrUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateCreateOrUpdateParameters (string data, string id = null, string name = null, string type = null, string etag = null, string thumbprintAlgorithm = null, string thumbprint = null, Microsoft.Azure.Management.Batch.Models.CertificateFormat format = Microsoft.Azure.Management.Batch.Models.CertificateFormat.Pfx, string password = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string data, string id, string name, string type, string etag, string thumbprintAlgorithm, string thumbprint, valuetype Microsoft.Azure.Management.Batch.Models.CertificateFormat format, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateFormat,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (data As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional etag As String = null, Optional thumbprintAlgorithm As String = null, Optional thumbprint As String = null, Optional format As CertificateFormat = Microsoft.Azure.Management.Batch.Models.CertificateFormat.Pfx, Optional password As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters : string * string * string * string * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateFormat * string -&gt; Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" Usage="new Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters (data, id, name, type, etag, thumbprintAlgorithm, thumbprint, format, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="data" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="format" Type="Microsoft.Azure.Management.Batch.Models.CertificateFormat" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="data"><span data-ttu-id="a6fc3-103">Die base64-codierte Inhalt des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-103">The base64-encoded contents of the certificate.</span></span></param>
        <param name="id"><span data-ttu-id="a6fc3-104">Die ID der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-104">The ID of the resource.</span></span></param>
        <param name="name"><span data-ttu-id="a6fc3-105">Der Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-105">The name of the resource.</span></span></param>
        <param name="type"><span data-ttu-id="a6fc3-106">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-106">The type of the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="a6fc3-107">Das ETag der Ressource, für Parallelität-Anweisungen verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-107">The ETag of the resource, used for concurrency statements.</span></span></param>
        <param name="thumbprintAlgorithm"><span data-ttu-id="a6fc3-108">Der Algorithmus den Fingerabdruck des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="a6fc3-108">The algorithm of the certificate thumbprint</span></span></param>
        <param name="thumbprint"><span data-ttu-id="a6fc3-109">Der Fingerabdruck des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="a6fc3-109">The thumbprint of the certificate</span></span></param>
        <param name="format"><span data-ttu-id="a6fc3-110">Das Format des Zertifikat - Pfx oder Cer.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-110">The format of the certificate - either Pfx or Cer.</span></span> <span data-ttu-id="a6fc3-111">Wenn nicht angegeben, ist die Standardeinstellung Pfx.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-111">If omitted, the default is Pfx.</span></span> <span data-ttu-id="a6fc3-112">Folgende Werte sind möglich: "Pfx", ". Cer"</span><span class="sxs-lookup"><span data-stu-id="a6fc3-112">Possible values include: 'Pfx', 'Cer'</span></span></param>
        <param name="password"><span data-ttu-id="a6fc3-113">Das Kennwort für privaten Schlüssel des Zertifikats zugreifen.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-113">The password to access the certificate's private key.</span></span></param>
        <summary>
            <span data-ttu-id="a6fc3-114">Initialisiert eine neue Instanz der CertificateCreateOrUpdateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-114">Initializes a new instance of the CertificateCreateOrUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public string Data { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Data" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Data" />
      <MemberSignature Language="VB.NET" Value="Public Property Data As String" />
      <MemberSignature Language="F#" Value="member this.Data : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.data")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6fc3-115">Ruft ab oder legt den base64-codierten Inhalt des Zertifikats fest.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-115">Gets or sets the base64-encoded contents of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a6fc3-116">Die maximale Größe beträgt 10KB.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-116">The maximum size is 10KB.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.CertificateFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.CertificateFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As CertificateFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Management.Batch.Models.CertificateFormat with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6fc3-117">Ruft ab oder legt das Format des Zertifikat - Pfx oder Cer.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-117">Gets or sets the format of the certificate - either Pfx or Cer.</span></span> <span data-ttu-id="a6fc3-118">Wenn nicht angegeben, ist die Standardeinstellung Pfx.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-118">If omitted, the default is Pfx.</span></span> <span data-ttu-id="a6fc3-119">Folgende Werte sind möglich: "Pfx", ". Cer"</span><span class="sxs-lookup"><span data-stu-id="a6fc3-119">Possible values include: 'Pfx', 'Cer'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6fc3-120">Ruft ab oder legt das Kennwort für privaten Schlüssel des Zertifikats zugreifen.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-120">Gets or sets the password to access the certificate's private key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a6fc3-121">Dies ist erforderlich, wenn das Format des Zertifikats Pfx und ausgelassen werden, muss Wenn das Format des Zertifikats Cer ist.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-121">This is required if the certificate format is pfx and must be omitted if the certificate format is cer.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6fc3-122">Ruft ab oder legt den Fingerabdruck des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="a6fc3-122">Gets or sets the thumbprint of the certificate</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a6fc3-123">Dieser muss den Fingerabdruck aus dem Namen entsprechen.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-123">This must match the thumbprint from the name.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintAlgorithm">
      <MemberSignature Language="C#" Value="public string ThumbprintAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.ThumbprintAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property ThumbprintAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintAlgorithm : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.ThumbprintAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.thumbprintAlgorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6fc3-124">Ruft ab oder legt den Hashalgorithmus den Fingerabdruck des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="a6fc3-124">Gets or sets the algorithm of the certificate thumbprint</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a6fc3-125">Dies muss den ersten Teil der Name des Zertifikats übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-125">This must match the first portion of the certificate name.</span></span>
            <span data-ttu-id="a6fc3-126">Derzeit muss "SHA1" sein.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-126">Currently required to be 'SHA1'.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateCreateOrUpdateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a6fc3-127">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="a6fc3-127">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a6fc3-128">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="a6fc3-128">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>