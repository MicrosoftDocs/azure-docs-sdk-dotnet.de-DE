<Type Name="GeoRegion" FullName="Microsoft.Azure.Management.WebSites.Models.GeoRegion">
  <TypeSignature Language="C#" Value="public class GeoRegion : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GeoRegion extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.GeoRegion" />
  <TypeSignature Language="VB.NET" Value="Public Class GeoRegion&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type GeoRegion = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e8452-101">Geografische Region.</span><span class="sxs-lookup"><span data-stu-id="e8452-101">Geographical region.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GeoRegion ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.GeoRegion.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e8452-102">Initialisiert eine neue Instanz der Klasse GeoRegion an.</span><span class="sxs-lookup"><span data-stu-id="e8452-102">Initializes a new instance of the GeoRegion class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GeoRegion (string id = null, string name = null, string kind = null, string type = null, string geoRegionName = null, string description = null, string displayName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string geoRegionName, string description, string displayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.GeoRegion.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional geoRegionName As String = null, Optional description As String = null, Optional displayName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.GeoRegion : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.GeoRegion" Usage="new Microsoft.Azure.Management.WebSites.Models.GeoRegion (id, name, kind, type, geoRegionName, description, displayName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="geoRegionName" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="e8452-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="e8452-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="e8452-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="e8452-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="e8452-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="e8452-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="e8452-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="e8452-106">Resource type.</span></span></param>
        <param name="geoRegionName"><span data-ttu-id="e8452-107">Name der Region.</span><span class="sxs-lookup"><span data-stu-id="e8452-107">Region name.</span></span></param>
        <param name="description"><span data-ttu-id="e8452-108">Beschreibung der Region.</span><span class="sxs-lookup"><span data-stu-id="e8452-108">Region description.</span></span></param>
        <param name="displayName"><span data-ttu-id="e8452-109">Der Anzeigename für die Region.</span><span class="sxs-lookup"><span data-stu-id="e8452-109">Display name for region.</span></span></param>
        <summary>
            <span data-ttu-id="e8452-110">Initialisiert eine neue Instanz der Klasse GeoRegion an.</span><span class="sxs-lookup"><span data-stu-id="e8452-110">Initializes a new instance of the GeoRegion class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.GeoRegion.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string" Usage="Microsoft.Azure.Management.WebSites.Models.GeoRegion.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8452-111">Ruft die Beschreibung der Region ab.</span><span class="sxs-lookup"><span data-stu-id="e8452-111">Gets region description.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.GeoRegion.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string" Usage="Microsoft.Azure.Management.WebSites.Models.GeoRegion.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8452-112">Ruft der Anzeigename für die Region.</span><span class="sxs-lookup"><span data-stu-id="e8452-112">Gets display name for region.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoRegionName">
      <MemberSignature Language="C#" Value="public string GeoRegionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GeoRegionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.GeoRegion.GeoRegionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GeoRegionName As String" />
      <MemberSignature Language="F#" Value="member this.GeoRegionName : string" Usage="Microsoft.Azure.Management.WebSites.Models.GeoRegion.GeoRegionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8452-113">Ruft die Regionsnamen ab.</span><span class="sxs-lookup"><span data-stu-id="e8452-113">Gets region name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>