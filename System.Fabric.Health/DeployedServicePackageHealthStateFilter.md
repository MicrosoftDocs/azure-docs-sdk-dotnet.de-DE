<Type Name="DeployedServicePackageHealthStateFilter" FullName="System.Fabric.Health.DeployedServicePackageHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealthStateFilter" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthStateFilter = class" />
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
            Filter für <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> Objekte.
            </summary>
    <remarks>Der Status-Segment integritätsabfragen können angeben, eine Liste der bereitgestellten Dienst Paket Filter feine wählen Sie die bereitgestellten dienstpakete, die in das Abfrageergebnis aufgenommen werden.
            Beachten Sie, dass alles, was die bereitgestellten dienstpakete zur Bewertung des übergeordneten Elementen Integritätsstatus, unabhängig von der übergebene Filter aggregiert.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStateFilter.HealthStateFilter" />
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
            Ruft ab oder legt Sie Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> Einträge in der Auflistung. 
            </summary>
        <value>Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> Einträge in der Auflistung.</value>
        <remarks>Die Integrität statusfilterwert stammen von Membern oder bitweisen Kombination von Membern der <see cref="T:System.Fabric.Health.HealthStateFilter" />. Für ein bereitgestelltes Dienstpaket, die dem Filter entsprechen muss der aggregierte Integritätszustand der angegebenen Integrität Statusfilter übereinstimmen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestNameFilter">
      <MemberSignature Language="C#" Value="public string ServiceManifestNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateFilter.ServiceManifestNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceManifestNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestNameFilter : string with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStateFilter.ServiceManifestNameFilter" />
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
            Abrufen oder Festlegen der Dienstfilter Manifestnamen.
            </summary>
        <value>Der Dienstfilter Manifestnamen.</value>
        <remarks>Wenn nicht angegeben, alle bereitgestellten Dienstpaketen, die die übergeordnete Filter (sofern vorhanden) entsprechen und die angegebenen Health Status filtern, die Filterkriterien erfüllen.
            Andernfalls der Filter gilt nur für das Paket bereitgestellten Dienst für den angegebenen Dienst Manifestnamen und anhand der Integrität Statusfilter abgeglichen werden.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationIdFilter">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationIdFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationIdFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateFilter.ServicePackageActivationIdFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePackageActivationIdFilter As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationIdFilter : string with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStateFilter.ServicePackageActivationIdFilter" />
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
            Abrufen oder festlegen den Dienst Paket ActivationId-Filter.
            </summary>
        <value>
          <para>
            Die <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> bereitgestellten Diensts Paket abgerufen werden kann, mithilfe von <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> Abfrage. 
             </para>
          <para>
            Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung des Diensts wurde <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wurde, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.
            Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedServicePackageHealthStateFilter.ToString " />
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