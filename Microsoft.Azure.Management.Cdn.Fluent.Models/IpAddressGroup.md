<Type Name="IpAddressGroup" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup">
  <TypeSignature Language="C#" Value="public class IpAddressGroup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IpAddressGroup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class IpAddressGroup" />
  <TypeSignature Language="F#" Value="type IpAddressGroup = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Gruppe der CDN-Ip-Adresse
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IpAddressGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der IpAddressGroup-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IpAddressGroup (string deliveryRegion = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress&gt; ipv4Addresses = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress&gt; ipv6Addresses = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deliveryRegion, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress&gt; ipv4Addresses, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress&gt; ipv6Addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress},System.Collections.Generic.IList{Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional deliveryRegion As String = null, Optional ipv4Addresses As IList(Of CidrIpAddress) = null, Optional ipv6Addresses As IList(Of CidrIpAddress) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup (deliveryRegion, ipv4Addresses, ipv6Addresses)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deliveryRegion" Type="System.String" />
        <Parameter Name="ipv4Addresses" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress&gt;" />
        <Parameter Name="ipv6Addresses" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress&gt;" />
      </Parameters>
      <Docs>
        <param name="deliveryRegion">Die Übermittlung Region der Gruppe "IP-Adresse"</param>
        <param name="ipv4Addresses">Die Liste der IP-v4-Adressen.</param>
        <param name="ipv6Addresses">Die Liste der IPv6-Adressen.</param>
        <summary>
            Initialisiert eine neue Instanz der IpAddressGroup-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeliveryRegion">
      <MemberSignature Language="C#" Value="public string DeliveryRegion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeliveryRegion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup.DeliveryRegion" />
      <MemberSignature Language="VB.NET" Value="Public Property DeliveryRegion As String" />
      <MemberSignature Language="F#" Value="member this.DeliveryRegion : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup.DeliveryRegion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deliveryRegion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Bereich der Übermittlung der Gruppe "IP-Adresse"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ipv4Addresses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress&gt; Ipv4Addresses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress&gt; Ipv4Addresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup.Ipv4Addresses" />
      <MemberSignature Language="VB.NET" Value="Public Property Ipv4Addresses As IList(Of CidrIpAddress)" />
      <MemberSignature Language="F#" Value="member this.Ipv4Addresses : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup.Ipv4Addresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipv4Addresses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der IP-v4-Adressen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ipv6Addresses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress&gt; Ipv6Addresses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress&gt; Ipv6Addresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup.Ipv6Addresses" />
      <MemberSignature Language="VB.NET" Value="Public Property Ipv6Addresses As IList(Of CidrIpAddress)" />
      <MemberSignature Language="F#" Value="member this.Ipv6Addresses : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup.Ipv6Addresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipv6Addresses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der IP-IPv6-Adressen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>