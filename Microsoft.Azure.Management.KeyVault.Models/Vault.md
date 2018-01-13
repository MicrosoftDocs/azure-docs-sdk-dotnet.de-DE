<Type Name="Vault" FullName="Microsoft.Azure.Management.KeyVault.Models.Vault">
  <TypeSignature Language="C#" Value="public class Vault : Microsoft.Azure.Management.KeyVault.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Vault extends Microsoft.Azure.Management.KeyVault.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Models.Vault" />
  <TypeSignature Language="VB.NET" Value="Public Class Vault&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Vault = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.KeyVault.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e2d59-101">Informationen zur Ressource mit nähere Einzelheiten.</span><span class="sxs-lookup"><span data-stu-id="e2d59-101">Resource information with extended details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Vault ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.Vault.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e2d59-102">Initialisiert eine neue Instanz der Klasse Tresor an.</span><span class="sxs-lookup"><span data-stu-id="e2d59-102">Initializes a new instance of the Vault class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Vault (string name, string location, Microsoft.Azure.Management.KeyVault.Models.VaultProperties properties, string id = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string location, class Microsoft.Azure.Management.KeyVault.Models.VaultProperties properties, string id, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.Vault.#ctor(System.String,System.String,Microsoft.Azure.Management.KeyVault.Models.VaultProperties,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, location As String, properties As VaultProperties, Optional id As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Models.Vault : string * string * Microsoft.Azure.Management.KeyVault.Models.VaultProperties * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.KeyVault.Models.Vault" Usage="new Microsoft.Azure.Management.KeyVault.Models.Vault (name, location, properties, id, type, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.KeyVault.Models.VaultProperties" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="e2d59-103">Der Name des schlüsseltresors.</span><span class="sxs-lookup"><span data-stu-id="e2d59-103">The name of the key vault.</span></span></param>
        <param name="location"><span data-ttu-id="e2d59-104">Den unterstützten Azure-Speicherort, in dem der schlüsseltresor erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2d59-104">The supported Azure location where the key vault should be created.</span></span></param>
        <param name="properties"><span data-ttu-id="e2d59-105">Eigenschaften des Tresors</span><span class="sxs-lookup"><span data-stu-id="e2d59-105">Properties of the vault</span></span></param>
        <param name="id"><span data-ttu-id="e2d59-106">Die Azure-Ressourcen-Manager-Ressourcen-ID für den schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="e2d59-106">The Azure Resource Manager resource ID for the key vault.</span></span></param>
        <param name="type"><span data-ttu-id="e2d59-107">Der Ressourcentyp des schlüsseltresors.</span><span class="sxs-lookup"><span data-stu-id="e2d59-107">The resource type of the key vault.</span></span></param>
        <param name="tags"><span data-ttu-id="e2d59-108">Die Tags, die auf den schlüsseltresor zugewiesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2d59-108">The tags that will be assigned to the key vault.</span></span> </param>
        <summary>
            <span data-ttu-id="e2d59-109">Initialisiert eine neue Instanz der Klasse Tresor an.</span><span class="sxs-lookup"><span data-stu-id="e2d59-109">Initializes a new instance of the Vault class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Models.VaultProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.KeyVault.Models.VaultProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.Vault.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As VaultProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.KeyVault.Models.VaultProperties with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.Vault.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Models.VaultProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2d59-110">Ruft ab oder legt die Eigenschaften des Tresors</span><span class="sxs-lookup"><span data-stu-id="e2d59-110">Gets or sets properties of the vault</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.Vault.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="vault.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e2d59-111">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="e2d59-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e2d59-112">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="e2d59-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>