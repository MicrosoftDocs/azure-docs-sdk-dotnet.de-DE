<Type Name="ClusterHealthChunkQueryDescription" FullName="System.Fabric.Description.ClusterHealthChunkQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ClusterHealthChunkQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterHealthChunkQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ClusterHealthChunkQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterHealthChunkQueryDescription" />
  <TypeSignature Language="F#" Value="type ClusterHealthChunkQueryDescription = class" />
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
            Beschreibt die Cluster Health Block abfrageeingaben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthChunkQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ClusterHealthChunkQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ClusterHealthChunkQueryDescription" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthStateFilter&gt; ApplicationFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ApplicationHealthStateFilter&gt; ApplicationFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthChunkQueryDescription.ApplicationFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationFilters As IList(Of ApplicationHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.ApplicationFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthStateFilter&gt;" Usage="System.Fabric.Description.ClusterHealthChunkQueryDescription.ApplicationFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der <see cref="T:System.Fabric.Health.ApplicationHealthStateFilter" /> auf die untergeordneten Elemente anwendungsintegritätszustände angewendet werden soll.
            </summary>
        <value>Die Liste der <see cref="T:System.Fabric.Health.ApplicationHealthStateFilter" /> auf die untergeordneten Elemente anwendungsintegritätszustände angewendet werden soll.</value>
        <remarks>Die Liste kann eine Anwendung-Standardfilter und/oder Anwendungsfilter für bestimmte Anwendungen oder Anwendungstypen feine-Entitäten, die von der Abfrage zurückgegebenen enthalten.
            Alle Anwendung untergeordneten Elemente, die dem Filter entsprechen, werden als untergeordnete Elemente des Clusters zurückgegeben.
            Falls leer, wird keine Anwendung zurückgegeben.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationHealthPolicies">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicies" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthChunkQueryDescription.ApplicationHealthPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationHealthPolicies As ApplicationHealthPolicyMap" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthPolicies : System.Fabric.Health.ApplicationHealthPolicyMap" Usage="System.Fabric.Description.ClusterHealthChunkQueryDescription.ApplicationHealthPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthPolicyMap</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die anwendungsintegritätsrichtlinien zum Auswerten der Integritäts der Anwendungen aus dem Cluster an. 
            </summary>
        <value>Die Integritätsrichtlinien für die Anwendung verwendet, um den Zustand des angegebenen auszuwerten.</value>
        <remarks>Jeder Eintrag gibt an, wie der Anwendungsname Schlüssel und als Wert ein <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> verwendet, um den Anwendungszustand auszuwerten.
            Wenn eine Anwendung nicht in der Zuordnung angegeben wird, wird die ApplicationHealthPolicy gefunden, die im Anwendungsmanifest für die Auswertung verwendet werden. Die Zuordnung ist standardmäßig leer.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterHealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthPolicy ClusterHealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthPolicy ClusterHealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthChunkQueryDescription.ClusterHealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterHealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.ClusterHealthPolicy : System.Fabric.Health.ClusterHealthPolicy with get, set" Usage="System.Fabric.Description.ClusterHealthChunkQueryDescription.ClusterHealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> verwendet, um den Clusterzustand auszuwerten. 
            </summary>
        <value>die <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> verwendet, um den Clusterzustand auszuwerten.</value>
        <remarks>Die Richtlinie wird zum Auswerten der aggregierte Integritätszustand der Ereignisse gemeldet und der aggregierte Integritätszustand der Knoten verwendet werden.
            Wenn nicht angegeben, werden die clusterintegritätsrichtlinie, die in das Manifest oder in der Standard-clusterintegritätsrichtlinie beschrieben verwendet.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.NodeHealthStateFilter&gt; NodeFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.NodeHealthStateFilter&gt; NodeFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthChunkQueryDescription.NodeFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeFilters As IList(Of NodeHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.NodeFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.NodeHealthStateFilter&gt;" Usage="System.Fabric.Description.ClusterHealthChunkQueryDescription.NodeFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.NodeHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der <see cref="T:System.Fabric.Health.NodeHealthStateFilter" /> auf die untergeordneten Elemente knotenintegritätszustände angewendet werden soll.
            </summary>
        <value>Die Liste der <see cref="T:System.Fabric.Health.NodeHealthStateFilter" /> auf die untergeordneten Elemente knotenintegritätszustände angewendet werden soll.</value>
        <remarks>
            Alle Knoten untergeordnete Elemente, die dem Filter entsprechen, werden als untergeordnete Elemente des Clusters zurückgegeben.
            Falls leer, wird kein Knoten zurückgegeben.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>