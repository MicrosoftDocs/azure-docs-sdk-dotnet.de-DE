<Type Name="EffectiveNetworkSecurityGroup" FullName="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroup">
  <TypeSignature Language="C#" Value="public class EffectiveNetworkSecurityGroup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EffectiveNetworkSecurityGroup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class EffectiveNetworkSecurityGroup" />
  <TypeSignature Language="F#" Value="type EffectiveNetworkSecurityGroup = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c3a78-101">Effektive Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="c3a78-101">Effective network security group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveNetworkSecurityGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroup.#ctor" />
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
            <span data-ttu-id="c3a78-102">Initialisiert eine neue Instanz der EffectiveNetworkSecurityGroup-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c3a78-102">Initializes a new instance of the EffectiveNetworkSecurityGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveNetworkSecurityGroup (Microsoft.Azure.Management.Network.Models.SubResource networkSecurityGroup = null, Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation association = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule&gt; effectiveSecurityRules = null, System.Collections.Generic.IDictionary&lt;string,System.Collections.Generic.IList&lt;string&gt;&gt; tagMap = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Network.Models.SubResource networkSecurityGroup, class Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation association, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule&gt; effectiveSecurityRules, class System.Collections.Generic.IDictionary`2&lt;string, class System.Collections.Generic.IList`1&lt;string&gt;&gt; tagMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroup.#ctor(Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule},System.Collections.Generic.IDictionary{System.String,System.Collections.Generic.IList{System.String}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional networkSecurityGroup As SubResource = null, Optional association As EffectiveNetworkSecurityGroupAssociation = null, Optional effectiveSecurityRules As IList(Of EffectiveNetworkSecurityRule) = null, Optional tagMap As IDictionary(Of String, IList(Of String)) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroup : Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule&gt; * System.Collections.Generic.IDictionary&lt;string, System.Collections.Generic.IList&lt;string&gt;&gt; -&gt; Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroup" Usage="new Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroup (networkSecurityGroup, association, effectiveSecurityRules, tagMap)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="networkSecurityGroup" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="association" Type="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation" />
        <Parameter Name="effectiveSecurityRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule&gt;" />
        <Parameter Name="tagMap" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Collections.Generic.IList&lt;System.String&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="networkSecurityGroup"><span data-ttu-id="c3a78-103">Die ID der Netzwerksicherheitsgruppe, die angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="c3a78-103">The ID of network security group that is applied.</span></span></param>
        <param name="association"><span data-ttu-id="c3a78-104">Zugehörige Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="c3a78-104">Associated resources.</span></span></param>
        <param name="effectiveSecurityRules"><span data-ttu-id="c3a78-105">Eine Auflistung von effektive Sicherheitsregeln.</span><span class="sxs-lookup"><span data-stu-id="c3a78-105">A collection of effective security rules.</span></span></param>
        <param name="tagMap"><span data-ttu-id="c3a78-106">Zuordnung von Tags aus, um die Liste der IP-Adressen innerhalb des Tags enthalten.</span><span class="sxs-lookup"><span data-stu-id="c3a78-106">Mapping of tags to list of IP Addresses included within the tag.</span></span></param>
        <summary>
            <span data-ttu-id="c3a78-107">Initialisiert eine neue Instanz der EffectiveNetworkSecurityGroup-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c3a78-107">Initializes a new instance of the EffectiveNetworkSecurityGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Association">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation Association { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation Association" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroup.Association" />
      <MemberSignature Language="VB.NET" Value="Public Property Association As EffectiveNetworkSecurityGroupAssociation" />
      <MemberSignature Language="F#" Value="member this.Association : Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroup.Association" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="association")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3a78-108">Ruft ab, oder legt ihn fest zugeordnete Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="c3a78-108">Gets or sets associated resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EffectiveSecurityRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule&gt; EffectiveSecurityRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule&gt; EffectiveSecurityRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroup.EffectiveSecurityRules" />
      <MemberSignature Language="VB.NET" Value="Public Property EffectiveSecurityRules As IList(Of EffectiveNetworkSecurityRule)" />
      <MemberSignature Language="F#" Value="member this.EffectiveSecurityRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroup.EffectiveSecurityRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="effectiveSecurityRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3a78-109">Ermittelt oder definiert eine Auflistung von effektive Sicherheitsregeln.</span><span class="sxs-lookup"><span data-stu-id="c3a78-109">Gets or sets a collection of effective security rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource NetworkSecurityGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource NetworkSecurityGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroup.NetworkSecurityGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkSecurityGroup As SubResource" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroup : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroup.NetworkSecurityGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkSecurityGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3a78-110">Ruft ab oder legt die ID der Netzwerksicherheitsgruppe, die angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="c3a78-110">Gets or sets the ID of network security group that is applied.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TagMap">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,System.Collections.Generic.IList&lt;string&gt;&gt; TagMap { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class System.Collections.Generic.IList`1&lt;string&gt;&gt; TagMap" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroup.TagMap" />
      <MemberSignature Language="VB.NET" Value="Public Property TagMap As IDictionary(Of String, IList(Of String))" />
      <MemberSignature Language="F#" Value="member this.TagMap : System.Collections.Generic.IDictionary&lt;string, System.Collections.Generic.IList&lt;string&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroup.TagMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tagMap")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Collections.Generic.IList&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3a78-111">Ermittelt oder definiert die Zuordnung von Tags zur Liste der IP-Adressen innerhalb des Tags enthalten.</span><span class="sxs-lookup"><span data-stu-id="c3a78-111">Gets or sets mapping of tags to list of IP Addresses included within the tag.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>