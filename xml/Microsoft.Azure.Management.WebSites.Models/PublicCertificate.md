<Type Name="PublicCertificate" FullName="Microsoft.Azure.Management.WebSites.Models.PublicCertificate">
  <TypeSignature Language="C#" Value="public class PublicCertificate : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PublicCertificate extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.PublicCertificate" />
  <TypeSignature Language="VB.NET" Value="Public Class PublicCertificate&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type PublicCertificate = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3177a-101">Öffentliches Zertifikat-Objekt</span><span class="sxs-lookup"><span data-stu-id="3177a-101">Public certificate object</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicCertificate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.PublicCertificate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3177a-102">Initialisiert eine neue Instanz der PublicCertificate-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3177a-102">Initializes a new instance of the PublicCertificate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicCertificate (string id = null, string name = null, string kind = null, string type = null, byte[] blob = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.PublicCertificateLocation&gt; publicCertificateLocation = null, string thumbprint = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, unsigned int8[] blob, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.PublicCertificateLocation&gt; publicCertificateLocation, string thumbprint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.PublicCertificate.#ctor(System.String,System.String,System.String,System.String,System.Byte[],System.Nullable{Microsoft.Azure.Management.WebSites.Models.PublicCertificateLocation},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional blob As Byte() = null, Optional publicCertificateLocation As Nullable(Of PublicCertificateLocation) = null, Optional thumbprint As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.PublicCertificate : string * string * string * string * byte[] * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.PublicCertificateLocation&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.PublicCertificate" Usage="new Microsoft.Azure.Management.WebSites.Models.PublicCertificate (id, name, kind, type, blob, publicCertificateLocation, thumbprint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="blob" Type="System.Byte[]" />
        <Parameter Name="publicCertificateLocation" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.PublicCertificateLocation&gt;" />
        <Parameter Name="thumbprint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="3177a-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="3177a-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="3177a-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="3177a-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="3177a-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="3177a-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="3177a-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="3177a-106">Resource type.</span></span></param>
        <param name="blob"><span data-ttu-id="3177a-107">Öffentliche Zertifikat-Byte-array</span><span class="sxs-lookup"><span data-stu-id="3177a-107">Public Certificate byte array</span></span></param>
        <param name="publicCertificateLocation"><span data-ttu-id="3177a-108">Speicherort des öffentlichen Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="3177a-108">Public Certificate Location.</span></span> <span data-ttu-id="3177a-109">Folgende Werte sind möglich: 'CurrentUserMy', 'LocalMachineMy', 'Unbekannt'</span><span class="sxs-lookup"><span data-stu-id="3177a-109">Possible values include: 'CurrentUserMy', 'LocalMachineMy', 'Unknown'</span></span></param>
        <param name="thumbprint"><span data-ttu-id="3177a-110">Zertifikatfingerabdruck</span><span class="sxs-lookup"><span data-stu-id="3177a-110">Certificate Thumbprint</span></span></param>
        <summary>
            <span data-ttu-id="3177a-111">Initialisiert eine neue Instanz der PublicCertificate-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3177a-111">Initializes a new instance of the PublicCertificate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Blob">
      <MemberSignature Language="C#" Value="public byte[] Blob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Blob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PublicCertificate.Blob" />
      <MemberSignature Language="VB.NET" Value="Public Property Blob As Byte()" />
      <MemberSignature Language="F#" Value="member this.Blob : byte[] with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PublicCertificate.Blob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.blob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3177a-112">Ruft ab oder legt ihn fest öffentliche Zertifikat-Byte-array</span><span class="sxs-lookup"><span data-stu-id="3177a-112">Gets or sets public Certificate byte array</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicCertificateLocation">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.PublicCertificateLocation&gt; PublicCertificateLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.PublicCertificateLocation&gt; PublicCertificateLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PublicCertificate.PublicCertificateLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicCertificateLocation As Nullable(Of PublicCertificateLocation)" />
      <MemberSignature Language="F#" Value="member this.PublicCertificateLocation : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.PublicCertificateLocation&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PublicCertificate.PublicCertificateLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicCertificateLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.PublicCertificateLocation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3177a-113">Ruft ab, oder legt ihn fest öffentlichen Speicherort des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="3177a-113">Gets or sets public Certificate Location.</span></span> <span data-ttu-id="3177a-114">Folgende Werte sind möglich: 'CurrentUserMy', 'LocalMachineMy', 'Unbekannt'</span><span class="sxs-lookup"><span data-stu-id="3177a-114">Possible values include: 'CurrentUserMy', 'LocalMachineMy', 'Unknown'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PublicCertificate.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string" Usage="Microsoft.Azure.Management.WebSites.Models.PublicCertificate.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
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
            <span data-ttu-id="3177a-115">Ruft den Zertifikatfingerabdruck</span><span class="sxs-lookup"><span data-stu-id="3177a-115">Gets certificate Thumbprint</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>