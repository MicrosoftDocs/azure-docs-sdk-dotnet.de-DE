<Type Name="IssuerBundle" FullName="Microsoft.Azure.KeyVault.Models.IssuerBundle">
  <TypeSignature Language="C#" Value="public class IssuerBundle" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IssuerBundle extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.IssuerBundle" />
  <TypeSignature Language="VB.NET" Value="Public Class IssuerBundle" />
  <TypeSignature Language="F#" Value="type IssuerBundle = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="53ae6-101">Der Aussteller für Key Vault-Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="53ae6-101">The issuer for Key Vault certificate.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IssuerBundle ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.IssuerBundle.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="53ae6-102">Initialisiert eine neue Instanz der IssuerBundle-Klasse.</span><span class="sxs-lookup"><span data-stu-id="53ae6-102">Initializes a new instance of the IssuerBundle class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IssuerBundle (string id = null, string provider = null, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.IssuerBundle.#ctor(System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.IssuerBundle : string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes -&gt; Microsoft.Azure.KeyVault.Models.IssuerBundle" Usage="new Microsoft.Azure.KeyVault.Models.IssuerBundle (id, provider, credentials, organizationDetails, attributes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="53ae6-103">Der Bezeichner für die Aussteller-Objekt.</span><span class="sxs-lookup"><span data-stu-id="53ae6-103">Identifier for the issuer object.</span></span></param>
        <param name="provider"><span data-ttu-id="53ae6-104">Der Aussteller-Anbieter.</span><span class="sxs-lookup"><span data-stu-id="53ae6-104">The issuer provider.</span></span></param>
        <param name="credentials"><span data-ttu-id="53ae6-105">Die Anmeldeinformationen für den Aussteller verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="53ae6-105">The credentials to be used for the issuer.</span></span></param>
        <param name="organizationDetails"><span data-ttu-id="53ae6-106">Details der Organisation wie an den Aussteller angegeben.</span><span class="sxs-lookup"><span data-stu-id="53ae6-106">Details of the organization as provided to the issuer.</span></span></param>
        <param name="attributes"><span data-ttu-id="53ae6-107">Attribute des Ausstellers-Objekts.</span><span class="sxs-lookup"><span data-stu-id="53ae6-107">Attributes of the issuer object.</span></span></param>
        <summary>
            <span data-ttu-id="53ae6-108">Initialisiert eine neue Instanz der IssuerBundle-Klasse.</span><span class="sxs-lookup"><span data-stu-id="53ae6-108">Initializes a new instance of the IssuerBundle class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Attributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.IssuerAttributes Attributes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.IssuerAttributes Attributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerBundle.Attributes" />
      <MemberSignature Language="VB.NET" Value="Public Property Attributes As IssuerAttributes" />
      <MemberSignature Language="F#" Value="member this.Attributes : Microsoft.Azure.KeyVault.Models.IssuerAttributes with get, set" Usage="Microsoft.Azure.KeyVault.Models.IssuerBundle.Attributes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="attributes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.IssuerAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="53ae6-109">Abrufen oder Festlegen der Attribute des Ausstellers-Objekts.</span><span class="sxs-lookup"><span data-stu-id="53ae6-109">Gets or sets attributes of the issuer object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.IssuerCredentials Credentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.IssuerCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerBundle.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public Property Credentials As IssuerCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.KeyVault.Models.IssuerCredentials with get, set" Usage="Microsoft.Azure.KeyVault.Models.IssuerBundle.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="credentials")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.IssuerCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="53ae6-110">Ruft ab oder legt die Anmeldeinformationen für den Aussteller zu verwendende fest.</span><span class="sxs-lookup"><span data-stu-id="53ae6-110">Gets or sets the credentials to be used for the issuer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerBundle.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.KeyVault.Models.IssuerBundle.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="53ae6-111">Ruft den Bezeichner für die Aussteller-Objekt.</span><span class="sxs-lookup"><span data-stu-id="53ae6-111">Gets identifier for the issuer object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssuerIdentifier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.CertificateIssuerIdentifier IssuerIdentifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.CertificateIssuerIdentifier IssuerIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerBundle.IssuerIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IssuerIdentifier As CertificateIssuerIdentifier" />
      <MemberSignature Language="F#" Value="member this.IssuerIdentifier : Microsoft.Azure.KeyVault.CertificateIssuerIdentifier" Usage="Microsoft.Azure.KeyVault.Models.IssuerBundle.IssuerIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.CertificateIssuerIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="53ae6-112">Der Bezeichner für die Aussteller-Objekt.</span><span class="sxs-lookup"><span data-stu-id="53ae6-112">Identifier for the issuer object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrganizationDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.OrganizationDetails OrganizationDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.OrganizationDetails OrganizationDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerBundle.OrganizationDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property OrganizationDetails As OrganizationDetails" />
      <MemberSignature Language="F#" Value="member this.OrganizationDetails : Microsoft.Azure.KeyVault.Models.OrganizationDetails with get, set" Usage="Microsoft.Azure.KeyVault.Models.IssuerBundle.OrganizationDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="org_details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.OrganizationDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="53ae6-113">Ermittelt oder definiert die Details der Organisation wie an den Aussteller angegeben.</span><span class="sxs-lookup"><span data-stu-id="53ae6-113">Gets or sets details of the organization as provided to the issuer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerBundle.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.IssuerBundle.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="53ae6-114">Abrufen oder Festlegen des Ausstellers-Anbieters.</span><span class="sxs-lookup"><span data-stu-id="53ae6-114">Gets or sets the issuer provider.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>