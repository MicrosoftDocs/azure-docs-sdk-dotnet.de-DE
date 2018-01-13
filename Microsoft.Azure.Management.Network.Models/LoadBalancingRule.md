<Type Name="LoadBalancingRule" FullName="Microsoft.Azure.Management.Network.Models.LoadBalancingRule">
  <TypeSignature Language="C#" Value="public class LoadBalancingRule : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LoadBalancingRule extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.LoadBalancingRule" />
  <TypeSignature Language="VB.NET" Value="Public Class LoadBalancingRule&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type LoadBalancingRule = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Eine lastenausgleichsregel für einen Lastenausgleich.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadBalancingRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.LoadBalancingRule.#ctor" />
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
            Initialisiert eine neue Instanz der LoadBalancingRule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadBalancingRule (string protocol, int frontendPort, string id = null, Microsoft.Azure.Management.Network.Models.SubResource frontendIPConfiguration = null, Microsoft.Azure.Management.Network.Models.SubResource backendAddressPool = null, Microsoft.Azure.Management.Network.Models.SubResource probe = null, string loadDistribution = null, Nullable&lt;int&gt; backendPort = null, Nullable&lt;int&gt; idleTimeoutInMinutes = null, Nullable&lt;bool&gt; enableFloatingIP = null, Nullable&lt;bool&gt; disableOutboundSnat = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string protocol, int32 frontendPort, string id, class Microsoft.Azure.Management.Network.Models.SubResource frontendIPConfiguration, class Microsoft.Azure.Management.Network.Models.SubResource backendAddressPool, class Microsoft.Azure.Management.Network.Models.SubResource probe, string loadDistribution, valuetype System.Nullable`1&lt;int32&gt; backendPort, valuetype System.Nullable`1&lt;int32&gt; idleTimeoutInMinutes, valuetype System.Nullable`1&lt;bool&gt; enableFloatingIP, valuetype System.Nullable`1&lt;bool&gt; disableOutboundSnat, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.LoadBalancingRule.#ctor(System.String,System.Int32,System.String,Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.SubResource,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (protocol As String, frontendPort As Integer, Optional id As String = null, Optional frontendIPConfiguration As SubResource = null, Optional backendAddressPool As SubResource = null, Optional probe As SubResource = null, Optional loadDistribution As String = null, Optional backendPort As Nullable(Of Integer) = null, Optional idleTimeoutInMinutes As Nullable(Of Integer) = null, Optional enableFloatingIP As Nullable(Of Boolean) = null, Optional disableOutboundSnat As Nullable(Of Boolean) = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.LoadBalancingRule : string * int * string * Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.SubResource * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.LoadBalancingRule" Usage="new Microsoft.Azure.Management.Network.Models.LoadBalancingRule (protocol, frontendPort, id, frontendIPConfiguration, backendAddressPool, probe, loadDistribution, backendPort, idleTimeoutInMinutes, enableFloatingIP, disableOutboundSnat, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="frontendPort" Type="System.Int32" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="frontendIPConfiguration" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="backendAddressPool" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="probe" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="loadDistribution" Type="System.String" />
        <Parameter Name="backendPort" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="idleTimeoutInMinutes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="enableFloatingIP" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="disableOutboundSnat" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol">Folgende Werte sind möglich: "Udp", "Tcp", "All"</param>
        <param name="frontendPort">Der Port für den externen Endpunkt. Portnummern für jede Regel müssen innerhalb des Lastenausgleichs eindeutig sein.
            Zulässige Werte liegen zwischen 0 und 65534 sein. Beachten Sie, dass der Wert 0 "Any-Port" aktiviert.</param>
        <param name="id">Ressourcen-ID</param>
        <param name="frontendIPConfiguration">Ein Verweis auf die Front-End-IP-Adressen.</param>
        <param name="backendAddressPool">Ein Verweis auf einen Pool von DIPs.
            Eingehender Datenverkehr wird nach dem Zufallsprinzip Lastenausgleich über IP-Adressen in der Back-End-IP-Adressen.</param>
        <param name="probe">Der Verweis der, in der Regel für Lastenausgleich des Load-Balancer-Test.</param>
        <param name="loadDistribution">Die Load-verteilungsrichtlinie für diese Regel. Mögliche Werte sind "Default", "%sourceip" und "SourceIPProtocol". Folgende Werte sind möglich: "Default", "%sourceip", "SourceIPProtocol"</param>
        <param name="backendPort">Der Port, der für interne Verbindungen am Endpunkt verwendet wird. Zulässige Werte liegen zwischen 0 und 65535 sein. Beachten Sie, dass der Wert 0 "Any-Port" aktiviert.</param>
        <param name="idleTimeoutInMinutes">Das Timeout für die TCP-Verbindung im Leerlauf. Der Wert kann zwischen 4 und 30 Minuten festgelegt werden. Der Standardwert ist 4 Minuten. Dieses Element wird nur verwendet, wenn das Protokoll auf TCP festgelegt ist.</param>
        <param name="enableFloatingIP">Konfiguriert den Endpunkt des virtuellen Computers für die floating-IP-Funktion erforderlich, um eine SQL-AlwaysOn-Verfügbarkeitsgruppe zu konfigurieren. Diese Einstellung ist erforderlich, wenn der SQL AlwaysOn-Verfügbarkeitsgruppen in SQLServer verwenden. Diese Einstellung kann nicht geändert werden, nachdem Sie den Endpunkt zu erstellen.</param>
        <param name="disableOutboundSnat">Konfiguriert SNAT für die virtuellen Computer im Back-End-Pool zu verwenden, die öffentliche IP-Adresse in das von der Regel für Lastenausgleich des Front-End angegeben.</param>
        <param name="provisioningState">Ruft den Bereitstellungsstatus der die öffentliche IP-Ressource ab. Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</param>
        <param name="name">Der Name der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist. Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</param>
        <param name="etag">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</param>
        <summary>
            Initialisiert eine neue Instanz der LoadBalancingRule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendAddressPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource BackendAddressPool { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource BackendAddressPool" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancingRule.BackendAddressPool" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendAddressPool As SubResource" />
      <MemberSignature Language="F#" Value="member this.BackendAddressPool : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancingRule.BackendAddressPool" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendAddressPool")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Verweis auf einen Pool von DIPs. Eingehender Datenverkehr wird nach dem Zufallsprinzip Lastenausgleich über IP-Adressen in der Back-End-IP-Adressen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BackendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BackendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancingRule.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BackendPort : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancingRule.BackendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt den Port für die interne Verbindungen am Endpunkt verwendet. Zulässige Werte liegen zwischen 0 und 65535 sein. Beachten Sie, dass der Wert 0 "Any-Port" aktiviert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableOutboundSnat">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DisableOutboundSnat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DisableOutboundSnat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancingRule.DisableOutboundSnat" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableOutboundSnat As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DisableOutboundSnat : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancingRule.DisableOutboundSnat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.disableOutboundSnat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt konfiguriert SNAT für die virtuellen Computer im Back-End-Pool zu verwenden, die öffentliche IP-Adresse in das von der Regel für Lastenausgleich des Front-End angegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableFloatingIP">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableFloatingIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableFloatingIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancingRule.EnableFloatingIP" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableFloatingIP As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableFloatingIP : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancingRule.EnableFloatingIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancingRule.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancingRule.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource FrontendIPConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource FrontendIPConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancingRule.FrontendIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendIPConfiguration As SubResource" />
      <MemberSignature Language="F#" Value="member this.FrontendIPConfiguration : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancingRule.FrontendIPConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendIPConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
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
      <MemberSignature Language="C#" Value="public int FrontendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancingRule.FrontendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPort As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPort : int with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancingRule.FrontendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Port für den externen Endpunkt fest. Portnummern für jede Regel müssen innerhalb des Lastenausgleichs eindeutig sein. Zulässige Werte liegen zwischen 0 und 65534 sein. Beachten Sie, dass der Wert 0 "Any-Port" aktiviert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IdleTimeoutInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IdleTimeoutInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancingRule.IdleTimeoutInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property IdleTimeoutInMinutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IdleTimeoutInMinutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancingRule.IdleTimeoutInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
    <Member MemberName="LoadDistribution">
      <MemberSignature Language="C#" Value="public string LoadDistribution { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LoadDistribution" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancingRule.LoadDistribution" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadDistribution As String" />
      <MemberSignature Language="F#" Value="member this.LoadDistribution : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancingRule.LoadDistribution" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadDistribution")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert die verteilungsrichtlinie Last für diese Regel. Mögliche Werte sind "Default", "%sourceip" und "SourceIPProtocol". Folgende Werte sind möglich: "Default", "%sourceip", "SourceIPProtocol"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancingRule.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancingRule.Name" />
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
            Ruft ab oder legt den Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist. Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Probe">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource Probe { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource Probe" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancingRule.Probe" />
      <MemberSignature Language="VB.NET" Value="Public Property Probe As SubResource" />
      <MemberSignature Language="F#" Value="member this.Probe : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancingRule.Probe" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.probe")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Verweis der lastenausgleichsüberprüfung, die von der lastenausgleichsregel verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancingRule.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancingRule.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt folgende Werte möglich sind: "Udp", "Tcp", "All"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancingRule.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancingRule.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft den Bereitstellungsstatus der die öffentliche IP-Ressource ab. Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.LoadBalancingRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="loadBalancingRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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