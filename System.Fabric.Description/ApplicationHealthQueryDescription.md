<Type Name="ApplicationHealthQueryDescription" FullName="System.Fabric.Description.ApplicationHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type ApplicationHealthQueryDescription = class" />
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
      <para>Stellt die abfrageeingabe zum Abrufen der Anwendungsintegrität dar. Wird von <see cref="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription)" /> verwendet.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationHealthQueryDescription (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationHealthQueryDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationHealthQueryDescription : Uri -&gt; System.Fabric.Description.ApplicationHealthQueryDescription" Usage="new System.Fabric.Description.ApplicationHealthQueryDescription applicationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der Anwendungsname. Nicht mit <languageKeyword>null</languageKeyword>.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>Ein null-Wert wurde für einen erforderlichen Parameter übergeben.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" />
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
    <Member MemberName="DeployedApplicationsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedApplicationHealthStatesFilter DeployedApplicationsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedApplicationHealthStatesFilter DeployedApplicationsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.DeployedApplicationsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property DeployedApplicationsFilter As DeployedApplicationHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.DeployedApplicationsFilter : System.Fabric.Health.DeployedApplicationHealthStatesFilter with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.DeployedApplicationsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedApplicationHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den Filter für <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> untergeordneten Elemente. Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben. Alle untergeordneten Elemente dienen zum Auswerten des integritätszustands der Anwendung aggregiert.</para>
        </summary>
        <value>
          <para>Der Filter für <see cref="T:System.Fabric.Health.DeployedApplicationHealthStatesFilter" /> untergeordneten Elemente.</para>
        </value>
        <remarks>
          <para> Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben. Alle untergeordneten Elemente dienen zum Auswerten des integritätszustands der Anwendung aggregiert.
            Wenn der Filter nicht angegeben ist, werden alle bereitgestellten Anwendung untergeordneten Elemente der Anwendung zurückgegeben.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.EventsFilter" />
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
          <para>Ruft ab oder legt Sie den Filter für die Auflistung von <see cref="T:System.Fabric.Health.HealthEvent" /> für die Anwendung gemeldet. Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben. Alle Ereignisse dienen zum Auswerten des integritätszustands der Anwendung aggregiert.</para>
        </summary>
        <value>
          <para>Der Filter für die Auflistung von <see cref="T:System.Fabric.Health.HealthEvent" /> für die Anwendung gemeldet.</para>
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.HealthPolicy" />
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
          <para>Ruft ab oder legt die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> verwendet, um den Anwendungszustand auszuwerten.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> zum Auswerten der Anwendungsintegrität verwendet.</para>
        </value>
        <remarks>Wenn nicht angegeben, verwendet den Health-Speicher die Anwendung Integritätsrichtlinie, die im Anwendungsmanifest angegebene zum Auswerten der Anwendung.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As ApplicationHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.ApplicationHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Integrität Statistiken Filter.
            </summary>
        <value>Der Filter für den Integritäts-Statistiken.</value>
        <remarks>
          <para>
            Filtersteuerelementen gibt an, ob die Statistiken für die Integrität der <see cref="T:System.Fabric.Health.ApplicationHealth" /> zurückgegeben werden, indem Sie die Abfrage enthält, die Integrität Anwendungsstatistiken. Wenn nicht angegeben, werden die Statistiken enthalten.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicesFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ServiceHealthStatesFilter ServicesFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ServiceHealthStatesFilter ServicesFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.ServicesFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicesFilter As ServiceHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.ServicesFilter : System.Fabric.Health.ServiceHealthStatesFilter with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.ServicesFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ServiceHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den Filter für <see cref="T:System.Fabric.Health.ServiceHealthState" /> untergeordneten Elemente. Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben. Alle untergeordneten Elemente dienen zum Auswerten des integritätszustands der Anwendung aggregiert.</para>
        </summary>
        <value>
          <para>Der Filter für <see cref="T:System.Fabric.Health.ServiceHealthState" /> untergeordneten Elemente.</para>
        </value>
        <remarks>
          <para> Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben. Alle untergeordneten Elemente dienen zum Auswerten des integritätszustands der Anwendung aggregiert.
            Wenn der Filter nicht angegeben ist, werden alle untergeordneten Objekte Dienst die Anwendung zurückgegeben.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthQueryDescription.ToString " />
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