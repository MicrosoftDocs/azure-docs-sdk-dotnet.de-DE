<Type Name="ProbeInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner">
  <TypeSignature Language="C#" Value="public class ProbeInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProbeInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ProbeInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ProbeInner = class&#xA;    inherit SubResource" />
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
            Ein Load Balancer-Test.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProbeInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ProbeInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProbeInner (string protocol, int port, string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; loadBalancingRules = null, Nullable&lt;int&gt; intervalInSeconds = null, Nullable&lt;int&gt; numberOfProbes = null, string requestPath = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string protocol, int32 port, string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; loadBalancingRules, valuetype System.Nullable`1&lt;int32&gt; intervalInSeconds, valuetype System.Nullable`1&lt;int32&gt; numberOfProbes, string requestPath, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.#ctor(System.String,System.Int32,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Fluent.SubResource},System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (protocol As String, port As Integer, Optional id As String = null, Optional loadBalancingRules As IList(Of SubResource) = null, Optional intervalInSeconds As Nullable(Of Integer) = null, Optional numberOfProbes As Nullable(Of Integer) = null, Optional requestPath As String = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner : string * int * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner (protocol, port, id, loadBalancingRules, intervalInSeconds, numberOfProbes, requestPath, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="port" Type="System.Int32" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="loadBalancingRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;" />
        <Parameter Name="intervalInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="numberOfProbes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requestPath" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol">Das Protokoll des Endpunkts an. Mögliche Werte sind: "Http" oder "Tcp". Wenn "Tcp" angegeben wird, ist eine empfangene Bestätigung erforderlich, damit der Test erfolgreich ist. Wenn "Http" angegeben wird, eine 200 OK-Antwort von der gibt der URI ist erforderlich, damit der Test erfolgreich ist. Folgende Werte sind möglich: "Http", "Tcp"</param>
        <param name="port">Der Port für die Übertragung des Tests. Mögliche Werte reichen von 1 bis einschließlich 65535.</param>
        <param name="id">To be added.</param>
        <param name="loadBalancingRules">Der Load Balancer-Regeln, die diesen Test verwenden.</param>
        <param name="intervalInSeconds">Das Intervall in Sekunden, in dem der Endpunkt auf den Integritätsstatus getestet werden soll. In der Regel ist das Intervall etwas kleiner als die Hälfte des zugeordneten Zeitlimits (in Sekunden). Dies ermöglicht die Durchführung von zwei vollständigen Tests, bevor die Instanz von der Rotation ausgenommen wird. Der Standardwert beträgt 15, der Mindestwert 5.</param>
        <param name="numberOfProbes">Die Anzahl der Prüfpunkte Where auf, wenn keine Antwort führt dazu, beenden die weiteren Datenverkehr an den Endpunkt gesendet werden. Diese Werte zulässt, die ausgeführt werden Endpunkte aus der Rotation schneller oder langsamer als die typischen Zeiten in Azure.</param>
        <param name="requestPath">Der URI, mit dem der Integritätsstatus über den virtuellen Computer angefordert wird. Pfad ist erforderlich, wenn ein Protokoll auf http festgelegt ist.
            Andernfalls ist die Angabe nicht zulässig. Es gibt keinen Standardwert.</param>
        <param name="provisioningState">Ruft den Bereitstellungsstatus der öffentlichen IP-Ressource ab. Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</param>
        <param name="name">Ruft die Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist. Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</param>
        <param name="etag">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</param>
        <summary>
            Initialisiert eine neue Instanz der ProbeInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Etag" />
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
    <Member MemberName="IntervalInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IntervalInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IntervalInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.IntervalInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property IntervalInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IntervalInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.IntervalInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.intervalInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Intervall in Sekunden an, wie häufig den Endpunkt für den Integritätsstatus Prüfpunkt. In der Regel ist das Intervall etwas kleiner als die Hälfte des zugeordneten Zeitlimits (in Sekunden). Dies ermöglicht die Durchführung von zwei vollständigen Tests, bevor die Instanz von der Rotation ausgenommen wird.
            Der Standardwert beträgt 15, der Mindestwert 5.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancingRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; LoadBalancingRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; LoadBalancingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.LoadBalancingRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancingRules As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancingRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.LoadBalancingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancingRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Load Balancer-Regeln, die diesen Test verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Name" />
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
    <Member MemberName="NumberOfProbes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfProbes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfProbes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.NumberOfProbes" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfProbes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfProbes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.NumberOfProbes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberOfProbes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl von Where Prüfpunkte, wenn keine Antwort führt zu Datenverkehr an den Endpunkt gesendet werden.
            Diese Werte zulässt, die ausgeführt werden Endpunkte aus der Rotation schneller oder langsamer als die typischen Zeiten in Azure.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public int Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Integer" />
      <MemberSignature Language="F#" Value="member this.Port : int with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Port für die Kommunikation mit der Überprüfung. Mögliche Werte reichen von 1 bis einschließlich 65535.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Protocol" />
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
            Ruft ab oder legt das Protokoll des Endpunkts an. Mögliche Werte sind: "Http" oder "Tcp". Wenn "Tcp" angegeben wird, ist eine empfangene Bestätigung erforderlich, damit der Test erfolgreich ist. Wenn "Http" angegeben wird, eine 200 OK-Antwort von der gibt der URI ist erforderlich, damit der Test erfolgreich ist. Folgende Werte sind möglich: "Http", "Tcp"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.ProvisioningState" />
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
    <Member MemberName="RequestPath">
      <MemberSignature Language="C#" Value="public string RequestPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.RequestPath" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestPath As String" />
      <MemberSignature Language="F#" Value="member this.RequestPath : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.RequestPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den URI für die Anforderung des Integritätsstatus des virtuellen Computers verwendet.
            Pfad ist erforderlich, wenn ein Protokoll auf http festgelegt ist. Andernfalls ist die Angabe nicht zulässig. Es gibt keinen Standardwert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="probeInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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