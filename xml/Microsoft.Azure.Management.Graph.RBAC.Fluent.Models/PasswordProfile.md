<Type Name="PasswordProfile" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile">
  <TypeSignature Language="C#" Value="public class PasswordProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PasswordProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class PasswordProfile" />
  <TypeSignature Language="F#" Value="type PasswordProfile = class" />
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
            <span data-ttu-id="3b179-101">Das kennwortprofil, das einem Benutzer zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3b179-101">The password profile associated with a user.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PasswordProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3b179-102">Initialisiert eine neue Instanz der PasswordProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3b179-102">Initializes a new instance of the PasswordProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PasswordProfile (string password, Nullable&lt;bool&gt; forceChangePasswordNextLogin = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string password, valuetype System.Nullable`1&lt;bool&gt; forceChangePasswordNextLogin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile.#ctor(System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (password As String, Optional forceChangePasswordNextLogin As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile : string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile (password, forceChangePasswordNextLogin)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="forceChangePasswordNextLogin" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="password"><span data-ttu-id="3b179-103">Password</span><span class="sxs-lookup"><span data-stu-id="3b179-103">Password</span></span></param>
        <param name="forceChangePasswordNextLogin"><span data-ttu-id="3b179-104">Ein Kennwort zu erzwingen, ob ändern bei der nächsten Anmeldung.</span><span class="sxs-lookup"><span data-stu-id="3b179-104">Whether to force a password change on next login.</span></span></param>
        <summary>
            <span data-ttu-id="3b179-105">Initialisiert eine neue Instanz der PasswordProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3b179-105">Initializes a new instance of the PasswordProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceChangePasswordNextLogin">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ForceChangePasswordNextLogin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ForceChangePasswordNextLogin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile.ForceChangePasswordNextLogin" />
      <MemberSignature Language="VB.NET" Value="Public Property ForceChangePasswordNextLogin As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ForceChangePasswordNextLogin : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile.ForceChangePasswordNextLogin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="forceChangePasswordNextLogin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b179-106">Ruft ab oder legt fest, ob eine kennwortänderung bei der nächsten Anmeldung zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="3b179-106">Gets or sets whether to force a password change on next login.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b179-107">Ruft ab oder legt das Kennwort fest</span><span class="sxs-lookup"><span data-stu-id="3b179-107">Gets or sets password</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="passwordProfile.Validate " />
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
            <span data-ttu-id="3b179-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="3b179-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3b179-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="3b179-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>