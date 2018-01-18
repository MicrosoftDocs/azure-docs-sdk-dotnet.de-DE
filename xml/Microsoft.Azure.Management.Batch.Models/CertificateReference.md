<Type Name="CertificateReference" FullName="Microsoft.Azure.Management.Batch.Models.CertificateReference">
  <TypeSignature Language="C#" Value="public class CertificateReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.CertificateReference" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateReference" />
  <TypeSignature Language="F#" Value="type CertificateReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="359de-101">Ein Verweis auf ein Zertifikat auf Serverknoten in einem Pool installiert werden.</span><span class="sxs-lookup"><span data-stu-id="359de-101">A reference to a certificate to be installed on compute nodes in a pool.</span></span> <span data-ttu-id="359de-102">Dies muss in demselben Konto als dem Pool vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="359de-102">This must exist inside the same account as the pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="359de-103">Initialisiert eine neue Instanz der CertificateReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="359de-103">Initializes a new instance of the CertificateReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateReference (string id, Nullable&lt;Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation&gt; storeLocation = null, string storeName = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateVisibility&gt; visibility = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation&gt; storeLocation, string storeName, class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.CertificateVisibility&gt; visibility) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateReference.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.CertificateVisibility})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, Optional storeLocation As Nullable(Of CertificateStoreLocation) = null, Optional storeName As String = null, Optional visibility As IList(Of CertificateVisibility) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.CertificateReference : string * Nullable&lt;Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateVisibility&gt; -&gt; Microsoft.Azure.Management.Batch.Models.CertificateReference" Usage="new Microsoft.Azure.Management.Batch.Models.CertificateReference (id, storeLocation, storeName, visibility)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="storeLocation" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation&gt;" />
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="visibility" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateVisibility&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="359de-104">Die vollqualifizierte ID des Zertifikats für den Pool zu installieren.</span><span class="sxs-lookup"><span data-stu-id="359de-104">The fully qualified ID of the certificate to install on the pool.</span></span> <span data-ttu-id="359de-105">Diese Angabe muss innerhalb der gleichen Batch-Konto mit dem Pool.</span><span class="sxs-lookup"><span data-stu-id="359de-105">This must be inside the same batch account as the pool.</span></span></param>
        <param name="storeLocation"><span data-ttu-id="359de-106">Der Speicherort des Zertifikatspeichers auf den Computeknoten in die das Zertifikat zu installieren.</span><span class="sxs-lookup"><span data-stu-id="359de-106">The location of the certificate store on the compute node into which to install the certificate.</span></span></param>
        <param name="storeName"><span data-ttu-id="359de-107">Der Name des Zertifikatspeichers auf den Computeknoten in die das Zertifikat zu installieren.</span><span class="sxs-lookup"><span data-stu-id="359de-107">The name of the certificate store on the compute node into which to install the certificate.</span></span></param>
        <param name="visibility"><span data-ttu-id="359de-108">Welche Benutzerkonten auf dem Computeknoten sollte Zugriff auf die privaten Daten des Zertifikats haben.</span><span class="sxs-lookup"><span data-stu-id="359de-108">Which user accounts on the compute node should have access to the private data of the certificate.</span></span></param>
        <summary>
            <span data-ttu-id="359de-109">Initialisiert eine neue Instanz der CertificateReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="359de-109">Initializes a new instance of the CertificateReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateReference.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateReference.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="359de-110">Ruft ab oder legt die vollständig qualifizierte ID des Zertifikats für den Pool zu installieren.</span><span class="sxs-lookup"><span data-stu-id="359de-110">Gets or sets the fully qualified ID of the certificate to install on the pool.</span></span> <span data-ttu-id="359de-111">Diese Angabe muss innerhalb der gleichen Batch-Konto mit dem Pool.</span><span class="sxs-lookup"><span data-stu-id="359de-111">This must be inside the same batch account as the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreLocation">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation&gt; StoreLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation&gt; StoreLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateReference.StoreLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreLocation As Nullable(Of CertificateStoreLocation)" />
      <MemberSignature Language="F#" Value="member this.StoreLocation : Nullable&lt;Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateReference.StoreLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storeLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="359de-112">Ruft ab oder legt den Speicherort des Zertifikatspeichers auf den Computeknoten in die das Zertifikat zu installieren.</span><span class="sxs-lookup"><span data-stu-id="359de-112">Gets or sets the location of the certificate store on the compute node into which to install the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="359de-113">Der Standardwert ist CurrentUser.</span><span class="sxs-lookup"><span data-stu-id="359de-113">The default value is currentUser.</span></span> <span data-ttu-id="359de-114">Diese Eigenschaft gilt nur für Anwendungspools, die mit Windows-Knoten (d. h. mit CloudServiceConfiguration erstellt oder mit VirtualMachineConfiguration mithilfe einer Windows-image Verweis) konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="359de-114">This property is applicable only for pools configured with Windows nodes (that is, created with cloudServiceConfiguration, or with virtualMachineConfiguration using a Windows image reference).</span></span> <span data-ttu-id="359de-115">Für Linux-Serverknoten werden die Zertifikate gespeichert, in einem Verzeichnis in das Arbeitsverzeichnis für die Aufgabe und eine Umgebung aus, die Variable AZ_BATCH_CERTIFICATES_DIR für den Task zum Abfragen von diesem Speicherort angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="359de-115">For Linux compute nodes, the certificates are stored in a directory inside the task working directory and an environment variable AZ_BATCH_CERTIFICATES_DIR is supplied to the task to query for this location.</span></span> <span data-ttu-id="359de-116">Für Zertifikate mit der Sichtbarkeit der "RemoteUser" ein "Zertifikate"-Verzeichnis im Basisverzeichnis des Benutzers erstellt wird (z. B. /home/ {Benutzername} / Zertifikaten) und Zertifikate in diesem Verzeichnis abgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="359de-116">For certificates with visibility of 'remoteUser', a 'certs' directory is created in the user's home directory (e.g., /home/{user-name}/certs) and certificates are placed in that directory.</span></span> <span data-ttu-id="359de-117">Folgende Werte sind möglich: "CurrentUser", "LocalMachine"</span><span class="sxs-lookup"><span data-stu-id="359de-117">Possible values include: 'CurrentUser', 'LocalMachine'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreName">
      <MemberSignature Language="C#" Value="public string StoreName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoreName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateReference.StoreName" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreName As String" />
      <MemberSignature Language="F#" Value="member this.StoreName : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateReference.StoreName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="359de-118">Ruft ab oder legt den Namen des Zertifikatspeichers auf den Computeknoten in die das Zertifikat zu installieren.</span><span class="sxs-lookup"><span data-stu-id="359de-118">Gets or sets the name of the certificate store on the compute node into which to install the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="359de-119">Diese Eigenschaft gilt nur für Anwendungspools, die mit Windows-Knoten (d. h. mit CloudServiceConfiguration erstellt oder mit VirtualMachineConfiguration mithilfe einer Windows-image Verweis) konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="359de-119">This property is applicable only for pools configured with Windows nodes (that is, created with cloudServiceConfiguration, or with virtualMachineConfiguration using a Windows image reference).</span></span>
            <span data-ttu-id="359de-120">Allgemeine Namen von Läden enthalten: My, Stamm-CA, Vertrauenswürdigkeit, nicht erlaubt, TrustedPeople, TrustedPublisher, AuthRoot, AddressBook, aber ein beliebiger benutzerdefinierter Speichername kann auch verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="359de-120">Common store names include: My, Root, CA, Trust, Disallowed, TrustedPeople, TrustedPublisher, AuthRoot, AddressBook, but any custom store name can also be used.</span></span> <span data-ttu-id="359de-121">Der Standardwert ist My.</span><span class="sxs-lookup"><span data-stu-id="359de-121">The default value is My.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateReference.Validate " />
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
            <span data-ttu-id="359de-122">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="359de-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="359de-123">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="359de-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Visibility">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateVisibility&gt; Visibility { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.CertificateVisibility&gt; Visibility" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateReference.Visibility" />
      <MemberSignature Language="VB.NET" Value="Public Property Visibility As IList(Of CertificateVisibility)" />
      <MemberSignature Language="F#" Value="member this.Visibility : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateVisibility&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateReference.Visibility" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="visibility")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateVisibility&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="359de-124">Ruft ab oder legt sie fest, welche Benutzerkonten auf dem Computeknoten Zugriff auf die privaten Daten des Zertifikats erhalten soll.</span><span class="sxs-lookup"><span data-stu-id="359de-124">Gets or sets which user accounts on the compute node should have access to the private data of the certificate.</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>
             <span data-ttu-id="359de-125">Gültige Werte:</span><span class="sxs-lookup"><span data-stu-id="359de-125">Values are:</span></span>
            
             <span data-ttu-id="359de-126">Starttask - das Benutzerkonto, unter denen die Startaufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="359de-126">starttask - The user account under which the start task is run.</span></span>
             <span data-ttu-id="359de-127">Aufgabe – die Konten, unter welcher Auftrag Aufgaben ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="359de-127">task - The accounts under which job tasks are run.</span></span>
             <span data-ttu-id="359de-128">RemoteUser - die Konten, unter denen Benutzer den Knoten Remotezugriff auf.</span><span class="sxs-lookup"><span data-stu-id="359de-128">remoteuser - The accounts under which users remotely access the node.</span></span>
             
            <span data-ttu-id="359de-129">Sie können mehrere Sichtbarkeit in diese Sammlung angeben.</span><span class="sxs-lookup"><span data-stu-id="359de-129">You can specify more than one visibility in this collection.</span></span> <span data-ttu-id="359de-130">Der Standardwert ist alle Konten.</span><span class="sxs-lookup"><span data-stu-id="359de-130">The default is all accounts.</span></span>
             </remarks>
      </Docs>
    </Member>
  </Members>
</Type>