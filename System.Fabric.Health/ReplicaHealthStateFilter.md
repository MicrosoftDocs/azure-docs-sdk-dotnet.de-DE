<Type Name="ReplicaHealthStateFilter" FullName="System.Fabric.Health.ReplicaHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class ReplicaHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicaHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ReplicaHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicaHealthStateFilter" />
  <TypeSignature Language="F#" Value="type ReplicaHealthStateFilter = class" />
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
            Filter für <see cref="T:System.Fabric.Health.ReplicaHealthState" /> Objekte.
            </summary>
    <remarks>Die Entität Health Status Block Abfragen können angeben, eine Liste der Replikatfilter feine auswählen, die Replikate, die in das Abfrageergebnis aufgenommen werden.
            Beachten Sie, dass alle Replikate dienen zum Auswerten von übergeordneten Elementen Integritätsstatus, unabhängig von der übergebene Filter aggregiert.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicaHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.ReplicaHealthStateFilter.HealthStateFilter" />
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
            Ruft ab oder legt Sie Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.ReplicaHealthState" /> Einträge in der Auflistung. 
            </summary>
        <value>Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.ReplicaHealthState" /> Einträge in der Auflistung.</value>
        <remarks>Die Integrität statusfilterwert stammen von Membern oder bitweisen Kombination von Membern der <see cref="T:System.Fabric.Health.HealthStateFilter" />. Für ein Replikat auf dem Filter entsprechen muss der aggregierte Integritätszustand der angegebenen Integrität Statusfilter übereinstimmen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaOrInstanceIdFilter">
      <MemberSignature Language="C#" Value="public long ReplicaOrInstanceIdFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaOrInstanceIdFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthStateFilter.ReplicaOrInstanceIdFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicaOrInstanceIdFilter As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaOrInstanceIdFilter : int64 with get, set" Usage="System.Fabric.Health.ReplicaHealthStateFilter.ReplicaOrInstanceIdFilter" />
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
            Ruft ab oder legt fest, der einem zustandsbehafteten Dienst-Id oder des zustandslose Instanz-Id-Filters.
            </summary>
        <value>Der zustandsbehaftete Dienst-Id oder des zustandslose Instanz-Id-Filters.</value>
        <remarks>Wenn nicht angegeben wird, werden alle Replikate, die das übergeordnete Element entsprechen gefiltert (sofern vorhanden), und der angegebenen Integrität Statusfilter stimmen Sie dem Filter überein.
            Andernfalls gilt der Filter nur für das Replikat durch die angegebene Id identifizierte.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="replicaHealthStateFilter.ToString " />
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