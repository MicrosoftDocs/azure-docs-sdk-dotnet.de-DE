<Type Name="ClusterHealthQueryDescription" FullName="System.Fabric.Description.ClusterHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ClusterHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ClusterHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type ClusterHealthQueryDescription = class" />
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
      <para>Enthält abfrageeingabe zum Herunterladen von <see cref="T:System.Fabric.Health.ClusterHealth" />. Wird von <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" /> verwendet.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ClusterHealthQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ClusterHealthQueryDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.ApplicationHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationHealthPolicyMap As ApplicationHealthPolicyMap" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthPolicyMap : System.Fabric.Health.ApplicationHealthPolicyMap" Usage="System.Fabric.Description.ClusterHealthQueryDescription.ApplicationHealthPolicyMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthPolicyMap</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die anwendungsintegritätsrichtlinien zum Auswerten der Integritäts der Anwendungen aus dem Cluster an. Jeder Eintrag gibt an, wie der Anwendungsname Schlüssel und als Wert ein <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> verwendet, um den Anwendungszustand auszuwerten.</para>
        </summary>
        <value>
          <para>Die anwendungsintegritätsrichtlinien zum Auswerten der Integritäts der Anwendungen aus dem Cluster verwendet.</para>
        </value>
        <remarks>
          <para>Wenn eine Anwendung nicht in der Zuordnung angegeben wird die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> gefunden in seiner Anwendung Manifest zur Auswertung verwendet werden. Die Zuordnung ist standardmäßig leer.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthStatesFilter ApplicationsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthStatesFilter ApplicationsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.ApplicationsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationsFilter As ApplicationHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.ApplicationsFilter : System.Fabric.Health.ApplicationHealthStatesFilter with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.ApplicationsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den Filter für <see cref="T:System.Fabric.Health.ApplicationHealthState" /> untergeordneten Elemente. Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben.</para>
        </summary>
        <value>
          <para>Der Filter für <see cref="T:System.Fabric.Health.ApplicationHealthState" /> untergeordneten Elemente.</para>
        </value>
        <remarks>
          <para> Nur Anwendungen, die dem Filter entsprechen, werden zurückgegeben. Alle Anwendungen dienen zum Auswerten des integritätszustands der Cluster aggregiert.
            Wenn der Filter nicht angegeben ist, werden alle Clusteranwendungen zurückgegeben.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.EventsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthEventsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt Sie den Filter für die Auflistung von <see cref="T:System.Fabric.Health.HealthEvent" /> im Cluster gemeldet.</para>
        </summary>
        <value>
          <para>Der Filter für die Auflistung von <see cref="T:System.Fabric.Health.HealthEvent" /> im Cluster gemeldet.</para>
        </value>
        <remarks>
          <para> Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben. Alle Ereignisse werden zum Auswerten der Cluster aggregiert integritätszustands verwendet werden.
            Wenn der Filter nicht angegeben wird, werden alle Ereignisse zurückgegeben.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ClusterHealthPolicy with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> verwendet, um den Clusterzustand auszuwerten. Die Richtlinie wird zum Auswerten der aggregierte Integritätszustand der Ereignisse gemeldet werden, auf dem Cluster als auch die aggregierten integritätszustände der Knoten verwendet werden.</para>
        </summary>
        <value>
          <para>die <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> verwendet, um den Clusterzustand auszuwerten.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As ClusterHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.ClusterHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Integrität Statistiken Filter.
            </summary>
        <value>Der Filter für den Integritäts-Statistiken.</value>
        <remarks>
          <para>
            Filtersteuerelementen gibt an, ob die Statistiken für die Integrität der <see cref="T:System.Fabric.Health.ClusterHealth" /> zurückgegeben werden, indem Sie die Abfrage enthält die Cluster Health Statistiken. Wenn nicht angegeben, werden die Statistiken enthalten.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodesFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.NodeHealthStatesFilter NodesFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.NodeHealthStatesFilter NodesFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.NodesFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property NodesFilter As NodeHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.NodesFilter : System.Fabric.Health.NodeHealthStatesFilter with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.NodesFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.NodeHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den Filter für <see cref="T:System.Fabric.Health.NodeHealthState" /> untergeordneten Elemente. Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben.</para>
        </summary>
        <value>
          <para>Der Filter für <see cref="T:System.Fabric.Health.NodeHealthState" /> untergeordneten Elemente.</para>
        </value>
        <remarks>
          <para> Nur Knoten, die dem Filter entsprechen, werden zurückgegeben. Alle Knoten dienen zum Auswerten des integritätszustands der Cluster aggregiert.
            Wenn der Filter nicht angegeben ist, werden alle Knoten des Clusters zurückgegeben.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ClusterHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterHealthQueryDescription.ToString " />
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
            Ruft eine Zeichenfolgendarstellung der Integrität abfragebeschreibung ab.
            </summary>
        <returns>Eine Zeichenfolgendarstellung der abfragebeschreibung Integrität.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>