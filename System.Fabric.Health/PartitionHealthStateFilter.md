<Type Name="PartitionHealthStateFilter" FullName="System.Fabric.Health.PartitionHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealthStateFilter" />
  <TypeSignature Language="F#" Value="type PartitionHealthStateFilter = class" />
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
            Filter für <see cref="T:System.Fabric.Health.PartitionHealthState" /> Objekte.
            </summary>
    <remarks>Der Status-Segment integritätsabfragen können angeben, eine Liste der Filter feine Partition wählen Sie die Partitionen, die in das Abfrageergebnis aufgenommen werden.
            Beachten Sie, dass alle Partitionen zur Bewertung des Eltern Integritätsstatus, unabhängig von der übergebene Filter aggregiert.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.PartitionHealthStateFilter" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.PartitionHealthStateFilter.HealthStateFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStateFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Sie Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.PartitionHealthState" /> Einträge in der Auflistung. 
            </summary>
        <value>Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.PartitionHealthState" /> Einträge in der Auflistung.</value>
        <remarks>Die Integrität statusfilterwert stammen von Membern oder bitweisen Kombination von Membern der <see cref="T:System.Fabric.Health.HealthStateFilter" />. Für eine Partition, die dem Filter entsprechen muss der aggregierte Integritätszustand der angegebenen Integrität Statusfilter übereinstimmen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionIdFilter">
      <MemberSignature Language="C#" Value="public Guid PartitionIdFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionIdFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateFilter.PartitionIdFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionIdFilter As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionIdFilter : Guid with get, set" Usage="System.Fabric.Health.PartitionHealthStateFilter.PartitionIdFilter" />
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
            Abrufen oder Festlegen des Partitions-Id-Filters.
            </summary>
        <value>Der Partitions-Id-Filter.</value>
        <remarks>Wenn nicht angegeben wird, werden alle Partitionen, die das übergeordnete Element entsprechen gefiltert (sofern vorhanden), und der angegebenen Integrität Statusfilter stimmen Sie dem Filter überein.
            Andernfalls gilt der Filter nur für die Partition, die durch die Partitions-Id identifiziert. Alle anderen Filter Member, wie Statusfilter Integrität und Replikate-Filter werden auf dieser Partition angewendet.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthStateFilter&gt; ReplicaFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ReplicaHealthStateFilter&gt; ReplicaFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateFilter.ReplicaFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaFilters As IList(Of ReplicaHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.ReplicaFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthStateFilter&gt;" Usage="System.Fabric.Health.PartitionHealthStateFilter.ReplicaFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der <see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" /> auf die untergeordneten Elemente replikatintegritätszustände angewendet werden soll.
            </summary>
        <value>Die Liste der <see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" /> auf die untergeordneten Elemente replikatintegritätszustände angewendet werden soll.</value>
        <remarks>Alle Replikat untergeordneten Elemente, die dem Filter entsprechen, werden als untergeordnete Elemente der Partition zurückgegeben.
            Ohne Angabe werden die untergeordneten Elemente standardmäßig nicht zurückgegeben.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionHealthStateFilter.ToString " />
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
            Gibt eine Zeichenfolgendarstellung des Filters zurück.
            </summary>
        <returns>Eine Zeichenfolgendarstellung des Filters.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>