<Type Name="PartitionHealthQueryDescription" FullName="System.Fabric.Description.PartitionHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.PartitionHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type PartitionHealthQueryDescription = class" />
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
      <para>Beschreibt abfrageeingabe zum Abrufen von <see cref="T:System.Fabric.Health.PartitionHealth" />. Wird von <see cref="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Fabric.Description.PartitionHealthQueryDescription)" /> verwendet.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionHealthQueryDescription (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.PartitionHealthQueryDescription.#ctor(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionId As Guid)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.PartitionHealthQueryDescription : Guid -&gt; System.Fabric.Description.PartitionHealthQueryDescription" Usage="new System.Fabric.Description.PartitionHealthQueryDescription partitionId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die Partitions-ID.</para>
        </param>
        <summary>
          <para>Instanziiert eine neue Instanz der <see cref="T:System.Fabric.Description.PartitionHealthQueryDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PartitionHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.PartitionHealthQueryDescription.EventsFilter" />
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
          <para>Ruft ab oder legt Sie den Filter für die Auflistung von <see cref="T:System.Fabric.Health.HealthEvent" /> für die Partition gemeldet. Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.Health.HealthEventsFilter" /> verwendet, um die zurückgegebenen Ereignisse gefiltert.</para>
        </value>
        <remarks>
          <para> Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben. Alle Ereignisse dienen zum Auswerten des integritätszustands der Partition aggregiert.
            Wenn der Filter nicht angegeben wird, werden alle Ereignisse zurückgegeben.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PartitionHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.PartitionHealthQueryDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> zur Bewertung der Integrität.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> zum Auswerten der partitionsintegrität verwendet.</para>
        </value>
        <remarks>Wenn nicht angegeben, verwendet der Health Store einer anwendungsintegritäts-Richtlinie für die übergeordnete Anwendung zum Auswerten der partitionsintegrität an.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.PartitionHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.PartitionHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PartitionHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As PartitionHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.PartitionHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.PartitionHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.PartitionHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Integrität Statistiken Filter.
            </summary>
        <value>Der Filter für den Integritäts-Statistiken.</value>
        <remarks>
          <para>
            Filtersteuerelementen gibt an, ob die Statistiken für die Integrität der <see cref="T:System.Fabric.Health.PartitionHealth" /> zurückgegeben werden, indem Sie die Abfrage enthält die Health partitionsstatistiken. Wenn nicht angegeben, werden die Statistiken enthalten.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PartitionHealthQueryDescription.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Description.PartitionHealthQueryDescription.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den Partitionsbezeichner.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Guid" /> , die die Partitions-ID darstellt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicasFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ReplicaHealthStatesFilter ReplicasFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ReplicaHealthStatesFilter ReplicasFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PartitionHealthQueryDescription.ReplicasFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicasFilter As ReplicaHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.ReplicasFilter : System.Fabric.Health.ReplicaHealthStatesFilter with get, set" Usage="System.Fabric.Description.PartitionHealthQueryDescription.ReplicasFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ReplicaHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den Filter für <see cref="T:System.Fabric.Health.ReplicaHealthState" /> untergeordneten Elemente. Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben. Alle untergeordneten Elemente dienen zum Auswerten des integritätszustands der Partition aggregiert.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.Health.ReplicaHealthStatesFilter" /> zum Filtern der zurückgegebenen Replikate.</para>
        </value>
        <remarks>
          <para> Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben. Alle untergeordneten Elemente dienen zum Auswerten des integritätszustands der Partition aggregiert.
            Wenn der Filter nicht angegeben ist, werden alle untergeordneten Elemente für Partition zurückgegeben.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.PartitionHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionHealthQueryDescription.ToString " />
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