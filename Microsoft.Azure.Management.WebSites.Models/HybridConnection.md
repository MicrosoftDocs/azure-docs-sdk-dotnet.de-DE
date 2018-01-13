<Type Name="HybridConnection" FullName="Microsoft.Azure.Management.WebSites.Models.HybridConnection">
  <TypeSignature Language="C#" Value="public class HybridConnection : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HybridConnection extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.HybridConnection" />
  <TypeSignature Language="VB.NET" Value="Public Class HybridConnection&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type HybridConnection = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Hybrid-Connection-Vertrag. Dient zum Konfigurieren einer Hybrid-Verbindung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HybridConnection.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der HybridConnection-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnection (string id = null, string name = null, string kind = null, string type = null, string serviceBusNamespace = null, string relayName = null, string relayArmUri = null, string hostname = null, Nullable&lt;int&gt; port = null, string sendKeyName = null, string sendKeyValue = null, string serviceBusSuffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string serviceBusNamespace, string relayName, string relayArmUri, string hostname, valuetype System.Nullable`1&lt;int32&gt; port, string sendKeyName, string sendKeyValue, string serviceBusSuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HybridConnection.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional serviceBusNamespace As String = null, Optional relayName As String = null, Optional relayArmUri As String = null, Optional hostname As String = null, Optional port As Nullable(Of Integer) = null, Optional sendKeyName As String = null, Optional sendKeyValue As String = null, Optional serviceBusSuffix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.HybridConnection : string * string * string * string * string * string * string * string * Nullable&lt;int&gt; * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.HybridConnection" Usage="new Microsoft.Azure.Management.WebSites.Models.HybridConnection (id, name, kind, type, serviceBusNamespace, relayName, relayArmUri, hostname, port, sendKeyName, sendKeyValue, serviceBusSuffix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="serviceBusNamespace" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="relayArmUri" Type="System.String" />
        <Parameter Name="hostname" Type="System.String" />
        <Parameter Name="port" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="sendKeyName" Type="System.String" />
        <Parameter Name="sendKeyValue" Type="System.String" />
        <Parameter Name="serviceBusSuffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id.</param>
        <param name="name">Ressourcenname.</param>
        <param name="kind">Die Art der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="serviceBusNamespace">Der Name des Service Bus-Namespace.</param>
        <param name="relayName">Der Name des Service Bus-Relay.</param>
        <param name="relayArmUri">Die ARM-URI, der Service Bus-Relay werden soll.</param>
        <param name="hostname">Der Hostname des Endpunkts.</param>
        <param name="port">Der Port des Endpunkts.</param>
        <param name="sendKeyName">Der Name des Schlüssels Service Bus Send-Berechtigungen besitzt. Hiermit wird die Service Bus zu authentifizieren.</param>
        <param name="sendKeyValue">Der Wert des Service Bus-Schlüssels. Hiermit wird die Service Bus zu authentifizieren. Verwenden Sie in ARM dieser Schlüssel nicht normal zurückgegeben werden stattdessen die POST-/listKeys API.</param>
        <param name="serviceBusSuffix">Das Suffix für den Servicebus-Endpunkt. Standardmäßig ist dies. *.Servicebus.Windows.NET</param>
        <summary>
            Initialisiert eine neue Instanz der HybridConnection-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Hostname">
      <MemberSignature Language="C#" Value="public string Hostname { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Hostname" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnection.Hostname" />
      <MemberSignature Language="VB.NET" Value="Public Property Hostname As String" />
      <MemberSignature Language="F#" Value="member this.Hostname : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnection.Hostname" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostname")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Hostnamen des Endpunkts.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnection.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Port : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnection.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Port des Endpunkts fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayArmUri">
      <MemberSignature Language="C#" Value="public string RelayArmUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RelayArmUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnection.RelayArmUri" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayArmUri As String" />
      <MemberSignature Language="F#" Value="member this.RelayArmUri : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnection.RelayArmUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.relayArmUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den ARM-URI an die Service Bus-Relay.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayName">
      <MemberSignature Language="C#" Value="public string RelayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RelayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnection.RelayName" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayName As String" />
      <MemberSignature Language="F#" Value="member this.RelayName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnection.RelayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.relayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Service Bus-Relay.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendKeyName">
      <MemberSignature Language="C#" Value="public string SendKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SendKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnection.SendKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SendKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SendKeyName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnection.SendKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sendKeyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Schlüssels Service Bus Send-Berechtigungen besitzt. Hiermit wird die Service Bus zu authentifizieren.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendKeyValue">
      <MemberSignature Language="C#" Value="public string SendKeyValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SendKeyValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnection.SendKeyValue" />
      <MemberSignature Language="VB.NET" Value="Public Property SendKeyValue As String" />
      <MemberSignature Language="F#" Value="member this.SendKeyValue : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnection.SendKeyValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sendKeyValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Wert für den Service Bus-Schlüssel. Hiermit wird die Service Bus zu authentifizieren. Verwenden Sie in ARM dieser Schlüssel nicht normal zurückgegeben werden stattdessen die POST-/listKeys API.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusNamespace">
      <MemberSignature Language="C#" Value="public string ServiceBusNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnection.ServiceBusNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusNamespace As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusNamespace : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnection.ServiceBusNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceBusNamespace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Service Bus-Namespace.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusSuffix">
      <MemberSignature Language="C#" Value="public string ServiceBusSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnection.ServiceBusSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusSuffix As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusSuffix : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnection.ServiceBusSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceBusSuffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Suffix für den Servicebus-Endpunkt. Standardmäßig ist dies. *.Servicebus.Windows.NET
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>