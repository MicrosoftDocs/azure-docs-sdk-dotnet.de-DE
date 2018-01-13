<Type Name="DeployedApplicationHealthQueryDescription" FullName="System.Fabric.Description.DeployedApplicationHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.DeployedApplicationHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthQueryDescription = class" />
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
      <para>Beschreibt abfrageeingabe zum Abrufen von <see cref="T:System.Fabric.Health.DeployedApplicationHealth" />. Wird von <see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Fabric.Description.DeployedApplicationHealthQueryDescription)" /> verwendet.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedApplicationHealthQueryDescription (Uri applicationName, string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedApplicationHealthQueryDescription.#ctor(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, nodeName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.DeployedApplicationHealthQueryDescription : Uri * string -&gt; System.Fabric.Description.DeployedApplicationHealthQueryDescription" Usage="new System.Fabric.Description.DeployedApplicationHealthQueryDescription (applicationName, nodeName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der Anwendungsname. Darf nicht NULL sein.</para>
        </param>
        <param name="nodeName">
          <para>Der Knotenname. Darf weder NULL noch leer sein.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.DeployedApplicationHealthQueryDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>Ein erforderlicher Parameter darf nicht null sein.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Ein erforderlicher Parameter darf nicht leer sein.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" />
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
          <para>Ruft den Namen der Anwendung ab.</para>
        </summary>
        <value>
          <para>Der Namen der Anwendung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedServicePackagesFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedServicePackageHealthStatesFilter DeployedServicePackagesFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedServicePackageHealthStatesFilter DeployedServicePackagesFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.DeployedServicePackagesFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property DeployedServicePackagesFilter As DeployedServicePackageHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.DeployedServicePackagesFilter : System.Fabric.Health.DeployedServicePackageHealthStatesFilter with get, set" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.DeployedServicePackagesFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedServicePackageHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den Filter für <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> untergeordneten Elemente. Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStatesFilter" /> zum Filtern der zurückgegebenen bereitgestellten dienstpakete verwendet.</para>
        </value>
        <remarks>
          <para> Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben. Alle untergeordneten Elemente dienen zum Auswerten des Integritätsstatus der bereitgestellten Anwendung aggregiert.
            Wenn der Filter nicht angegeben ist, werden alle bereitgestellten Dienst Paket untergeordneten Elemente der bereitgestellten Anwendung zurückgegeben.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.EventsFilter" />
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
          <para>Ruft ab oder legt Sie den Filter für die Auflistung von <see cref="T:System.Fabric.Health.HealthEvent" /> für die bereitgestellte Anwendung gemeldet. Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.Health.HealthEventsFilter" /> verwendet, um die zurückgegebenen Ereignisse gefiltert.</para>
        </value>
        <remarks>
          <para> Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben. Alle Ereignisse dienen zum Auswerten des integritätszustands der Anwendung aggregiert.
            Wenn der Filter nicht angegeben wird, werden alle Ereignisse zurückgegeben.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.HealthPolicy" />
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
          <para>Ruft ab oder legt die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> verwendet, um die Integrität der bereitgestellten Anwendung auszuwerten.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> zur Bewertung der Integrität.</para>
        </value>
        <remarks>Wenn nicht angegeben, verwendet der Health Store einer anwendungsintegritäts-Richtlinie oder die übergeordnete Anwendung zum Auswerten der bereitgestellten Anwendung.
            Die Integritätsrichtlinie für die Anwendung wird im Anwendungsmanifest angegeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedApplicationHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedApplicationHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As DeployedApplicationHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.DeployedApplicationHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedApplicationHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Integrität Statistiken Filter.
            </summary>
        <value>Der Filter für den Integritäts-Statistiken.</value>
        <remarks>
          <para>
            Filtersteuerelementen gibt an, ob die Statistiken für die Integrität der <see cref="T:System.Fabric.Health.DeployedApplicationHealth" /> zurückgegeben werden, indem Sie die Abfrage enthält die bereitgestellte Anwendung Integrität Statistiken. Wenn nicht angegeben, werden die Statistiken enthalten.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.NodeName" />
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
          <para>Ruft den Knotennamen ab.</para>
        </summary>
        <value>
          <para>Der Knotenname.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedApplicationHealthQueryDescription.ToString " />
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