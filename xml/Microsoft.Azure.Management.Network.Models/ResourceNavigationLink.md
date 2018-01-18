<Type Name="ResourceNavigationLink" FullName="Microsoft.Azure.Management.Network.Models.ResourceNavigationLink">
  <TypeSignature Language="C#" Value="public class ResourceNavigationLink : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceNavigationLink extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ResourceNavigationLink" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceNavigationLink&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ResourceNavigationLink = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="6b2e1-101">ResourceNavigationLink-Ressource.</span><span class="sxs-lookup"><span data-stu-id="6b2e1-101">ResourceNavigationLink resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceNavigationLink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ResourceNavigationLink.#ctor" />
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
            <span data-ttu-id="6b2e1-102">Initialisiert eine neue Instanz der ResourceNavigationLink-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6b2e1-102">Initializes a new instance of the ResourceNavigationLink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceNavigationLink (string id = null, string linkedResourceType = null, string link = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string linkedResourceType, string link, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ResourceNavigationLink.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional linkedResourceType As String = null, Optional link As String = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ResourceNavigationLink : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ResourceNavigationLink" Usage="new Microsoft.Azure.Management.Network.Models.ResourceNavigationLink (id, linkedResourceType, link, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="linkedResourceType" Type="System.String" />
        <Parameter Name="link" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="6b2e1-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="6b2e1-103">Resource ID.</span></span></param>
        <param name="linkedResourceType"><span data-ttu-id="6b2e1-104">Der Ressourcentyp der verknüpften Ressource.</span><span class="sxs-lookup"><span data-stu-id="6b2e1-104">Resource type of the linked resource.</span></span></param>
        <param name="link"><span data-ttu-id="6b2e1-105">Mit der externen Ressource verknüpfen</span><span class="sxs-lookup"><span data-stu-id="6b2e1-105">Link to the external resource</span></span></param>
        <param name="provisioningState"><span data-ttu-id="6b2e1-106">Der Bereitstellungsstatus der ResourceNavigationLink Ressource.</span><span class="sxs-lookup"><span data-stu-id="6b2e1-106">Provisioning state of the ResourceNavigationLink resource.</span></span></param>
        <param name="name"><span data-ttu-id="6b2e1-107">Der Name der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="6b2e1-107">Name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="6b2e1-108">Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="6b2e1-108">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="6b2e1-109">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="6b2e1-109">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="6b2e1-110">Initialisiert eine neue Instanz der ResourceNavigationLink-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6b2e1-110">Initializes a new instance of the ResourceNavigationLink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ResourceNavigationLink.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.Network.Models.ResourceNavigationLink.Etag" />
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
            <span data-ttu-id="6b2e1-111">Ruft eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="6b2e1-111">Gets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Link">
      <MemberSignature Language="C#" Value="public string Link { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Link" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ResourceNavigationLink.Link" />
      <MemberSignature Language="VB.NET" Value="Public Property Link As String" />
      <MemberSignature Language="F#" Value="member this.Link : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ResourceNavigationLink.Link" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.link")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b2e1-112">Ruft ab oder legt auf die externe Ressource verknüpfen</span><span class="sxs-lookup"><span data-stu-id="6b2e1-112">Gets or sets link to the external resource</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedResourceType">
      <MemberSignature Language="C#" Value="public string LinkedResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinkedResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ResourceNavigationLink.LinkedResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedResourceType As String" />
      <MemberSignature Language="F#" Value="member this.LinkedResourceType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ResourceNavigationLink.LinkedResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.linkedResourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b2e1-113">Ruft ab, oder legt ihn fest Ressourcentyp der verknüpften Ressource.</span><span class="sxs-lookup"><span data-stu-id="6b2e1-113">Gets or sets resource type of the linked resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ResourceNavigationLink.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ResourceNavigationLink.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="6b2e1-114">Ruft ab oder legt die Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="6b2e1-114">Gets or sets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="6b2e1-115">Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="6b2e1-115">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ResourceNavigationLink.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Network.Models.ResourceNavigationLink.ProvisioningState" />
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
            <span data-ttu-id="6b2e1-116">Zustand der Ressource ResourceNavigationLink ruft bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="6b2e1-116">Gets provisioning state of the ResourceNavigationLink resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>