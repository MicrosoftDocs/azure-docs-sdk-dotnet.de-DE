<Type Name="Target" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.Target">
  <TypeSignature Language="C#" Value="public class Target" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Target extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.Target" />
  <TypeSignature Language="VB.NET" Value="Public Class Target" />
  <TypeSignature Language="F#" Value="type Target = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="88d81-101">Das Ziel des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="88d81-101">The target of the event.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Target ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Target.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="88d81-102">Initialisiert eine neue Instanz der Zielklasse an.</span><span class="sxs-lookup"><span data-stu-id="88d81-102">Initializes a new instance of the Target class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Target (string mediaType = null, Nullable&lt;long&gt; size = null, string digest = null, Nullable&lt;long&gt; length = null, string repository = null, string url = null, string tag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string mediaType, valuetype System.Nullable`1&lt;int64&gt; size, string digest, valuetype System.Nullable`1&lt;int64&gt; length, string repository, string url, string tag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Target.#ctor(System.String,System.Nullable{System.Int64},System.String,System.Nullable{System.Int64},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional mediaType As String = null, Optional size As Nullable(Of Long) = null, Optional digest As String = null, Optional length As Nullable(Of Long) = null, Optional repository As String = null, Optional url As String = null, Optional tag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.Target : string * Nullable&lt;int64&gt; * string * Nullable&lt;int64&gt; * string * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Target" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.Target (mediaType, size, digest, length, repository, url, tag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mediaType" Type="System.String" />
        <Parameter Name="size" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="digest" Type="System.String" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="repository" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="tag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="mediaType"><span data-ttu-id="88d81-103">Der MIME-Typ des Objekts, auf das verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="88d81-103">The MIME type of the referenced object.</span></span></param>
        <param name="size"><span data-ttu-id="88d81-104">Die Byte-Anzahl des Inhalts.</span><span class="sxs-lookup"><span data-stu-id="88d81-104">The number of bytes of the content.</span></span> <span data-ttu-id="88d81-105">Entspricht dem Feld „Length“ (Länge).</span><span class="sxs-lookup"><span data-stu-id="88d81-105">Same as Length field.</span></span></param>
        <param name="digest"><span data-ttu-id="88d81-106">Der Hashwert des Inhalts, wie durch die Registrierung V2 HTTP-API-Initialisierungszeichenfolge definiert.</span><span class="sxs-lookup"><span data-stu-id="88d81-106">The digest of the content, as defined by the Registry V2 HTTP API Specificiation.</span></span></param>
        <param name="length"><span data-ttu-id="88d81-107">Die Byte-Anzahl des Inhalts.</span><span class="sxs-lookup"><span data-stu-id="88d81-107">The number of bytes of the content.</span></span> <span data-ttu-id="88d81-108">Entspricht dem Feld „Size“ (Größe).</span><span class="sxs-lookup"><span data-stu-id="88d81-108">Same as Size field.</span></span></param>
        <param name="repository"><span data-ttu-id="88d81-109">Der Name des Repositorys.</span><span class="sxs-lookup"><span data-stu-id="88d81-109">The repository name.</span></span></param>
        <param name="url"><span data-ttu-id="88d81-110">Die direkte URL auf den Inhalt.</span><span class="sxs-lookup"><span data-stu-id="88d81-110">The direct URL to the content.</span></span></param>
        <param name="tag"><span data-ttu-id="88d81-111">Der Tagname.</span><span class="sxs-lookup"><span data-stu-id="88d81-111">The tag name.</span></span></param>
        <summary>
            <span data-ttu-id="88d81-112">Initialisiert eine neue Instanz der Zielklasse an.</span><span class="sxs-lookup"><span data-stu-id="88d81-112">Initializes a new instance of the Target class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Digest">
      <MemberSignature Language="C#" Value="public string Digest { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Digest" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Target.Digest" />
      <MemberSignature Language="VB.NET" Value="Public Property Digest As String" />
      <MemberSignature Language="F#" Value="member this.Digest : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Target.Digest" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="digest")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88d81-113">Ermittelt oder definiert den Hashwert des Inhalts, wie durch die Registrierung V2 HTTP-API-Initialisierungszeichenfolge definiert.</span><span class="sxs-lookup"><span data-stu-id="88d81-113">Gets or sets the digest of the content, as defined by the Registry V2 HTTP API Specificiation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Length { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Target.Length" />
      <MemberSignature Language="VB.NET" Value="Public Property Length As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Length : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Target.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="length")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88d81-114">Ruft ab oder legt die Anzahl der Bytes des Inhalts.</span><span class="sxs-lookup"><span data-stu-id="88d81-114">Gets or sets the number of bytes of the content.</span></span> <span data-ttu-id="88d81-115">Entspricht dem Feld „Size“ (Größe).</span><span class="sxs-lookup"><span data-stu-id="88d81-115">Same as Size field.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MediaType">
      <MemberSignature Language="C#" Value="public string MediaType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MediaType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Target.MediaType" />
      <MemberSignature Language="VB.NET" Value="Public Property MediaType As String" />
      <MemberSignature Language="F#" Value="member this.MediaType : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Target.MediaType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mediaType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88d81-116">Ruft ab oder legt den MIME-Typ des Objekts, auf die verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="88d81-116">Gets or sets the MIME type of the referenced object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Repository">
      <MemberSignature Language="C#" Value="public string Repository { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Repository" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Target.Repository" />
      <MemberSignature Language="VB.NET" Value="Public Property Repository As String" />
      <MemberSignature Language="F#" Value="member this.Repository : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Target.Repository" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="repository")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88d81-117">Ruft ab oder legt den Repositorynamen ein.</span><span class="sxs-lookup"><span data-stu-id="88d81-117">Gets or sets the repository name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Size { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Target.Size" />
      <MemberSignature Language="VB.NET" Value="Public Property Size As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Size : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Target.Size" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="size")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88d81-118">Ruft ab oder legt die Anzahl der Bytes des Inhalts.</span><span class="sxs-lookup"><span data-stu-id="88d81-118">Gets or sets the number of bytes of the content.</span></span> <span data-ttu-id="88d81-119">Entspricht dem Feld „Length“ (Länge).</span><span class="sxs-lookup"><span data-stu-id="88d81-119">Same as Length field.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tag">
      <MemberSignature Language="C#" Value="public string Tag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Target.Tag" />
      <MemberSignature Language="VB.NET" Value="Public Property Tag As String" />
      <MemberSignature Language="F#" Value="member this.Tag : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Target.Tag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88d81-120">Ruft ab oder legt den Tagnamen.</span><span class="sxs-lookup"><span data-stu-id="88d81-120">Gets or sets the tag name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Target.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Target.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88d81-121">Ruft ab oder legt die direkte URL auf den Inhalt.</span><span class="sxs-lookup"><span data-stu-id="88d81-121">Gets or sets the direct URL to the content.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>