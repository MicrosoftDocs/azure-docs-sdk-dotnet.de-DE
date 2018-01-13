<Type Name="VirtualMachineScaleSetIPConfiguration" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetIPConfiguration : Microsoft.Azure.Management.Compute.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetIPConfiguration extends Microsoft.Azure.Management.Compute.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetIPConfiguration&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetIPConfiguration = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetIPConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.#ctor" />
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
            Initialisiert eine neue Instanz der VirtualMachineScaleSetIPConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetIPConfiguration (string name, string id = null, Microsoft.Azure.Management.Compute.Models.ApiEntityReference subnet = null, Nullable&lt;bool&gt; primary = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration publicIPAddressConfiguration = null, string privateIPAddressVersion = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; applicationGatewayBackendAddressPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; loadBalancerBackendAddressPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; loadBalancerInboundNatPools = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string id, class Microsoft.Azure.Management.Compute.Models.ApiEntityReference subnet, valuetype System.Nullable`1&lt;bool&gt; primary, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration publicIPAddressConfiguration, string privateIPAddressVersion, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; applicationGatewayBackendAddressPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; loadBalancerBackendAddressPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; loadBalancerInboundNatPools) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.#ctor(System.String,System.String,Microsoft.Azure.Management.Compute.Models.ApiEntityReference,System.Nullable{System.Boolean},Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.SubResource},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.SubResource},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.SubResource})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional id As String = null, Optional subnet As ApiEntityReference = null, Optional primary As Nullable(Of Boolean) = null, Optional publicIPAddressConfiguration As VirtualMachineScaleSetPublicIPAddressConfiguration = null, Optional privateIPAddressVersion As String = null, Optional applicationGatewayBackendAddressPools As IList(Of SubResource) = null, Optional loadBalancerBackendAddressPools As IList(Of SubResource) = null, Optional loadBalancerInboundNatPools As IList(Of SubResource) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration : string * string * Microsoft.Azure.Management.Compute.Models.ApiEntityReference * Nullable&lt;bool&gt; * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration (name, id, subnet, primary, publicIPAddressConfiguration, privateIPAddressVersion, applicationGatewayBackendAddressPools, loadBalancerBackendAddressPools, loadBalancerInboundNatPools)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.Compute.Models.ApiEntityReference" />
        <Parameter Name="primary" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="publicIPAddressConfiguration" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration" />
        <Parameter Name="privateIPAddressVersion" Type="System.String" />
        <Parameter Name="applicationGatewayBackendAddressPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;" />
        <Parameter Name="loadBalancerBackendAddressPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;" />
        <Parameter Name="loadBalancerInboundNatPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des IP-Konfiguration.</param>
        <param name="id">Ressourcen-Id</param>
        <param name="subnet">Gibt den Bezeichner des Subnetzes.</param>
        <param name="primary">Gibt die primäre Netzwerkschnittstelle an, für den Fall, dass der virtuelle Computer mehr als 1 Netzwerkschnittstelle hat.</param>
        <param name="publicIPAddressConfiguration">Die PublicIPAddressConfiguration.</param>
        <param name="privateIPAddressVersion">Von Api-Version 2017-03-30 darstellt oder höher, er, ob die spezifische IP-Konfiguration IPv4 oder IPv6 ist. Standardmäßig wird als IPv4 verwendet.
            Mögliche Werte sind: "IPv4" und "IPv6". Folgende Werte sind möglich: "IPv4", "IPv6"</param>
        <param name="applicationGatewayBackendAddressPools">Gibt ein Array von Verweisen auf Back-End-Adresspool des Anwendungsgateways an. Eine Skalierungsgruppe kann die Back-End-Adresspools von mehreren Anwendungsgateways verweisen. Mehrere skalierungsgruppen können nicht das gleiche Anwendungsgateway verwenden.</param>
        <param name="loadBalancerBackendAddressPools">Gibt ein Array von Verweisen auf Back-End-Adresspools der Lastenausgleichsmodule an. Eine Skalierungsgruppe kann die Back-End-Adresspools ein öffentlicher und ein interner Lastenausgleich verweisen. Mehrere kann nicht Skalierung der gleiche Load Balancer verwendet.</param>
        <param name="loadBalancerInboundNatPools">Gibt ein Array von Verweisen auf die eingehende Nat-Pools der Lastenausgleichsmodule an. Eine Skalierungsgruppe kann eingehende Nat-Pools mit einem öffentlichen und einen internen Lastenausgleich verweisen. Mehrere skalierungsgruppen können nicht demselben Lastenausgleich verwendet werden.</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineScaleSetIPConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationGatewayBackendAddressPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; ApplicationGatewayBackendAddressPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; ApplicationGatewayBackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.ApplicationGatewayBackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationGatewayBackendAddressPools As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.ApplicationGatewayBackendAddressPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.ApplicationGatewayBackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt gibt ein Array von Verweisen auf Back-End-Adresspool des Anwendungsgateways an. Eine Skalierungsgruppe kann die Back-End-Adresspools von mehreren Anwendungsgateways verweisen. Mehrere skalierungsgruppen können nicht das gleiche Anwendungsgateway verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerBackendAddressPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; LoadBalancerBackendAddressPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; LoadBalancerBackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.LoadBalancerBackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadBalancerBackendAddressPools As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerBackendAddressPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.LoadBalancerBackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt gibt ein Array von Verweisen auf Back-End-Adresspools der Lastenausgleichsmodule an. Eine Skalierungsgruppe kann die Back-End-Adresspools ein öffentlicher und ein interner Lastenausgleich verweisen. Mehrere kann nicht Skalierung der gleiche Load Balancer verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerInboundNatPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; LoadBalancerInboundNatPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; LoadBalancerInboundNatPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.LoadBalancerInboundNatPools" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadBalancerInboundNatPools As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerInboundNatPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.LoadBalancerInboundNatPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt gibt ein Array von Verweisen auf die eingehende Nat-Pools der Lastenausgleichsmodule an. Eine Skalierungsgruppe kann eingehende Nat-Pools mit einem öffentlichen und einen internen Lastenausgleich verweisen. Mehrere skalierungsgruppen können nicht demselben Lastenausgleich verwendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.Primary" />
      <MemberSignature Language="VB.NET" Value="Public Property Primary As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Primary : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.Primary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt gibt die primäre Netzwerkschnittstelle für den Fall, dass der virtuelle Computer mehr als 1 Netzwerkschnittstelle hat.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateIPAddressVersion">
      <MemberSignature Language="C#" Value="public string PrivateIPAddressVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateIPAddressVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.PrivateIPAddressVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateIPAddressVersion As String" />
      <MemberSignature Language="F#" Value="member this.PrivateIPAddressVersion : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.PrivateIPAddressVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration PublicIPAddressConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration PublicIPAddressConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.PublicIPAddressConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicIPAddressConfiguration As VirtualMachineScaleSetPublicIPAddressConfiguration" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddressConfiguration : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.PublicIPAddressConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicIPAddressConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As ApiEntityReference" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.Compute.Models.ApiEntityReference with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.Subnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt gibt den Bezeichner des Subnetzes an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetIPConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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