<Type Name="NetworkAdapters" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters">
  <TypeSignature Language="C#" Value="public class NetworkAdapters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkAdapters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkAdapters" />
  <TypeSignature Language="F#" Value="type NetworkAdapters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Netzwerkadapter auf Gerät darstellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkAdapters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse Netzwerkadapter an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkAdapters (Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceId interfaceId, Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceStatus netInterfaceStatus, Microsoft.Azure.Management.StorSimple8000Series.Models.ISCSIAndCloudStatus iscsiAndCloudStatus, Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkMode mode, Nullable&lt;bool&gt; isDefault = null, Nullable&lt;long&gt; speed = null, Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv4 nicIpv4Settings = null, Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6 nicIpv6Settings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceId interfaceId, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceStatus netInterfaceStatus, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ISCSIAndCloudStatus iscsiAndCloudStatus, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkMode mode, valuetype System.Nullable`1&lt;bool&gt; isDefault, valuetype System.Nullable`1&lt;int64&gt; speed, class Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv4 nicIpv4Settings, class Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6 nicIpv6Settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceId,Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceStatus,Microsoft.Azure.Management.StorSimple8000Series.Models.ISCSIAndCloudStatus,Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkMode,System.Nullable{System.Boolean},System.Nullable{System.Int64},Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv4,Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters : Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceId * Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceStatus * Microsoft.Azure.Management.StorSimple8000Series.Models.ISCSIAndCloudStatus * Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkMode * Nullable&lt;bool&gt; * Nullable&lt;int64&gt; * Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv4 * Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6 -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters (interfaceId, netInterfaceStatus, iscsiAndCloudStatus, mode, isDefault, speed, nicIpv4Settings, nicIpv6Settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="interfaceId" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceId" />
        <Parameter Name="netInterfaceStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceStatus" />
        <Parameter Name="iscsiAndCloudStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ISCSIAndCloudStatus" />
        <Parameter Name="mode" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkMode" />
        <Parameter Name="isDefault" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="speed" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="nicIpv4Settings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv4" />
        <Parameter Name="nicIpv6Settings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6" />
      </Parameters>
      <Docs>
        <param name="interfaceId">Die ID des Netzwerkadapters. Folgende Werte sind möglich: "Ungültig", "Data0", "Data1", "Data2", "Data3", "Data4", "Data5"</param>
        <param name="netInterfaceStatus">Der Wert, der angibt, der Status des Netzwerkadapters. Folgende Werte sind möglich: "Enabled", "Disabled"</param>
        <param name="iscsiAndCloudStatus">Der Wert, der angibt, Cloud- und iSCSI-Status des Netzwerkadapters. Folgende Werte sind möglich: "Deaktiviert", "IscsiEnabled", "CloudEnabled", "IscsiAndCloudEnabled"</param>
        <param name="mode">Der Modus des Netzwerkadapters, IPv4, IPv6 oder beides. Folgende Werte sind möglich: "Ungültig", "IPV4" und "IPV6", "BOTH"</param>
        <param name="isDefault">Der Wert, der angibt, ob diese Instanz die Standardinstanz ist.</param>
        <param name="speed">Die Geschwindigkeit des Netzwerkadapters.</param>
        <param name="nicIpv4Settings">Die IPv4-Konfiguration des Netzwerkadapters.</param>
        <param name="nicIpv6Settings">Die IPv6-Konfiguration des Netzwerkadapters.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse Netzwerkadapter an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InterfaceId">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceId InterfaceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceId InterfaceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.InterfaceId" />
      <MemberSignature Language="VB.NET" Value="Public Property InterfaceId As NetInterfaceId" />
      <MemberSignature Language="F#" Value="member this.InterfaceId : Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceId with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.InterfaceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="interfaceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ID des Netzwerkadapters fest. Folgende Werte sind möglich: "Ungültig", "Data0", "Data1", "Data2", "Data3", "Data4", "Data5"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IscsiAndCloudStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ISCSIAndCloudStatus IscsiAndCloudStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ISCSIAndCloudStatus IscsiAndCloudStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.IscsiAndCloudStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property IscsiAndCloudStatus As ISCSIAndCloudStatus" />
      <MemberSignature Language="F#" Value="member this.IscsiAndCloudStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.ISCSIAndCloudStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.IscsiAndCloudStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="iscsiAndCloudStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ISCSIAndCloudStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest, der angibt, Cloud- und iSCSI-Status des Netzwerkadapters. Folgende Werte sind möglich: "Deaktiviert", "IscsiEnabled", "CloudEnabled", "IscsiAndCloudEnabled"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDefault">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDefault { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDefault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.IsDefault" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDefault As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDefault : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.IsDefault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isDefault")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest, der angibt, ob diese Instanz die Standardinstanz ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As NetworkMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkMode with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Modus des Netzwerkadapters, IPv4, IPv6 oder beides fest. Folgende Werte sind möglich: "Ungültig", "IPV4" und "IPV6", "BOTH"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetInterfaceStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceStatus NetInterfaceStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceStatus NetInterfaceStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.NetInterfaceStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property NetInterfaceStatus As NetInterfaceStatus" />
      <MemberSignature Language="F#" Value="member this.NetInterfaceStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.NetInterfaceStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="netInterfaceStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.NetInterfaceStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest, der angibt, der Status des Netzwerkadapters. Folgende Werte sind möglich: "Enabled", "Disabled"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NicIpv4Settings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv4 NicIpv4Settings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv4 NicIpv4Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.NicIpv4Settings" />
      <MemberSignature Language="VB.NET" Value="Public Property NicIpv4Settings As NicIPv4" />
      <MemberSignature Language="F#" Value="member this.NicIpv4Settings : Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv4 with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.NicIpv4Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nicIpv4Settings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv4</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die IPv4-Konfiguration des Netzwerkadapters fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NicIpv6Settings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6 NicIpv6Settings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6 NicIpv6Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.NicIpv6Settings" />
      <MemberSignature Language="VB.NET" Value="Public Property NicIpv6Settings As NicIPv6" />
      <MemberSignature Language="F#" Value="member this.NicIpv6Settings : Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6 with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.NicIpv6Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nicIpv6Settings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die IPv6-Konfiguration des Netzwerkadapters fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Speed">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Speed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Speed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.Speed" />
      <MemberSignature Language="VB.NET" Value="Public Property Speed As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Speed : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.Speed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="speed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Geschwindigkeit des Netzwerkadapters.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="networkAdapters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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