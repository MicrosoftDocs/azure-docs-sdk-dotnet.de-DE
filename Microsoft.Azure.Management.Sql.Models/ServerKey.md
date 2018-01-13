<Type Name="ServerKey" FullName="Microsoft.Azure.Management.Sql.Models.ServerKey">
  <TypeSignature Language="C#" Value="public class ServerKey : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServerKey extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ServerKey" />
  <TypeSignature Language="VB.NET" Value="Public Class ServerKey&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type ServerKey = class&#xA;    inherit ProxyResource" />
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
            <span data-ttu-id="31483-101">Ein Serverschlüssel.</span><span class="sxs-lookup"><span data-stu-id="31483-101">A server key.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerKey.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="31483-102">Initialisiert eine neue Instanz der ServerKey-Klasse.</span><span class="sxs-lookup"><span data-stu-id="31483-102">Initializes a new instance of the ServerKey class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerKey (string serverKeyType, string id = null, string name = null, string type = null, string kind = null, string location = null, string subregion = null, string uri = null, string thumbprint = null, Nullable&lt;DateTime&gt; creationDate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serverKeyType, string id, string name, string type, string kind, string location, string subregion, string uri, string thumbprint, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerKey.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serverKeyType As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As String = null, Optional location As String = null, Optional subregion As String = null, Optional uri As String = null, Optional thumbprint As String = null, Optional creationDate As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ServerKey : string * string * string * string * string * string * string * string * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Sql.Models.ServerKey" Usage="new Microsoft.Azure.Management.Sql.Models.ServerKey (serverKeyType, id, name, type, kind, location, subregion, uri, thumbprint, creationDate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="subregion" Type="System.String" />
        <Parameter Name="serverKeyType" Type="System.String" />
        <Parameter Name="uri" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="creationDate" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="serverKeyType"><span data-ttu-id="31483-103">Der Schlüsseltyp Server, z. B. "ServiceManaged", "AzureKeyVault".</span><span class="sxs-lookup"><span data-stu-id="31483-103">The server key type like 'ServiceManaged', 'AzureKeyVault'.</span></span> <span data-ttu-id="31483-104">Folgende Werte sind möglich: "ServiceManaged", "AzureKeyVault"</span><span class="sxs-lookup"><span data-stu-id="31483-104">Possible values include: 'ServiceManaged', 'AzureKeyVault'</span></span></param>
        <param name="id"><span data-ttu-id="31483-105">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="31483-105">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="31483-106">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="31483-106">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="31483-107">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="31483-107">Resource type.</span></span></param>
        <param name="kind"><span data-ttu-id="31483-108">Art der Verschlüsselung Schutzvorrichtung.</span><span class="sxs-lookup"><span data-stu-id="31483-108">Kind of encryption protector.</span></span> <span data-ttu-id="31483-109">Dies ist die Metadaten für die Azure portalumgebung verwendet.</span><span class="sxs-lookup"><span data-stu-id="31483-109">This is metadata used for the Azure portal experience.</span></span></param>
        <param name="location"><span data-ttu-id="31483-110">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="31483-110">Resource location.</span></span></param>
        <param name="subregion"><span data-ttu-id="31483-111">Unterbereich des Schlüssels für Server.</span><span class="sxs-lookup"><span data-stu-id="31483-111">Subregion of the server key.</span></span></param>
        <param name="uri"><span data-ttu-id="31483-112">Der URI des Schlüssels für Server.</span><span class="sxs-lookup"><span data-stu-id="31483-112">The URI of the server key.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="31483-113">Der Fingerabdruck des Schlüssels für Server.</span><span class="sxs-lookup"><span data-stu-id="31483-113">Thumbprint of the server key.</span></span></param>
        <param name="creationDate"><span data-ttu-id="31483-114">Das Erstellungsdatum für den Server-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="31483-114">The server key creation date.</span></span></param>
        <summary>
            <span data-ttu-id="31483-115">Initialisiert eine neue Instanz der ServerKey-Klasse.</span><span class="sxs-lookup"><span data-stu-id="31483-115">Initializes a new instance of the ServerKey class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerKey.CreationDate" />
      <MemberSignature Language="VB.NET" Value="Public Property CreationDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ServerKey.CreationDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="31483-116">Ruft ab oder legt das Erstellungsdatum der Server Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="31483-116">Gets or sets the server key creation date.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerKey.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ServerKey.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="31483-117">Ruft ab oder legt die Art der Verschlüsselung Schutzvorrichtung.</span><span class="sxs-lookup"><span data-stu-id="31483-117">Gets or sets kind of encryption protector.</span></span> <span data-ttu-id="31483-118">Dies ist die Metadaten für die Azure portalumgebung verwendet.</span><span class="sxs-lookup"><span data-stu-id="31483-118">This is metadata used for the Azure portal experience.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerKey.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.ServerKey.Location" />
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
            <span data-ttu-id="31483-119">Ruft die Position der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="31483-119">Gets resource location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerKeyType">
      <MemberSignature Language="C#" Value="public string ServerKeyType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerKeyType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerKey.ServerKeyType" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerKeyType As String" />
      <MemberSignature Language="F#" Value="member this.ServerKeyType : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ServerKey.ServerKeyType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverKeyType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="31483-120">Ruft ab oder legt den Server Schlüsseltyp wie "ServiceManaged", "AzureKeyVault".</span><span class="sxs-lookup"><span data-stu-id="31483-120">Gets or sets the server key type like 'ServiceManaged', 'AzureKeyVault'.</span></span> <span data-ttu-id="31483-121">Folgende Werte sind möglich: "ServiceManaged", "AzureKeyVault"</span><span class="sxs-lookup"><span data-stu-id="31483-121">Possible values include: 'ServiceManaged', 'AzureKeyVault'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subregion">
      <MemberSignature Language="C#" Value="public string Subregion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Subregion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerKey.Subregion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subregion As String" />
      <MemberSignature Language="F#" Value="member this.Subregion : string" Usage="Microsoft.Azure.Management.Sql.Models.ServerKey.Subregion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subregion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="31483-122">Ruft die Unterbereich des Schlüssels für den Server ab.</span><span class="sxs-lookup"><span data-stu-id="31483-122">Gets subregion of the server key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerKey.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ServerKey.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="31483-123">Abrufen oder Festlegen der Fingerabdruck des Schlüssels für Server.</span><span class="sxs-lookup"><span data-stu-id="31483-123">Gets or sets thumbprint of the server key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public string Uri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerKey.Uri" />
      <MemberSignature Language="VB.NET" Value="Public Property Uri As String" />
      <MemberSignature Language="F#" Value="member this.Uri : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ServerKey.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.uri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="31483-124">Ruft ab oder legt den URI des Schlüssels für den Server fest.</span><span class="sxs-lookup"><span data-stu-id="31483-124">Gets or sets the URI of the server key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerKey.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="serverKey.Validate " />
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
            <span data-ttu-id="31483-125">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="31483-125">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="31483-126">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="31483-126">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>