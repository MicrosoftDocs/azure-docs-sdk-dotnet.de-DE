<Type Name="ServerUpdate" FullName="Microsoft.Azure.Management.Sql.Models.ServerUpdate">
  <TypeSignature Language="C#" Value="public class ServerUpdate" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServerUpdate extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ServerUpdate" />
  <TypeSignature Language="VB.NET" Value="Public Class ServerUpdate" />
  <TypeSignature Language="F#" Value="type ServerUpdate = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="34c65-101">Eine updateanforderung für eine Azure SQL-Datenbankserver.</span><span class="sxs-lookup"><span data-stu-id="34c65-101">An update request for an Azure SQL Database server.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerUpdate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="34c65-102">Initialisiert eine neue Instanz der Klasse ServerUpdate an.</span><span class="sxs-lookup"><span data-stu-id="34c65-102">Initializes a new instance of the ServerUpdate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerUpdate (string administratorLogin = null, string administratorLoginPassword = null, string version = null, string state = null, string fullyQualifiedDomainName = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string administratorLogin, string administratorLoginPassword, string version, string state, string fullyQualifiedDomainName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerUpdate.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional administratorLogin As String = null, Optional administratorLoginPassword As String = null, Optional version As String = null, Optional state As String = null, Optional fullyQualifiedDomainName As String = null, Optional tags As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ServerUpdate : string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Sql.Models.ServerUpdate" Usage="new Microsoft.Azure.Management.Sql.Models.ServerUpdate (administratorLogin, administratorLoginPassword, version, state, fullyQualifiedDomainName, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="administratorLogin" Type="System.String" />
        <Parameter Name="administratorLoginPassword" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="fullyQualifiedDomainName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="administratorLogin"><span data-ttu-id="34c65-103">Administratorbenutzername für den Server.</span><span class="sxs-lookup"><span data-stu-id="34c65-103">Administrator username for the server.</span></span> <span data-ttu-id="34c65-104">Nach der Erstellung nicht geändert werden kann.</span><span class="sxs-lookup"><span data-stu-id="34c65-104">Once created it cannot be changed.</span></span></param>
        <param name="administratorLoginPassword"><span data-ttu-id="34c65-105">Das Administratorkennwort (erforderlich für die Erstellung des Servers).</span><span class="sxs-lookup"><span data-stu-id="34c65-105">The administrator login password (required for server creation).</span></span></param>
        <param name="version"><span data-ttu-id="34c65-106">Die Version des Servers.</span><span class="sxs-lookup"><span data-stu-id="34c65-106">The version of the server.</span></span></param>
        <param name="state"><span data-ttu-id="34c65-107">Der Status des Servers.</span><span class="sxs-lookup"><span data-stu-id="34c65-107">The state of the server.</span></span></param>
        <param name="fullyQualifiedDomainName"><span data-ttu-id="34c65-108">Der vollqualifizierte Domänenname des Servers.</span><span class="sxs-lookup"><span data-stu-id="34c65-108">The fully qualified domain name of the server.</span></span></param>
        <param name="tags"><span data-ttu-id="34c65-109">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="34c65-109">Resource tags.</span></span></param>
        <summary>
            <span data-ttu-id="34c65-110">Initialisiert eine neue Instanz der Klasse ServerUpdate an.</span><span class="sxs-lookup"><span data-stu-id="34c65-110">Initializes a new instance of the ServerUpdate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdministratorLogin">
      <MemberSignature Language="C#" Value="public string AdministratorLogin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdministratorLogin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerUpdate.AdministratorLogin" />
      <MemberSignature Language="VB.NET" Value="Public Property AdministratorLogin As String" />
      <MemberSignature Language="F#" Value="member this.AdministratorLogin : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ServerUpdate.AdministratorLogin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.administratorLogin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34c65-111">Ruft ab oder legt der Administratorbenutzername für den Server.</span><span class="sxs-lookup"><span data-stu-id="34c65-111">Gets or sets administrator username for the server.</span></span> <span data-ttu-id="34c65-112">Nach der Erstellung nicht geändert werden kann.</span><span class="sxs-lookup"><span data-stu-id="34c65-112">Once created it cannot be changed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdministratorLoginPassword">
      <MemberSignature Language="C#" Value="public string AdministratorLoginPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdministratorLoginPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerUpdate.AdministratorLoginPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property AdministratorLoginPassword As String" />
      <MemberSignature Language="F#" Value="member this.AdministratorLoginPassword : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ServerUpdate.AdministratorLoginPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.administratorLoginPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34c65-113">Ruft ab oder legt der Administrator Anmeldekennwort (erforderlich für die Erstellung von Server).</span><span class="sxs-lookup"><span data-stu-id="34c65-113">Gets or sets the administrator login password (required for server creation).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FullyQualifiedDomainName">
      <MemberSignature Language="C#" Value="public string FullyQualifiedDomainName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FullyQualifiedDomainName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerUpdate.FullyQualifiedDomainName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FullyQualifiedDomainName As String" />
      <MemberSignature Language="F#" Value="member this.FullyQualifiedDomainName : string" Usage="Microsoft.Azure.Management.Sql.Models.ServerUpdate.FullyQualifiedDomainName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.fullyQualifiedDomainName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34c65-114">Ruft den vollqualifizierten Domänennamen des Servers ab.</span><span class="sxs-lookup"><span data-stu-id="34c65-114">Gets the fully qualified domain name of the server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerUpdate.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Sql.Models.ServerUpdate.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34c65-115">Ruft den Zustand des Servers ab.</span><span class="sxs-lookup"><span data-stu-id="34c65-115">Gets the state of the server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerUpdate.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ServerUpdate.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34c65-116">Ermittelt oder Ressourcen-Tags definiert.</span><span class="sxs-lookup"><span data-stu-id="34c65-116">Gets or sets resource tags.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerUpdate.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ServerUpdate.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34c65-117">Ruft ab oder legt die Version des Servers.</span><span class="sxs-lookup"><span data-stu-id="34c65-117">Gets or sets the version of the server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>