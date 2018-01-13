<Type Name="ServerAzureADAdministrator" FullName="Microsoft.Azure.Management.Sql.Models.ServerAzureADAdministrator">
  <TypeSignature Language="C#" Value="public class ServerAzureADAdministrator : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi ServerAzureADAdministrator extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ServerAzureADAdministrator" />
  <TypeSignature Language="VB.NET" Value="Public Class ServerAzureADAdministrator&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type ServerAzureADAdministrator = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.SqlSubResource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="053f7-101">Ein Server Active Directory-Administrator.</span><span class="sxs-lookup"><span data-stu-id="053f7-101">An server Active Directory Administrator.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerAzureADAdministrator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerAzureADAdministrator.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="053f7-102">Initialisiert eine neue Instanz der ServerAzureADAdministrator-Klasse.</span><span class="sxs-lookup"><span data-stu-id="053f7-102">Initializes a new instance of the ServerAzureADAdministrator class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerAzureADAdministrator (string login, Guid sid, Guid tenantId, string id = null, string name = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string login, valuetype System.Guid sid, valuetype System.Guid tenantId, string id, string name, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerAzureADAdministrator.#ctor(System.String,System.Guid,System.Guid,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (login As String, sid As Guid, tenantId As Guid, Optional id As String = null, Optional name As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ServerAzureADAdministrator : string * Guid * Guid * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ServerAzureADAdministrator" Usage="new Microsoft.Azure.Management.Sql.Models.ServerAzureADAdministrator (login, sid, tenantId, id, name, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="login" Type="System.String" />
        <Parameter Name="sid" Type="System.Guid" />
        <Parameter Name="tenantId" Type="System.Guid" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="login"><span data-ttu-id="053f7-103">Der Wert der Server-Administrator-Anmeldung.</span><span class="sxs-lookup"><span data-stu-id="053f7-103">The server administrator login value.</span></span></param>
        <param name="sid"><span data-ttu-id="053f7-104">Der Serveradministrator Sid (Secure-ID).</span><span class="sxs-lookup"><span data-stu-id="053f7-104">The server administrator Sid (Secure ID).</span></span></param>
        <param name="tenantId"><span data-ttu-id="053f7-105">Die Mandanten-Id Server Active Directory-Administrator.</span><span class="sxs-lookup"><span data-stu-id="053f7-105">The server Active Directory Administrator tenant id.</span></span></param>
        <param name="id"><span data-ttu-id="053f7-106">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="053f7-106">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="053f7-107">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="053f7-107">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="053f7-108">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="053f7-108">Resource type.</span></span></param>
        <summary>
            <span data-ttu-id="053f7-109">Initialisiert eine neue Instanz der ServerAzureADAdministrator-Klasse.</span><span class="sxs-lookup"><span data-stu-id="053f7-109">Initializes a new instance of the ServerAzureADAdministrator class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdministratorType">
      <MemberSignature Language="C#" Value="public static string AdministratorType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string AdministratorType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerAzureADAdministrator.AdministratorType" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property AdministratorType As String" />
      <MemberSignature Language="F#" Value="member this.AdministratorType : string" Usage="Microsoft.Azure.Management.Sql.Models.ServerAzureADAdministrator.AdministratorType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.administratorType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="053f7-110">Der Typ des Administrators.</span><span class="sxs-lookup"><span data-stu-id="053f7-110">The type of administrator.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Login">
      <MemberSignature Language="C#" Value="public string Login { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Login" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerAzureADAdministrator.Login" />
      <MemberSignature Language="VB.NET" Value="Public Property Login As String" />
      <MemberSignature Language="F#" Value="member this.Login : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ServerAzureADAdministrator.Login" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.login")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="053f7-111">Ruft ab oder legt der Server Administrator Anmeldung Wert fest.</span><span class="sxs-lookup"><span data-stu-id="053f7-111">Gets or sets the server administrator login value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sid">
      <MemberSignature Language="C#" Value="public Guid Sid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid Sid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerAzureADAdministrator.Sid" />
      <MemberSignature Language="VB.NET" Value="Public Property Sid As Guid" />
      <MemberSignature Language="F#" Value="member this.Sid : Guid with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ServerAzureADAdministrator.Sid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="053f7-112">Ruft ab oder legt den Sid-Serveradministrator (Secure-ID).</span><span class="sxs-lookup"><span data-stu-id="053f7-112">Gets or sets the server administrator Sid (Secure ID).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public Guid TenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerAzureADAdministrator.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantId As Guid" />
      <MemberSignature Language="F#" Value="member this.TenantId : Guid with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ServerAzureADAdministrator.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="053f7-113">Ruft ab, oder legt Sie die Active Directory-Administrator-Mandanten-Id fest.</span><span class="sxs-lookup"><span data-stu-id="053f7-113">Gets or sets the server Active Directory Administrator tenant id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerAzureADAdministrator.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="serverAzureADAdministrator.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="053f7-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="053f7-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="053f7-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="053f7-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>