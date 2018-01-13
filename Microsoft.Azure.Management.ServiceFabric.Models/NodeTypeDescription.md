<Type Name="NodeTypeDescription" FullName="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription">
  <TypeSignature Language="C#" Value="public class NodeTypeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeTypeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeTypeDescription" />
  <TypeSignature Language="F#" Value="type NodeTypeDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Beschreibt einen Knotentyp im Cluster, jeden Knotentyp Sub Satz von Knoten im Cluster darstellt
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeTypeDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der NodeTypeDescription-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeTypeDescription (string name, int clientConnectionEndpointPort, int httpGatewayEndpointPort, bool isPrimary, int vmInstanceCount, System.Collections.Generic.IDictionary&lt;string,string&gt; placementProperties = null, System.Collections.Generic.IDictionary&lt;string,string&gt; capacities = null, string durabilityLevel = null, Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription applicationPorts = null, Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription ephemeralPorts = null, Nullable&lt;int&gt; reverseProxyEndpointPort = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, int32 clientConnectionEndpointPort, int32 httpGatewayEndpointPort, bool isPrimary, int32 vmInstanceCount, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; placementProperties, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; capacities, string durabilityLevel, class Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription applicationPorts, class Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription ephemeralPorts, valuetype System.Nullable`1&lt;int32&gt; reverseProxyEndpointPort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.#ctor(System.String,System.Int32,System.Int32,System.Boolean,System.Int32,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription,Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, clientConnectionEndpointPort As Integer, httpGatewayEndpointPort As Integer, isPrimary As Boolean, vmInstanceCount As Integer, Optional placementProperties As IDictionary(Of String, String) = null, Optional capacities As IDictionary(Of String, String) = null, Optional durabilityLevel As String = null, Optional applicationPorts As EndpointRangeDescription = null, Optional ephemeralPorts As EndpointRangeDescription = null, Optional reverseProxyEndpointPort As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription : string * int * int * bool * int * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription * Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription (name, clientConnectionEndpointPort, httpGatewayEndpointPort, isPrimary, vmInstanceCount, placementProperties, capacities, durabilityLevel, applicationPorts, ephemeralPorts, reverseProxyEndpointPort)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="clientConnectionEndpointPort" Type="System.Int32" />
        <Parameter Name="httpGatewayEndpointPort" Type="System.Int32" />
        <Parameter Name="isPrimary" Type="System.Boolean" />
        <Parameter Name="vmInstanceCount" Type="System.Int32" />
        <Parameter Name="placementProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="capacities" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="durabilityLevel" Type="System.String" />
        <Parameter Name="applicationPorts" Type="Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription" />
        <Parameter Name="ephemeralPorts" Type="Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription" />
        <Parameter Name="reverseProxyEndpointPort" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Name des Knotentyps</param>
        <param name="clientConnectionEndpointPort">Der TCP-Cluster Management-Endpunkt-port</param>
        <param name="httpGatewayEndpointPort">Der HTTP-Cluster Management-Endpunkt-port</param>
        <param name="isPrimary">Markieren Sie dies als Typ des primären Knotens</param>
        <param name="vmInstanceCount">Geben Sie die Anzahl der Knoteninstanzen im Knoten ""</param>
        <param name="placementProperties">Der platzierungsmarkierungen angewendet, um Knoten in den Knotentyp, der verwendet werden kann, um anzugeben, in denen bestimmte Dienste (Workload) ausgeführt werden sollen</param>
        <param name="capacities">Die Kapazität-Tags, die auf die Knoten in der Knotentyp angewendet, verwendet die Clusterressourcen-Manager diese Tags um zu verstehen, wie viel von einer Ressource einen Knoten</param>
        <param name="durabilityLevel">Dauerhaftigkeit zur einfacheren NodeType Ebene. Folgende Werte sind möglich: "Bronze", "Silber", "Gold"</param>
        <param name="applicationPorts">Ports, die von Clientanwendungen verwendet werden.</param>
        <param name="ephemeralPorts">System zugewiesene Softwarepaket Anwendungsports</param>
        <param name="reverseProxyEndpointPort">Endpunkt, der durch reverse-Proxy verwendet wird.</param>
        <summary>
            Initialisiert eine neue Instanz der NodeTypeDescription-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPorts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription ApplicationPorts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription ApplicationPorts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.ApplicationPorts" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPorts As EndpointRangeDescription" />
      <MemberSignature Language="F#" Value="member this.ApplicationPorts : Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.ApplicationPorts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationPorts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest von Anwendungen verwendete ports
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Capacities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Capacities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.Capacities" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacities As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Capacities : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.Capacities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt angewendet Tags Kapazität auf die Knoten in der Knotentyp die Clusterressourcen-Manager verwendet diese tags, um zu verstehen, wie viel von einer Ressource einen Knoten
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientConnectionEndpointPort">
      <MemberSignature Language="C#" Value="public int ClientConnectionEndpointPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ClientConnectionEndpointPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.ClientConnectionEndpointPort" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientConnectionEndpointPort As Integer" />
      <MemberSignature Language="F#" Value="member this.ClientConnectionEndpointPort : int with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.ClientConnectionEndpointPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="clientConnectionEndpointPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die TCP-Cluster Management Endpunktport
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DurabilityLevel">
      <MemberSignature Language="C#" Value="public string DurabilityLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DurabilityLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.DurabilityLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property DurabilityLevel As String" />
      <MemberSignature Language="F#" Value="member this.DurabilityLevel : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.DurabilityLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="durabilityLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Nodetype Dauerhaftigkeit Ebene. Folgende Werte sind möglich: "Bronze", "Silber", "Gold"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EphemeralPorts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription EphemeralPorts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription EphemeralPorts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.EphemeralPorts" />
      <MemberSignature Language="VB.NET" Value="Public Property EphemeralPorts As EndpointRangeDescription" />
      <MemberSignature Language="F#" Value="member this.EphemeralPorts : Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.EphemeralPorts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ephemeralPorts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt System zugewiesene Softwarepaket Anwendungsports
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpGatewayEndpointPort">
      <MemberSignature Language="C#" Value="public int HttpGatewayEndpointPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HttpGatewayEndpointPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.HttpGatewayEndpointPort" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpGatewayEndpointPort As Integer" />
      <MemberSignature Language="F#" Value="member this.HttpGatewayEndpointPort : int with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.HttpGatewayEndpointPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="httpGatewayEndpointPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den HTTP-Cluster Management Endpunktport
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPrimary">
      <MemberSignature Language="C#" Value="public bool IsPrimary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPrimary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.IsPrimary" />
      <MemberSignature Language="VB.NET" Value="Public Property IsPrimary As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPrimary : bool with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.IsPrimary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isPrimary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest, dies als Typ des primären Knotens markieren
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt den Namen des Knotentyps fest
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlacementProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; PlacementProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; PlacementProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.PlacementProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property PlacementProperties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.PlacementProperties : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.PlacementProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="placementProperties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die platzierungsmarkierungen angewendet, um Knoten in den Knotentyp, der verwendet werden kann, um anzugeben, in denen bestimmte Dienste (Workload) ausgeführt werden sollen
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReverseProxyEndpointPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ReverseProxyEndpointPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ReverseProxyEndpointPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.ReverseProxyEndpointPort" />
      <MemberSignature Language="VB.NET" Value="Public Property ReverseProxyEndpointPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ReverseProxyEndpointPort : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.ReverseProxyEndpointPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reverseProxyEndpointPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Endpunkt, der durch reverse-Proxy verwendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="nodeTypeDescription.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
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
    <Member MemberName="VmInstanceCount">
      <MemberSignature Language="C#" Value="public int VmInstanceCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 VmInstanceCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.VmInstanceCount" />
      <MemberSignature Language="VB.NET" Value="Public Property VmInstanceCount As Integer" />
      <MemberSignature Language="F#" Value="member this.VmInstanceCount : int with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.VmInstanceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmInstanceCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Knoteninstanzen in der Knotentyp
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>