<Type Name="PacketCaptureFilter" FullName="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter">
  <TypeSignature Language="C#" Value="public class PacketCaptureFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PacketCaptureFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class PacketCaptureFilter" />
  <TypeSignature Language="F#" Value="type PacketCaptureFilter = class" />
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
            Filter für die erfassungsanforderung Paket angewendet werden. Es können mehrere Filter angewendet werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der PacketCaptureFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureFilter (string protocol = null, string localIPAddress = null, string remoteIPAddress = null, string localPort = null, string remotePort = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string protocol, string localIPAddress, string remoteIPAddress, string localPort, string remotePort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional protocol As String = null, Optional localIPAddress As String = null, Optional remoteIPAddress As String = null, Optional localPort As String = null, Optional remotePort As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter : string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter (protocol, localIPAddress, remoteIPAddress, localPort, remotePort)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="localIPAddress" Type="System.String" />
        <Parameter Name="remoteIPAddress" Type="System.String" />
        <Parameter Name="localPort" Type="System.String" />
        <Parameter Name="remotePort" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol">Protokoll auf gefiltert werden sollen. Folgende Werte sind möglich: "TCP", "UDP", "Alle"</param>
        <param name="localIPAddress">Lokale IP-Adresse auf gefiltert werden sollen.
            Notation: "127.0.0.1" für einzelne-Adresseintrag.
            "127.0.0.1-127.0.0.255" für den Bereich. "127.0.0.1;127.0.0.5"? für mehrere Einträge. Mehrere Bereiche, die derzeit nicht unterstützt. Mischen von Bereichen mit mehreren Einträgen, die derzeit nicht unterstützt. Standard = Null.</param>
        <param name="remoteIPAddress">Lokale IP-Adresse auf gefiltert werden sollen.
            Notation: "127.0.0.1" für einzelne-Adresseintrag.
            "127.0.0.1-127.0.0.255" für den Bereich. "127.0.0.1;127.0.0.5;" für mehrere Einträge. Mehrere Bereiche, die derzeit nicht unterstützt. Mischen von Bereichen mit mehreren Einträgen, die derzeit nicht unterstützt. Standard = Null.</param>
        <param name="localPort">Lokaler Port auf gefiltert werden sollen. Notation: nach Eingabe eines einzelnen Port "80". " 80-85" für den Bereich. "80, 443;" für mehrere Einträge. Mehrere Bereiche, die derzeit nicht unterstützt. Mischen von Bereichen mit mehreren Einträgen, die derzeit nicht unterstützt. Standard = Null.</param>
        <param name="remotePort">Der Remoteport auf gefiltert werden sollen. Notation: nach Eingabe eines einzelnen Port "80". " 80-85" für den Bereich. "80, 443;" für mehrere Einträge. Mehrere Bereiche, die derzeit nicht unterstützt. Mischen von Bereichen mit mehreren Einträgen, die derzeit nicht unterstützt. Standard = Null.</param>
        <summary>
            Initialisiert eine neue Instanz der PacketCaptureFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalIPAddress">
      <MemberSignature Language="C#" Value="public string LocalIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.LocalIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.LocalIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.LocalIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="localIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest lokale IP-Adresse auf gefiltert werden sollen. Notation: "127.0.0.1" für einzelne-Adresseintrag. "127.0.0.1-127.0.0.255" für den Bereich. "127.0.0.1;127.0.0.5"? für mehrere Einträge. Mehrere Bereiche, die derzeit nicht unterstützt. Mischen von Bereichen mit mehreren Einträgen, die derzeit nicht unterstützt. Standard = Null.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalPort">
      <MemberSignature Language="C#" Value="public string LocalPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.LocalPort" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalPort As String" />
      <MemberSignature Language="F#" Value="member this.LocalPort : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.LocalPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="localPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der lokalen Port gefiltert werden. Notation: nach Eingabe eines einzelnen Port "80". " 80-85" für den Bereich. "80, 443;" für mehrere Einträge. Mehrere Bereiche, die derzeit nicht unterstützt. Mischen von Bereichen mit mehreren Einträgen, die derzeit nicht unterstützt. Standard = Null.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            Ruft ab, oder legt sie fest, die gefiltert werden. Folgende Werte sind möglich: "TCP", "UDP", "Alle"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteIPAddress">
      <MemberSignature Language="C#" Value="public string RemoteIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.RemoteIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.RemoteIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.RemoteIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="remoteIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest lokale IP-Adresse auf gefiltert werden sollen. Notation: "127.0.0.1" für einzelne-Adresseintrag. "127.0.0.1-127.0.0.255" für den Bereich. "127.0.0.1;127.0.0.5;" für mehrere Einträge. Mehrere Bereiche, die derzeit nicht unterstützt. Mischen von Bereichen mit mehreren Einträgen, die derzeit nicht unterstützt. Standard = Null.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotePort">
      <MemberSignature Language="C#" Value="public string RemotePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemotePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.RemotePort" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotePort As String" />
      <MemberSignature Language="F#" Value="member this.RemotePort : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.RemotePort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="remotePort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Remoteport auf gefiltert werden sollen. Notation: nach Eingabe eines einzelnen Port "80". " 80-85" für den Bereich. "80, 443;" für mehrere Einträge. Mehrere Bereiche, die derzeit nicht unterstützt. Mischen von Bereichen mit mehreren Einträgen, die derzeit nicht unterstützt. Standard = Null.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>