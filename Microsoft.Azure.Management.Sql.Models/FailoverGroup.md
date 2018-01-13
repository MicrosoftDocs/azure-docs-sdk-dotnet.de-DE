<Type Name="FailoverGroup" FullName="Microsoft.Azure.Management.Sql.Models.FailoverGroup">
  <TypeSignature Language="C#" Value="public class FailoverGroup : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FailoverGroup extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.FailoverGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class FailoverGroup&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type FailoverGroup = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c3a5f-101">Eine Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-101">A failover group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c3a5f-102">Initialisiert eine neue Instanz der FailoverGroup-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-102">Initializes a new instance of the FailoverGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverGroup (Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint readWriteEndpoint, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.PartnerInfo&gt; partnerServers, string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint readOnlyEndpoint = null, string replicationRole = null, string replicationState = null, System.Collections.Generic.IList&lt;string&gt; databases = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint readWriteEndpoint, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.PartnerInfo&gt; partnerServers, string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint readOnlyEndpoint, string replicationRole, string replicationState, class System.Collections.Generic.IList`1&lt;string&gt; databases) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroup.#ctor(Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint,System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.PartnerInfo},System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (readWriteEndpoint As FailoverGroupReadWriteEndpoint, partnerServers As IList(Of PartnerInfo), Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional readOnlyEndpoint As FailoverGroupReadOnlyEndpoint = null, Optional replicationRole As String = null, Optional replicationState As String = null, Optional databases As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.FailoverGroup : Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.PartnerInfo&gt; * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="new Microsoft.Azure.Management.Sql.Models.FailoverGroup (readWriteEndpoint, partnerServers, id, name, type, location, tags, readOnlyEndpoint, replicationRole, replicationState, databases)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="readWriteEndpoint" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint" />
        <Parameter Name="partnerServers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.PartnerInfo&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="readOnlyEndpoint" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint" />
        <Parameter Name="replicationRole" Type="System.String" />
        <Parameter Name="replicationState" Type="System.String" />
        <Parameter Name="databases" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="readWriteEndpoint"><span data-ttu-id="c3a5f-103">Lese-/ Schreibzugriff Endpunkt der Gruppeninstanz Failover.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-103">Read-write endpoint of the failover group instance.</span></span></param>
        <param name="partnerServers"><span data-ttu-id="c3a5f-104">Liste der Partner-Serverinformationen für die Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-104">List of partner server information for the failover group.</span></span></param>
        <param name="id"><span data-ttu-id="c3a5f-105">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="c3a5f-105">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="c3a5f-106">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-106">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="c3a5f-107">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-107">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="c3a5f-108">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-108">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="c3a5f-109">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-109">Resource tags.</span></span></param>
        <param name="readOnlyEndpoint"><span data-ttu-id="c3a5f-110">Nur-Lese Endpunkt der Gruppeninstanz Failover.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-110">Read-only endpoint of the failover group instance.</span></span></param>
        <param name="replicationRole"><span data-ttu-id="c3a5f-111">Lokale replikationsrolle der Gruppeninstanz Failover.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-111">Local replication role of the failover group instance.</span></span> <span data-ttu-id="c3a5f-112">Folgende Werte sind möglich: 'Primary', 'Sekundären'</span><span class="sxs-lookup"><span data-stu-id="c3a5f-112">Possible values include: 'Primary', 'Secondary'</span></span></param>
        <param name="replicationState"><span data-ttu-id="c3a5f-113">Der Replikationsstatus der Gruppeninstanz Failover.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-113">Replication state of the failover group instance.</span></span></param>
        <param name="databases"><span data-ttu-id="c3a5f-114">Die Liste der Datenbanken in der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="c3a5f-114">List of databases in the failover group.</span></span></param>
        <summary>
            <span data-ttu-id="c3a5f-115">Initialisiert eine neue Instanz der FailoverGroup-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-115">Initializes a new instance of the FailoverGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Databases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Databases { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Databases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroup.Databases" />
      <MemberSignature Language="VB.NET" Value="Public Property Databases As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Databases : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroup.Databases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3a5f-116">Ruft ab oder legt die Liste der Datenbanken in der Gruppe "Failover" fest.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-116">Gets or sets list of databases in the failover group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroup.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroup.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3a5f-117">Ruft die Position der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-117">Gets resource location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.PartnerInfo&gt; PartnerServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.PartnerInfo&gt; PartnerServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroup.PartnerServers" />
      <MemberSignature Language="VB.NET" Value="Public Property PartnerServers As IList(Of PartnerInfo)" />
      <MemberSignature Language="F#" Value="member this.PartnerServers : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.PartnerInfo&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroup.PartnerServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partnerServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.PartnerInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3a5f-118">Ruft ab oder legt die Liste der Partner-Serverinformationen für die Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-118">Gets or sets list of partner server information for the failover group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadOnlyEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint ReadOnlyEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint ReadOnlyEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroup.ReadOnlyEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadOnlyEndpoint As FailoverGroupReadOnlyEndpoint" />
      <MemberSignature Language="F#" Value="member this.ReadOnlyEndpoint : Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroup.ReadOnlyEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.readOnlyEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3a5f-119">Ruft ab, oder legt ihn fest-nur-Lese-Endpunkt der Gruppeninstanz Failover.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-119">Gets or sets read-only endpoint of the failover group instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadWriteEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint ReadWriteEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint ReadWriteEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroup.ReadWriteEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadWriteEndpoint As FailoverGroupReadWriteEndpoint" />
      <MemberSignature Language="F#" Value="member this.ReadWriteEndpoint : Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroup.ReadWriteEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.readWriteEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3a5f-120">Abrufen oder Festlegen von Lese-/ Schreibzugriff-Endpunkt der Gruppeninstanz Failover.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-120">Gets or sets read-write endpoint of the failover group instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationRole">
      <MemberSignature Language="C#" Value="public string ReplicationRole { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicationRole" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroup.ReplicationRole" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationRole As String" />
      <MemberSignature Language="F#" Value="member this.ReplicationRole : string" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroup.ReplicationRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.replicationRole")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3a5f-121">Ruft die Failover-Gruppeninstanz lokale replikationsrolle ab.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-121">Gets local replication role of the failover group instance.</span></span>
            <span data-ttu-id="c3a5f-122">Folgende Werte sind möglich: 'Primary', 'Sekundären'</span><span class="sxs-lookup"><span data-stu-id="c3a5f-122">Possible values include: 'Primary', 'Secondary'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationState">
      <MemberSignature Language="C#" Value="public string ReplicationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroup.ReplicationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationState As String" />
      <MemberSignature Language="F#" Value="member this.ReplicationState : string" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroup.ReplicationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.replicationState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3a5f-123">Ruft die Replikationsstatus der Gruppeninstanz Failover ab.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-123">Gets replication state of the failover group instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroup.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroup.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3a5f-124">Ermittelt oder Ressourcen-Tags definiert.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-124">Gets or sets resource tags.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroup.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="failoverGroup.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c3a5f-125">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="c3a5f-125">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a5f-126">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="c3a5f-126">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>