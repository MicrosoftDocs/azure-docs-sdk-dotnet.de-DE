<Type Name="Certificate" FullName="Microsoft.Azure.Management.Batch.Models.Certificate">
  <TypeSignature Language="C#" Value="public class Certificate : Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Certificate extends Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.Certificate" />
  <TypeSignature Language="VB.NET" Value="Public Class Certificate&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type Certificate = class&#xA;    inherit ProxyResource" />
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
            <span data-ttu-id="bfbe4-101">Enthält Informationen über ein Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-101">Contains information about a certificate.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Certificate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Certificate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bfbe4-102">Initialisiert eine neue Instanz der Zertifikat-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-102">Initializes a new instance of the Certificate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Certificate (string id = null, string name = null, string type = null, string etag = null, string thumbprintAlgorithm = null, string thumbprint = null, Microsoft.Azure.Management.Batch.Models.CertificateFormat format = Microsoft.Azure.Management.Batch.Models.CertificateFormat.Pfx, Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState provisioningState = Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState.Succeeded, Nullable&lt;DateTime&gt; provisioningStateTransitionTime = null, Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState previousProvisioningState = Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState.Succeeded, Nullable&lt;DateTime&gt; previousProvisioningStateTransitionTime = null, string publicData = null, Microsoft.Azure.Management.Batch.Models.DeleteCertificateError deleteCertificateError = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string etag, string thumbprintAlgorithm, string thumbprint, valuetype Microsoft.Azure.Management.Batch.Models.CertificateFormat format, valuetype Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; provisioningStateTransitionTime, valuetype Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState previousProvisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; previousProvisioningStateTransitionTime, string publicData, class Microsoft.Azure.Management.Batch.Models.DeleteCertificateError deleteCertificateError) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Certificate.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateFormat,Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState,System.Nullable{System.DateTime},Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState,System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.Batch.Models.DeleteCertificateError)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.Certificate : string * string * string * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateFormat * Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.Batch.Models.DeleteCertificateError -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="new Microsoft.Azure.Management.Batch.Models.Certificate (id, name, type, etag, thumbprintAlgorithm, thumbprint, format, provisioningState, provisioningStateTransitionTime, previousProvisioningState, previousProvisioningStateTransitionTime, publicData, deleteCertificateError)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="format" Type="Microsoft.Azure.Management.Batch.Models.CertificateFormat" />
        <Parameter Name="provisioningState" Type="Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState" />
        <Parameter Name="provisioningStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="previousProvisioningState" Type="Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState" />
        <Parameter Name="previousProvisioningStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="publicData" Type="System.String" />
        <Parameter Name="deleteCertificateError" Type="Microsoft.Azure.Management.Batch.Models.DeleteCertificateError" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="bfbe4-103">Die ID der Ressource.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-103">The ID of the resource.</span></span></param>
        <param name="name"><span data-ttu-id="bfbe4-104">Der Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-104">The name of the resource.</span></span></param>
        <param name="type"><span data-ttu-id="bfbe4-105">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-105">The type of the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="bfbe4-106">Das ETag der Ressource, für Parallelität-Anweisungen verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-106">The ETag of the resource, used for concurrency statements.</span></span></param>
        <param name="thumbprintAlgorithm"><span data-ttu-id="bfbe4-107">Der Algorithmus den Fingerabdruck des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="bfbe4-107">The algorithm of the certificate thumbprint</span></span></param>
        <param name="thumbprint"><span data-ttu-id="bfbe4-108">Der Fingerabdruck des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="bfbe4-108">The thumbprint of the certificate</span></span></param>
        <param name="format"><span data-ttu-id="bfbe4-109">Das Format des Zertifikat - Pfx oder Cer.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-109">The format of the certificate - either Pfx or Cer.</span></span> <span data-ttu-id="bfbe4-110">Wenn nicht angegeben, ist die Standardeinstellung Pfx.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-110">If omitted, the default is Pfx.</span></span> <span data-ttu-id="bfbe4-111">Folgende Werte sind möglich: "Pfx", ". Cer"</span><span class="sxs-lookup"><span data-stu-id="bfbe4-111">Possible values include: 'Pfx', 'Cer'</span></span></param>
        <param name="provisioningState"><span data-ttu-id="bfbe4-112">Der Bereitstellungsstatus der Ressource</span><span class="sxs-lookup"><span data-stu-id="bfbe4-112">The provisioned state of the resource</span></span></param>
        <param name="provisioningStateTransitionTime"><span data-ttu-id="bfbe4-113">Der Zeitpunkt, an dem das Zertifikat in seinem aktuellen Zustand übergegangen.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-113">The time at which the certificate entered its current state.</span></span></param>
        <param name="previousProvisioningState"><span data-ttu-id="bfbe4-114">Der vorherige bereitgestellte Status der Ressource.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-114">The previous provisioned state of the resource.</span></span> <span data-ttu-id="bfbe4-115">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Löschen", "fehlgeschlagen"</span><span class="sxs-lookup"><span data-stu-id="bfbe4-115">Possible values include: 'Succeeded', 'Deleting', 'Failed'</span></span></param>
        <param name="previousProvisioningStateTransitionTime"><span data-ttu-id="bfbe4-116">Der Zeitpunkt, an dem das Zertifikat in den vorherigen Zustand übergegangen.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-116">The time at which the certificate entered its previous state.</span></span></param>
        <param name="publicData"><span data-ttu-id="bfbe4-117">Der öffentliche Schlüssel des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-117">The public key of the certificate.</span></span></param>
        <param name="deleteCertificateError"><span data-ttu-id="bfbe4-118">Der Fehler beim Löschen des Zertifikats trat</span><span class="sxs-lookup"><span data-stu-id="bfbe4-118">The error which occurred while deleting the certificate</span></span></param>
        <summary>
            <span data-ttu-id="bfbe4-119">Initialisiert eine neue Instanz der Zertifikat-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-119">Initializes a new instance of the Certificate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.DeleteCertificateError DeleteCertificateError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.DeleteCertificateError DeleteCertificateError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.DeleteCertificateError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeleteCertificateError As DeleteCertificateError" />
      <MemberSignature Language="F#" Value="member this.DeleteCertificateError : Microsoft.Azure.Management.Batch.Models.DeleteCertificateError" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.DeleteCertificateError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deleteCertificateError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.DeleteCertificateError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfbe4-120">Ruft den Fehler beim Löschen des Zertifikats eingetreten ab</span><span class="sxs-lookup"><span data-stu-id="bfbe4-120">Gets the error which occurred while deleting the certificate</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="bfbe4-121">Dies wird nur zurückgegeben, wenn das Zertifikat ProvisioningState "fehlgeschlagen".</span><span class="sxs-lookup"><span data-stu-id="bfbe4-121">This is only returned when the certificate provisioningState is 'Failed'.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.CertificateFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.CertificateFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As CertificateFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Management.Batch.Models.CertificateFormat with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.Format" />
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
            <span data-ttu-id="bfbe4-122">Ruft ab oder legt das Format des Zertifikat - Pfx oder Cer.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-122">Gets or sets the format of the certificate - either Pfx or Cer.</span></span> <span data-ttu-id="bfbe4-123">Wenn nicht angegeben, ist die Standardeinstellung Pfx.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-123">If omitted, the default is Pfx.</span></span> <span data-ttu-id="bfbe4-124">Folgende Werte sind möglich: "Pfx", ". Cer"</span><span class="sxs-lookup"><span data-stu-id="bfbe4-124">Possible values include: 'Pfx', 'Cer'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState PreviousProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState PreviousProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.PreviousProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousProvisioningState As CertificateProvisioningState" />
      <MemberSignature Language="F#" Value="member this.PreviousProvisioningState : Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.PreviousProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.previousProvisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfbe4-125">Ruft den vorherigen bereitgestellten Zustand der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-125">Gets the previous provisioned state of the resource.</span></span> <span data-ttu-id="bfbe4-126">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Löschen", "fehlgeschlagen"</span><span class="sxs-lookup"><span data-stu-id="bfbe4-126">Possible values include: 'Succeeded', 'Deleting', 'Failed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousProvisioningStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousProvisioningStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousProvisioningStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.PreviousProvisioningStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousProvisioningStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousProvisioningStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.PreviousProvisioningStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.previousProvisioningStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfbe4-127">Ruft den Zeitpunkt, an dem das Zertifikat in den vorherigen Zustand übergegangen.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-127">Gets the time at which the certificate entered its previous state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As CertificateProvisioningState" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="bfbe4-128">Ruft den Bereitstellungsstatus der Ressource</span><span class="sxs-lookup"><span data-stu-id="bfbe4-128">Gets the provisioned state of the resource</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>
             <span data-ttu-id="bfbe4-129">Gültige Werte:</span><span class="sxs-lookup"><span data-stu-id="bfbe4-129">Values are:</span></span>
            
             <span data-ttu-id="bfbe4-130">Erfolgreich – ist das Zertifikat für die Verwendung in Pools verfügbar.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-130">Succeeded - The certificate is available for use in pools.</span></span>
             <span data-ttu-id="bfbe4-131">Wird gelöscht – der Benutzer fordert, dass das Zertifikat gelöscht werden, aber der Delete-Vorgang wurde noch nicht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-131">Deleting - The user has requested that the certificate be deleted, but the delete operation has not yet completed.</span></span> <span data-ttu-id="bfbe4-132">Sie können nicht auf das Zertifikat beim Erstellen oder Aktualisieren von Pools verweisen.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-132">You may not reference the certificate when creating or updating pools.</span></span>
             <span data-ttu-id="bfbe4-133">Fehler - der Benutzer angefordert, dass das Zertifikat gelöscht werden, aber hinzu, die Verweise auf das Zertifikat immer noch vorhanden sind, oder noch auf einem oder mehreren Computeknoten installiert ist.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-133">Failed - The user requested that the certificate be deleted, but there are pools that still have references to the certificate, or it is still installed on one or more compute nodes.</span></span> <span data-ttu-id="bfbe4-134">(Letzteres kann auftreten, wenn das Zertifikat aus dem Pool entfernt wurde, aber der Knoten noch nicht neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-134">(The latter can occur if the certificate has been removed from the pool, but the node has not yet restarted.</span></span> <span data-ttu-id="bfbe4-135">Knoten aktualisieren ihre Zertifikate nur beim Neustart.) Sie können den Vorgang "Abbrechen" Zertifikat löschen, um den Löschvorgang abzubrechen, oder der Löschvorgang des Zertifikats den Löschvorgang wiederholt.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-135">Nodes refresh their certificates only when they restart.) You may use the cancel certificate delete operation to cancel the delete, or the delete certificate operation to retry the delete.</span></span> <span data-ttu-id="bfbe4-136">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Löschen", "fehlgeschlagen"</span><span class="sxs-lookup"><span data-stu-id="bfbe4-136">Possible values include: 'Succeeded', 'Deleting', 'Failed'</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ProvisioningStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ProvisioningStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.ProvisioningStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.ProvisioningStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfbe4-137">Ruft den Zeitpunkt, an dem das Zertifikat in seinem aktuellen Zustand übergegangen.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-137">Gets the time at which the certificate entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicData">
      <MemberSignature Language="C#" Value="public string PublicData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.PublicData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicData As String" />
      <MemberSignature Language="F#" Value="member this.PublicData : string" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.PublicData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfbe4-138">Ruft den öffentlichen Schlüssel des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-138">Gets the public key of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.Thumbprint" />
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
            <span data-ttu-id="bfbe4-139">Ruft ab oder legt den Fingerabdruck des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="bfbe4-139">Gets or sets the thumbprint of the certificate</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="bfbe4-140">Dieser muss den Fingerabdruck aus dem Namen entsprechen.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-140">This must match the thumbprint from the name.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintAlgorithm">
      <MemberSignature Language="C#" Value="public string ThumbprintAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.ThumbprintAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property ThumbprintAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintAlgorithm : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.ThumbprintAlgorithm" />
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
            <span data-ttu-id="bfbe4-141">Ruft ab oder legt den Hashalgorithmus den Fingerabdruck des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="bfbe4-141">Gets or sets the algorithm of the certificate thumbprint</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="bfbe4-142">Dies muss den ersten Teil der Name des Zertifikats übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-142">This must match the first portion of the certificate name.</span></span>
            <span data-ttu-id="bfbe4-143">Derzeit muss "SHA1" sein.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-143">Currently required to be 'SHA1'.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Certificate.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificate.Validate " />
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
            <span data-ttu-id="bfbe4-144">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="bfbe4-144">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bfbe4-145">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="bfbe4-145">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>