<Type Name="AuthenticationParameters" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters">
  <TypeSignature Language="C#" Value="public sealed class AuthenticationParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AuthenticationParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AuthenticationParameters" />
  <TypeSignature Language="F#" Value="type AuthenticationParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c9772-101">Enthält die Authentifizierungsparameter basierend auf nicht autorisierte Antwort vom Ressourcenserver.</span><span class="sxs-lookup"><span data-stu-id="c9772-101">Contains authentication parameters based on unauthorized response from resource server.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authority">
      <MemberSignature Language="C#" Value="public string Authority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Authority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.Authority" />
      <MemberSignature Language="VB.NET" Value="Public Property Authority As String" />
      <MemberSignature Language="F#" Value="member this.Authority : string with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.Authority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c9772-102">Ruft ab oder legt die Adresse der Autorisierungsstelle auf Token ausstellen.</span><span class="sxs-lookup"><span data-stu-id="c9772-102">Gets or sets the address of the authority to issue token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromResourceUrlAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters&gt; CreateFromResourceUrlAsync (Uri resourceUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters&gt; CreateFromResourceUrlAsync(class System.Uri resourceUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.CreateFromResourceUrlAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromResourceUrlAsync (resourceUrl As Uri) As Task(Of AuthenticationParameters)" />
      <MemberSignature Language="F#" Value="static member CreateFromResourceUrlAsync : Uri -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters&gt;" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.CreateFromResourceUrlAsync resourceUrl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters/&lt;CreateFromResourceUrlAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceUrl" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="resourceUrl"><span data-ttu-id="c9772-103">Adresse der Ressource</span><span class="sxs-lookup"><span data-stu-id="c9772-103">Address of the resource</span></span></param>
        <summary>
            <span data-ttu-id="c9772-104">Authentifizierungsparameter erstellt von der Adresse der Ressource.</span><span class="sxs-lookup"><span data-stu-id="c9772-104">Creates authentication parameters from address of the resource.</span></span> <span data-ttu-id="c9772-105">Diese Methode erwartet den Ressourcenserver um nicht autorisierte Antwort mit dem WWW-Authenticate-Header enthält die Authentifizierungsparameter zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="c9772-105">This method expects the resource server to return unauthorized response with WWW-Authenticate header containing authentication parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="c9772-106">AuthenticationParameters-Objekt, die Authentifizierungsparameter enthält.</span><span class="sxs-lookup"><span data-stu-id="c9772-106">AuthenticationParameters object containing authentication parameters</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromResponseAuthenticateHeader">
      <MemberSignature Language="C#" Value="public static Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters CreateFromResponseAuthenticateHeader (string authenticateHeader);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters CreateFromResponseAuthenticateHeader(string authenticateHeader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.CreateFromResponseAuthenticateHeader(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromResponseAuthenticateHeader (authenticateHeader As String) As AuthenticationParameters" />
      <MemberSignature Language="F#" Value="static member CreateFromResponseAuthenticateHeader : string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.CreateFromResponseAuthenticateHeader authenticateHeader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authenticateHeader" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authenticateHeader"><span data-ttu-id="c9772-107">Inhalt des Headers WWW-Authenticate-header</span><span class="sxs-lookup"><span data-stu-id="c9772-107">Content of header WWW-Authenticate header</span></span></param>
        <summary>
            <span data-ttu-id="c9772-108">Erstellt die Authentifizierungsparameter aus dem WWW-Authenticate-Header in von der Ressource empfangene Antwort.</span><span class="sxs-lookup"><span data-stu-id="c9772-108">Creates authentication parameters from the WWW-Authenticate header in response received from resource.</span></span> <span data-ttu-id="c9772-109">Diese Methode erwartet den Header Authentifizierungsparameter enthalten.</span><span class="sxs-lookup"><span data-stu-id="c9772-109">This method expects the header to contain authentication parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="c9772-110">AuthenticationParameters-Objekt, die Authentifizierungsparameter enthält.</span><span class="sxs-lookup"><span data-stu-id="c9772-110">AuthenticationParameters object containing authentication parameters</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromUnauthorizedResponseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters&gt; CreateFromUnauthorizedResponseAsync (System.Net.Http.HttpResponseMessage responseMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters&gt; CreateFromUnauthorizedResponseAsync(class System.Net.Http.HttpResponseMessage responseMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.CreateFromUnauthorizedResponseAsync(System.Net.Http.HttpResponseMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromUnauthorizedResponseAsync (responseMessage As HttpResponseMessage) As Task(Of AuthenticationParameters)" />
      <MemberSignature Language="F#" Value="static member CreateFromUnauthorizedResponseAsync : System.Net.Http.HttpResponseMessage -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters&gt;" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.CreateFromUnauthorizedResponseAsync responseMessage" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters/&lt;CreateFromUnauthorizedResponseAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="responseMessage" Type="System.Net.Http.HttpResponseMessage" />
      </Parameters>
      <Docs>
        <param name="responseMessage"><span data-ttu-id="c9772-111">Die Antwort von der Ressource (z. B. über einen http-Aufruf mithilfe von HttpClient) empfangen.</span><span class="sxs-lookup"><span data-stu-id="c9772-111">Response received from the resource (e.g. via an http call using HttpClient).</span></span></param>
        <summary>
            <span data-ttu-id="c9772-112">Erstellt die Authentifizierungsparameter aus der Antwort von der von der Ressource empfangene Antwort empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="c9772-112">Creates authentication parameters from the response received from the response received from the resource.</span></span> <span data-ttu-id="c9772-113">Diese Methode erwartet die Antwort auf Status und der WWW-Authenticate-Header, die Authentifizierungsparameter enthält nicht autorisiert haben.</span><span class="sxs-lookup"><span data-stu-id="c9772-113">This method expects the response to have unauthorized status and WWW-Authenticate header containing authentication parameters.</span></span></summary>
        <returns><span data-ttu-id="c9772-114">AuthenticationParameters-Objekt, die Authentifizierungsparameter enthält.</span><span class="sxs-lookup"><span data-stu-id="c9772-114">AuthenticationParameters object containing authentication parameters</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resource">
      <MemberSignature Language="C#" Value="public string Resource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.Resource" />
      <MemberSignature Language="VB.NET" Value="Public Property Resource As String" />
      <MemberSignature Language="F#" Value="member this.Resource : string with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.Resource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c9772-115">Ruft ab oder legt den Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</span><span class="sxs-lookup"><span data-stu-id="c9772-115">Gets or sets the identifier of the target resource that is the recipient of the requested token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>