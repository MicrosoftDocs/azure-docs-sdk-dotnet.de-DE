<Type Name="InboundNatRuleInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner">
  <TypeSignature Language="C#" Value="public class InboundNatRuleInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InboundNatRuleInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner" />
  <TypeSignature Language="VB.NET" Value="Public Class InboundNatRuleInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type InboundNatRuleInner = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Regel für eingehende NAT des Load Balancers.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatRuleInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der InboundNatRuleInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatRuleInner (string id = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource frontendIPConfiguration = null, Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner backendIPConfiguration = null, string protocol = null, Nullable&lt;int&gt; frontendPort = null, Nullable&lt;int&gt; backendPort = null, Nullable&lt;int&gt; idleTimeoutInMinutes = null, Nullable&lt;bool&gt; enableFloatingIP = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource frontendIPConfiguration, class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner backendIPConfiguration, string protocol, valuetype System.Nullable`1&lt;int32&gt; frontendPort, valuetype System.Nullable`1&lt;int32&gt; backendPort, valuetype System.Nullable`1&lt;int32&gt; idleTimeoutInMinutes, valuetype System.Nullable`1&lt;bool&gt; enableFloatingIP, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.#ctor(System.String,Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional frontendIPConfiguration As SubResource = null, Optional backendIPConfiguration As NetworkInterfaceIPConfigurationInner = null, Optional protocol As String = null, Optional frontendPort As Nullable(Of Integer) = null, Optional backendPort As Nullable(Of Integer) = null, Optional idleTimeoutInMinutes As Nullable(Of Integer) = null, Optional enableFloatingIP As Nullable(Of Boolean) = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner : string * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner (id, frontendIPConfiguration, backendIPConfiguration, protocol, frontendPort, backendPort, idleTimeoutInMinutes, enableFloatingIP, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="frontendIPConfiguration" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="backendIPConfiguration" Type="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner" />
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="frontendPort" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="backendPort" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="idleTimeoutInMinutes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="enableFloatingIP" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="frontendIPConfiguration">Ein Verweis auf die Front-End-IP-Adressen.</param>
        <param name="backendIPConfiguration">Ein Verweis auf eine private IP-Adresse für eine Netzwerkschnittstelle eines virtuellen Computers definiert. Mit dem Front-End-Port, der jede der Front-End-IP-Konfigurationen-Datenverkehr wird an die gesicherten IP-Adresse weitergeleitet.</param>
        <param name="protocol">Das Transportprotokoll für den Endpunkt.
            Mögliche Werte sind: "Udp" oder "Tcp". Folgende Werte sind möglich: "Udp", "Tcp"</param>
        <param name="frontendPort">Der Port für den externen Endpunkt. Portnummern für jede Regel müssen innerhalb des Lastenausgleichs eindeutig sein.
            Zulässige Werte zwischen 1 und 65534 sein.</param>
        <param name="backendPort">Der für den internen Endpunkt verwendete Port.
            Die zulässigen Werte reichen von 1 bis 65535.</param>
        <param name="idleTimeoutInMinutes">Das Timeout für die TCP-Verbindung im Leerlauf. Der Wert kann zwischen 4 und 30 Minuten festgelegt werden. Der Standardwert ist 4 Minuten. Dieses Element wird nur verwendet, wenn das Protokoll auf TCP festgelegt ist.</param>
        <param name="enableFloatingIP">Konfiguriert den Endpunkt des virtuellen Computers für die floating-IP-Funktion erforderlich, um eine SQL-AlwaysOn-Verfügbarkeitsgruppe zu konfigurieren. Diese Einstellung ist erforderlich, wenn der SQL AlwaysOn-Verfügbarkeitsgruppen in SQLServer verwenden. Diese Einstellung kann nicht geändert werden, nachdem Sie den Endpunkt zu erstellen.</param>
        <param name="provisioningState">Ruft den Bereitstellungsstatus der öffentlichen IP-Ressource ab. Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</param>
        <param name="name">Ruft die Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist. Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</param>
        <param name="etag">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</param>
        <summary>
            Initialisiert eine neue Instanz der InboundNatRuleInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner BackendIPConfiguration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner BackendIPConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.BackendIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackendIPConfiguration As NetworkInterfaceIPConfigurationInner" />
      <MemberSignature Language="F#" Value="member this.BackendIPConfiguration : Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.BackendIPConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendIPConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Verweis auf eine private IP-Adresse für eine Netzwerkschnittstelle eines virtuellen Computers definiert. Mit dem Front-End-Port, der jede der Front-End-IP-Konfigurationen-Datenverkehr wird an die gesicherten IP-Adresse weitergeleitet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BackendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BackendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BackendPort : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.BackendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Port für den internen Endpunkt verwendet. Die zulässigen Werte reichen von 1 bis 65535.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableFloatingIP">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableFloatingIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableFloatingIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.EnableFloatingIP" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableFloatingIP As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableFloatingIP : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.EnableFloatingIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableFloatingIP")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt konfiguriert eines virtuellen Computers den Endpunkt für die floating-IP-Funktion erforderlich, um eine SQL-AlwaysOn-Verfügbarkeitsgruppe zu konfigurieren. Diese Einstellung ist erforderlich, wenn der SQL AlwaysOn-Verfügbarkeitsgruppen in SQLServer verwenden. Diese Einstellung kann nicht geändert werden, nachdem Sie den Endpunkt zu erstellen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource FrontendIPConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource FrontendIPConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.FrontendIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendIPConfiguration As SubResource" />
      <MemberSignature Language="F#" Value="member this.FrontendIPConfiguration : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.FrontendIPConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendIPConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Verweis auf die Front-End-IP-Adressen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; FrontendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; FrontendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.FrontendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.FrontendPort : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.FrontendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Port für den externen Endpunkt fest. Portnummern für jede Regel müssen innerhalb des Lastenausgleichs eindeutig sein. Zulässige Werte zwischen 1 und 65534 sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IdleTimeoutInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IdleTimeoutInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.IdleTimeoutInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property IdleTimeoutInMinutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IdleTimeoutInMinutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.IdleTimeoutInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.idleTimeoutInMinutes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Timeout für die TCP-Verbindung im Leerlauf. Der Wert kann zwischen 4 und 30 Minuten festgelegt werden. Der Standardwert ist 4 Minuten.
            Dieses Element wird nur verwendet, wenn das Protokoll auf TCP festgelegt ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            Ruft die Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.
            Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Transportprotokoll für den Endpunkt. Mögliche Werte sind: "Udp" oder "Tcp". Folgende Werte sind möglich: "Udp", "Tcp"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Bereitstellungsstatus der öffentlichen IP-Ressource ab. Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>