<Type Name="ServiceHealthStateFilter" FullName="System.Fabric.Health.ServiceHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealthStateFilter" />
  <TypeSignature Language="F#" Value="type ServiceHealthStateFilter = class" />
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
            Filter für <see cref="T:System.Fabric.Health.ServiceHealthState" /> Objekte.
            </summary>
    <remarks>Die Entität Health Status Block Abfragen können angeben, eine Liste der Filter feine Service wählen Sie die Dienste, die in das Abfrageergebnis aufgenommen werden.
            Beachten Sie, dass alles, was die Dienste zur Bewertung des übergeordneten Elementen Integritätsstatus, unabhängig von der übergebene Filter aggregiert.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ServiceHealthStateFilter" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.ServiceHealthStateFilter.HealthStateFilter" />
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
            Ruft ab oder legt Sie Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.ServiceHealthState" /> Einträge in der Auflistung. 
            </summary>
        <value>Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.ServiceHealthState" /> Einträge in der Auflistung.</value>
        <remarks>Die Integrität statusfilterwert stammen von Membern oder bitweisen Kombination von Membern der <see cref="T:System.Fabric.Health.HealthStateFilter" />. Für einen Dienst auf dem Filter entsprechen muss der aggregierte Integritätszustand der angegebenen Integrität Statusfilter übereinstimmen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthStateFilter&gt; PartitionFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.PartitionHealthStateFilter&gt; PartitionFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateFilter.PartitionFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionFilters As IList(Of PartitionHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.PartitionFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthStateFilter&gt;" Usage="System.Fabric.Health.ServiceHealthStateFilter.PartitionFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der <see cref="T:System.Fabric.Health.PartitionHealthStateFilter" /> auf untergeordnete Elemente Zustände Partition angewendet werden soll.
            </summary>
        <value>Die Liste der <see cref="T:System.Fabric.Health.PartitionHealthStateFilter" /> auf untergeordnete Elemente Zustände Partition angewendet werden soll.</value>
        <remarks>Die Liste kann es sich um einen Standardfilter Partition und/oder Partition Filter für bestimmte Partitionen feine-Entitäten, die von der Abfrage zurückgegebenen enthalten.
            Alle Partitionen untergeordneten Elemente, die dem Filter entsprechen, werden als untergeordnete Elemente des Diensts zurückgegeben.
            Ohne Angabe werden die untergeordneten Elemente standardmäßig nicht zurückgegeben.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceNameFilter">
      <MemberSignature Language="C#" Value="public Uri ServiceNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateFilter.ServiceNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceNameFilter As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceNameFilter : Uri with get, set" Usage="System.Fabric.Health.ServiceHealthStateFilter.ServiceNameFilter" />
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
            Abrufen / definieren den Dienst Namensfilter.
            </summary>
        <value>Der Filter für den Service-Name.</value>
        <remarks>Wenn nicht angegeben, werden alle Dienste, die die übergeordnete Filter (sofern vorhanden) und der angegebenen Integrität Statusfilter übereinstimmen Filter entsprechen.
            Andernfalls gilt der Filter nur für den angegebenen Dienst. Alle anderen Filter Member, wie die Integrität der Statusfilter, werden auf diesen Dienst angewendet.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceHealthStateFilter.ToString " />
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