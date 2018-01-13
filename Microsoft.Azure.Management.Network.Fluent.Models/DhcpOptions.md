<Type Name="DhcpOptions" FullName="Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions">
  <TypeSignature Language="C#" Value="public class DhcpOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DhcpOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class DhcpOptions" />
  <TypeSignature Language="F#" Value="type DhcpOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="714bd-101">DhcpOptions enthält ein Array von DNS-Server im virtuellen Netzwerk bereitgestellten virtuellen Maschinen zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="714bd-101">DhcpOptions contains an array of DNS servers available to VMs deployed in the virtual network.</span></span> <span data-ttu-id="714bd-102">Standard-DHCP-Option für ein Subnetz überschreibt VNET DHCP-Optionen.</span><span class="sxs-lookup"><span data-stu-id="714bd-102">Standard DHCP option for a subnet overrides VNET DHCP options.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DhcpOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="714bd-103">Initialisiert eine neue Instanz der DhcpOptions-Klasse.</span><span class="sxs-lookup"><span data-stu-id="714bd-103">Initializes a new instance of the DhcpOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DhcpOptions (System.Collections.Generic.IList&lt;string&gt; dnsServers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; dnsServers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions.#ctor(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dnsServers As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions dnsServers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dnsServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="dnsServers"><span data-ttu-id="714bd-104">Die Liste der IP-Adressen von DNS-Server.</span><span class="sxs-lookup"><span data-stu-id="714bd-104">The list of DNS servers IP addresses.</span></span></param>
        <summary>
            <span data-ttu-id="714bd-105">Initialisiert eine neue Instanz der DhcpOptions-Klasse.</span><span class="sxs-lookup"><span data-stu-id="714bd-105">Initializes a new instance of the DhcpOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DnsServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DnsServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions.DnsServers" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DnsServers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions.DnsServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dnsServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="714bd-106">Ruft ab oder legt die Liste der DNS-Server IP-Adressen.</span><span class="sxs-lookup"><span data-stu-id="714bd-106">Gets or sets the list of DNS servers IP addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>