<Type Name="PushSettings" FullName="Microsoft.Azure.Management.WebSites.Models.PushSettings">
  <TypeSignature Language="C#" Value="public class PushSettings : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PushSettings extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.PushSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class PushSettings&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type PushSettings = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="1ef58-101">Push-Einstellungen für die App an.</span><span class="sxs-lookup"><span data-stu-id="1ef58-101">Push settings for the App.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PushSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.PushSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1ef58-102">Initialisiert eine neue Instanz der PushSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1ef58-102">Initializes a new instance of the PushSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PushSettings (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;bool&gt; isPushEnabled = null, string tagWhitelistJson = null, string tagsRequiringAuth = null, string dynamicTagsJson = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;bool&gt; isPushEnabled, string tagWhitelistJson, string tagsRequiringAuth, string dynamicTagsJson) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.PushSettings.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional isPushEnabled As Nullable(Of Boolean) = null, Optional tagWhitelistJson As String = null, Optional tagsRequiringAuth As String = null, Optional dynamicTagsJson As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.PushSettings : string * string * string * string * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.PushSettings" Usage="new Microsoft.Azure.Management.WebSites.Models.PushSettings (id, name, kind, type, isPushEnabled, tagWhitelistJson, tagsRequiringAuth, dynamicTagsJson)" />
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
        <Parameter Name="isPushEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="tagWhitelistJson" Type="System.String" />
        <Parameter Name="tagsRequiringAuth" Type="System.String" />
        <Parameter Name="dynamicTagsJson" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="1ef58-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="1ef58-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="1ef58-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="1ef58-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="1ef58-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="1ef58-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="1ef58-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="1ef58-106">Resource type.</span></span></param>
        <param name="isPushEnabled"><span data-ttu-id="1ef58-107">Ruft ab oder legt ein Flag, das angibt, ob sich die Push-Endpunkt aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="1ef58-107">Gets or sets a flag indicating whether the Push endpoint is enabled.</span></span></param>
        <param name="tagWhitelistJson"><span data-ttu-id="1ef58-108">Ruft ab, oder legt ihn fest eine JSON-Zeichenfolge, enthält eine Liste der Tags, die für die Verwendung durch den registrierungsendpunkt Push in der Zulassungsliste enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="1ef58-108">Gets or sets a JSON string containing a list of tags that are whitelisted for use by the push registration endpoint.</span></span></param>
        <param name="tagsRequiringAuth"><span data-ttu-id="1ef58-109">Ruft ab, oder legt ihn fest eine JSON-Zeichenfolge mit einer Liste der Transponder, die Benutzerauthentifizierung, die in der Push-registrierungsendpunkt verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="1ef58-109">Gets or sets a JSON string containing a list of tags that require user authentication to be used in the push registration endpoint.</span></span>
            <span data-ttu-id="1ef58-110">Tags können alphanumerische Zeichen und die folgenden bestehen: "_", "@", "#", ".",":", "-".</span><span class="sxs-lookup"><span data-stu-id="1ef58-110">Tags can consist of alphanumeric characters and the following: '_', '@', '#', '.', ':', '-'.</span></span>
            <span data-ttu-id="1ef58-111">Überprüfung sollte an die PushRequestHandler ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="1ef58-111">Validation should be performed at the PushRequestHandler.</span></span></param>
        <param name="dynamicTagsJson"><span data-ttu-id="1ef58-112">Ruft ab, oder legt ihn fest eine JSON-Zeichenfolge mit einer Liste der dynamischen Transponder, die von Benutzeransprüche in der Push-registrierungsendpunkt ausgewertet wird.</span><span class="sxs-lookup"><span data-stu-id="1ef58-112">Gets or sets a JSON string containing a list of dynamic tags that will be evaluated from user claims in the push registration endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="1ef58-113">Initialisiert eine neue Instanz der PushSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1ef58-113">Initializes a new instance of the PushSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DynamicTagsJson">
      <MemberSignature Language="C#" Value="public string DynamicTagsJson { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DynamicTagsJson" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PushSettings.DynamicTagsJson" />
      <MemberSignature Language="VB.NET" Value="Public Property DynamicTagsJson As String" />
      <MemberSignature Language="F#" Value="member this.DynamicTagsJson : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PushSettings.DynamicTagsJson" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dynamicTagsJson")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ef58-114">Ruft ab, oder legt ihn fest eine JSON-Zeichenfolge mit einer Liste der dynamischen Transponder, die von Benutzeransprüche in der Push-registrierungsendpunkt ausgewertet wird.</span><span class="sxs-lookup"><span data-stu-id="1ef58-114">Gets or sets a JSON string containing a list of dynamic tags that will be evaluated from user claims in the push registration endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPushEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsPushEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsPushEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PushSettings.IsPushEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsPushEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsPushEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PushSettings.IsPushEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isPushEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ef58-115">Ruft ab oder legt ein Flag, das angibt, ob sich die Push-Endpunkt aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="1ef58-115">Gets or sets a flag indicating whether the Push endpoint is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TagsRequiringAuth">
      <MemberSignature Language="C#" Value="public string TagsRequiringAuth { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TagsRequiringAuth" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PushSettings.TagsRequiringAuth" />
      <MemberSignature Language="VB.NET" Value="Public Property TagsRequiringAuth As String" />
      <MemberSignature Language="F#" Value="member this.TagsRequiringAuth : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PushSettings.TagsRequiringAuth" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tagsRequiringAuth")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ef58-116">Ruft ab, oder legt ihn fest eine JSON-Zeichenfolge mit einer Liste der Transponder, die Benutzerauthentifizierung, die in der Push-registrierungsendpunkt verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="1ef58-116">Gets or sets a JSON string containing a list of tags that require user authentication to be used in the push registration endpoint.</span></span>
            <span data-ttu-id="1ef58-117">Tags können alphanumerische Zeichen und die folgenden bestehen: "_", "@", "#", ".",":", "-".</span><span class="sxs-lookup"><span data-stu-id="1ef58-117">Tags can consist of alphanumeric characters and the following: '_', '@', '#', '.', ':', '-'.</span></span>
            <span data-ttu-id="1ef58-118">Überprüfung sollte an die PushRequestHandler ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="1ef58-118">Validation should be performed at the PushRequestHandler.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TagWhitelistJson">
      <MemberSignature Language="C#" Value="public string TagWhitelistJson { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TagWhitelistJson" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PushSettings.TagWhitelistJson" />
      <MemberSignature Language="VB.NET" Value="Public Property TagWhitelistJson As String" />
      <MemberSignature Language="F#" Value="member this.TagWhitelistJson : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PushSettings.TagWhitelistJson" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tagWhitelistJson")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ef58-119">Ruft ab, oder legt ihn fest eine JSON-Zeichenfolge, enthält eine Liste der Tags, die für die Verwendung durch den registrierungsendpunkt Push in der Zulassungsliste enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="1ef58-119">Gets or sets a JSON string containing a list of tags that are whitelisted for use by the push registration endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>