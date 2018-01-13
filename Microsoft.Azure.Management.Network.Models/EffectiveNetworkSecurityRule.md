<Type Name="EffectiveNetworkSecurityRule" FullName="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule">
  <TypeSignature Language="C#" Value="public class EffectiveNetworkSecurityRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EffectiveNetworkSecurityRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule" />
  <TypeSignature Language="VB.NET" Value="Public Class EffectiveNetworkSecurityRule" />
  <TypeSignature Language="F#" Value="type EffectiveNetworkSecurityRule = class" />
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
            Effektive Netzwerksicherheitsregeln.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveNetworkSecurityRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.#ctor" />
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
            Initialisiert eine neue Instanz der EffectiveNetworkSecurityRule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveNetworkSecurityRule (string name = null, string protocol = null, string sourcePortRange = null, string destinationPortRange = null, System.Collections.Generic.IList&lt;string&gt; sourcePortRanges = null, System.Collections.Generic.IList&lt;string&gt; destinationPortRanges = null, string sourceAddressPrefix = null, string destinationAddressPrefix = null, System.Collections.Generic.IList&lt;string&gt; sourceAddressPrefixes = null, System.Collections.Generic.IList&lt;string&gt; destinationAddressPrefixes = null, System.Collections.Generic.IList&lt;string&gt; expandedSourceAddressPrefix = null, System.Collections.Generic.IList&lt;string&gt; expandedDestinationAddressPrefix = null, string access = null, Nullable&lt;int&gt; priority = null, string direction = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string protocol, string sourcePortRange, string destinationPortRange, class System.Collections.Generic.IList`1&lt;string&gt; sourcePortRanges, class System.Collections.Generic.IList`1&lt;string&gt; destinationPortRanges, string sourceAddressPrefix, string destinationAddressPrefix, class System.Collections.Generic.IList`1&lt;string&gt; sourceAddressPrefixes, class System.Collections.Generic.IList`1&lt;string&gt; destinationAddressPrefixes, class System.Collections.Generic.IList`1&lt;string&gt; expandedSourceAddressPrefix, class System.Collections.Generic.IList`1&lt;string&gt; expandedDestinationAddressPrefix, string access, valuetype System.Nullable`1&lt;int32&gt; priority, string direction) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.String,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional protocol As String = null, Optional sourcePortRange As String = null, Optional destinationPortRange As String = null, Optional sourcePortRanges As IList(Of String) = null, Optional destinationPortRanges As IList(Of String) = null, Optional sourceAddressPrefix As String = null, Optional destinationAddressPrefix As String = null, Optional sourceAddressPrefixes As IList(Of String) = null, Optional destinationAddressPrefixes As IList(Of String) = null, Optional expandedSourceAddressPrefix As IList(Of String) = null, Optional expandedDestinationAddressPrefix As IList(Of String) = null, Optional access As String = null, Optional priority As Nullable(Of Integer) = null, Optional direction As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule : string * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * string * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule" Usage="new Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule (name, protocol, sourcePortRange, destinationPortRange, sourcePortRanges, destinationPortRanges, sourceAddressPrefix, destinationAddressPrefix, sourceAddressPrefixes, destinationAddressPrefixes, expandedSourceAddressPrefix, expandedDestinationAddressPrefix, access, priority, direction)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="sourcePortRange" Type="System.String" />
        <Parameter Name="destinationPortRange" Type="System.String" />
        <Parameter Name="sourcePortRanges" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="destinationPortRanges" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="sourceAddressPrefix" Type="System.String" />
        <Parameter Name="destinationAddressPrefix" Type="System.String" />
        <Parameter Name="sourceAddressPrefixes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="destinationAddressPrefixes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="expandedSourceAddressPrefix" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="expandedDestinationAddressPrefix" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="access" Type="System.String" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="direction" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Sicherheitsregel vom Benutzer angegeben wird (wenn vom Benutzer erstellt).</param>
        <param name="protocol">Das Netzwerkprotokoll, dem diese Regel gilt.
            Mögliche Werte sind: "Tcp", "Udp" und "All". Folgende Werte sind möglich: "Tcp", "Udp", "All"</param>
        <param name="sourcePortRange">Den Quellport oder -Bereich.</param>
        <param name="destinationPortRange">Den Zielport oder -Bereich.</param>
        <param name="sourcePortRanges">Die Quellbereiche Port. Den erwarteten Werten gehören eine einzelne ganze Zahl zwischen 0 und 65535 ein Bereich mit "-" als Trennzeichen (z. B. 100 bis 400), oder ein Sternchen (*)</param>
        <param name="destinationPortRanges">Der Ziel-Portbereiche.
            Den erwarteten Werten gehören eine einzelne ganze Zahl zwischen 0 und 65535 ein Bereich mit "-" als Trennzeichen (z. B. 100 bis 400), oder ein Sternchen (*)</param>
        <param name="sourceAddressPrefix">Das Adresspräfix "Quelle".</param>
        <param name="destinationAddressPrefix">Das Adresspräfix "Ziel".</param>
        <param name="sourceAddressPrefixes">Die Adresspräfixe "Quelle".
            Erwarteten Werten gehören CIDR IP Bereiche, Default Tags ("VirtualNetwork", "AureLoadBalancer", "Internet"), System Tags und das Sternchen (*).</param>
        <param name="destinationAddressPrefixes">Die Ziel-Adresspräfixe. Erwarteten Werten gehören CIDR IP Bereiche, Default Tags ("VirtualNetwork", "AureLoadBalancer", "Internet"), System Tags und das Sternchen (*).</param>
        <param name="expandedSourceAddressPrefix">Das Adresspräfix erweiterten Quelle.</param>
        <param name="expandedDestinationAddressPrefix">Erweiterte Zieladresspräfix.</param>
        <param name="access">Gibt an, ob Netzwerkdatenverkehr zugelassen oder verweigert wird.
            Mögliche Werte sind: "Zulassen" und "Verweigern". Folgende Werte sind möglich: "Zulassen", "Ablehnen"</param>
        <param name="priority">Die Priorität der Regel.</param>
        <param name="direction">Die Richtung der Regel. Mögliche Werte sind: "Eingehend und ausgehend". Folgende Werte sind möglich: "Inbound", "Ausgehend"</param>
        <summary>
            Initialisiert eine neue Instanz der EffectiveNetworkSecurityRule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public string Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As String" />
      <MemberSignature Language="F#" Value="member this.Access : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="access")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob Netzwerkdatenverkehr zugelassen oder verweigert wird. Mögliche Werte sind: "Zulassen" und "Verweigern". Folgende Werte sind möglich: "Zulassen", "Ablehnen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationAddressPrefix">
      <MemberSignature Language="C#" Value="public string DestinationAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.DestinationAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.DestinationAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.DestinationAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destinationAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert das Zieladresspräfix.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationAddressPrefixes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DestinationAddressPrefixes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DestinationAddressPrefixes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.DestinationAddressPrefixes" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationAddressPrefixes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DestinationAddressPrefixes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.DestinationAddressPrefixes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destinationAddressPrefixes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Ziel-Adresspräfixe. Erwarteten Werten gehören CIDR IP Bereiche, Default Tags ("VirtualNetwork", "AureLoadBalancer", "Internet"), System Tags und das Sternchen (*).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationPortRange">
      <MemberSignature Language="C#" Value="public string DestinationPortRange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationPortRange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.DestinationPortRange" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationPortRange As String" />
      <MemberSignature Language="F#" Value="member this.DestinationPortRange : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.DestinationPortRange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destinationPortRange")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Zielport oder-Bereich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationPortRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DestinationPortRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DestinationPortRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.DestinationPortRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationPortRanges As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DestinationPortRanges : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.DestinationPortRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destinationPortRanges")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Ziel Portbereiche. Den erwarteten Werten gehören eine einzelne ganze Zahl zwischen 0 und 65535 ein Bereich mit "-" als Trennzeichen (z. B. 100 bis 400), oder ein Sternchen (*)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Direction">
      <MemberSignature Language="C#" Value="public string Direction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Direction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Direction" />
      <MemberSignature Language="VB.NET" Value="Public Property Direction As String" />
      <MemberSignature Language="F#" Value="member this.Direction : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Direction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="direction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Richtung der Regel fest. Mögliche Werte sind: "Eingehend und ausgehend". Folgende Werte sind möglich: "Inbound", "Ausgehend"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpandedDestinationAddressPrefix">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ExpandedDestinationAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ExpandedDestinationAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.ExpandedDestinationAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpandedDestinationAddressPrefix As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ExpandedDestinationAddressPrefix : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.ExpandedDestinationAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="expandedDestinationAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der erweiterten Zieladresspräfix.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpandedSourceAddressPrefix">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ExpandedSourceAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ExpandedSourceAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.ExpandedSourceAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpandedSourceAddressPrefix As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ExpandedSourceAddressPrefix : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.ExpandedSourceAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="expandedSourceAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert das Adresspräfix erweiterten Quelle.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt den Namen der Sicherheitsregel vom Benutzer angegeben wird (wenn vom Benutzer erstellt).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Priorität der Regel fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Netzwerkprotokoll, dem diese Regel gilt. Mögliche Werte sind: "Tcp", "Udp" und "All". Folgende Werte sind möglich: "Tcp", "Udp", "All"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAddressPrefix">
      <MemberSignature Language="C#" Value="public string SourceAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.SourceAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.SourceAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.SourceAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert das Adresspräfix der Quelle.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAddressPrefixes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SourceAddressPrefixes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SourceAddressPrefixes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.SourceAddressPrefixes" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceAddressPrefixes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SourceAddressPrefixes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.SourceAddressPrefixes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceAddressPrefixes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Quelle Adresspräfixe. Erwarteten Werten gehören CIDR IP Bereiche, Default Tags ("VirtualNetwork", "AureLoadBalancer", "Internet"), System Tags und das Sternchen (*).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourcePortRange">
      <MemberSignature Language="C#" Value="public string SourcePortRange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourcePortRange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.SourcePortRange" />
      <MemberSignature Language="VB.NET" Value="Public Property SourcePortRange As String" />
      <MemberSignature Language="F#" Value="member this.SourcePortRange : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.SourcePortRange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourcePortRange")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Quellport oder-Bereich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourcePortRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SourcePortRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SourcePortRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.SourcePortRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property SourcePortRanges As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SourcePortRanges : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.SourcePortRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourcePortRanges")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Quelle Portbereiche fest. Den erwarteten Werten gehören eine einzelne ganze Zahl zwischen 0 und 65535 ein Bereich mit "-" als Trennzeichen (z. B. 100 bis 400), oder ein Sternchen (*)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>