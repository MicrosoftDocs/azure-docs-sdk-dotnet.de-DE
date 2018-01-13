<Type Name="ExpressRouteServiceProviderInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner">
  <TypeSignature Language="C#" Value="public class ExpressRouteServiceProviderInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteServiceProviderInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteServiceProviderInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ExpressRouteServiceProviderInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="fe036-101">Ein ExpressRouteResourceProvider-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fe036-101">A ExpressRouteResourceProvider object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteServiceProviderInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fe036-102">Initialisiert eine neue Instanz der ExpressRouteServiceProviderInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fe036-102">Initializes a new instance of the ExpressRouteServiceProviderInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteServiceProviderInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;string&gt; peeringLocations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderBandwidthsOffered&gt; bandwidthsOffered = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;string&gt; peeringLocations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderBandwidthsOffered&gt; bandwidthsOffered, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderBandwidthsOffered},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional peeringLocations As IList(Of String) = null, Optional bandwidthsOffered As IList(Of ExpressRouteServiceProviderBandwidthsOffered) = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderBandwidthsOffered&gt; * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner (location, id, name, type, tags, peeringLocations, bandwidthsOffered, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="peeringLocations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="bandwidthsOffered" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderBandwidthsOffered&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="peeringLocations"><span data-ttu-id="fe036-103">Ruft eine Liste der peering Speicherorte.</span><span class="sxs-lookup"><span data-stu-id="fe036-103">Get a list of peering locations.</span></span></param>
        <param name="bandwidthsOffered"><span data-ttu-id="fe036-104">Ruft die Bandbreiten-angeboten.</span><span class="sxs-lookup"><span data-stu-id="fe036-104">Gets bandwidths offered.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="fe036-105">Ruft den Bereitstellungsstatus der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="fe036-105">Gets the provisioning state of the resource.</span></span></param>
        <summary>
            <span data-ttu-id="fe036-106">Initialisiert eine neue Instanz der ExpressRouteServiceProviderInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fe036-106">Initializes a new instance of the ExpressRouteServiceProviderInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BandwidthsOffered">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderBandwidthsOffered&gt; BandwidthsOffered { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderBandwidthsOffered&gt; BandwidthsOffered" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner.BandwidthsOffered" />
      <MemberSignature Language="VB.NET" Value="Public Property BandwidthsOffered As IList(Of ExpressRouteServiceProviderBandwidthsOffered)" />
      <MemberSignature Language="F#" Value="member this.BandwidthsOffered : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderBandwidthsOffered&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner.BandwidthsOffered" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.bandwidthsOffered")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderBandwidthsOffered&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe036-107">Ruft die Bandbreiten-angeboten.</span><span class="sxs-lookup"><span data-stu-id="fe036-107">Gets bandwidths offered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeeringLocations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; PeeringLocations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; PeeringLocations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner.PeeringLocations" />
      <MemberSignature Language="VB.NET" Value="Public Property PeeringLocations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PeeringLocations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner.PeeringLocations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.peeringLocations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe036-108">Erhalten eine Liste der peering-Speicherorte, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="fe036-108">Gets or sets get a list of peering locations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="fe036-109">Ruft den Bereitstellungsstatus der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="fe036-109">Gets the provisioning state of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>