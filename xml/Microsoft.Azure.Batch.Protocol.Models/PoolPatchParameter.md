<Type Name="PoolPatchParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter">
  <TypeSignature Language="C#" Value="public class PoolPatchParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolPatchParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolPatchParameter" />
  <TypeSignature Language="F#" Value="type PoolPatchParameter = class" />
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
            <span data-ttu-id="14e16-101">Der Satz von Änderungen an einem Pool vorgenommen werden müssen.</span><span class="sxs-lookup"><span data-stu-id="14e16-101">The set of changes to be made to a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolPatchParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.#ctor" />
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
            <span data-ttu-id="14e16-102">Initialisiert eine neue Instanz der PoolPatchParameter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="14e16-102">Initializes a new instance of the PoolPatchParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolPatchParameter (Microsoft.Azure.Batch.Protocol.Models.StartTask startTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.Models.StartTask startTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.#ctor(Microsoft.Azure.Batch.Protocol.Models.StartTask,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.CertificateReference},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter : Microsoft.Azure.Batch.Protocol.Models.StartTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter (startTask, certificateReferences, applicationPackageReferences, metadata)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startTask" Type="Microsoft.Azure.Batch.Protocol.Models.StartTask" />
        <Parameter Name="certificateReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;" />
        <Parameter Name="applicationPackageReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
      </Parameters>
      <Docs>
        <param name="startTask"><span data-ttu-id="14e16-103">Eine Aufgabe, die auf jedem Computeknoten ausgeführt wird, wie sie den Pool verknüpft werden soll.</span><span class="sxs-lookup"><span data-stu-id="14e16-103">A task to run on each compute node as it joins the pool.</span></span> <span data-ttu-id="14e16-104">Der Task ausgeführt wird, wenn der Knoten hinzugefügt wird, an den Pool oder der Knoten neu gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="14e16-104">The task runs when the node is added to the pool or when the node is restarted.</span></span></param>
        <param name="certificateReferences"><span data-ttu-id="14e16-105">Eine Liste der Zertifikate auf jeder Serverknoten im Pool installiert werden.</span><span class="sxs-lookup"><span data-stu-id="14e16-105">A list of certificates to be installed on each compute node in the pool.</span></span></param>
        <param name="applicationPackageReferences"><span data-ttu-id="14e16-106">Eine Liste von Anwendungspaketen auf jeder Serverknoten im Pool installiert werden.</span><span class="sxs-lookup"><span data-stu-id="14e16-106">A list of application packages to be installed on each compute node in the pool.</span></span></param>
        <param name="metadata"><span data-ttu-id="14e16-107">Eine Liste von Name / Wert-Paaren, die dem Pool als Metadaten zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="14e16-107">A list of name-value pairs associated with the pool as metadata.</span></span></param>
        <summary>
            <span data-ttu-id="14e16-108">Initialisiert eine neue Instanz der PoolPatchParameter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="14e16-108">Initializes a new instance of the PoolPatchParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.ApplicationPackageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationPackageReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14e16-109">Ruft ab oder legt eine Liste von Anwendungspaketen auf jeder Serverknoten im Pool installiert werden.</span><span class="sxs-lookup"><span data-stu-id="14e16-109">Gets or sets a list of application packages to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="14e16-110">Änderungen an der Anwendung Paketverweise Auswirkungen auf alle neuen Serverknoten verknüpfen den Pool, aber wirken sich nicht auf die Serverknoten, die bereits im Pool befinden, bis er neu gestartet oder ein reimaging ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="14e16-110">Changes to application package references affect all new compute nodes joining the pool, but do not affect compute nodes that are already in the pool until they are rebooted or reimaged.</span></span> <span data-ttu-id="14e16-111">Wenn dieses Element vorhanden ist, wird die vorhandene Anwendung Paketverweise ersetzt.</span><span class="sxs-lookup"><span data-stu-id="14e16-111">If this element is present, it replaces any existing application package references.</span></span> <span data-ttu-id="14e16-112">Wenn Sie eine leere Auflistung angeben, werden alle Anwendungsverweise Paket aus dem Pool entfernt.</span><span class="sxs-lookup"><span data-stu-id="14e16-112">If you specify an empty collection, then all application package references are removed from the pool.</span></span> <span data-ttu-id="14e16-113">Wenn nicht angegeben, unverändert alle vorhandenen Anwendungspaket, das Verweise übrig sind.</span><span class="sxs-lookup"><span data-stu-id="14e16-113">If omitted, any existing application package references are left unchanged.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateReferences As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.CertificateReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14e16-114">Ruft ab oder legt eine Liste der Zertifikate auf jeder Serverknoten im Pool installiert werden.</span><span class="sxs-lookup"><span data-stu-id="14e16-114">Gets or sets a list of certificates to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="14e16-115">Wenn dieses Element vorhanden ist, ersetzt alle vorhandenen zertifikatsverweise, die für den Pool konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="14e16-115">If this element is present, it replaces any existing certificate references configured on the pool.</span></span> <span data-ttu-id="14e16-116">Wenn nicht angegeben, unverändert alle vorhandenen Zertifikate, die Verweise übrig sind.</span><span class="sxs-lookup"><span data-stu-id="14e16-116">If omitted, any existing certificate references are left unchanged.</span></span> <span data-ttu-id="14e16-117">Für Serverknoten für Windows, installiert der Batch-Dienst die Zertifikate auf den angegebenen Zertifikatspeicher und den Speicherort an.</span><span class="sxs-lookup"><span data-stu-id="14e16-117">For Windows compute nodes, the Batch service installs the certificates to the specified certificate store and location.</span></span> <span data-ttu-id="14e16-118">Für Linux-Serverknoten werden die Zertifikate gespeichert, in einem Verzeichnis in das Arbeitsverzeichnis für die Aufgabe und eine Umgebung aus, die Variable AZ_BATCH_CERTIFICATES_DIR für den Task zum Abfragen von diesem Speicherort angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="14e16-118">For Linux compute nodes, the certificates are stored in a directory inside the task working directory and an environment variable AZ_BATCH_CERTIFICATES_DIR is supplied to the task to query for this location.</span></span> <span data-ttu-id="14e16-119">Für Zertifikate mit der Sichtbarkeit der "RemoteUser" ein "Zertifikate"-Verzeichnis im Basisverzeichnis des Benutzers erstellt wird (z. B. /home/ {Benutzername} / Zertifikaten) und Zertifikate in diesem Verzeichnis abgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="14e16-119">For certificates with visibility of 'remoteUser', a 'certs' directory is created in the user's home directory (e.g., /home/{user-name}/certs) and certificates are placed in that directory.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14e16-120">Ruft ab oder legt eine Liste von Name / Wert-Paaren, die dem Pool als Metadaten zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="14e16-120">Gets or sets a list of name-value pairs associated with the pool as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="14e16-121">Wenn dieses Element vorhanden ist, ersetzt alle vorhandenen Metadaten für den Pool konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="14e16-121">If this element is present, it replaces any existing metadata configured on the pool.</span></span> <span data-ttu-id="14e16-122">Wenn Sie eine leere Auflistung angeben, werden alle Metadaten aus dem Pool entfernt.</span><span class="sxs-lookup"><span data-stu-id="14e16-122">If you specify an empty collection, any metadata is removed from the pool.</span></span> <span data-ttu-id="14e16-123">Wenn nicht angegeben, alle vorhandener Metadaten bleibt unverändert.</span><span class="sxs-lookup"><span data-stu-id="14e16-123">If omitted, any existing metadata is left unchanged.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.Protocol.Models.StartTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14e16-124">Ruft ab oder legt einen Task auf jeder Compute-Knoten ausgeführt wird, wie den Pool hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="14e16-124">Gets or sets a task to run on each compute node as it joins the pool.</span></span> <span data-ttu-id="14e16-125">Der Task ausgeführt wird, wenn der Knoten hinzugefügt wird, an den Pool oder der Knoten neu gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="14e16-125">The task runs when the node is added to the pool or when the node is restarted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="14e16-126">Wenn dieses Element vorhanden ist, überschreibt jede vorhandene Startaufgabe.</span><span class="sxs-lookup"><span data-stu-id="14e16-126">If this element is present, it overwrites any existing start task.</span></span>
            <span data-ttu-id="14e16-127">Wenn nicht angegeben, alle vorhandenen Startaufgabe bleibt unverändert.</span><span class="sxs-lookup"><span data-stu-id="14e16-127">If omitted, any existing start task is left unchanged.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolPatchParameter.Validate " />
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
            <span data-ttu-id="14e16-128">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="14e16-128">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="14e16-129">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="14e16-129">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>