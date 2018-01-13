<Type Name="LoadMetricInformation" FullName="System.Fabric.Query.LoadMetricInformation">
  <TypeSignature Language="C#" Value="public sealed class LoadMetricInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit LoadMetricInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.LoadMetricInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LoadMetricInformation" />
  <TypeSignature Language="F#" Value="type LoadMetricInformation = class" />
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
      <para>Stellt die Metrik Load-Informationen.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadMetricInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.LoadMetricInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz von <see cref="T:System.Fabric.Query.LoadMetricInformation" />.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public string Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Action" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As String" />
      <MemberSignature Language="F#" Value="member this.Action : string" Usage="System.Fabric.Query.LoadMetricInformation.Action" />
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
          <para>Ruft die aktuelle Aktion im Hinblick auf diese Metrik ausgeführt werden. Beispiele für konnte Platzierung, Lastenausgleich und einschränkungsüberprüfungen sein.</para>
        </summary>
        <value>
          <para>Die aktuelle Aktion im Hinblick auf diese Metrik ausgeführt werden.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityThreshold">
      <MemberSignature Language="C#" Value="public long ActivityThreshold { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ActivityThreshold" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.ActivityThreshold" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityThreshold As Long" />
      <MemberSignature Language="F#" Value="member this.ActivityThreshold : int64" Usage="System.Fabric.Query.LoadMetricInformation.ActivityThreshold" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Aktivität Schwellenwert für die Metrik im Cluster Manifest System angegeben.</para>
        </summary>
        <value>
          <para>Der Schwellenwert der Aktivität für die Metrik im Cluster Manifest System angegeben.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BalancingThreshold">
      <MemberSignature Language="C#" Value="public double BalancingThreshold { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 BalancingThreshold" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.BalancingThreshold" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BalancingThreshold As Double" />
      <MemberSignature Language="F#" Value="member this.BalancingThreshold : double" Usage="System.Fabric.Query.LoadMetricInformation.BalancingThreshold" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Er ruft Schwellenwert für eine bestimmte Metrik Lastenausgleich.</para>
        </summary>
        <value>
          <para>Der Lastenausgleich Schwellenwert für eine bestimmte Metrik.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BufferedClusterCapacityRemaining">
      <MemberSignature Language="C#" Value="public double BufferedClusterCapacityRemaining { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 BufferedClusterCapacityRemaining" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.BufferedClusterCapacityRemaining" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BufferedClusterCapacityRemaining As Double" />
      <MemberSignature Language="F#" Value="member this.BufferedClusterCapacityRemaining : double" Usage="System.Fabric.Query.LoadMetricInformation.BufferedClusterCapacityRemaining" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Der reservierte Prozentsatz der Gesamtkapazität der Cluster für die Metrik
            </para>
        </summary>
        <value>
          <para>Verbleibende Kapazität in den Cluster ohne reservierte Speicherplatz.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterBufferedCapacity">
      <MemberSignature Language="C#" Value="public long ClusterBufferedCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ClusterBufferedCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.ClusterBufferedCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterBufferedCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.ClusterBufferedCapacity : int64" Usage="System.Fabric.Query.LoadMetricInformation.ClusterBufferedCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Der reservierte Prozentsatz der Gesamtkapazität der Cluster für die Metrik
            </para>
          <para>
            In zukünftigen Versionen von Service Fabric dieser Parameter als veraltet zugunsten des markiert wird <see cref="P:System.Fabric.Query.LoadMetricInformation.BufferedClusterCapacityRemaining" />.
            </para>
        </summary>
        <value>
          <para>ClusterBufferedCapacity-Eigenschaft: Legt den Wert des Felds lange _clusterBufferedCapacity ein/aus.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterCapacity">
      <MemberSignature Language="C#" Value="public long ClusterCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ClusterCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.ClusterCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.ClusterCapacity : int64" Usage="System.Fabric.Query.LoadMetricInformation.ClusterCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den gesamten Cluster Kapazität für eine bestimmte Metrik, die bestimmt, indem er hat die Kapazität für die Metrik in allen Knoten ab.</para>
        </summary>
        <value>
          <para>Die gesamte Cluster Kapazität für eine bestimmte Metrik.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterCapacityRemaining">
      <MemberSignature Language="C#" Value="public double ClusterCapacityRemaining { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 ClusterCapacityRemaining" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.ClusterCapacityRemaining" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterCapacityRemaining As Double" />
      <MemberSignature Language="F#" Value="member this.ClusterCapacityRemaining : double" Usage="System.Fabric.Query.LoadMetricInformation.ClusterCapacityRemaining" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die verbleibende Kapazität für die Metrik im Cluster. Verbleibende Kapazität ist als die aktuelle Kapazität von Cluster minus der aktuellen Arbeitslast für den Cluster definiert.</para>
        </summary>
        <value>
          <para>Die verbleibende Kapazität für die Metrik im Cluster.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterLoad">
      <MemberSignature Language="C#" Value="public long ClusterLoad { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ClusterLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.ClusterLoad" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterLoad As Long" />
      <MemberSignature Language="F#" Value="member this.ClusterLoad : int64" Usage="System.Fabric.Query.LoadMetricInformation.ClusterLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die gesamte Cluster Auslastung für eine bestimmte Metrik innerhalb des Clusters</para>
          <para>
            In zukünftigen Versionen von Service Fabric dieser Parameter als veraltet zugunsten des markiert wird <see cref="P:System.Fabric.Query.LoadMetricInformation.CurrentClusterLoad" />.
            </para>
        </summary>
        <value>
          <para>Das Laden des gesamten Cluster.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterRemainingBufferedCapacity">
      <MemberSignature Language="C#" Value="public long ClusterRemainingBufferedCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ClusterRemainingBufferedCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.ClusterRemainingBufferedCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterRemainingBufferedCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.ClusterRemainingBufferedCapacity : int64" Usage="System.Fabric.Query.LoadMetricInformation.ClusterRemainingBufferedCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft den verbleibenden Prozentsatz der Gesamtkapazität der Cluster für die Metrik
            </para>
        </summary>
        <value>
          <para>Der verbleibende Prozentsatz der Gesamtkapazität der Cluster für die Metrik.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterRemainingCapacity">
      <MemberSignature Language="C#" Value="public long ClusterRemainingCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ClusterRemainingCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.ClusterRemainingCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterRemainingCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.ClusterRemainingCapacity : int64" Usage="System.Fabric.Query.LoadMetricInformation.ClusterRemainingCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die verbleibende Kapazität für die Metrik im Cluster. Verbleibende Kapazität ist als die aktuelle Kapazität von Cluster minus der aktuellen Arbeitslast für den Cluster definiert.</para>
          <para>
            In zukünftigen Versionen von Service Fabric dieser Parameter als veraltet zugunsten des markiert wird <see cref="P:System.Fabric.Query.LoadMetricInformation.ClusterCapacityRemaining" />.
            </para>
        </summary>
        <value>
          <para>Die verbleibende Kapazität für die Metrik im Cluster.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentClusterLoad">
      <MemberSignature Language="C#" Value="public double CurrentClusterLoad { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 CurrentClusterLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.CurrentClusterLoad" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentClusterLoad As Double" />
      <MemberSignature Language="F#" Value="member this.CurrentClusterLoad : double" Usage="System.Fabric.Query.LoadMetricInformation.CurrentClusterLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die gesamte Cluster Last für eine bestimmte Metrik innerhalb des Clusters ab.</para>
        </summary>
        <value>
          <para>Das Laden des gesamten Cluster.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviationAfter">
      <MemberSignature Language="C#" Value="public double DeviationAfter { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DeviationAfter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.DeviationAfter" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeviationAfter As Double" />
      <MemberSignature Language="F#" Value="member this.DeviationAfter : double" Usage="System.Fabric.Query.LoadMetricInformation.DeviationAfter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die durchschnittliche Standardabweichung der Metriken nach Ressource des Lastenausgleichsmoduls ausführen.</para>
        </summary>
        <value>
          <para>Die durchschnittliche Standardabweichung der Metriken nach Ressource des Lastenausgleichsmoduls ausführen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviationBefore">
      <MemberSignature Language="C#" Value="public double DeviationBefore { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DeviationBefore" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.DeviationBefore" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeviationBefore As Double" />
      <MemberSignature Language="F#" Value="member this.DeviationBefore : double" Usage="System.Fabric.Query.LoadMetricInformation.DeviationBefore" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die durchschnittliche Standardabweichung der Metriken vor der Resource Balancer ausführen.</para>
        </summary>
        <value>
          <para>Die durchschnittliche Standardabweichung der Metriken vor der Resource Balancer ausführen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBalancedAfter">
      <MemberSignature Language="C#" Value="public bool IsBalancedAfter { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBalancedAfter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.IsBalancedAfter" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBalancedAfter As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBalancedAfter : bool" Usage="System.Fabric.Query.LoadMetricInformation.IsBalancedAfter" />
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
          <para>Ruft einen Wert, der angibt, ob die Metriken ausgeglichen ist oder nicht nach Ressource des Lastenausgleichsmoduls ausführen.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn Metriken ausgeglichen ist oder nicht nach Resource Balancer ausgeführt; andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBalancedBefore">
      <MemberSignature Language="C#" Value="public bool IsBalancedBefore { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBalancedBefore" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.IsBalancedBefore" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBalancedBefore As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBalancedBefore : bool" Usage="System.Fabric.Query.LoadMetricInformation.IsBalancedBefore" />
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
          <para>Ruft einen Wert, der angibt, ob die Metriken ausgeglichen ist oder nicht vor der Resource Balancer ausführen.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn Metriken ausgeglichen ist oder nicht vor der Resource Balancer ausgeführt; andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsClusterCapacityViolation">
      <MemberSignature Language="C#" Value="public bool IsClusterCapacityViolation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsClusterCapacityViolation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.IsClusterCapacityViolation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsClusterCapacityViolation As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsClusterCapacityViolation : bool" Usage="System.Fabric.Query.LoadMetricInformation.IsClusterCapacityViolation" />
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
          <para>Ruft ab, ob die Metrik derzeit über Kapazität im Cluster befindet.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn die Metrik derzeit über Kapazität in den Cluster befindet, andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNodeLoad">
      <MemberSignature Language="C#" Value="public double MaximumNodeLoad { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 MaximumNodeLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.MaximumNodeLoad" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumNodeLoad As Double" />
      <MemberSignature Language="F#" Value="member this.MaximumNodeLoad : double" Usage="System.Fabric.Query.LoadMetricInformation.MaximumNodeLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft die maximale Last auf einem beliebigen Knoten für die Metrik an.
            </para>
        </summary>
        <value>
          <para>Die maximale Last auf einem beliebigen Knoten für die Metrik.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxNodeLoadNodeId">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeId MaxNodeLoadNodeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.NodeId MaxNodeLoadNodeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.MaxNodeLoadNodeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxNodeLoadNodeId As NodeId" />
      <MemberSignature Language="F#" Value="member this.MaxNodeLoadNodeId : System.Fabric.NodeId" Usage="System.Fabric.Query.LoadMetricInformation.MaxNodeLoadNodeId" />
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
          <para>
            Ruft die Knoten-Id des Knotens mit der maximale Last für die Metrik
            </para>
        </summary>
        <value>
          <para>Der Knoten-Id des Knotens mit der maximale Last für die Metrik.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxNodeLoadValue">
      <MemberSignature Language="C#" Value="public long MaxNodeLoadValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxNodeLoadValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.MaxNodeLoadValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxNodeLoadValue As Long" />
      <MemberSignature Language="F#" Value="member this.MaxNodeLoadValue : int64" Usage="System.Fabric.Query.LoadMetricInformation.MaxNodeLoadValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft die maximale Last auf einem beliebigen Knoten für die Metrik an.
            </para>
          <para>
            In zukünftigen Versionen von Service Fabric dieser Parameter als veraltet zugunsten des markiert wird <see cref="P:System.Fabric.Query.LoadMetricInformation.MaximumNodeLoad" />.
            </para>
        </summary>
        <value>
          <para>Die maximale Last auf einem beliebigen Knoten für die Metrik.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumNodeLoad">
      <MemberSignature Language="C#" Value="public double MinimumNodeLoad { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 MinimumNodeLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.MinimumNodeLoad" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinimumNodeLoad As Double" />
      <MemberSignature Language="F#" Value="member this.MinimumNodeLoad : double" Usage="System.Fabric.Query.LoadMetricInformation.MinimumNodeLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft die minimale Auslastung auf einem beliebigen Knoten für die Metrik an.
            </para>
        </summary>
        <value>
          <para>Die minimale Auslastung auf einem beliebigen Knoten für die Metrik.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinNodeLoadNodeId">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeId MinNodeLoadNodeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.NodeId MinNodeLoadNodeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.MinNodeLoadNodeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinNodeLoadNodeId As NodeId" />
      <MemberSignature Language="F#" Value="member this.MinNodeLoadNodeId : System.Fabric.NodeId" Usage="System.Fabric.Query.LoadMetricInformation.MinNodeLoadNodeId" />
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
          <para>
            Ruft die Knoten-Id des Knotens mit der minimalen Last für die Metrik
            </para>
        </summary>
        <value>
          <para>Der Knoten-Id des Knotens mit der minimalen Last für die Metrik.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinNodeLoadValue">
      <MemberSignature Language="C#" Value="public long MinNodeLoadValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MinNodeLoadValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.MinNodeLoadValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinNodeLoadValue As Long" />
      <MemberSignature Language="F#" Value="member this.MinNodeLoadValue : int64" Usage="System.Fabric.Query.LoadMetricInformation.MinNodeLoadValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft die minimale Auslastung auf einem beliebigen Knoten für die Metrik an.
            </para>
          <para>
            In zukünftigen Versionen von Service Fabric dieser Parameter als veraltet zugunsten des markiert wird <see cref="P:System.Fabric.Query.LoadMetricInformation.MinimumNodeLoad" />.
            </para>
        </summary>
        <value>
          <para>Die minimale Auslastung auf einem beliebigen Knoten für die Metrik.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.Query.LoadMetricInformation.Name" />
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
          <para>Ruft den Namen der Metrik.</para>
        </summary>
        <value>
          <para>Der Name der Metrik.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeBufferPercentage">
      <MemberSignature Language="C#" Value="public double NodeBufferPercentage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 NodeBufferPercentage" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.LoadMetricInformation.NodeBufferPercentage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeBufferPercentage As Double" />
      <MemberSignature Language="F#" Value="member this.NodeBufferPercentage : double" Usage="System.Fabric.Query.LoadMetricInformation.NodeBufferPercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft ab, der reservierte Prozentsatz der Gesamtanzahl der Knoten-Kapazität für die Metrik
            </para>
        </summary>
        <value>
          <para>Der reservierte Prozentsatz der Gesamtanzahl der Knoten-Kapazität für die Metrik</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.LoadMetricInformation.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="loadMetricInformation.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            Jedes Feld der Recht Drucken <see cref="T:System.Fabric.Query.LoadMetricInformation" />.
            </para>
        </summary>
        <returns>
          <para>Eine Zeichenfolge, die Informationen zur Metrik geladen.</para>
        </returns>
        <remarks>To be added.</remarks>
        <example>
                LoadMetricName: Metric1 IsBalancedBefore: "true" IsBalancedAfter: "true" DeviationBefore: 2 DeviationAfter: 2 BalancingThreshold: 1-Aktion: NoActionNeeded ActivityThreshold: 3 ClusterCapacity: 100 CurrentClusterLoad: 1. ClusterCapacityRemaining 0: 0.0 NodeBufferPercentage: 0 ClusterBufferedCapacity: BufferedClusterCapacityRemaining 0: 0.0 ClusterCapacityViolation: "true" MaximumNodeLoad: 1.0 MinNodeLoadNodeId: 1ca9521d70301383417536df0c96f671 MinimumNodeLoad       : 0,0 MaxNodeLoadNodeId: cf68563e16a44f808e86197a9cf83de5
                </example>
      </Docs>
    </Member>
  </Members>
</Type>