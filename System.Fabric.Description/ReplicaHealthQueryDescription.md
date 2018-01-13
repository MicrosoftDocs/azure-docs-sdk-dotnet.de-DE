<Type Name="ReplicaHealthQueryDescription" FullName="System.Fabric.Description.ReplicaHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ReplicaHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicaHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ReplicaHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicaHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type ReplicaHealthQueryDescription = class" />
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
      <para>Beschreibt die als abfrageeingabe für die erste <see cref="T:System.Fabric.Health.ReplicaHealth" />. Wird von <see cref="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Fabric.Description.ReplicaHealthQueryDescription)" /> verwendet.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicaHealthQueryDescription (Guid partitionId, long replicaOrInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid partitionId, int64 replicaOrInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ReplicaHealthQueryDescription.#ctor(System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionId As Guid, replicaOrInstanceId As Long)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ReplicaHealthQueryDescription : Guid * int64 -&gt; System.Fabric.Description.ReplicaHealthQueryDescription" Usage="new System.Fabric.Description.ReplicaHealthQueryDescription (partitionId, replicaOrInstanceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die Partitions-ID.</para>
        </param>
        <param name="replicaOrInstanceId">
          <para>Die Replikat-Id mit einem zustandsbehafteten Dienst oder der statusfreien Dienstinstanz.</para>
        </param>
        <summary>
          <para>Instanziiert eine neue Instanz der <see cref="T:System.Fabric.Description.ReplicaHealthQueryDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ReplicaHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.ReplicaHealthQueryDescription.EventsFilter" />
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
          <para>Ruft ab oder legt Sie den Filter für die Auflistung von <see cref="T:System.Fabric.Health.HealthEvent" /> auf dem Replikat gemeldet. Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.Health.HealthEventsFilter" /> verwendet, um die von der Abfrage zurückgegebenen Ereignisse zu filtern.</para>
        </value>
        <remarks>
          <para> Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben. Alle Ereignisse dienen zum Auswerten der Zustand des Replikats aggregiert.
            Wenn der Filter nicht angegeben wird, werden alle Ereignisse zurückgegeben.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ReplicaHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.ReplicaHealthQueryDescription.HealthPolicy" />
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
          <para>Die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> zur Bewertung der Integrität.</para>
        </value>
        <remarks>Wenn nicht angegeben, verwendet der Health Store einer anwendungsintegritäts-Richtlinie für die übergeordnete Anwendung zum Auswerten der replikatintegrität an.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ReplicaHealthQueryDescription.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Description.ReplicaHealthQueryDescription.PartitionId" />
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
          <para>Ruft den Partitionsbezeichner ab.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Guid" /> , die die Partitions-ID darstellt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaOrInstanceId">
      <MemberSignature Language="C#" Value="public long ReplicaOrInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaOrInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ReplicaHealthQueryDescription.ReplicaOrInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaOrInstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaOrInstanceId : int64" Usage="System.Fabric.Description.ReplicaHealthQueryDescription.ReplicaOrInstanceId" />
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
          <para>Der Replikat-Id einem zustandsbehafteten Dienst oder zustandslosen Dienstinstanz.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Int64" /> , der einem zustandsbehafteten Dienst-Id oder der statusfreien Dienstinstanz darstellt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ReplicaHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="replicaHealthQueryDescription.ToString " />
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