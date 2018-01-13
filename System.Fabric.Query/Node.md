<Type Name="Node" FullName="System.Fabric.Query.Node">
  <TypeSignature Language="C#" Value="public sealed class Node" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Node extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.Node" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Node" />
  <TypeSignature Language="F#" Value="type Node = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt einen Service Fabric-Cluster-Knoten dar.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CodeVersion">
      <MemberSignature Language="C#" Value="public string CodeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.CodeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodeVersion As String" />
      <MemberSignature Language="F#" Value="member this.CodeVersion : string" Usage="System.Fabric.Query.Node.CodeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Service Fabric-Runtime-Version, die auf den Knoten ab.</para>
        </summary>
        <value>
          <para>Die Service Fabric-Runtime-Version auf den Knoten ausgeführt wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigVersion">
      <MemberSignature Language="C#" Value="public string ConfigVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConfigVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.ConfigVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConfigVersion As String" />
      <MemberSignature Language="F#" Value="member this.ConfigVersion : string" Usage="System.Fabric.Query.Node.ConfigVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Cluster-Konfigurationsversion auf den Knoten ab.</para>
        </summary>
        <value>
          <para>Die Cluster-Konfigurationsversion auf dem Knoten.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FaultDomain">
      <MemberSignature Language="C#" Value="public Uri FaultDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri FaultDomain" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.FaultDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FaultDomain As Uri" />
      <MemberSignature Language="F#" Value="member this.FaultDomain : Uri" Usage="System.Fabric.Query.Node.FaultDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Fehlerdomäne für diesen Knoten ab.</para>
          <remarks>
            <para>Fehlerdomänen definieren Sätze von Knoten, die wahrscheinlich gleichzeitig aufgrund von freigegebenen physischen Abhängigkeiten wie Strom oder Netzwerkressourcen Fehler auftreten. Fehlerdomänen stellen in der Regel die Hierarchie und daher werden mit dargestellt <see cref="T:System.Uri" />.</para>
          </remarks>
        </summary>
        <value>
          <para>Die Fehlerdomäne für diesen Knoten.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Query.Node.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Integritätsstatus des Knotens ab.</para>
        </summary>
        <value>
          <para>Der Integritätsstatus des Knotens.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddressOrFQDN">
      <MemberSignature Language="C#" Value="public string IpAddressOrFQDN { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpAddressOrFQDN" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.IpAddressOrFQDN" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IpAddressOrFQDN As String" />
      <MemberSignature Language="F#" Value="member this.IpAddressOrFQDN : string" Usage="System.Fabric.Query.Node.IpAddressOrFQDN" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die IP-Adresse oder den vollständig qualifizierten Domänennamen (FQDN) des Knotens ab.</para>
        </summary>
        <value>
          <para>Die IP-Adresse oder den vollständig qualifizierten Domänennamen (FQDN) des Knotens.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSeedNode">
      <MemberSignature Language="C#" Value="public bool IsSeedNode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSeedNode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.IsSeedNode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSeedNode As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSeedNode : bool" Usage="System.Fabric.Query.Node.IsSeedNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft einen Wert, der angibt, ob dies eine Seed-Knoten ist. SEED-Knoten sind besondere Art von Knoten automatisch konfiguriert und wird intern vom System verwendet. </para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn diese Instanz einen Seed-Knoten handelt, andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsStopped">
      <MemberSignature Language="C#" Value="public bool IsStopped { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsStopped" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.IsStopped" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsStopped As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsStopped : bool" Usage="System.Fabric.Query.Node.IsStopped" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            "True", wenn ein Knoten beendet wird.  Ein Knoten ist im Status "beendet", wenn sie das Ziel einen erfolgreichen Aufruf von StartNodeTransitionAsync mit NodeTransitionType beendet wurde.
            </para>
        </summary>
        <value>
          <para>Und zwar unabhängig davon, ob ein Knoten wurde beendet</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDeactivationInfo">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.NodeDeactivationResult NodeDeactivationInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.NodeDeactivationResult NodeDeactivationInfo" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeDeactivationInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeDeactivationInfo As NodeDeactivationResult" />
      <MemberSignature Language="F#" Value="member this.NodeDeactivationInfo : System.Fabric.Query.NodeDeactivationResult" Usage="System.Fabric.Query.Node.NodeDeactivationInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.NodeDeactivationResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft die Deaktivierungsinformationen für den Knoten ab.
            </para>
        </summary>
        <value>
          <para>Die Deaktivierung Knoteninformationen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDownAt">
      <MemberSignature Language="C#" Value="public DateTime NodeDownAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime NodeDownAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeDownAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeDownAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.NodeDownAt : DateTime" Usage="System.Fabric.Query.Node.NodeDownAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Datum-Zeit Knotenstatus Änderungszeitpunkt zu nach unten ab.</para>
        </summary>
        <value>
          <para>Datum Uhrzeit Knotenstatus Änderungszeitpunkt zu nach unten.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDownTime">
      <MemberSignature Language="C#" Value="public TimeSpan NodeDownTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan NodeDownTime" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeDownTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeDownTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.NodeDownTime : TimeSpan" Usage="System.Fabric.Query.Node.NodeDownTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This property is deprecated, use NodeDownAt instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Knoten außer Betrieb genommen.</para>
        </summary>
        <value>
          <para>Der Knoten, außer Betrieb genommen werden soll.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeId">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeId NodeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.NodeId NodeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeId As NodeId" />
      <MemberSignature Language="F#" Value="member this.NodeId : System.Fabric.NodeId" Usage="System.Fabric.Query.Node.NodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die interne ID, die von Service Fabric verwendet, um einen Knoten eindeutig zu identifizieren.</para>
        </summary>
        <value>
          <para>Die interne ID, die von Service Fabric verwendet, um einen Knoten eindeutig zu identifizieren.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeInstanceId">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger NodeInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger NodeInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeInstanceId As BigInteger" />
      <MemberSignature Language="F#" Value="member this.NodeInstanceId : System.Numerics.BigInteger" Usage="System.Fabric.Query.Node.NodeInstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Numerics.BigInteger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die interne ID, die von Service Fabric verwendet, um eine Knoteninstanz eindeutig zu identifizieren. Die Knoten-ID wird aus der "nodename" deterministisch zugeordnet und ändert sich nicht über den Knoten neu gestartet wird. Allerdings wird die NodeInstanceId bei jedem Neustart des Knotens ändern.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Numerics.BigInteger" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Query.Node.NodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Namen des Knotens ab.</para>
        </summary>
        <value>
          <para>Der Name des Knotens.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.NodeStatus NodeStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.NodeStatus NodeStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeStatus As NodeStatus" />
      <MemberSignature Language="F#" Value="member this.NodeStatus : System.Fabric.Query.NodeStatus" Usage="System.Fabric.Query.Node.NodeStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.NodeStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Knotenstatus ab.</para>
        </summary>
        <value>
          <para>Der Knotenstatus.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeType">
      <MemberSignature Language="C#" Value="public string NodeType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeType As String" />
      <MemberSignature Language="F#" Value="member this.NodeType : string" Usage="System.Fabric.Query.Node.NodeType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Knotentyp ab.</para>
        </summary>
        <value>
          <para>Der Knotentyp.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeUpAt">
      <MemberSignature Language="C#" Value="public DateTime NodeUpAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime NodeUpAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeUpAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeUpAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.NodeUpAt : DateTime" Usage="System.Fabric.Query.Node.NodeUpAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft das Datum-Uhrzeit Knotenstatus Änderungszeitpunkt zu nach oben.</para>
        </summary>
        <value>
          <para>Datum Uhrzeit Knotenstatus Änderungszeitpunkt zu nach oben.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeUpTime">
      <MemberSignature Language="C#" Value="public TimeSpan NodeUpTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan NodeUpTime" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeUpTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeUpTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.NodeUpTime : TimeSpan" Usage="System.Fabric.Query.Node.NodeUpTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This property is deprecated, use NodeUpAt instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die knotenbetriebszeit ab.</para>
        </summary>
        <value>
          <para>Die knotenbetriebszeit.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomain">
      <MemberSignature Language="C#" Value="public string UpgradeDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeDomain" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.UpgradeDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomain As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomain : string" Usage="System.Fabric.Query.Node.UpgradeDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den upgradedomäne-Wert für diesen Knoten ab. </para>
          <remarks>Upgradedomänen definieren Sätze von Knoten, die ungefähr zur gleichen Zeit für Upgrades heruntergefahren werden.</remarks>
        </summary>
        <value>
          <para>Die upgradedomäne für diesen Knoten.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>