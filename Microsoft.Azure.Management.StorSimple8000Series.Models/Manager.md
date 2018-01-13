<Type Name="Manager" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.Manager">
  <TypeSignature Language="C#" Value="public class Manager : Microsoft.Azure.Management.StorSimple8000Series.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi Manager extends Microsoft.Azure.Management.StorSimple8000Series.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.Manager" />
  <TypeSignature Language="VB.NET" Value="Public Class Manager&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Manager = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5b87d-101">Der StorSimple-Manager.</span><span class="sxs-lookup"><span data-stu-id="5b87d-101">The StorSimple Manager.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Manager ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5b87d-102">Initialisiert eine neue Instanz der Manager-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5b87d-102">Initializes a new instance of the Manager class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Manager (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings cisIntrinsicSettings = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings cisIntrinsicSettings, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional cisIntrinsicSettings As ManagerIntrinsicSettings = null, Optional provisioningState As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.Manager : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Manager" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.Manager (location, id, name, type, tags, cisIntrinsicSettings, provisioningState, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cisIntrinsicSettings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="5b87d-103">Der geografische Standort der Ressource.</span><span class="sxs-lookup"><span data-stu-id="5b87d-103">The geo location of the resource.</span></span></param>
        <param name="id"><span data-ttu-id="5b87d-104">Die Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="5b87d-104">The resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="5b87d-105">Der Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="5b87d-105">The resource name.</span></span></param>
        <param name="type"><span data-ttu-id="5b87d-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="5b87d-106">The resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="5b87d-107">Die auf die Ressource angefügten Tags.</span><span class="sxs-lookup"><span data-stu-id="5b87d-107">The tags attached to the resource.</span></span></param>
        <param name="cisIntrinsicSettings"><span data-ttu-id="5b87d-108">Stellt den Typ des StorSimple-Managers dar.</span><span class="sxs-lookup"><span data-stu-id="5b87d-108">Represents the type of StorSimple Manager.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="5b87d-109">Gibt den Zustand der Ressource an, wie er erste bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="5b87d-109">Specifies the state of the resource as it is getting provisioned.</span></span> <span data-ttu-id="5b87d-110">Wert von "Succeeded" bedeutet, dass der Manager wurde erfolgreich erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="5b87d-110">Value of "Succeeded" means the Manager was successfully created.</span></span></param>
        <param name="etag"><span data-ttu-id="5b87d-111">Das Etag des Managers.</span><span class="sxs-lookup"><span data-stu-id="5b87d-111">The etag of the manager.</span></span></param>
        <summary>
            <span data-ttu-id="5b87d-112">Initialisiert eine neue Instanz der Manager-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5b87d-112">Initializes a new instance of the Manager class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CisIntrinsicSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings CisIntrinsicSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings CisIntrinsicSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.CisIntrinsicSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CisIntrinsicSettings As ManagerIntrinsicSettings" />
      <MemberSignature Language="F#" Value="member this.CisIntrinsicSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.CisIntrinsicSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cisIntrinsicSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b87d-113">Ruft ab oder legt stellt den Typ des StorSimple-Managers dar.</span><span class="sxs-lookup"><span data-stu-id="5b87d-113">Gets or sets represents the type of StorSimple Manager.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b87d-114">Ruft ab oder legt das Etag des Managers.</span><span class="sxs-lookup"><span data-stu-id="5b87d-114">Gets or sets the etag of the manager.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b87d-115">Ruft ab oder legt ihn fest gibt den Status der Ressource, wie er erste bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="5b87d-115">Gets or sets specifies the state of the resource as it is getting provisioned.</span></span> <span data-ttu-id="5b87d-116">Wert von "Succeeded" bedeutet, dass der Manager wurde erfolgreich erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="5b87d-116">Value of "Succeeded" means the Manager was successfully created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerSku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerSku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Sku As ManagerSku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerSku" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerSku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b87d-117">Gibt die Sku.</span><span class="sxs-lookup"><span data-stu-id="5b87d-117">Specifies the Sku.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="manager.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5b87d-118">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="5b87d-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5b87d-119">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="5b87d-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>