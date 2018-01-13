<Type Name="DeployedServicePackageHealthQueryDescription" FullName="System.Fabric.Description.DeployedServicePackageHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.DeployedServicePackageHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthQueryDescription = class" />
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
      <para>Beschreibt die als abfrageeingabe für die erste <see cref="T:System.Fabric.Health.DeployedServicePackageHealth" />. Wird von <see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Fabric.Description.DeployedServicePackageHealthQueryDescription)" /> verwendet.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthQueryDescription (Uri applicationName, string nodeName, string serviceManifestName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string nodeName, string serviceManifestName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.#ctor(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, nodeName As String, serviceManifestName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.DeployedServicePackageHealthQueryDescription : Uri * string * string -&gt; System.Fabric.Description.DeployedServicePackageHealthQueryDescription" Usage="new System.Fabric.Description.DeployedServicePackageHealthQueryDescription (applicationName, nodeName, serviceManifestName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der Anwendungsname. Darf nicht NULL sein.</para>
        </param>
        <param name="nodeName">
          <para>Der Knotenname. Darf weder NULL noch leer sein.</para>
        </param>
        <param name="serviceManifestName">
          <para>Der dienstmanifestname. Darf weder NULL noch leer sein.</para>
        </param>
        <summary>
          <para>Instanziiert eine <see cref="T:System.Fabric.Description.DeployedServicePackageHealthQueryDescription" /> Klasse.</para>
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
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthQueryDescription (Uri applicationName, string nodeName, string serviceManifestName, string servicePackageActivationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string nodeName, string serviceManifestName, string servicePackageActivationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.#ctor(System.Uri,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, nodeName As String, serviceManifestName As String, servicePackageActivationId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.DeployedServicePackageHealthQueryDescription : Uri * string * string * string -&gt; System.Fabric.Description.DeployedServicePackageHealthQueryDescription" Usage="new System.Fabric.Description.DeployedServicePackageHealthQueryDescription (applicationName, nodeName, serviceManifestName, servicePackageActivationId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der Anwendungsname. Darf nicht NULL sein.</para>
        </param>
        <param name="nodeName">
          <para>Der Knotenname. Darf weder NULL noch leer sein.</para>
        </param>
        <param name="serviceManifestName">
          <para>Der dienstmanifestname. Darf weder NULL noch leer sein.</para>
        </param>
        <param name="servicePackageActivationId">
          <para>
            Die <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> des bereitgestellten Dienstpakets.
            ServicePackageActivationId für ein bereitgestelltes Dienstpaket kann abgerufen, indem <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> Abfrage. 
            </para>
          <para>
            Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung der Dienst ist <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wird, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.
            Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.
            </para>
        </param>
        <summary>
          <para>Instanziiert eine <see cref="T:System.Fabric.Description.DeployedServicePackageHealthQueryDescription" /> Klasse.</para>
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" />
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
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.EventsFilter" />
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
          <para>Ruft ab oder legt Sie den Filter für die Auflistung von <see cref="T:System.Fabric.Health.HealthEvent" /> für das Paket bereitgestellten Dienst gemeldet. Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben. Alle Ereignisse werden zum Auswerten der aggregierten integritätszustands verwendet werden.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.Health.HealthEventsFilter" /> verwendet, um die zurückgegebenen Ereignisse gefiltert.</para>
        </value>
        <remarks>
          <para> Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben. Alle Ereignisse dienen zum Auswerten des integritätszustands der Entität, die aggregiert.
            Wenn der Filter nicht angegeben wird, werden alle Ereignisse zurückgegeben.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.HealthPolicy" />
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
          <para>Ruft ab oder legt die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> verwendet, um den Zustand auszuwerten.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> zur Bewertung der Integrität.</para>
        </value>
        <remarks>Wenn nicht angegeben, verwendet der Health Store einer anwendungsintegritäts-Richtlinie für die übergeordnete Anwendung zur bereitgestellten dienstpaketintegrität Auswertung an.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.NodeName" />
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
          <para>Die <see cref="T:System.String" /> , der Name des Knotens darstellt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ServiceManifestName" />
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
          <para>Ruft den Namen des Dienst-Manifests ab.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.String" /> der dienstmanifestname darstellt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ServicePackageActivationId" />
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
            Ruft die ActivationId des Dienstpakets ab.
            </summary>
        <value>
          <para>
            Die <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> des bereitgestellten Dienstpakets. ServicePackageActivationId für ein bereitgestelltes Dienstpaket kann abgerufen, indem <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> Abfrage. 
            </para>
          <para>
            Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung der Dienst ist <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wird, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.
            Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />. 
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedServicePackageHealthQueryDescription.ToString " />
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