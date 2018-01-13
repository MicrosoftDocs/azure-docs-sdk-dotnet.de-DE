<Type Name="SourceControl" FullName="Microsoft.Azure.Management.WebSites.Models.SourceControl">
  <TypeSignature Language="C#" Value="public class SourceControl : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SourceControl extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SourceControl" />
  <TypeSignature Language="VB.NET" Value="Public Class SourceControl&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SourceControl = class&#xA;    inherit ProxyOnlyResource" />
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
            <span data-ttu-id="73d8a-101">Die Datenquellen-Steuerelements OAuth-Token.</span><span class="sxs-lookup"><span data-stu-id="73d8a-101">The source control OAuth token.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SourceControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SourceControl.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="73d8a-102">Initialisiert eine neue Instanz der SourceControl-Klasse.</span><span class="sxs-lookup"><span data-stu-id="73d8a-102">Initializes a new instance of the SourceControl class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SourceControl (string id = null, string name = null, string kind = null, string type = null, string sourceControlName = null, string token = null, string tokenSecret = null, string refreshToken = null, Nullable&lt;DateTime&gt; expirationTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string sourceControlName, string token, string tokenSecret, string refreshToken, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expirationTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SourceControl.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional sourceControlName As String = null, Optional token As String = null, Optional tokenSecret As String = null, Optional refreshToken As String = null, Optional expirationTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SourceControl : string * string * string * string * string * string * string * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.SourceControl" Usage="new Microsoft.Azure.Management.WebSites.Models.SourceControl (id, name, kind, type, sourceControlName, token, tokenSecret, refreshToken, expirationTime)" />
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
        <Parameter Name="sourceControlName" Type="System.String" />
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="tokenSecret" Type="System.String" />
        <Parameter Name="refreshToken" Type="System.String" />
        <Parameter Name="expirationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="73d8a-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="73d8a-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="73d8a-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="73d8a-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="73d8a-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="73d8a-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="73d8a-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="73d8a-106">Resource type.</span></span></param>
        <param name="sourceControlName"><span data-ttu-id="73d8a-107">Der Name oder die Quelle Steuerelementtyp.</span><span class="sxs-lookup"><span data-stu-id="73d8a-107">Name or source control type.</span></span></param>
        <param name="token"><span data-ttu-id="73d8a-108">OAuth-Zugriffstoken.</span><span class="sxs-lookup"><span data-stu-id="73d8a-108">OAuth access token.</span></span></param>
        <param name="tokenSecret"><span data-ttu-id="73d8a-109">Geheime Schlüssel token der OAuth-Zugriff.</span><span class="sxs-lookup"><span data-stu-id="73d8a-109">OAuth access token secret.</span></span></param>
        <param name="refreshToken"><span data-ttu-id="73d8a-110">OAuth-aktualisierungstokens.</span><span class="sxs-lookup"><span data-stu-id="73d8a-110">OAuth refresh token.</span></span></param>
        <param name="expirationTime"><span data-ttu-id="73d8a-111">Ablauf der OAuth-token.</span><span class="sxs-lookup"><span data-stu-id="73d8a-111">OAuth token expiration.</span></span></param>
        <summary>
            <span data-ttu-id="73d8a-112">Initialisiert eine neue Instanz der SourceControl-Klasse.</span><span class="sxs-lookup"><span data-stu-id="73d8a-112">Initializes a new instance of the SourceControl class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpirationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SourceControl.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SourceControl.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.expirationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73d8a-113">Ruft ab, oder legt ihn fest oAuth-token-Ablauf.</span><span class="sxs-lookup"><span data-stu-id="73d8a-113">Gets or sets oAuth token expiration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshToken">
      <MemberSignature Language="C#" Value="public string RefreshToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RefreshToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SourceControl.RefreshToken" />
      <MemberSignature Language="VB.NET" Value="Public Property RefreshToken As String" />
      <MemberSignature Language="F#" Value="member this.RefreshToken : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SourceControl.RefreshToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.refreshToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73d8a-114">Ruft ab, oder legt die oAuth-aktualisierungstokens fest.</span><span class="sxs-lookup"><span data-stu-id="73d8a-114">Gets or sets oAuth refresh token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceControlName">
      <MemberSignature Language="C#" Value="public string SourceControlName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceControlName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SourceControl.SourceControlName" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceControlName As String" />
      <MemberSignature Language="F#" Value="member this.SourceControlName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SourceControl.SourceControlName" />
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
            <span data-ttu-id="73d8a-115">Ruft ab, oder legt ihn fest Steuerelementtyp "Name" oder "Quelle".</span><span class="sxs-lookup"><span data-stu-id="73d8a-115">Gets or sets name or source control type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SourceControl.Token" />
      <MemberSignature Language="VB.NET" Value="Public Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SourceControl.Token" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.token")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73d8a-116">Ruft ab, oder legt ihn fest oAuth-Zugriffstoken.</span><span class="sxs-lookup"><span data-stu-id="73d8a-116">Gets or sets oAuth access token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenSecret">
      <MemberSignature Language="C#" Value="public string TokenSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SourceControl.TokenSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenSecret As String" />
      <MemberSignature Language="F#" Value="member this.TokenSecret : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SourceControl.TokenSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tokenSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73d8a-117">Ruft ab, oder legt die geheimen für den Zugriff der oAuth-Tokenschlüssel fest.</span><span class="sxs-lookup"><span data-stu-id="73d8a-117">Gets or sets oAuth access token secret.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>