<Type Name="CertificateReference" FullName="Microsoft.Azure.Batch.Protocol.Models.CertificateReference">
  <TypeSignature Language="C#" Value="public class CertificateReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.CertificateReference" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateReference" />
  <TypeSignature Language="F#" Value="type CertificateReference = class" />
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
            <span data-ttu-id="f6289-101">Ein Verweis auf ein Zertifikat auf Serverknoten in einem Pool installiert werden.</span><span class="sxs-lookup"><span data-stu-id="f6289-101">A reference to a certificate to be installed on compute nodes in a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CertificateReference.#ctor" />
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
            <span data-ttu-id="f6289-102">Initialisiert eine neue Instanz der CertificateReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f6289-102">Initializes a new instance of the CertificateReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateReference (string thumbprint, string thumbprintAlgorithm, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation&gt; storeLocation = null, string storeName = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility&gt; visibility = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string thumbprint, string thumbprintAlgorithm, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation&gt; storeLocation, string storeName, class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility&gt; visibility) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CertificateReference.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation},System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (thumbprint As String, thumbprintAlgorithm As String, Optional storeLocation As Nullable(Of CertificateStoreLocation) = null, Optional storeName As String = null, Optional visibility As IList(Of CertificateVisibility) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.CertificateReference : string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.CertificateReference" Usage="new Microsoft.Azure.Batch.Protocol.Models.CertificateReference (thumbprint, thumbprintAlgorithm, storeLocation, storeName, visibility)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="storeLocation" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation&gt;" />
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="visibility" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility&gt;" />
      </Parameters>
      <Docs>
        <param name="thumbprint"><span data-ttu-id="f6289-103">Der Fingerabdruck des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="f6289-103">The thumbprint of the certificate.</span></span></param>
        <param name="thumbprintAlgorithm"><span data-ttu-id="f6289-104">Der Algorithmus, den der Fingerabdruck zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="f6289-104">The algorithm with which the thumbprint is associated.</span></span> <span data-ttu-id="f6289-105">Diese Angabe muss sha1.</span><span class="sxs-lookup"><span data-stu-id="f6289-105">This must be sha1.</span></span></param>
        <param name="storeLocation"><span data-ttu-id="f6289-106">Der Speicherort des Zertifikatspeichers auf den Computeknoten in die das Zertifikat zu installieren.</span><span class="sxs-lookup"><span data-stu-id="f6289-106">The location of the certificate store on the compute node into which to install the certificate.</span></span></param>
        <param name="storeName"><span data-ttu-id="f6289-107">Der Name des Zertifikatspeichers auf den Computeknoten in die das Zertifikat zu installieren.</span><span class="sxs-lookup"><span data-stu-id="f6289-107">The name of the certificate store on the compute node into which to install the certificate.</span></span></param>
        <param name="visibility"><span data-ttu-id="f6289-108">Welche Benutzerkonten auf dem Computeknoten sollte Zugriff auf die privaten Daten des Zertifikats haben.</span><span class="sxs-lookup"><span data-stu-id="f6289-108">Which user accounts on the compute node should have access to the private data of the certificate.</span></span></param>
        <summary>
            <span data-ttu-id="f6289-109">Initialisiert eine neue Instanz der CertificateReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f6289-109">Initializes a new instance of the CertificateReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreLocation">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation&gt; StoreLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation&gt; StoreLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateReference.StoreLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreLocation As Nullable(Of CertificateStoreLocation)" />
      <MemberSignature Language="F#" Value="member this.StoreLocation : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateReference.StoreLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storeLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6289-110">Ruft ab oder legt den Speicherort des Zertifikatspeichers auf den Computeknoten in die das Zertifikat zu installieren.</span><span class="sxs-lookup"><span data-stu-id="f6289-110">Gets or sets the location of the certificate store on the compute node into which to install the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f6289-111">Der Standardwert ist Currentuser.</span><span class="sxs-lookup"><span data-stu-id="f6289-111">The default value is currentuser.</span></span> <span data-ttu-id="f6289-112">Diese Eigenschaft gilt nur für Anwendungspools, die mit Windows-Knoten (d. h. mit CloudServiceConfiguration erstellt oder mit VirtualMachineConfiguration mithilfe einer Windows-image Verweis) konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="f6289-112">This property is applicable only for pools configured with Windows nodes (that is, created with cloudServiceConfiguration, or with virtualMachineConfiguration using a Windows image reference).</span></span> <span data-ttu-id="f6289-113">Für Linux-Serverknoten werden die Zertifikate gespeichert, in einem Verzeichnis in das Arbeitsverzeichnis für die Aufgabe und eine Umgebung aus, die Variable AZ_BATCH_CERTIFICATES_DIR für den Task zum Abfragen von diesem Speicherort angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="f6289-113">For Linux compute nodes, the certificates are stored in a directory inside the task working directory and an environment variable AZ_BATCH_CERTIFICATES_DIR is supplied to the task to query for this location.</span></span> <span data-ttu-id="f6289-114">Für Zertifikate mit der Sichtbarkeit der "RemoteUser" ein "Zertifikate"-Verzeichnis im Basisverzeichnis des Benutzers erstellt wird (z. B. /home/ {Benutzername} / Zertifikaten) und Zertifikate in diesem Verzeichnis abgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="f6289-114">For certificates with visibility of 'remoteUser', a 'certs' directory is created in the user's home directory (e.g., /home/{user-name}/certs) and certificates are placed in that directory.</span></span> <span data-ttu-id="f6289-115">Folgende Werte sind möglich: "CurrentUser", "LocalMachine"</span><span class="sxs-lookup"><span data-stu-id="f6289-115">Possible values include: 'currentUser', 'localMachine'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreName">
      <MemberSignature Language="C#" Value="public string StoreName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoreName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateReference.StoreName" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreName As String" />
      <MemberSignature Language="F#" Value="member this.StoreName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateReference.StoreName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storeName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6289-116">Ruft ab oder legt den Namen des Zertifikatspeichers auf den Computeknoten in die das Zertifikat zu installieren.</span><span class="sxs-lookup"><span data-stu-id="f6289-116">Gets or sets the name of the certificate store on the compute node into which to install the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f6289-117">Diese Eigenschaft gilt nur für Anwendungspools, die mit Windows-Knoten (d. h. mit CloudServiceConfiguration erstellt oder mit VirtualMachineConfiguration mithilfe einer Windows-image Verweis) konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="f6289-117">This property is applicable only for pools configured with Windows nodes (that is, created with cloudServiceConfiguration, or with virtualMachineConfiguration using a Windows image reference).</span></span>
            <span data-ttu-id="f6289-118">Allgemeine Namen von Läden enthalten: My, Stamm-CA, Vertrauenswürdigkeit, nicht erlaubt, TrustedPeople, TrustedPublisher, AuthRoot, AddressBook, aber ein beliebiger benutzerdefinierter Speichername kann auch verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="f6289-118">Common store names include: My, Root, CA, Trust, Disallowed, TrustedPeople, TrustedPublisher, AuthRoot, AddressBook, but any custom store name can also be used.</span></span> <span data-ttu-id="f6289-119">Der Standardwert ist My.</span><span class="sxs-lookup"><span data-stu-id="f6289-119">The default value is My.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateReference.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateReference.Thumbprint" />
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
            <span data-ttu-id="f6289-120">Ruft ab oder legt den Fingerabdruck des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="f6289-120">Gets or sets the thumbprint of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintAlgorithm">
      <MemberSignature Language="C#" Value="public string ThumbprintAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateReference.ThumbprintAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property ThumbprintAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintAlgorithm : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateReference.ThumbprintAlgorithm" />
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
            <span data-ttu-id="f6289-121">Ruft ab oder legt den Hashalgorithmus, den der Fingerabdruck zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="f6289-121">Gets or sets the algorithm with which the thumbprint is associated.</span></span>
            <span data-ttu-id="f6289-122">Diese Angabe muss sha1.</span><span class="sxs-lookup"><span data-stu-id="f6289-122">This must be sha1.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CertificateReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateReference.Validate " />
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
            <span data-ttu-id="f6289-123">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="f6289-123">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f6289-124">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="f6289-124">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Visibility">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility&gt; Visibility { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility&gt; Visibility" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateReference.Visibility" />
      <MemberSignature Language="VB.NET" Value="Public Property Visibility As IList(Of CertificateVisibility)" />
      <MemberSignature Language="F#" Value="member this.Visibility : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateReference.Visibility" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="visibility")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6289-125">Ruft ab oder legt sie fest, welche Benutzerkonten auf dem Computeknoten Zugriff auf die privaten Daten des Zertifikats erhalten soll.</span><span class="sxs-lookup"><span data-stu-id="f6289-125">Gets or sets which user accounts on the compute node should have access to the private data of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f6289-126">Sie können mehrere Sichtbarkeit in diese Sammlung angeben.</span><span class="sxs-lookup"><span data-stu-id="f6289-126">You can specify more than one visibility in this collection.</span></span> <span data-ttu-id="f6289-127">Der Standardwert ist alle Konten.</span><span class="sxs-lookup"><span data-stu-id="f6289-127">The default is all accounts.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>