<Type Name="InboundNatPool" FullName="Microsoft.Azure.Batch.InboundNatPool">
  <TypeSignature Language="C#" Value="public class InboundNatPool" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InboundNatPool extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.InboundNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Class InboundNatPool" />
  <TypeSignature Language="F#" Value="type InboundNatPool = class&#xA;    interface ITransportObjectProvider&lt;InboundNATPool&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
      <MemberSignature Language="C#" Value="public InboundNatPool (string name, Microsoft.Azure.Batch.Common.InboundEndpointProtocol protocol, int backendPort, int frontendPortRangeStart, int frontendPortRangeEnd, System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; networkSecurityGroupRules = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Batch.Common.InboundEndpointProtocol protocol, int32 backendPort, int32 frontendPortRangeStart, int32 frontendPortRangeEnd, class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; networkSecurityGroupRules) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.InboundNatPool.#ctor(System.String,Microsoft.Azure.Batch.Common.InboundEndpointProtocol,System.Int32,System.Int32,System.Int32,System.Collections.Generic.IReadOnlyList{Microsoft.Azure.Batch.NetworkSecurityGroupRule})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, protocol As InboundEndpointProtocol, backendPort As Integer, frontendPortRangeStart As Integer, frontendPortRangeEnd As Integer, Optional networkSecurityGroupRules As IReadOnlyList(Of NetworkSecurityGroupRule) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.InboundNatPool : string * Microsoft.Azure.Batch.Common.InboundEndpointProtocol * int * int * int * System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; -&gt; Microsoft.Azure.Batch.InboundNatPool" Usage="new Microsoft.Azure.Batch.InboundNatPool (name, protocol, backendPort, frontendPortRangeStart, frontendPortRangeEnd, networkSecurityGroupRules)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="protocol" Type="Microsoft.Azure.Batch.Common.InboundEndpointProtocol" />
        <Parameter Name="backendPort" Type="System.Int32" />
        <Parameter Name="frontendPortRangeStart" Type="System.Int32" />
        <Parameter Name="frontendPortRangeEnd" Type="System.Int32" />
        <Parameter Name="networkSecurityGroupRules" Type="System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Endpunkts.</param>
        <param name="protocol">Das Protokoll des Endpunkts.</param>
        <param name="backendPort">Die Nummer des Ports auf den Computeknoten.</param>
        <param name="frontendPortRangeStart">Die erste Portnummer im Bereich des externen Ports, die verwendet wird, um eingehenden Zugriff auf die BackendPort auf einzelne Serverknoten bereitzustellen.</param>
        <param name="frontendPortRangeEnd">Die letzten Portnummer im Bereich des externen Ports, die verwendet wird, um eingehenden Zugriff auf die BackendPort auf einzelne Serverknoten bereitzustellen.</param>
        <param name="networkSecurityGroupRules">Eine Liste von Netzwerksicherheits-Gruppenregeln, die an den Endpunkt angewendet werden.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.InboundNatPool" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendPort">
      <MemberSignature Language="C#" Value="public int BackendPort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 BackendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackendPort As Integer" />
      <MemberSignature Language="F#" Value="member this.BackendPort : int" Usage="Microsoft.Azure.Batch.InboundNatPool.BackendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Nummer des Ports auf den Computeknoten.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies muss in einem Batch-Pool eindeutig sein. Zulässige Werte liegen zwischen 1 und 65535, außer für 22, 3389, 29876 und 29877 wie diese reserviert sind.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeEnd">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeEnd { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.FrontendPortRangeEnd" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FrontendPortRangeEnd As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeEnd : int" Usage="Microsoft.Azure.Batch.InboundNatPool.FrontendPortRangeEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die letzten Portnummer im Bereich von externen Ports, die verwendet wird, um eingehenden Zugriff auf die BackendPort auf einzelne Serverknoten bereitzustellen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Zulässige Werte zwischen 1 und 65534 außer Ports von 50000 55000 der Batch-Dienst reserviert sind. Alle Bereiche in einem Pool müssen eindeutig sein und dürfen sich nicht überschneiden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeStart">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeStart { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.FrontendPortRangeStart" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FrontendPortRangeStart As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeStart : int" Usage="Microsoft.Azure.Batch.InboundNatPool.FrontendPortRangeStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die erste Portnummer im Bereich von externen Ports, die verwendet wird, um eingehenden Zugriff auf die BackendPort auf einzelne Serverknoten bereitzustellen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die zulässigen Werte-Bereich zwischen 1 und 65534 außer Ports von 50000 55000 die reserviert sind. Alle Bereiche in einem Pool müssen eindeutig sein und dürfen sich nicht überschneiden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Batch.InboundNatPool.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen des Endpunkts ab.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Name in einem Batch-Pool muss eindeutig sein, kann Buchstaben, Zahlen, Unterstriche, Punkte und Bindestriche enthalten. Namen müssen mit einem Buchstaben beginnen oder Zahl, mit einem Buchstaben, eine Zahl oder ein Unterstrich enden und 77 Zeichen nicht überschreiten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroupRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; NetworkSecurityGroupRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; NetworkSecurityGroupRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.NetworkSecurityGroupRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkSecurityGroupRules As IReadOnlyList(Of NetworkSecurityGroupRule)" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroupRules : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt;" Usage="Microsoft.Azure.Batch.InboundNatPool.NetworkSecurityGroupRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine Liste der Netzwerksicherheit, Regeln, die an den Endpunkt angewendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die maximale Anzahl von Regeln, die für alle Endpunkte für einen Pool angegeben werden können, ist 25. Wenn keine Netzwerksicherheits-Gruppenregeln angegeben sind, wird eine Standardregel erstellt werden, um eingehenden Zugriff auf den angegebenen BackendPort zulassen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.InboundEndpointProtocol Protocol { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.InboundEndpointProtocol Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Protocol As InboundEndpointProtocol" />
      <MemberSignature Language="F#" Value="member this.Protocol : Microsoft.Azure.Batch.Common.InboundEndpointProtocol" Usage="Microsoft.Azure.Batch.InboundNatPool.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.InboundEndpointProtocol</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Protokoll des Endpunkts ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>