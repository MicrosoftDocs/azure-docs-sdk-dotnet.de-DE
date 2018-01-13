<Type Name="ApplicationHealthStateFilter" FullName="System.Fabric.Health.ApplicationHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthStateFilter" />
  <TypeSignature Language="F#" Value="type ApplicationHealthStateFilter = class" />
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
            Filter für <see cref="T:System.Fabric.Health.ApplicationHealthState" /> Objekte.
            </summary>
    <remarks>Die Entität Health Status Block Abfragen können angeben, eine Liste der feine Anwendungsfilter wählen Sie die Anwendungen, die in das Abfrageergebnis aufgenommen werden.
            Beachten Sie, dass alle Anwendungen zur Bewertung des Integritätsstatus des Clusters aggregiert, unabhängig von den Filter übergeben.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ApplicationHealthStateFilter" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationNameFilter">
      <MemberSignature Language="C#" Value="public Uri ApplicationNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateFilter.ApplicationNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationNameFilter As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationNameFilter : Uri with get, set" Usage="System.Fabric.Health.ApplicationHealthStateFilter.ApplicationNameFilter" />
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
            Abrufen oder Festlegen der Anwendung Namensfilter.
            </summary>
        <value>Die Anwendung Namensfilter.</value>
        <remarks>Wenn angegeben, gilt der Filter nur auf die gewünschte Anwendung. Für die Anwendung, die dem Filter entsprechen muss der aggregierte Integritätszustand der angegebenen Integrität Statusfilter übereinstimmen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeNameFilter">
      <MemberSignature Language="C#" Value="public string ApplicationTypeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateFilter.ApplicationTypeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeNameFilter : string with get, set" Usage="System.Fabric.Health.ApplicationHealthStateFilter.ApplicationTypeNameFilter" />
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
            Abrufen oder Festlegen der Anwendung Namen Typfilter.
            </summary>
        <value>Die Anwendung Typ Namensfilter.</value>
        <remarks>Wenn angegeben, gilt der Filter für alle Anwendungen vom angegebenen Typ, die einen spezifischeren Filter (für einen bestimmten Anwendungsnamen) besitzen.
            Für eine Anwendung, die dem Filter entsprechen muss der aggregierte Integritätszustand der angegebenen Integrität Statusfilter übereinstimmen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedApplicationFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthStateFilter&gt; DeployedApplicationFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.DeployedApplicationHealthStateFilter&gt; DeployedApplicationFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateFilter.DeployedApplicationFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedApplicationFilters As IList(Of DeployedApplicationHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.DeployedApplicationFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthStateFilter&gt;" Usage="System.Fabric.Health.ApplicationHealthStateFilter.DeployedApplicationFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der <see cref="T:System.Fabric.Health.DeployedApplicationHealthStateFilter" /> auf des Integritätsstatus der bereitgestellten Anwendung untergeordnete Elemente angewendet werden soll.
            </summary>
        <value>Die Liste der <see cref="T:System.Fabric.Health.DeployedApplicationHealthStateFilter" /> auf des Integritätsstatus der bereitgestellten Anwendung untergeordnete Elemente angewendet werden soll.</value>
        <remarks>Die Liste kann es sich um ein Standard-bereitgestellten Anwendung oder die bereitgestellte Anwendungsfilter für bestimmte bereitgestellte Anwendungen auf feine-Entitäten, die von der Abfrage zurückgegebenen enthalten.
            Alle bereitgestellten Anwendung, die untergeordnete Elemente, die dem Filter entsprechen, als untergeordnete Elemente der Anwendung zurückgegeben werden.
            Ohne Angabe werden die untergeordneten Elemente standardmäßig nicht zurückgegeben.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.ApplicationHealthStateFilter.HealthStateFilter" />
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
            Ruft ab oder legt Sie Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.ApplicationHealthState" /> Einträge in der Auflistung. 
            </summary>
        <value>Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.ApplicationHealthState" /> Einträge in der Auflistung.</value>
        <remarks>Die Integrität statusfilterwert stammen von Membern oder bitweisen Kombination von Membern der <see cref="T:System.Fabric.Health.HealthStateFilter" />. Für eine Anwendung, die dem Filter entsprechen muss der aggregierte Integritätszustand der angegebenen Integrität Statusfilter übereinstimmen.
            Wenn die Integrität Statusfilter Standard, standardmäßig der Statusfilter Integrität auf None, wenn es keine spezifischen Filter (Anwendungsname oder Name des Anwendungstyps sind).
            Andernfalls gilt der Standardfilter für alle gelten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthStateFilter&gt; ServiceFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ServiceHealthStateFilter&gt; ServiceFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateFilter.ServiceFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceFilters As IList(Of ServiceHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.ServiceFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthStateFilter&gt;" Usage="System.Fabric.Health.ApplicationHealthStateFilter.ServiceFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der <see cref="T:System.Fabric.Health.ServiceHealthStateFilter" /> auf die untergeordneten Elemente dienstintegritätszustände angewendet werden soll.
            </summary>
        <value>Die Liste der <see cref="T:System.Fabric.Health.ServiceHealthStateFilter" /> auf die untergeordneten Elemente dienstintegritätszustände angewendet werden soll.</value>
        <remarks>Die Liste kann es sich um eine Standard-Dienst oder die Service Filter für bestimmte Dienste feine-Entitäten, die von der Abfrage zurückgegebenen enthalten.
            Alle Service untergeordneten Elemente, die dem Filter entsprechen, werden als untergeordnete Elemente der Anwendung zurückgegeben.
            Ohne Angabe werden die untergeordneten Elemente standardmäßig nicht zurückgegeben.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthStateFilter.ToString " />
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