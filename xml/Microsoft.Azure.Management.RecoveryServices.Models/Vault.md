<Type Name="Vault" FullName="Microsoft.Azure.Management.RecoveryServices.Models.Vault">
  <TypeSignature Language="C#" Value="public class Vault : Microsoft.Azure.Management.RecoveryServices.Models.TrackedResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Vault extends Microsoft.Azure.Management.RecoveryServices.Models.TrackedResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.Vault" />
  <TypeSignature Language="VB.NET" Value="Public Class Vault&#xA;Inherits TrackedResource" />
  <TypeSignature Language="F#" Value="type Vault = class&#xA;    inherit TrackedResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Models.TrackedResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6c9e8-101">Informationen zur Ressource, wie Sie den Ressourcenanbieter zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="6c9e8-101">Resource information, as returned by the resource provider.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Vault ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.Vault.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6c9e8-102">Initialisiert eine neue Instanz der Klasse Tresor an.</span><span class="sxs-lookup"><span data-stu-id="6c9e8-102">Initializes a new instance of the Vault class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Vault (string location, string id = null, string name = null, string type = null, string eTag = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties properties = null, Microsoft.Azure.Management.RecoveryServices.Models.Sku sku = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, string eTag, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties properties, class Microsoft.Azure.Management.RecoveryServices.Models.Sku sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.Vault.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties,Microsoft.Azure.Management.RecoveryServices.Models.Sku)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.Vault : string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties * Microsoft.Azure.Management.RecoveryServices.Models.Sku -&gt; Microsoft.Azure.Management.RecoveryServices.Models.Vault" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.Vault (location, id, name, type, eTag, tags, properties, sku)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.RecoveryServices.Models.Sku" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="6c9e8-103">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="6c9e8-103">Resource location.</span></span></param>
        <param name="id"><span data-ttu-id="6c9e8-104">Ressourcen-Id stellt den vollständigen Pfad zur Ressource dar.</span><span class="sxs-lookup"><span data-stu-id="6c9e8-104">Resource Id represents the complete path to the resource.</span></span></param>
        <param name="name"><span data-ttu-id="6c9e8-105">Ressourcennamen der Ressource zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="6c9e8-105">Resource name associated with the resource.</span></span></param>
        <param name="type"><span data-ttu-id="6c9e8-106">Ressourcentyp "" stellt den vollständigen Pfad des Formulars Namespace/ResourceType/ResourceType /...</span><span class="sxs-lookup"><span data-stu-id="6c9e8-106">Resource type represents the complete path of the form Namespace/ResourceType/ResourceType/...</span></span></param>
        <param name="eTag"><span data-ttu-id="6c9e8-107">Optionale ETag.</span><span class="sxs-lookup"><span data-stu-id="6c9e8-107">Optional ETag.</span></span></param>
        <param name="tags"><span data-ttu-id="6c9e8-108">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="6c9e8-108">Resource tags.</span></span></param>
        <param name="properties">To be added.</param>
        <param name="sku">To be added.</param>
        <summary>
            <span data-ttu-id="6c9e8-109">Initialisiert eine neue Instanz der Klasse Tresor an.</span><span class="sxs-lookup"><span data-stu-id="6c9e8-109">Initializes a new instance of the Vault class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.Vault.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As VaultProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.Vault.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.Vault.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.RecoveryServices.Models.Sku with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.Vault.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.Vault.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="vault.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6c9e8-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="6c9e8-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6c9e8-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="6c9e8-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>