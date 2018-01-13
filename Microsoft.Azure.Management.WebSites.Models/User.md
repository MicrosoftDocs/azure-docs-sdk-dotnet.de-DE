<Type Name="User" FullName="Microsoft.Azure.Management.WebSites.Models.User">
  <TypeSignature Language="C#" Value="public class User : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit User extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.User" />
  <TypeSignature Language="VB.NET" Value="Public Class User&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type User = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
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
            <span data-ttu-id="9e06b-101">Benutzer Crendentials für die Veröffentlichung von Aktivität verwendet.</span><span class="sxs-lookup"><span data-stu-id="9e06b-101">User crendentials used for publishing activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public User ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.User.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9e06b-102">Initialisiert eine neue Instanz der User-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9e06b-102">Initializes a new instance of the User class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public User (string id = null, string name = null, string kind = null, string type = null, string userName = null, string publishingUserName = null, string publishingPassword = null, string publishingPasswordHash = null, string publishingPasswordHashSalt = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string userName, string publishingUserName, string publishingPassword, string publishingPasswordHash, string publishingPasswordHashSalt) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.User.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional userName As String = null, Optional publishingUserName As String = null, Optional publishingPassword As String = null, Optional publishingPasswordHash As String = null, Optional publishingPasswordHashSalt As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.User : string * string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.User" Usage="new Microsoft.Azure.Management.WebSites.Models.User (id, name, kind, type, userName, publishingUserName, publishingPassword, publishingPasswordHash, publishingPasswordHashSalt)" />
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
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="publishingUserName" Type="System.String" />
        <Parameter Name="publishingPassword" Type="System.String" />
        <Parameter Name="publishingPasswordHash" Type="System.String" />
        <Parameter Name="publishingPasswordHashSalt" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="9e06b-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="9e06b-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="9e06b-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="9e06b-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="9e06b-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9e06b-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="9e06b-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="9e06b-106">Resource type.</span></span></param>
        <param name="userName"><span data-ttu-id="9e06b-107">Username</span><span class="sxs-lookup"><span data-stu-id="9e06b-107">Username</span></span></param>
        <param name="publishingUserName"><span data-ttu-id="9e06b-108">Der Benutzername für die Veröffentlichung verwendet.</span><span class="sxs-lookup"><span data-stu-id="9e06b-108">Username used for publishing.</span></span></param>
        <param name="publishingPassword"><span data-ttu-id="9e06b-109">Für die Veröffentlichung verwendete Kennwort.</span><span class="sxs-lookup"><span data-stu-id="9e06b-109">Password used for publishing.</span></span></param>
        <param name="publishingPasswordHash"><span data-ttu-id="9e06b-110">Kennwort-hashtags, die für die Veröffentlichung verwendet.</span><span class="sxs-lookup"><span data-stu-id="9e06b-110">Password hash used for publishing.</span></span></param>
        <param name="publishingPasswordHashSalt"><span data-ttu-id="9e06b-111">Hash-Saltwert des Kennworts für die Veröffentlichung verwendet.</span><span class="sxs-lookup"><span data-stu-id="9e06b-111">Password hash salt used for publishing.</span></span></param>
        <summary>
            <span data-ttu-id="9e06b-112">Initialisiert eine neue Instanz der User-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9e06b-112">Initializes a new instance of the User class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishingPassword">
      <MemberSignature Language="C#" Value="public string PublishingPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishingPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.User.PublishingPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishingPassword As String" />
      <MemberSignature Language="F#" Value="member this.PublishingPassword : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.User.PublishingPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publishingPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e06b-113">Ruft ab oder legt das Kennwort für die Veröffentlichung verwendet.</span><span class="sxs-lookup"><span data-stu-id="9e06b-113">Gets or sets password used for publishing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishingPasswordHash">
      <MemberSignature Language="C#" Value="public string PublishingPasswordHash { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishingPasswordHash" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.User.PublishingPasswordHash" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishingPasswordHash As String" />
      <MemberSignature Language="F#" Value="member this.PublishingPasswordHash : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.User.PublishingPasswordHash" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publishingPasswordHash")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e06b-114">Abrufen oder Festlegen von Kennwort-hashtags, die für die Veröffentlichung verwendet.</span><span class="sxs-lookup"><span data-stu-id="9e06b-114">Gets or sets password hash used for publishing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishingPasswordHashSalt">
      <MemberSignature Language="C#" Value="public string PublishingPasswordHashSalt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishingPasswordHashSalt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.User.PublishingPasswordHashSalt" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishingPasswordHashSalt As String" />
      <MemberSignature Language="F#" Value="member this.PublishingPasswordHashSalt : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.User.PublishingPasswordHashSalt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publishingPasswordHashSalt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e06b-115">Abrufen oder Festlegen von Kennwort-Hash-Salt für die Veröffentlichung verwendet.</span><span class="sxs-lookup"><span data-stu-id="9e06b-115">Gets or sets password hash salt used for publishing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishingUserName">
      <MemberSignature Language="C#" Value="public string PublishingUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishingUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.User.PublishingUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishingUserName As String" />
      <MemberSignature Language="F#" Value="member this.PublishingUserName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.User.PublishingUserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publishingUserName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e06b-116">Abrufen oder Festlegen der Benutzername, der für die Veröffentlichung verwendet.</span><span class="sxs-lookup"><span data-stu-id="9e06b-116">Gets or sets username used for publishing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.User.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.User.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e06b-117">Ruft ab oder legt den Benutzernamen fest</span><span class="sxs-lookup"><span data-stu-id="9e06b-117">Gets or sets username</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>