<Type Name="VirtualMachineScaleSetUpdateIPConfiguration" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetUpdateIPConfiguration : Microsoft.Azure.Management.Compute.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetUpdateIPConfiguration extends Microsoft.Azure.Management.Compute.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetUpdateIPConfiguration&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetUpdateIPConfiguration = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Beschreibt eine virtuelle Maschine Skalierung Satz Netzwerkprofil des IP-Konfiguration.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetUpdateIPConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineScaleSetUpdateIPConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetUpdateIPConfiguration (string id = null, string name = null, Microsoft.Azure.Management.Compute.Models.ApiEntityReference subnet = null, Nullable&lt;bool&gt; primary = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration publicIPAddressConfiguration = null, string privateIPAddressVersion = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; applicationGatewayBackendAddressPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; loadBalancerBackendAddressPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; loadBalancerInboundNatPools = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, class Microsoft.Azure.Management.Compute.Models.ApiEntityReference subnet, valuetype System.Nullable`1&lt;bool&gt; primary, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration publicIPAddressConfiguration, string privateIPAddressVersion, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; applicationGatewayBackendAddressPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; loadBalancerBackendAddressPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; loadBalancerInboundNatPools) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.#ctor(System.String,System.String,Microsoft.Azure.Management.Compute.Models.ApiEntityReference,System.Nullable{System.Boolean},Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.SubResource},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.SubResource},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.SubResource})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional subnet As ApiEntityReference = null, Optional primary As Nullable(Of Boolean) = null, Optional publicIPAddressConfiguration As VirtualMachineScaleSetUpdatePublicIPAddressConfiguration = null, Optional privateIPAddressVersion As String = null, Optional applicationGatewayBackendAddressPools As IList(Of SubResource) = null, Optional loadBalancerBackendAddressPools As IList(Of SubResource) = null, Optional loadBalancerInboundNatPools As IList(Of SubResource) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration : string * string * Microsoft.Azure.Management.Compute.Models.ApiEntityReference * Nullable&lt;bool&gt; * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration (id, name, subnet, primary, publicIPAddressConfiguration, privateIPAddressVersion, applicationGatewayBackendAddressPools, loadBalancerBackendAddressPools, loadBalancerInboundNatPools)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.Compute.Models.ApiEntityReference" />
        <Parameter Name="primary" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="publicIPAddressConfiguration" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration" />
        <Parameter Name="privateIPAddressVersion" Type="System.String" />
        <Parameter Name="applicationGatewayBackendAddressPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;" />
        <Parameter Name="loadBalancerBackendAddressPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;" />
        <Parameter Name="loadBalancerInboundNatPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id</param>
        <param name="name">Der Name des IP-Konfiguration.</param>
        <param name="subnet">Das Subnetz.</param>
        <param name="primary">Gibt die primäre IP-Konfiguration an, für den Fall, dass die Netzwerkschnittstelle mit mehr als eine IP-Konfiguration hat.</param>
        <param name="publicIPAddressConfiguration">Die PublicIPAddressConfiguration.</param>
        <param name="privateIPAddressVersion">Von Api-Version 2017-03-30 darstellt oder höher, er, ob die spezifische IP-Konfiguration IPv4 oder IPv6 ist. Standardmäßig wird als IPv4 verwendet.
            Mögliche Werte sind: "IPv4" und "IPv6". Folgende Werte sind möglich: "IPv4", "IPv6"</param>
        <param name="applicationGatewayBackendAddressPools">Application Gateway Back-End-Adresspools.</param>
        <param name="loadBalancerBackendAddressPools">Load Balancer Back-End-Adresspools.</param>
        <param name="loadBalancerInboundNatPools">Der Load Balancer eingehende Nat-Pools an.</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineScaleSetUpdateIPConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationGatewayBackendAddressPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; ApplicationGatewayBackendAddressPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; ApplicationGatewayBackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.ApplicationGatewayBackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationGatewayBackendAddressPools As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.ApplicationGatewayBackendAddressPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.ApplicationGatewayBackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationGatewayBackendAddressPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Application Gateway Back-End-Adresspools.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerBackendAddressPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; LoadBalancerBackendAddressPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; LoadBalancerBackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.LoadBalancerBackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadBalancerBackendAddressPools As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerBackendAddressPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.LoadBalancerBackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancerBackendAddressPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Load Balancer Back-End-Adresspools.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerInboundNatPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; LoadBalancerInboundNatPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; LoadBalancerInboundNatPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.LoadBalancerInboundNatPools" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadBalancerInboundNatPools As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerInboundNatPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.LoadBalancerInboundNatPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancerInboundNatPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest der Load Balancer eingehende Nat-Pools.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt den Namen der IP-Konfiguration fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Primary">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Primary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Primary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.Primary" />
      <MemberSignature Language="VB.NET" Value="Public Property Primary As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Primary : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.Primary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die primäre IP-Konfiguration für den Fall, dass die Netzwerkschnittstelle mit mehr als eine IP-Konfiguration hat.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateIPAddressVersion">
      <MemberSignature Language="C#" Value="public string PrivateIPAddressVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateIPAddressVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.PrivateIPAddressVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateIPAddressVersion As String" />
      <MemberSignature Language="F#" Value="member this.PrivateIPAddressVersion : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.PrivateIPAddressVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privateIPAddressVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest-Api-Version 2017-03-30 verfügbar oder höher, stellt, ob die spezifische IP-Konfiguration IPv4 oder IPv6 ist dar.
            Standardmäßig wird als IPv4 verwendet.  Mögliche Werte sind: "IPv4" und "IPv6".
            Folgende Werte sind möglich: "IPv4", "IPv6"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAddressConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration PublicIPAddressConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration PublicIPAddressConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.PublicIPAddressConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicIPAddressConfiguration As VirtualMachineScaleSetUpdatePublicIPAddressConfiguration" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddressConfiguration : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.PublicIPAddressConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicIPAddressConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die PublicIPAddressConfiguration.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ApiEntityReference Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ApiEntityReference Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As ApiEntityReference" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.Compute.Models.ApiEntityReference with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.Subnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ApiEntityReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Subnetz.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetUpdateIPConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>