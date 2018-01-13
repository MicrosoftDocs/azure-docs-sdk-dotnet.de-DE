<Type Name="VerificationIPFlowParametersInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner">
  <TypeSignature Language="C#" Value="public class VerificationIPFlowParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VerificationIPFlowParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class VerificationIPFlowParametersInner" />
  <TypeSignature Language="F#" Value="type VerificationIPFlowParametersInner = class" />
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
            Parameter, die den IP-Nachrichtenfluss zu prüfende definieren.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VerificationIPFlowParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VerificationIPFlowParametersInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VerificationIPFlowParametersInner (string targetResourceId, string direction, string protocol, string localPort, string remotePort, string localIPAddress, string remoteIPAddress, string targetNicResourceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetResourceId, string direction, string protocol, string localPort, string remotePort, string localIPAddress, string remoteIPAddress, string targetNicResourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetResourceId As String, direction As String, protocol As String, localPort As String, remotePort As String, localIPAddress As String, remoteIPAddress As String, Optional targetNicResourceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner (targetResourceId, direction, protocol, localPort, remotePort, localIPAddress, remoteIPAddress, targetNicResourceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="direction" Type="System.String" />
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="localPort" Type="System.String" />
        <Parameter Name="remotePort" Type="System.String" />
        <Parameter Name="localIPAddress" Type="System.String" />
        <Parameter Name="remoteIPAddress" Type="System.String" />
        <Parameter Name="targetNicResourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetResourceId">Die ID der Zielressource Nächster Hop auf ausführen.</param>
        <param name="direction">Die Richtung des Pakets als ein 5-Tupel dargestellt. Folgende Werte sind möglich: "Inbound", "Ausgehend"</param>
        <param name="protocol">Protokoll auf überprüft werden. Folgende Werte sind möglich: "TCP", "UDP"</param>
        <param name="localPort">Der lokale Port. Zulässige Werte sind eine einzelne ganze Zahl im Bereich (0-65535). Unterstützung für * für den Quellport abhängig von der Richtung.</param>
        <param name="remotePort">Der Remoteport. Zulässige Werte sind eine einzelne ganze Zahl im Bereich (0-65535). Unterstützung für * für den Quellport abhängig von der Richtung.</param>
        <param name="localIPAddress">Die lokale IP-Adresse. Zulässige Werte sind gültige IPv4-Adressen.</param>
        <param name="remoteIPAddress">Die IP-Remoteadresse. Zulässige Werte sind gültige IPv4-Adressen.</param>
        <param name="targetNicResourceId">Der NIC-ID. (Wenn der virtuelle Computer mehrere NICs hat, und IP-Weiterleitung für ein beliebiges von ihnen aktiviert ist, muss dann dieser Parameter angegeben werden. Andernfalls optional).</param>
        <summary>
            Initialisiert eine neue Instanz der VerificationIPFlowParametersInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Direction">
      <MemberSignature Language="C#" Value="public string Direction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Direction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.Direction" />
      <MemberSignature Language="VB.NET" Value="Public Property Direction As String" />
      <MemberSignature Language="F#" Value="member this.Direction : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.Direction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            Ruft ab oder legt die Richtung des Pakets als ein 5-Tupel dargestellt.
            Folgende Werte sind möglich: "Inbound", "Ausgehend"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalIPAddress">
      <MemberSignature Language="C#" Value="public string LocalIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.LocalIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.LocalIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.LocalIPAddress" />
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
            Ruft ab oder legt die lokale IP-Adresse. Zulässige Werte sind gültige IPv4-Adressen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalPort">
      <MemberSignature Language="C#" Value="public string LocalPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.LocalPort" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalPort As String" />
      <MemberSignature Language="F#" Value="member this.LocalPort : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.LocalPort" />
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
            Ruft ab oder legt den lokalen Port. Zulässige Werte sind eine einzelne ganze Zahl im Bereich (0-65535). Unterstützung für * für den Quellport abhängig von der Richtung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.Protocol" />
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
            Ruft ab, oder legt sie fest, die auf überprüft werden. Folgende Werte sind möglich: "TCP", "UDP"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteIPAddress">
      <MemberSignature Language="C#" Value="public string RemoteIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.RemoteIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.RemoteIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.RemoteIPAddress" />
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
            Ruft ab oder legt die IP-Remoteadresse. Zulässige Werte sind gültige IPv4-Adressen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotePort">
      <MemberSignature Language="C#" Value="public string RemotePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemotePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.RemotePort" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotePort As String" />
      <MemberSignature Language="F#" Value="member this.RemotePort : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.RemotePort" />
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
            Ruft ab oder legt den Remoteport. Zulässige Werte sind eine einzelne ganze Zahl im Bereich (0-65535). Unterstützung für * für den Quellport abhängig von der Richtung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetNicResourceId">
      <MemberSignature Language="C#" Value="public string TargetNicResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetNicResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.TargetNicResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetNicResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetNicResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.TargetNicResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetNicResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die NIC ID. (Wenn der virtuelle Computer mehrere NICs hat, und IP-Weiterleitung für ein beliebiges von ihnen aktiviert ist, muss dann dieser Parameter angegeben werden.
            Andernfalls optional).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceId">
      <MemberSignature Language="C#" Value="public string TargetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.TargetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.TargetResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ID der Zielressource Nächster Hop auf ausführen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="verificationIPFlowParametersInner.Validate " />
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