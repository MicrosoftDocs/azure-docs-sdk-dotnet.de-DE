<Type Name="NetworkWatcher" FullName="Microsoft.Azure.Management.Network.Models.NetworkWatcher">
  <TypeSignature Language="C#" Value="public class NetworkWatcher : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkWatcher extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.NetworkWatcher" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkWatcher&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type NetworkWatcher = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="aabab-101">Der netzwerküberwachung in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="aabab-101">Network watcher in a resource group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkWatcher ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkWatcher.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="aabab-102">Initialisiert eine neue Instanz der NetworkWatcher-Klasse.</span><span class="sxs-lookup"><span data-stu-id="aabab-102">Initializes a new instance of the NetworkWatcher class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkWatcher (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string etag = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string etag, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkWatcher.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional etag As String = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.NetworkWatcher : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkWatcher" Usage="new Microsoft.Azure.Management.Network.Models.NetworkWatcher (id, name, type, location, tags, etag, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="aabab-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="aabab-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="aabab-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="aabab-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="aabab-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="aabab-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="aabab-106">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="aabab-106">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="aabab-107">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="aabab-107">Resource tags.</span></span></param>
        <param name="etag"><span data-ttu-id="aabab-108">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="aabab-108">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="aabab-109">Der Bereitstellungsstatus der Ressource.</span><span class="sxs-lookup"><span data-stu-id="aabab-109">The provisioning state of the resource.</span></span> <span data-ttu-id="aabab-110">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Aktualisieren", "Löschen", "fehlgeschlagen"</span><span class="sxs-lookup"><span data-stu-id="aabab-110">Possible values include: 'Succeeded', 'Updating', 'Deleting', 'Failed'</span></span></param>
        <summary>
            <span data-ttu-id="aabab-111">Initialisiert eine neue Instanz der NetworkWatcher-Klasse.</span><span class="sxs-lookup"><span data-stu-id="aabab-111">Initializes a new instance of the NetworkWatcher class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkWatcher.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkWatcher.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="aabab-112">Ruft ab oder legt eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="aabab-112">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkWatcher.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Network.Models.NetworkWatcher.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="aabab-113">Ruft den Bereitstellungsstatus der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="aabab-113">Gets the provisioning state of the resource.</span></span> <span data-ttu-id="aabab-114">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Aktualisieren", "Löschen", "fehlgeschlagen"</span><span class="sxs-lookup"><span data-stu-id="aabab-114">Possible values include: 'Succeeded', 'Updating', 'Deleting', 'Failed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>