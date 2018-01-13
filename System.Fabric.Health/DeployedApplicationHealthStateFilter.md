<Type Name="DeployedApplicationHealthStateFilter" FullName="System.Fabric.Health.DeployedApplicationHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealthStateFilter" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthStateFilter = class" />
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
            Filter für <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> Objekte.
            </summary>
    <remarks>Der Status-Segment integritätsabfragen können angeben, wählen Sie eine Liste der bereitgestellten Anwendungsfilter feine bereitgestellten Anwendungen, die in das Abfrageergebnis aufgenommen werden.
            Beachten Sie, dass alle bereitgestellten Anwendungen zur Bewertung des Eltern Integritätsstatus, unabhängig von der übergebene Filter aggregiert.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedApplicationHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.DeployedApplicationHealthStateFilter" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedServicePackageFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthStateFilter&gt; DeployedServicePackageFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.DeployedServicePackageHealthStateFilter&gt; DeployedServicePackageFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateFilter.DeployedServicePackageFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedServicePackageFilters As IList(Of DeployedServicePackageHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.DeployedServicePackageFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthStateFilter&gt;" Usage="System.Fabric.Health.DeployedApplicationHealthStateFilter.DeployedServicePackageFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" /> auf die integritätszustände der bereitgestellten Dienst Paket angewendet werden soll.
            </summary>
        <value>Die Liste der <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" /> auf die integritätszustände der bereitgestellten Dienst Paket angewendet werden soll.</value>
        <remarks>Alle bereitgestellten Dienst aus, die Pakete, die dem Filter entsprechen, als untergeordnete Elemente der bereitgestellten Anwendung zurückgegeben werden.
            Ohne Angabe werden die untergeordneten Elemente standardmäßig nicht zurückgegeben.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.DeployedApplicationHealthStateFilter.HealthStateFilter" />
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
            Ruft ab oder legt Sie Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> Einträge in der Auflistung. 
            </summary>
        <value>Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> Einträge in der Auflistung.</value>
        <remarks>Die Integrität statusfilterwert stammen von Membern oder bitweisen Kombination von Membern der <see cref="T:System.Fabric.Health.HealthStateFilter" />. Für eine bereitgestellte Anwendung, die dem Filter entsprechen muss der aggregierte Integritätszustand der angegebenen Integrität Statusfilter übereinstimmen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeNameFilter">
      <MemberSignature Language="C#" Value="public string NodeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateFilter.NodeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.NodeNameFilter : string with get, set" Usage="System.Fabric.Health.DeployedApplicationHealthStateFilter.NodeNameFilter" />
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
            Abrufen oder Festlegen der Knoten Namensfilter.
            </summary>
        <value>Der Knoten Namensfilter.</value>
        <remarks>Wenn nicht angegebene wird, werden alle bereitgestellte Anwendungen, die die übergeordnete Filter (sofern vorhanden) entsprechen berücksichtigt und mit den anderen Elementen in einem Filter, wie die Integrität Statusfilter abgeglichen werden.
            Andernfalls gilt der Filter nur für Anwendungen, die auf dem angegebenen Knoten bereitgestellt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedApplicationHealthStateFilter.ToString " />
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