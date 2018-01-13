<Type Name="VirtualMachineScaleSetNetworkConfigurationDnsSettings" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetNetworkConfigurationDnsSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetNetworkConfigurationDnsSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetNetworkConfigurationDnsSettings" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetNetworkConfigurationDnsSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="35eaa-101">Beschreibt einen virtuellen Computer Skalierung legt Netzwerk-DNS-Konfigurationseinstellungen an.</span><span class="sxs-lookup"><span data-stu-id="35eaa-101">Describes a virtual machines scale sets network configuration's DNS settings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetNetworkConfigurationDnsSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="35eaa-102">Initialisiert eine neue Instanz der VirtualMachineScaleSetNetworkConfigurationDnsSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="35eaa-102">Initializes a new instance of the VirtualMachineScaleSetNetworkConfigurationDnsSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetNetworkConfigurationDnsSettings (System.Collections.Generic.IList&lt;string&gt; dnsServers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; dnsServers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings.#ctor(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dnsServers As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings dnsServers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dnsServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="dnsServers"><span data-ttu-id="35eaa-103">Liste der IP-Adressen von DNS-Server</span><span class="sxs-lookup"><span data-stu-id="35eaa-103">List of DNS servers IP addresses</span></span></param>
        <summary>
            <span data-ttu-id="35eaa-104">Initialisiert eine neue Instanz der VirtualMachineScaleSetNetworkConfigurationDnsSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="35eaa-104">Initializes a new instance of the VirtualMachineScaleSetNetworkConfigurationDnsSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DnsServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DnsServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings.DnsServers" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DnsServers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings.DnsServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="35eaa-105">Ruft ab oder legt die Liste der IP-Adressen von DNS-Server</span><span class="sxs-lookup"><span data-stu-id="35eaa-105">Gets or sets list of DNS servers IP addresses</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>