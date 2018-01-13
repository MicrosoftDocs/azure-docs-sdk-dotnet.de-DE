<Type Name="InboundNATPool" FullName="Microsoft.Azure.Batch.Protocol.Models.InboundNATPool">
  <TypeSignature Language="C#" Value="public class InboundNATPool" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InboundNATPool extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool" />
  <TypeSignature Language="VB.NET" Value="Public Class InboundNATPool" />
  <TypeSignature Language="F#" Value="type InboundNATPool = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public InboundNATPool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public InboundNATPool (string name, Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol protocol, int backendPort, int frontendPortRangeStart, int frontendPortRangeEnd, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule&gt; networkSecurityGroupRules = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol protocol, int32 backendPort, int32 frontendPortRangeStart, int32 frontendPortRangeEnd, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule&gt; networkSecurityGroupRules) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol,System.Int32,System.Int32,System.Int32,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, protocol As InboundEndpointProtocol, backendPort As Integer, frontendPortRangeStart As Integer, frontendPortRangeEnd As Integer, Optional networkSecurityGroupRules As IList(Of NetworkSecurityGroupRule) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.InboundNATPool : string * Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol * int * int * int * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.InboundNATPool" Usage="new Microsoft.Azure.Batch.Protocol.Models.InboundNATPool (name, protocol, backendPort, frontendPortRangeStart, frontendPortRangeEnd, networkSecurityGroupRules)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="protocol" Type="Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol" />
        <Parameter Name="backendPort" Type="System.Int32" />
        <Parameter Name="frontendPortRangeStart" Type="System.Int32" />
        <Parameter Name="frontendPortRangeEnd" Type="System.Int32" />
        <Parameter Name="networkSecurityGroupRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule&gt;" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendPort As Integer" />
      <MemberSignature Language="F#" Value="member this.BackendPort : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.BackendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.FrontendPortRangeEnd" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPortRangeEnd As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeEnd : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.FrontendPortRangeEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
            Zulässige Werte zwischen 1 und 65534 außer Ports von 50000 55000 der Batch-Dienst reserviert sind. Alle Bereiche in einem Pool müssen eindeutig sein und dürfen sich nicht überschneiden. Jeder Bereich muss mindestens 40 Ports enthalten. Wenn alle reservierten oder überlappende Werte, dass die Anforderung mit HTTP-Statuscode 400 schlägt fehl bereitgestellt werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeStart">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeStart { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.FrontendPortRangeStart" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPortRangeStart As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeStart : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.FrontendPortRangeStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
            Die zulässigen Werte-Bereich zwischen 1 und 65534 außer Ports von 50000 55000 die reserviert sind. Alle Bereiche in einem Pool müssen eindeutig sein und dürfen sich nicht überschneiden. Jeder Bereich muss mindestens 40 Ports enthalten. Wenn alle reservierten oder überlappende Werte, dass die Anforderung mit HTTP-Statuscode 400 schlägt fehl bereitgestellt werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule&gt; NetworkSecurityGroupRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule&gt; NetworkSecurityGroupRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.NetworkSecurityGroupRules" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkSecurityGroupRules As IList(Of NetworkSecurityGroupRule)" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroupRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.NetworkSecurityGroupRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkSecurityGroupRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As InboundEndpointProtocol" />
      <MemberSignature Language="F#" Value="member this.Protocol : Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Protokoll des Endpunkts.
            </summary>
        <value>To be added.</value>
        <remarks>
            Folgende Werte sind möglich: "Tcp", "Udp"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="inboundNATPool.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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