<Type Name="VpnDeviceScriptParameters" FullName="Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters">
  <TypeSignature Language="C#" Value="public class VpnDeviceScriptParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VpnDeviceScriptParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class VpnDeviceScriptParameters" />
  <TypeSignature Language="F#" Value="type VpnDeviceScriptParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            VPN-Gerät Skript Generation Konfigurationsparameter
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VpnDeviceScriptParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VpnDeviceScriptParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VpnDeviceScriptParameters (string vendor = null, string deviceFamily = null, string firmwareVersion = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vendor, string deviceFamily, string firmwareVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional vendor As String = null, Optional deviceFamily As String = null, Optional firmwareVersion As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters : string * string * string -&gt; Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters" Usage="new Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters (vendor, deviceFamily, firmwareVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vendor" Type="System.String" />
        <Parameter Name="deviceFamily" Type="System.String" />
        <Parameter Name="firmwareVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="vendor">Der Hersteller des VPN-Geräts.</param>
        <param name="deviceFamily">Die Gerätefamilie für das VPN-Gerät.</param>
        <param name="firmwareVersion">Die Firmwareversion für das VPN-Gerät.</param>
        <summary>
            Initialisiert eine neue Instanz der VpnDeviceScriptParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceFamily">
      <MemberSignature Language="C#" Value="public string DeviceFamily { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceFamily" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters.DeviceFamily" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceFamily As String" />
      <MemberSignature Language="F#" Value="member this.DeviceFamily : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters.DeviceFamily" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deviceFamily")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Gerätefamilie für das VPN-Gerät.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirmwareVersion">
      <MemberSignature Language="C#" Value="public string FirmwareVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FirmwareVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters.FirmwareVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property FirmwareVersion As String" />
      <MemberSignature Language="F#" Value="member this.FirmwareVersion : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters.FirmwareVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="firmwareVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Firmwareversion für das VPN-Gerät.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Vendor">
      <MemberSignature Language="C#" Value="public string Vendor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Vendor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters.Vendor" />
      <MemberSignature Language="VB.NET" Value="Public Property Vendor As String" />
      <MemberSignature Language="F#" Value="member this.Vendor : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters.Vendor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vendor")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Hersteller des VPN-Geräts.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>