<Type Name="BgpServiceCommunity" FullName="Microsoft.Azure.Management.Network.Models.BgpServiceCommunity">
  <TypeSignature Language="C#" Value="public class BgpServiceCommunity : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BgpServiceCommunity extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.BgpServiceCommunity" />
  <TypeSignature Language="VB.NET" Value="Public Class BgpServiceCommunity&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type BgpServiceCommunity = class&#xA;    inherit Resource" />
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
            Community-Diensteigenschaften.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BgpServiceCommunity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.BgpServiceCommunity.#ctor" />
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
            Initialisiert eine neue Instanz der BgpServiceCommunity-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BgpServiceCommunity (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string serviceName = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BGPCommunity&gt; bgpCommunities = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string serviceName, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.BGPCommunity&gt; bgpCommunities) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.BgpServiceCommunity.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.BGPCommunity})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional serviceName As String = null, Optional bgpCommunities As IList(Of BGPCommunity) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.BgpServiceCommunity : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BGPCommunity&gt; -&gt; Microsoft.Azure.Management.Network.Models.BgpServiceCommunity" Usage="new Microsoft.Azure.Management.Network.Models.BgpServiceCommunity (id, name, type, location, tags, serviceName, bgpCommunities)" />
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
        <Parameter Name="serviceName" Type="System.String" />
        <Parameter Name="bgpCommunities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BGPCommunity&gt;" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-ID</param>
        <param name="name">Name der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="location">Der Ressourcenspeicherort.</param>
        <param name="tags">Ressourcentags.</param>
        <param name="serviceName">Der Name des Bgp-Community. z. B. Skype.</param>
        <param name="bgpCommunities">Ruft eine Liste der Bgp-Communitys.</param>
        <summary>
            Initialisiert eine neue Instanz der BgpServiceCommunity-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BgpCommunities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BGPCommunity&gt; BgpCommunities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.BGPCommunity&gt; BgpCommunities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BgpServiceCommunity.BgpCommunities" />
      <MemberSignature Language="VB.NET" Value="Public Property BgpCommunities As IList(Of BGPCommunity)" />
      <MemberSignature Language="F#" Value="member this.BgpCommunities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BGPCommunity&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.BgpServiceCommunity.BgpCommunities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.bgpCommunities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BGPCommunity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erhalten eine Liste der Bgp-Communitys, ruft ab oder legt ihn fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public string ServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BgpServiceCommunity.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.BgpServiceCommunity.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Bgp-Community. z. B. Skype.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>