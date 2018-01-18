<Type Name="UserCreateParametersInner" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner">
  <TypeSignature Language="C#" Value="public class UserCreateParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserCreateParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class UserCreateParametersInner" />
  <TypeSignature Language="F#" Value="type UserCreateParametersInner = class" />
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
            <span data-ttu-id="fd8f7-101">Fordern Sie Parameter zum Erstellen eines neuen Geschäfts- oder Schul-Benutzerkonto an.</span><span class="sxs-lookup"><span data-stu-id="fd8f7-101">Request parameters for creating a new work or school account user.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserCreateParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fd8f7-102">Initialisiert eine neue Instanz der UserCreateParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fd8f7-102">Initializes a new instance of the UserCreateParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserCreateParametersInner (bool accountEnabled, string displayName, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile passwordProfile, string userPrincipalName, string mailNickname, string immutableId = null, string usageLocation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool accountEnabled, string displayName, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile passwordProfile, string userPrincipalName, string mailNickname, string immutableId, string usageLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.#ctor(System.Boolean,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner : bool * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile * string * string * string * string -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner (accountEnabled, displayName, passwordProfile, userPrincipalName, mailNickname, immutableId, usageLocation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountEnabled" Type="System.Boolean" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="passwordProfile" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile" />
        <Parameter Name="userPrincipalName" Type="System.String" />
        <Parameter Name="mailNickname" Type="System.String" />
        <Parameter Name="immutableId" Type="System.String" />
        <Parameter Name="usageLocation" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountEnabled">To be added.</param>
        <param name="displayName">To be added.</param>
        <param name="passwordProfile">To be added.</param>
        <param name="userPrincipalName">To be added.</param>
        <param name="mailNickname">To be added.</param>
        <param name="immutableId">To be added.</param>
        <param name="usageLocation">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountEnabled">
      <MemberSignature Language="C#" Value="public bool AccountEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AccountEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.AccountEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.AccountEnabled : bool with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.AccountEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accountEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd8f7-103">Ruft ab oder legt fest, ob das Konto aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="fd8f7-103">Gets or sets whether the account is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.DisplayName" />
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
            <span data-ttu-id="fd8f7-104">Ruft ab oder legt den Anzeigenamen des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="fd8f7-104">Gets or sets the display name of the user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImmutableId">
      <MemberSignature Language="C#" Value="public string ImmutableId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ImmutableId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.ImmutableId" />
      <MemberSignature Language="VB.NET" Value="Public Property ImmutableId As String" />
      <MemberSignature Language="F#" Value="member this.ImmutableId : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.ImmutableId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="immutableId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd8f7-105">Ruft ab oder legt diese Funktion muss angegeben werden, wenn Sie eine verbunddomäne für die Benutzereigenschaft UserPrincipalName (UPN) verwendet werden, für die Erstellung ein neuen Benutzerkontos.</span><span class="sxs-lookup"><span data-stu-id="fd8f7-105">Gets or sets this must be specified if you are using a federated domain for the user's userPrincipalName (UPN) property when creating a new user account.</span></span> <span data-ttu-id="fd8f7-106">Es wird verwendet, um eine lokale Active Directory-Benutzerkonto mit ihren Azure AD-Benutzerobjekt zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="fd8f7-106">It is used to associate an on-premises Active Directory user account with their Azure AD user object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MailNickname">
      <MemberSignature Language="C#" Value="public string MailNickname { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MailNickname" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.MailNickname" />
      <MemberSignature Language="VB.NET" Value="Public Property MailNickname As String" />
      <MemberSignature Language="F#" Value="member this.MailNickname : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.MailNickname" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mailNickname")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd8f7-107">Ruft ab oder legt die e-Mail-Alias für den Benutzer.</span><span class="sxs-lookup"><span data-stu-id="fd8f7-107">Gets or sets the mail alias for the user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PasswordProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile PasswordProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile PasswordProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.PasswordProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property PasswordProfile As PasswordProfile" />
      <MemberSignature Language="F#" Value="member this.PasswordProfile : Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.PasswordProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="passwordProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd8f7-108">Ruft ab oder legt das Kennwort Profil</span><span class="sxs-lookup"><span data-stu-id="fd8f7-108">Gets or sets password Profile</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageLocation">
      <MemberSignature Language="C#" Value="public string UsageLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UsageLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.UsageLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property UsageLocation As String" />
      <MemberSignature Language="F#" Value="member this.UsageLocation : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.UsageLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="usageLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserPrincipalName">
      <MemberSignature Language="C#" Value="public string UserPrincipalName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserPrincipalName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.UserPrincipalName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserPrincipalName As String" />
      <MemberSignature Language="F#" Value="member this.UserPrincipalName : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.UserPrincipalName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userPrincipalName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd8f7-109">Ruft ab oder legt den Benutzerprinzipalnamen (someuser@contoso.com).</span><span class="sxs-lookup"><span data-stu-id="fd8f7-109">Gets or sets the user principal name (someuser@contoso.com).</span></span> <span data-ttu-id="fd8f7-110">Es muss eine der überprüften Domänen des Mandanten enthalten.</span><span class="sxs-lookup"><span data-stu-id="fd8f7-110">It must contain one of the verified domains for the tenant.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="userCreateParametersInner.Validate " />
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
            <span data-ttu-id="fd8f7-111">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8f7-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fd8f7-112">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="fd8f7-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>