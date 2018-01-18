<Type Name="OAuthBasedDataSourceProperties" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties">
  <TypeSignature Language="C#" Value="public class OAuthBasedDataSourceProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OAuthBasedDataSourceProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class OAuthBasedDataSourceProperties" />
  <TypeSignature Language="F#" Value="type OAuthBasedDataSourceProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="14f48-101">Die Eigenschaften, die Datenquellen zugeordnet sind, die OAuth als ihre Authentifizierungsmodell verwenden.</span><span class="sxs-lookup"><span data-stu-id="14f48-101">The properties that are associated with data sources that use OAuth as their authentication model.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OAuthBasedDataSourceProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="14f48-102">Initialisiert eine neue Instanz der OAuthBasedDataSourceProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="14f48-102">Initializes a new instance of the OAuthBasedDataSourceProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OAuthBasedDataSourceProperties (string refreshToken = null, string tokenUserPrincipalName = null, string tokenUserDisplayName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string refreshToken, string tokenUserPrincipalName, string tokenUserDisplayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional refreshToken As String = null, Optional tokenUserPrincipalName As String = null, Optional tokenUserDisplayName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties : string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties (refreshToken, tokenUserPrincipalName, tokenUserDisplayName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="refreshToken" Type="System.String" />
        <Parameter Name="tokenUserPrincipalName" Type="System.String" />
        <Parameter Name="tokenUserDisplayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="refreshToken"><span data-ttu-id="14f48-103">Ein Aktualisierungstoken, das verwendet werden kann, um eine gültige Zugriffstoken abrufen, die für die Authentifizierung bei der Datenquelle verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="14f48-103">A refresh token that can be used to obtain a valid access token that can then be used to authenticate with the data source.</span></span> <span data-ttu-id="14f48-104">Ein gültiges Aktualisierungstoken ist derzeit nur über das Azure Portal erhältlich.</span><span class="sxs-lookup"><span data-stu-id="14f48-104">A valid refresh token is currently only obtainable via the Azure Portal.</span></span> <span data-ttu-id="14f48-105">Es wird empfohlen, einen dummy-Zeichenfolgenwert für die Erstellung der Datenquelle und dann hörmal im Azure-Verwaltungsportal, um die Datenquelle zu authentifizieren, die diese Eigenschaft mit einem gültigen Aktualisierungstoken aktualisiert wird hier eingefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="14f48-105">It is recommended to put a dummy string value here when creating the data source and then going to the Azure Portal to authenticate the data source which will update this property with a valid refresh token.</span></span> <span data-ttu-id="14f48-106">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="14f48-106">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="tokenUserPrincipalName"><span data-ttu-id="14f48-107">Prinzipalname (UPN) des Benutzers, der verwendet wurde, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="14f48-107">The user principal name (UPN) of the user that was used to obtain the refresh token.</span></span> <span data-ttu-id="14f48-108">Verwenden Sie diese Eigenschaft, um Beachten Sie, welche Benutzer verwendet wurde, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="14f48-108">Use this property to help remember which user was used to obtain the refresh token.</span></span></param>
        <param name="tokenUserDisplayName"><span data-ttu-id="14f48-109">Der Anzeigename des Benutzers, der verwendet wurde, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="14f48-109">The user display name of the user that was used to obtain the refresh token.</span></span> <span data-ttu-id="14f48-110">Verwenden Sie diese Eigenschaft, um Beachten Sie, welche Benutzer verwendet wurde, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="14f48-110">Use this property to help remember which user was used to obtain the refresh token.</span></span></param>
        <summary>
            <span data-ttu-id="14f48-111">Initialisiert eine neue Instanz der OAuthBasedDataSourceProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="14f48-111">Initializes a new instance of the OAuthBasedDataSourceProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshToken">
      <MemberSignature Language="C#" Value="public string RefreshToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RefreshToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.RefreshToken" />
      <MemberSignature Language="VB.NET" Value="Public Property RefreshToken As String" />
      <MemberSignature Language="F#" Value="member this.RefreshToken : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.RefreshToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="refreshToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14f48-112">Ruft ab oder legt ein Aktualisierungstoken, das verwendet werden kann, um eine gültige Zugriffstoken abrufen, die für die Authentifizierung bei der Datenquelle verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="14f48-112">Gets or sets a refresh token that can be used to obtain a valid access token that can then be used to authenticate with the data source.</span></span> <span data-ttu-id="14f48-113">Ein gültiges Aktualisierungstoken ist derzeit nur über das Azure Portal erhältlich.</span><span class="sxs-lookup"><span data-stu-id="14f48-113">A valid refresh token is currently only obtainable via the Azure Portal.</span></span> <span data-ttu-id="14f48-114">Es wird empfohlen, einen dummy-Zeichenfolgenwert für die Erstellung der Datenquelle und dann hörmal im Azure-Verwaltungsportal, um die Datenquelle zu authentifizieren, die diese Eigenschaft mit einem gültigen Aktualisierungstoken aktualisiert wird hier eingefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="14f48-114">It is recommended to put a dummy string value here when creating the data source and then going to the Azure Portal to authenticate the data source which will update this property with a valid refresh token.</span></span> <span data-ttu-id="14f48-115">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="14f48-115">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenUserDisplayName">
      <MemberSignature Language="C#" Value="public string TokenUserDisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenUserDisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.TokenUserDisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenUserDisplayName As String" />
      <MemberSignature Language="F#" Value="member this.TokenUserDisplayName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.TokenUserDisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenUserDisplayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14f48-116">Ruft ab oder legt den Benutzernamen für die Anzeige des Benutzers, der verwendet wurde, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="14f48-116">Gets or sets the user display name of the user that was used to obtain the refresh token.</span></span> <span data-ttu-id="14f48-117">Verwenden Sie diese Eigenschaft, um Beachten Sie, welche Benutzer verwendet wurde, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="14f48-117">Use this property to help remember which user was used to obtain the refresh token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenUserPrincipalName">
      <MemberSignature Language="C#" Value="public string TokenUserPrincipalName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenUserPrincipalName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.TokenUserPrincipalName" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenUserPrincipalName As String" />
      <MemberSignature Language="F#" Value="member this.TokenUserPrincipalName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.TokenUserPrincipalName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenUserPrincipalName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14f48-118">Ruft ab oder legt den Benutzerprinzipalnamen (UPN) des Benutzers, der verwendet wurde, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="14f48-118">Gets or sets the user principal name (UPN) of the user that was used to obtain the refresh token.</span></span> <span data-ttu-id="14f48-119">Verwenden Sie diese Eigenschaft, um Beachten Sie, welche Benutzer verwendet wurde, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="14f48-119">Use this property to help remember which user was used to obtain the refresh token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>