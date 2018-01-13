<Type Name="ManagementLockObject" FullName="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject">
  <TypeSignature Language="C#" Value="public class ManagementLockObject : Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagementLockObject extends System.Object implements class Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagementLockObject&#xA;Implements IResource" />
  <TypeSignature Language="F#" Value="type ManagementLockObject = class&#xA;    interface IResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IResource</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f977b-101">Die Sperrinformationen.</span><span class="sxs-lookup"><span data-stu-id="f977b-101">The lock information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementLockObject ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f977b-102">Initialisiert eine neue Instanz der ManagementLockObject-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f977b-102">Initializes a new instance of the ManagementLockObject class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementLockObject (string level, string notes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner&gt; owners = null, string id = null, string type = null, string name = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string level, string notes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner&gt; owners, string id, string type, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (level As String, Optional notes As String = null, Optional owners As IList(Of ManagementLockOwner) = null, Optional id As String = null, Optional type As String = null, Optional name As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner&gt; * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject (level, notes, owners, id, type, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="level" Type="System.String" />
        <Parameter Name="notes" Type="System.String" />
        <Parameter Name="owners" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="level"><span data-ttu-id="f977b-103">Die Ebene der Sperre.</span><span class="sxs-lookup"><span data-stu-id="f977b-103">The level of the lock.</span></span> <span data-ttu-id="f977b-104">Mögliche Werte sind: "NotSpecified", CanNotDelete, ReadOnly.</span><span class="sxs-lookup"><span data-stu-id="f977b-104">Possible values are: NotSpecified, CanNotDelete, ReadOnly.</span></span> <span data-ttu-id="f977b-105">CanNotDelete bedeutet, dass die autorisierte Benutzer lesen und die Ressourcen ändern, aber nicht gelöscht werden können.</span><span class="sxs-lookup"><span data-stu-id="f977b-105">CanNotDelete means authorized users are able to read and modify the resources, but not delete.</span></span>
            <span data-ttu-id="f977b-106">ReadOnly bedeutet, dass autorisierte Benutzer können nur aus einer Ressource lesen, aber nicht ändern oder löschen Sie ihn.</span><span class="sxs-lookup"><span data-stu-id="f977b-106">ReadOnly means authorized users can only read from a resource, but they can't modify or delete it.</span></span> <span data-ttu-id="f977b-107">Folgende Werte sind möglich: "NotSpecified" "", "CanNotDelete", "ReadOnly"</span><span class="sxs-lookup"><span data-stu-id="f977b-107">Possible values include: 'NotSpecified', 'CanNotDelete', 'ReadOnly'</span></span></param>
        <param name="notes"><span data-ttu-id="f977b-108">Hinweise zu den sperren.</span><span class="sxs-lookup"><span data-stu-id="f977b-108">Notes about the lock.</span></span> <span data-ttu-id="f977b-109">Maximal 512 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="f977b-109">Maximum of 512 characters.</span></span></param>
        <param name="owners"><span data-ttu-id="f977b-110">Die Besitzer der Sperre.</span><span class="sxs-lookup"><span data-stu-id="f977b-110">The owners of the lock.</span></span></param>
        <param name="id"><span data-ttu-id="f977b-111">Die Ressourcen-ID der Sperre.</span><span class="sxs-lookup"><span data-stu-id="f977b-111">The resource ID of the lock.</span></span></param>
        <param name="type"><span data-ttu-id="f977b-112">Der Ressourcentyp der Sperre - Microsoft.Authorization/locks.</span><span class="sxs-lookup"><span data-stu-id="f977b-112">The resource type of the lock - Microsoft.Authorization/locks.</span></span></param>
        <param name="name"><span data-ttu-id="f977b-113">Der Name der Sperre.</span><span class="sxs-lookup"><span data-stu-id="f977b-113">The name of the lock.</span></span></param>
        <summary>
            <span data-ttu-id="f977b-114">Initialisiert eine neue Instanz der ManagementLockObject-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f977b-114">Initializes a new instance of the ManagementLockObject class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f977b-115">Ruft die Ressourcen-ID der Sperre ab.</span><span class="sxs-lookup"><span data-stu-id="f977b-115">Gets the resource ID of the lock.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public string Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As String" />
      <MemberSignature Language="F#" Value="member this.Level : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f977b-116">Ruft ab oder legt fest, der Sperre.</span><span class="sxs-lookup"><span data-stu-id="f977b-116">Gets or sets the level of the lock.</span></span> <span data-ttu-id="f977b-117">Mögliche Werte sind: "NotSpecified", CanNotDelete, ReadOnly.</span><span class="sxs-lookup"><span data-stu-id="f977b-117">Possible values are: NotSpecified, CanNotDelete, ReadOnly.</span></span> <span data-ttu-id="f977b-118">CanNotDelete bedeutet, dass die autorisierte Benutzer lesen und die Ressourcen ändern, aber nicht gelöscht werden können.</span><span class="sxs-lookup"><span data-stu-id="f977b-118">CanNotDelete means authorized users are able to read and modify the resources, but not delete.</span></span>
            <span data-ttu-id="f977b-119">ReadOnly bedeutet, dass autorisierte Benutzer können nur aus einer Ressource lesen, aber nicht ändern oder löschen Sie ihn.</span><span class="sxs-lookup"><span data-stu-id="f977b-119">ReadOnly means authorized users can only read from a resource, but they can't modify or delete it.</span></span> <span data-ttu-id="f977b-120">Folgende Werte sind möglich: "NotSpecified" "", "CanNotDelete", "ReadOnly"</span><span class="sxs-lookup"><span data-stu-id="f977b-120">Possible values include: 'NotSpecified', 'CanNotDelete', 'ReadOnly'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f977b-121">Ruft ab oder legt den Namen der Sperre.</span><span class="sxs-lookup"><span data-stu-id="f977b-121">Gets or sets the name of the lock.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Notes">
      <MemberSignature Language="C#" Value="public string Notes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Notes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Notes" />
      <MemberSignature Language="VB.NET" Value="Public Property Notes As String" />
      <MemberSignature Language="F#" Value="member this.Notes : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Notes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.notes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f977b-122">Ruft ab, oder legt Sie Hinweise für die Sperre fest.</span><span class="sxs-lookup"><span data-stu-id="f977b-122">Gets or sets notes about the lock.</span></span> <span data-ttu-id="f977b-123">Maximal 512 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="f977b-123">Maximum of 512 characters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Owners">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner&gt; Owners { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner&gt; Owners" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Owners" />
      <MemberSignature Language="VB.NET" Value="Public Property Owners As IList(Of ManagementLockOwner)" />
      <MemberSignature Language="F#" Value="member this.Owners : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Owners" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.owners")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f977b-124">Ruft ab oder legt den Besitzer der Sperre.</span><span class="sxs-lookup"><span data-stu-id="f977b-124">Gets or sets the owners of the lock.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f977b-125">Ruft den Ressourcentyp der Sperre - Microsoft.Authorization/locks ab.</span><span class="sxs-lookup"><span data-stu-id="f977b-125">Gets the resource type of the lock - Microsoft.Authorization/locks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="managementLockObject.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f977b-126">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="f977b-126">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f977b-127">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="f977b-127">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>