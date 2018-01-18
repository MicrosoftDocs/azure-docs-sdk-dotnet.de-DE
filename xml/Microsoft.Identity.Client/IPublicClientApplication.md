<Type Name="IPublicClientApplication" FullName="Microsoft.Identity.Client.IPublicClientApplication">
  <TypeSignature Language="C#" Value="public interface IPublicClientApplication : Microsoft.Identity.Client.IClientApplicationBase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPublicClientApplication implements class Microsoft.Identity.Client.IClientApplicationBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.IPublicClientApplication" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPublicClientApplication&#xA;Implements IClientApplicationBase" />
  <TypeSignature Language="F#" Value="type IPublicClientApplication = interface&#xA;    interface IClientApplicationBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Identity.Client.IClientApplicationBase</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="fd9f5-101">Die Komponente für systemeigene Anwendungen (Desktop/UWP/iOS/Android) verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-101">Component to be used for native applications (Desktop/UWP/iOS/Android).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync scopes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="fd9f5-102">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-102">Array of scopes requested for resource</span></span></param>
        <summary>
            <span data-ttu-id="fd9f5-103">Interaktive Anforderung zum Abrufen von Token.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-103">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="fd9f5-104">Das Ergebnis der Authentifizierung mit Token des Benutzers</span><span class="sxs-lookup"><span data-stu-id="fd9f5-104">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="fd9f5-105">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-105">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="fd9f5-106">User-Objekt, um denselben Benutzer authentifiziert werden, in der Webbenutzeroberfläche zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-106">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <summary>
            <span data-ttu-id="fd9f5-107">Interaktive Anforderung zum Abrufen von Token.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-107">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="fd9f5-108">Das Ergebnis der Authentifizierung mit Token des Benutzers</span><span class="sxs-lookup"><span data-stu-id="fd9f5-108">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, parent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="fd9f5-109">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-109">Array of scopes requested for resource</span></span></param>
        <param name="parent"><span data-ttu-id="fd9f5-110">Objekt enthält Verweis auf das übergeordnete Fenster/Aktivität.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-110">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="fd9f5-111">Nur erforderlich für Xamarin.Android.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-111">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="fd9f5-112">Interaktive Anforderung zum Abrufen von Token.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-112">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="fd9f5-113">Das Ergebnis der Authentifizierung mit Token des Benutzers</span><span class="sxs-lookup"><span data-stu-id="fd9f5-113">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="fd9f5-114">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-114">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="fd9f5-115">Der Bezeichner des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-115">Identifier of the user.</span></span> <span data-ttu-id="fd9f5-116">Im Allgemeinen einen UPN.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-116">Generally a UPN.</span></span></param>
        <summary>
            <span data-ttu-id="fd9f5-117">Interaktive Anforderung zum Abrufen von Token.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-117">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="fd9f5-118">Das Ergebnis der Authentifizierung mit Token des Benutzers</span><span class="sxs-lookup"><span data-stu-id="fd9f5-118">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user, parent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="fd9f5-119">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-119">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="fd9f5-120">User-Objekt, um denselben Benutzer authentifiziert werden, in der Webbenutzeroberfläche zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-120">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <param name="parent"><span data-ttu-id="fd9f5-121">Objekt enthält Verweis auf das übergeordnete Fenster/Aktivität.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-121">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="fd9f5-122">Nur erforderlich für Xamarin.Android.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-122">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="fd9f5-123">Interaktive Anforderung zum Abrufen von Token.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-123">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="fd9f5-124">Das Ergebnis der Authentifizierung mit Token des Benutzers</span><span class="sxs-lookup"><span data-stu-id="fd9f5-124">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint, parent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="fd9f5-125">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-125">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="fd9f5-126">Der Bezeichner des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-126">Identifier of the user.</span></span> <span data-ttu-id="fd9f5-127">Im Allgemeinen einen UPN.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-127">Generally a UPN.</span></span></param>
        <param name="parent"><span data-ttu-id="fd9f5-128">Objekt enthält Verweis auf das übergeordnete Fenster/Aktivität.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-128">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="fd9f5-129">Nur erforderlich für Xamarin.Android.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-129">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="fd9f5-130">Interaktive Anforderung zum Abrufen von Token.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-130">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="fd9f5-131">Das Ergebnis der Authentifizierung mit Token des Benutzers</span><span class="sxs-lookup"><span data-stu-id="fd9f5-131">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="fd9f5-132">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-132">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="fd9f5-133">User-Objekt, um denselben Benutzer authentifiziert werden, in der Webbenutzeroberfläche zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-133">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <param name="behavior"><span data-ttu-id="fd9f5-134">Steuern des Verhaltens des UI-Enumeration.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-134">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="fd9f5-135">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-135">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="fd9f5-136">Der Parameter kann null sein.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-136">The parameter can be null.</span></span></param>
        <summary>
            <span data-ttu-id="fd9f5-137">Interaktive Anforderung zum Abrufen von Token.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-137">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="fd9f5-138">Das Ergebnis der Authentifizierung mit Token des Benutzers</span><span class="sxs-lookup"><span data-stu-id="fd9f5-138">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="fd9f5-139">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-139">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="fd9f5-140">Der Bezeichner des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-140">Identifier of the user.</span></span> <span data-ttu-id="fd9f5-141">Im Allgemeinen einen UPN.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-141">Generally a UPN.</span></span></param>
        <param name="behavior"><span data-ttu-id="fd9f5-142">Steuern des Verhaltens des UI-Enumeration.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-142">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="fd9f5-143">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-143">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="fd9f5-144">Der Parameter kann null sein.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-144">The parameter can be null.</span></span></param>
        <summary>
            <span data-ttu-id="fd9f5-145">Interaktive Anforderung zum Abrufen von Token.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-145">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="fd9f5-146">Das Ergebnis der Authentifizierung mit Token des Benutzers</span><span class="sxs-lookup"><span data-stu-id="fd9f5-146">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters, parent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="fd9f5-147">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-147">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="fd9f5-148">User-Objekt, um denselben Benutzer authentifiziert werden, in der Webbenutzeroberfläche zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-148">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <param name="behavior"><span data-ttu-id="fd9f5-149">Steuern des Verhaltens des UI-Enumeration.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-149">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="fd9f5-150">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-150">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="fd9f5-151">Der Parameter kann null sein.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-151">The parameter can be null.</span></span></param>
        <param name="parent"><span data-ttu-id="fd9f5-152">Objekt enthält Verweis auf das übergeordnete Fenster/Aktivität.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-152">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="fd9f5-153">Nur erforderlich für Xamarin.Android.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-153">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="fd9f5-154">Interaktive Anforderung zum Abrufen von Token.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-154">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="fd9f5-155">Das Ergebnis der Authentifizierung mit Token des Benutzers</span><span class="sxs-lookup"><span data-stu-id="fd9f5-155">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters, parent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="fd9f5-156">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-156">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="fd9f5-157">Der Bezeichner des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-157">Identifier of the user.</span></span> <span data-ttu-id="fd9f5-158">Im Allgemeinen einen UPN.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-158">Generally a UPN.</span></span></param>
        <param name="behavior"><span data-ttu-id="fd9f5-159">Steuern des Verhaltens des UI-Enumeration.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-159">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="fd9f5-160">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-160">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="fd9f5-161">Der Parameter kann null sein.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-161">The parameter can be null.</span></span></param>
        <param name="parent"><span data-ttu-id="fd9f5-162">Objekt enthält Verweis auf das übergeordnete Fenster/Aktivität.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-162">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="fd9f5-163">Nur erforderlich für Xamarin.Android.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-163">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="fd9f5-164">Interaktive Anforderung zum Abrufen von Token.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-164">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="fd9f5-165">Das Ergebnis der Authentifizierung mit Token des Benutzers</span><span class="sxs-lookup"><span data-stu-id="fd9f5-165">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters, extraScopesToConsent, authority)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="fd9f5-166">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-166">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="fd9f5-167">User-Objekt, um denselben Benutzer authentifiziert werden, in der Webbenutzeroberfläche zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-167">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <param name="behavior"><span data-ttu-id="fd9f5-168">Steuern des Verhaltens des UI-Enumeration.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-168">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="fd9f5-169">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-169">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="fd9f5-170">Der Parameter kann null sein.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-170">The parameter can be null.</span></span></param>
        <param name="extraScopesToConsent"><span data-ttu-id="fd9f5-171">Ein Array von Bereichen, die für die ein Entwickler die Zustimmung im Vorfeld anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-171">Array of scopes for which a developer can request consent upfront.</span></span></param>
        <param name="authority"><span data-ttu-id="fd9f5-172">Spezifische Stelle, die für die das Token angefordert wird.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-172">Specific authority for which the token is requested.</span></span> <span data-ttu-id="fd9f5-173">Übergeben einen anderen Wert als die konfigurierte ändert nicht den konfigurierten Wert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-173">Passing a different value than configured does not change the configured value</span></span></param>
        <summary>
            <span data-ttu-id="fd9f5-174">Interaktive Anforderung zum Abrufen von Token.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-174">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="fd9f5-175">Das Ergebnis der Authentifizierung mit Token des Benutzers</span><span class="sxs-lookup"><span data-stu-id="fd9f5-175">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters, extraScopesToConsent, authority)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="fd9f5-176">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-176">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="fd9f5-177">Der Bezeichner des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-177">Identifier of the user.</span></span> <span data-ttu-id="fd9f5-178">Im Allgemeinen einen UPN.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-178">Generally a UPN.</span></span></param>
        <param name="behavior"><span data-ttu-id="fd9f5-179">Steuern des Verhaltens des UI-Enumeration.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-179">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="fd9f5-180">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-180">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="fd9f5-181">Der Parameter kann null sein.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-181">The parameter can be null.</span></span></param>
        <param name="extraScopesToConsent"><span data-ttu-id="fd9f5-182">Ein Array von Bereichen, die für die ein Entwickler die Zustimmung im Vorfeld anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-182">Array of scopes for which a developer can request consent upfront.</span></span></param>
        <param name="authority"><span data-ttu-id="fd9f5-183">Spezifische Stelle, die für die das Token angefordert wird.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-183">Specific authority for which the token is requested.</span></span> <span data-ttu-id="fd9f5-184">Übergeben einen anderen Wert als die konfigurierte ändert nicht den konfigurierten Wert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-184">Passing a different value than configured does not change the configured value</span></span></param>
        <summary>
            <span data-ttu-id="fd9f5-185">Interaktive Anforderung zum Abrufen von Token.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-185">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="fd9f5-186">Das Ergebnis der Authentifizierung mit Token des Benutzers</span><span class="sxs-lookup"><span data-stu-id="fd9f5-186">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters, extraScopesToConsent, authority, parent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="fd9f5-187">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-187">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="fd9f5-188">User-Objekt, um denselben Benutzer authentifiziert werden, in der Webbenutzeroberfläche zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-188">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <param name="behavior"><span data-ttu-id="fd9f5-189">Steuern des Verhaltens des UI-Enumeration.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-189">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="fd9f5-190">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-190">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="fd9f5-191">Der Parameter kann null sein.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-191">The parameter can be null.</span></span></param>
        <param name="extraScopesToConsent"><span data-ttu-id="fd9f5-192">Ein Array von Bereichen, die für die ein Entwickler die Zustimmung im Vorfeld anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-192">Array of scopes for which a developer can request consent upfront.</span></span></param>
        <param name="authority"><span data-ttu-id="fd9f5-193">Spezifische Stelle, die für die das Token angefordert wird.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-193">Specific authority for which the token is requested.</span></span> <span data-ttu-id="fd9f5-194">Übergeben einen anderen Wert als die konfigurierte ändert nicht den konfigurierten Wert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-194">Passing a different value than configured does not change the configured value</span></span></param>
        <param name="parent"><span data-ttu-id="fd9f5-195">Objekt enthält Verweis auf das übergeordnete Fenster/Aktivität.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-195">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="fd9f5-196">Nur erforderlich für Xamarin.Android.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-196">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="fd9f5-197">Interaktive Anforderung zum Abrufen von Token.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-197">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="fd9f5-198">Das Ergebnis der Authentifizierung mit Token des Benutzers</span><span class="sxs-lookup"><span data-stu-id="fd9f5-198">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters, extraScopesToConsent, authority, parent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="fd9f5-199">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-199">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="fd9f5-200">Der Bezeichner des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-200">Identifier of the user.</span></span> <span data-ttu-id="fd9f5-201">Im Allgemeinen einen UPN.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-201">Generally a UPN.</span></span></param>
        <param name="behavior"><span data-ttu-id="fd9f5-202">Steuern des Verhaltens des UI-Enumeration.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-202">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="fd9f5-203">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-203">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="fd9f5-204">Der Parameter kann null sein.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-204">The parameter can be null.</span></span></param>
        <param name="extraScopesToConsent"><span data-ttu-id="fd9f5-205">Ein Array von Bereichen, die für die ein Entwickler die Zustimmung im Vorfeld anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-205">Array of scopes for which a developer can request consent upfront.</span></span></param>
        <param name="authority"><span data-ttu-id="fd9f5-206">Spezifische Stelle, die für die das Token angefordert wird.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-206">Specific authority for which the token is requested.</span></span> <span data-ttu-id="fd9f5-207">Übergeben einen anderen Wert als die konfigurierte ändert nicht den konfigurierten Wert</span><span class="sxs-lookup"><span data-stu-id="fd9f5-207">Passing a different value than configured does not change the configured value</span></span></param>
        <param name="parent"><span data-ttu-id="fd9f5-208">Objekt enthält Verweis auf das übergeordnete Fenster/Aktivität.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-208">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="fd9f5-209">Nur erforderlich für Xamarin.Android.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-209">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="fd9f5-210">Interaktive Anforderung zum Abrufen von Token.</span><span class="sxs-lookup"><span data-stu-id="fd9f5-210">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="fd9f5-211">Das Ergebnis der Authentifizierung mit Token des Benutzers</span><span class="sxs-lookup"><span data-stu-id="fd9f5-211">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>