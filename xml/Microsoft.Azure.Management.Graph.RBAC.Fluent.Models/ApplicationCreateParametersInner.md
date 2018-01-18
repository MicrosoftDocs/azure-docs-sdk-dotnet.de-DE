<Type Name="ApplicationCreateParametersInner" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner">
  <TypeSignature Language="C#" Value="public class ApplicationCreateParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationCreateParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationCreateParametersInner" />
  <TypeSignature Language="F#" Value="type ApplicationCreateParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="30c16-101">Anforderungsparameter für eine neue Anwendung erstellen.</span><span class="sxs-lookup"><span data-stu-id="30c16-101">Request parameters for creating a new application.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationCreateParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="30c16-102">Initialisiert eine neue Instanz der ApplicationCreateParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="30c16-102">Initializes a new instance of the ApplicationCreateParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationCreateParametersInner (bool availableToOtherTenants, string displayName, System.Collections.Generic.IList&lt;string&gt; identifierUris, string homepage = null, System.Collections.Generic.IList&lt;string&gt; replyUrls = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt; keyCredentials = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt; passwordCredentials = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool availableToOtherTenants, string displayName, class System.Collections.Generic.IList`1&lt;string&gt; identifierUris, string homepage, class System.Collections.Generic.IList`1&lt;string&gt; replyUrls, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt; keyCredentials, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt; passwordCredentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.#ctor(System.Boolean,System.String,System.Collections.Generic.IList{System.String},System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential},System.Collections.Generic.IList{Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (availableToOtherTenants As Boolean, displayName As String, identifierUris As IList(Of String), Optional homepage As String = null, Optional replyUrls As IList(Of String) = null, Optional keyCredentials As IList(Of KeyCredential) = null, Optional passwordCredentials As IList(Of PasswordCredential) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner : bool * string * System.Collections.Generic.IList&lt;string&gt; * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt; -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner (availableToOtherTenants, displayName, identifierUris, homepage, replyUrls, keyCredentials, passwordCredentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="availableToOtherTenants" Type="System.Boolean" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="identifierUris" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="homepage" Type="System.String" />
        <Parameter Name="replyUrls" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyCredentials" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;" />
        <Parameter Name="passwordCredentials" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt;" />
      </Parameters>
      <Docs>
        <param name="availableToOtherTenants"><span data-ttu-id="30c16-103">Gibt an, ob die Anwendung für andere Mandanten verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="30c16-103">Whether the application is available to other tenants.</span></span></param>
        <param name="displayName"><span data-ttu-id="30c16-104">Der Anzeigename der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="30c16-104">The display name of the application.</span></span></param>
        <param name="identifierUris"><span data-ttu-id="30c16-105">Eine Auflistung von URIs für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="30c16-105">A collection of URIs for the application.</span></span></param>
        <param name="homepage"><span data-ttu-id="30c16-106">Die Startseite der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="30c16-106">The home page of the application.</span></span></param>
        <param name="replyUrls"><span data-ttu-id="30c16-107">Eine Auflistung von Antwort-URLs für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="30c16-107">A collection of reply URLs for the application.</span></span></param>
        <param name="keyCredentials"><span data-ttu-id="30c16-108">Die Liste der KeyCredential Objekte.</span><span class="sxs-lookup"><span data-stu-id="30c16-108">The list of KeyCredential objects.</span></span></param>
        <param name="passwordCredentials"><span data-ttu-id="30c16-109">Die Liste der PasswordCredential-Objekte.</span><span class="sxs-lookup"><span data-stu-id="30c16-109">The list of PasswordCredential objects.</span></span></param>
        <summary>
            <span data-ttu-id="30c16-110">Initialisiert eine neue Instanz der ApplicationCreateParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="30c16-110">Initializes a new instance of the ApplicationCreateParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableToOtherTenants">
      <MemberSignature Language="C#" Value="public bool AvailableToOtherTenants { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AvailableToOtherTenants" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.AvailableToOtherTenants" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailableToOtherTenants As Boolean" />
      <MemberSignature Language="F#" Value="member this.AvailableToOtherTenants : bool with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.AvailableToOtherTenants" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="availableToOtherTenants")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30c16-111">Ruft ab oder legt fest, ob die Anwendung anderen Mandanten verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="30c16-111">Gets or sets whether the application is available to other tenants.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30c16-112">Ruft ab oder legt den Anzeigenamen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="30c16-112">Gets or sets the display name of the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Homepage">
      <MemberSignature Language="C#" Value="public string Homepage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Homepage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.Homepage" />
      <MemberSignature Language="VB.NET" Value="Public Property Homepage As String" />
      <MemberSignature Language="F#" Value="member this.Homepage : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.Homepage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="homepage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30c16-113">Ruft ab oder legt die Startseite der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="30c16-113">Gets or sets the home page of the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdentifierUris">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; IdentifierUris { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; IdentifierUris" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.IdentifierUris" />
      <MemberSignature Language="VB.NET" Value="Public Property IdentifierUris As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.IdentifierUris : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.IdentifierUris" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identifierUris")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30c16-114">Ruft ab oder legt eine Auflistung von URIs für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="30c16-114">Gets or sets a collection of URIs for the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyCredentials">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt; KeyCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt; KeyCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.KeyCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyCredentials As IList(Of KeyCredential)" />
      <MemberSignature Language="F#" Value="member this.KeyCredentials : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.KeyCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyCredentials")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30c16-115">Ruft ab oder legt die Liste der KeyCredential Objekte.</span><span class="sxs-lookup"><span data-stu-id="30c16-115">Gets or sets the list of KeyCredential objects.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PasswordCredentials">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt; PasswordCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt; PasswordCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.PasswordCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property PasswordCredentials As IList(Of PasswordCredential)" />
      <MemberSignature Language="F#" Value="member this.PasswordCredentials : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.PasswordCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="passwordCredentials")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30c16-116">Ruft ab oder legt die Liste der PasswordCredential-Objekte.</span><span class="sxs-lookup"><span data-stu-id="30c16-116">Gets or sets the list of PasswordCredential objects.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyUrls">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ReplyUrls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ReplyUrls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.ReplyUrls" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyUrls As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ReplyUrls : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.ReplyUrls" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="replyUrls")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30c16-117">Ruft ab oder legt eine Auflistung von Antwort-URLs für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="30c16-117">Gets or sets a collection of reply URLs for the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationCreateParametersInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="30c16-118">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="30c16-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="30c16-119">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="30c16-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>