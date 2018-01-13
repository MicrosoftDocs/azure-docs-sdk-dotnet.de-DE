<Type Name="InboundNatPool" FullName="Microsoft.Azure.Management.Batch.Models.InboundNatPool">
  <TypeSignature Language="C#" Value="public class InboundNatPool" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InboundNatPool extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.InboundNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Class InboundNatPool" />
  <TypeSignature Language="F#" Value="type InboundNatPool = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine eingehende NAT-Pool, der verwendet werden kann, um bestimmte Ports auf Serverknoten in einem Batch-Pool extern zu behandeln.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatPool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.InboundNatPool.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse Pool an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatPool (string name, Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol protocol, int backendPort, int frontendPortRangeStart, int frontendPortRangeEnd, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule&gt; networkSecurityGroupRules = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol protocol, int32 backendPort, int32 frontendPortRangeStart, int32 frontendPortRangeEnd, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule&gt; networkSecurityGroupRules) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.InboundNatPool.#ctor(System.String,Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol,System.Int32,System.Int32,System.Int32,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, protocol As InboundEndpointProtocol, backendPort As Integer, frontendPortRangeStart As Integer, frontendPortRangeEnd As Integer, Optional networkSecurityGroupRules As IList(Of NetworkSecurityGroupRule) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.InboundNatPool : string * Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol * int * int * int * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule&gt; -&gt; Microsoft.Azure.Management.Batch.Models.InboundNatPool" Usage="new Microsoft.Azure.Management.Batch.Models.InboundNatPool (name, protocol, backendPort, frontendPortRangeStart, frontendPortRangeEnd, networkSecurityGroupRules)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="protocol" Type="Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol" />
        <Parameter Name="backendPort" Type="System.Int32" />
        <Parameter Name="frontendPortRangeStart" Type="System.Int32" />
        <Parameter Name="frontendPortRangeEnd" Type="System.Int32" />
        <Parameter Name="networkSecurityGroupRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Endpunkts.</param>
        <param name="protocol">Das Protokoll des Endpunkts.</param>
        <param name="backendPort">Die Nummer des Ports auf den Computeknoten.</param>
        <param name="frontendPortRangeStart">Die erste Portnummer im Bereich des externen Ports, die verwendet wird, um eingehenden Zugriff auf die BackendPort auf einzelne Serverknoten bereitzustellen.</param>
        <param name="frontendPortRangeEnd">Die letzten Portnummer im Bereich des externen Ports, die verwendet wird, um eingehenden Zugriff auf die BackendPort auf einzelne Serverknoten bereitzustellen.</param>
        <param name="networkSecurityGroupRules">Eine Liste von Netzwerksicherheits-Gruppenregeln, die an den Endpunkt angewendet werden.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse Pool an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendPort">
      <MemberSignature Language="C#" Value="public int BackendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 BackendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.InboundNatPool.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendPort As Integer" />
      <MemberSignature Language="F#" Value="member this.BackendPort : int with get, set" Usage="Microsoft.Azure.Management.Batch.Models.InboundNatPool.BackendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backendPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Portnummer auf dem Computeknoten.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies muss in einem Batch-Pool eindeutig sein. Zulässige Werte liegen zwischen 1 und 65535, außer für 22, 3389, 29876 und 29877 wie diese reserviert sind. Ggf. reserviert werden die Werte bereitgestellt, die Anforderung mit HTTP-Statuscode 400 ein Fehler auftritt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeEnd">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeEnd { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.InboundNatPool.FrontendPortRangeEnd" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPortRangeEnd As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeEnd : int with get, set" Usage="Microsoft.Azure.Management.Batch.Models.InboundNatPool.FrontendPortRangeEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="frontendPortRangeEnd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die letzten Portnummer im Bereich von externen Ports, die verwendet wird, um eingehenden Zugriff auf die BackendPort auf einzelne Serverknoten bereitzustellen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Zulässige Werte zwischen 1 und 65534 außer Ports von 50000 55000 der Batch-Dienst reserviert sind. Alle Bereiche in einem Pool müssen eindeutig sein und dürfen sich nicht überschneiden. Wenn alle reservierten oder überlappende Werte, dass die Anforderung mit HTTP-Statuscode 400 schlägt fehl bereitgestellt werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeStart">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeStart { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.InboundNatPool.FrontendPortRangeStart" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPortRangeStart As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeStart : int with get, set" Usage="Microsoft.Azure.Management.Batch.Models.InboundNatPool.FrontendPortRangeStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="frontendPortRangeStart")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die erste Portnummer im Bereich von externen Ports, die verwendet wird, um eingehenden Zugriff auf die BackendPort auf einzelne Serverknoten bereitzustellen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die zulässigen Werte-Bereich zwischen 1 und 65534 außer Ports von 50000 55000 die reserviert sind. Alle Bereiche in einem Pool müssen eindeutig sein und dürfen sich nicht überschneiden. Wenn alle reservierten oder überlappende Werte, dass die Anforderung mit HTTP-Statuscode 400 schlägt fehl bereitgestellt werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.InboundNatPool.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.InboundNatPool.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            Ruft den Namen des Endpunkts ab oder legt diesen fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Name in einem Batch-Pool muss eindeutig sein, kann Buchstaben, Zahlen, Unterstriche, Punkte und Bindestriche enthalten. Namen müssen mit einem Buchstaben beginnen oder Zahl, mit einem Buchstaben, eine Zahl oder ein Unterstrich enden und 77 Zeichen nicht überschreiten.  Wenn alle ungültigen Werte, dass die Anforderung mit HTTP-Statuscode 400 schlägt fehl bereitgestellt werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroupRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule&gt; NetworkSecurityGroupRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule&gt; NetworkSecurityGroupRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.InboundNatPool.NetworkSecurityGroupRules" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkSecurityGroupRules As IList(Of NetworkSecurityGroupRule)" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroupRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.InboundNatPool.NetworkSecurityGroupRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkSecurityGroupRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Netzwerksicherheit, Regeln, die an den Endpunkt angewendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die maximale Anzahl von Regeln, die für alle Endpunkte in einem Batch-Pool angegeben werden können, ist 25. Wenn keine Netzwerksicherheits-Gruppenregeln angegeben sind, wird eine Standardregel erstellt werden, um eingehenden Zugriff auf den angegebenen BackendPort zulassen. Wenn die maximale Anzahl von Netzwerksicherheits-Gruppenregeln überschritten, wird die Anforderung mit HTTP-Statuscode 400 schlägt fehl.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.InboundNatPool.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As InboundEndpointProtocol" />
      <MemberSignature Language="F#" Value="member this.Protocol : Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol with get, set" Usage="Microsoft.Azure.Management.Batch.Models.InboundNatPool.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.InboundEndpointProtocol</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Protokoll des Endpunkts.
            </summary>
        <value>To be added.</value>
        <remarks>
            Folgende Werte sind möglich: "TCP", "UDP"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.InboundNatPool.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="inboundNatPool.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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