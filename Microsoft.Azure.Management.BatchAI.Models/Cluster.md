<Type Name="Cluster" FullName="Microsoft.Azure.Management.BatchAI.Models.Cluster">
  <TypeSignature Language="C#" Value="public class Cluster : Microsoft.Azure.Management.BatchAI.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Cluster extends Microsoft.Azure.Management.BatchAI.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.Cluster" />
  <TypeSignature Language="VB.NET" Value="Public Class Cluster&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Cluster = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.BatchAI.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Enthält Informationen zu einem Cluster.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Cluster ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.Cluster.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Cluster-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Cluster (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string vmSize = null, Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; vmPriority = null, Microsoft.Azure.Management.BatchAI.Models.ScaleSettings scaleSettings = null, Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration virtualMachineConfiguration = null, Microsoft.Azure.Management.BatchAI.Models.NodeSetup nodeSetup = null, Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings userAccountSettings = null, Microsoft.Azure.Management.BatchAI.Models.ResourceId subnet = null, Nullable&lt;DateTime&gt; creationTime = null, Microsoft.Azure.Management.BatchAI.Models.ProvisioningState provisioningState = Microsoft.Azure.Management.BatchAI.Models.ProvisioningState.Creating, Nullable&lt;DateTime&gt; provisioningStateTransitionTime = null, Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.AllocationState&gt; allocationState = null, Nullable&lt;DateTime&gt; allocationStateTransitionTime = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; errors = null, Nullable&lt;int&gt; currentNodeCount = null, Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts nodeStateCounts = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string vmSize, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; vmPriority, class Microsoft.Azure.Management.BatchAI.Models.ScaleSettings scaleSettings, class Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration virtualMachineConfiguration, class Microsoft.Azure.Management.BatchAI.Models.NodeSetup nodeSetup, class Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings userAccountSettings, class Microsoft.Azure.Management.BatchAI.Models.ResourceId subnet, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype Microsoft.Azure.Management.BatchAI.Models.ProvisioningState provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; provisioningStateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.AllocationState&gt; allocationState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; allocationStateTransitionTime, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; errors, valuetype System.Nullable`1&lt;int32&gt; currentNodeCount, class Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts nodeStateCounts) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.Cluster.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{Microsoft.Azure.Management.BatchAI.Models.VmPriority},Microsoft.Azure.Management.BatchAI.Models.ScaleSettings,Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration,Microsoft.Azure.Management.BatchAI.Models.NodeSetup,Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings,Microsoft.Azure.Management.BatchAI.Models.ResourceId,System.Nullable{System.DateTime},Microsoft.Azure.Management.BatchAI.Models.ProvisioningState,System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.BatchAI.Models.AllocationState},System.Nullable{System.DateTime},System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.BatchAIError},System.Nullable{System.Int32},Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.Cluster : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; * Microsoft.Azure.Management.BatchAI.Models.ScaleSettings * Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration * Microsoft.Azure.Management.BatchAI.Models.NodeSetup * Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings * Microsoft.Azure.Management.BatchAI.Models.ResourceId * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.BatchAI.Models.ProvisioningState * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.AllocationState&gt; * Nullable&lt;DateTime&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts -&gt; Microsoft.Azure.Management.BatchAI.Models.Cluster" Usage="new Microsoft.Azure.Management.BatchAI.Models.Cluster (id, name, type, location, tags, vmSize, vmPriority, scaleSettings, virtualMachineConfiguration, nodeSetup, userAccountSettings, subnet, creationTime, provisioningState, provisioningStateTransitionTime, allocationState, allocationStateTransitionTime, errors, currentNodeCount, nodeStateCounts)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="vmPriority" Type="System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt;" />
        <Parameter Name="scaleSettings" Type="Microsoft.Azure.Management.BatchAI.Models.ScaleSettings" />
        <Parameter Name="virtualMachineConfiguration" Type="Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration" />
        <Parameter Name="nodeSetup" Type="Microsoft.Azure.Management.BatchAI.Models.NodeSetup" />
        <Parameter Name="userAccountSettings" Type="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings" />
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.BatchAI.Models.ResourceId" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="provisioningState" Type="Microsoft.Azure.Management.BatchAI.Models.ProvisioningState" />
        <Parameter Name="provisioningStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="allocationState" Type="System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.AllocationState&gt;" />
        <Parameter Name="allocationStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="errors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt;" />
        <Parameter Name="currentNodeCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="nodeStateCounts" Type="Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts" />
      </Parameters>
      <Docs>
        <param name="id">Die ID der Ressource</param>
        <param name="name">Der Name der Ressource</param>
        <param name="type">Der Typ der Ressource</param>
        <param name="location">Der Speicherort der Ressource</param>
        <param name="tags">Die Tags der Ressource</param>
        <param name="vmSize">Die Größe der virtuellen Computer im Cluster.</param>
        <param name="vmPriority">dedizierte oder Lowpriority.</param>
        <param name="scaleSettings">Gewünschte Skalierung für den Cluster.</param>
        <param name="virtualMachineConfiguration">Einstellungen für das Betriebssystem-Image und Datenvolumes bereitgestellt.</param>
        <param name="nodeSetup">Setup, um auf allen Serverknoten im Cluster ausgeführt werden.</param>
        <param name="userAccountSettings">Einstellungen für das Benutzerkonto des Compute-Knoten.</param>
        <param name="subnet">Gibt den Bezeichner des Subnetzes.</param>
        <param name="creationTime">Der Zeitpunkt der Erstellung des Clusters.</param>
        <param name="provisioningState">Gibt den Bereitstellungsstatus des Clusters an.</param>
        <param name="provisioningStateTransitionTime">Die Status Übergang Bereitstellungszeit des Clusters.</param>
        <param name="allocationState">Gibt an, ob der Cluster die Größe ändert.</param>
        <param name="allocationStateTransitionTime">Der Zeitpunkt, zu dem Cluster seinen aktuellen Zuordnungsstatus erlangt hat.</param>
        <param name="errors">Enthält Details zu verschiedenen Fehlern auf dem Cluster, einschließlich Größe und die Knoten dem Setup durchzuführende Aufgabe</param>
        <param name="currentNodeCount">Die Anzahl von Compute-Knoten dem Cluster zugewiesen werden soll.</param>
        <param name="nodeStateCounts">Die Anzahl der Status der verschiedenen Knoten im Cluster.</param>
        <summary>
            Initialisiert eine neue Instanz der Cluster-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.AllocationState&gt; AllocationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.AllocationState&gt; AllocationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.AllocationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationState As Nullable(Of AllocationState)" />
      <MemberSignature Language="F#" Value="member this.AllocationState : Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.AllocationState&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.AllocationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allocationState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.AllocationState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft gibt an, ob der Cluster die Größe ändert.
            </summary>
        <value>To be added.</value>
        <remarks>
            Mögliche Werte sind: stetige und Größenänderung von Fenstern annimmt. gleich bleibenden Status Gibt an, dass der Cluster nicht Größe ist. Es sind keine Änderungen auf die Anzahl von Serverknoten im Cluster ausgeführt. Ein Cluster in diesen Status versetzt, während der Erstellung und keine Vorgänge für den Cluster so ändern Sie die Anzahl der Serverknoten ausgeführt werden. Ändern der Größe von Status Gibt an, dass das Ändern der Größe des Clusters; d. h. berechnen Knoten werden hinzugefügt oder aus dem Cluster entfernt.
            Folgende Werte sind möglich: "stabilen", "Größe"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AllocationStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AllocationStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.AllocationStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AllocationStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.AllocationStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allocationStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitpunkt, zu dem Cluster seinen aktuellen Zuordnungsstatus erlangt hat.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitpunkt der Erstellung des Clusters ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentNodeCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentNodeCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentNodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.CurrentNodeCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentNodeCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentNodeCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.CurrentNodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentNodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl von Compute-Knoten dem Cluster zugewiesen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; Errors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.Errors" />
      <MemberSignature Language="VB.NET" Value="Public Property Errors As IList(Of BatchAIError)" />
      <MemberSignature Language="F#" Value="member this.Errors : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt enthält Details zu verschiedenen Fehlern auf dem Cluster, einschließlich Größe und die Knoten dem Setup durchzuführende Aufgabe
            </summary>
        <value>To be added.</value>
        <remarks>
            Dieses Element enthält alle Fehler, die von verschiedenen Serverknoten während des Setups Knoten gefunden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeSetup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.NodeSetup NodeSetup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.NodeSetup NodeSetup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.NodeSetup" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeSetup As NodeSetup" />
      <MemberSignature Language="F#" Value="member this.NodeSetup : Microsoft.Azure.Management.BatchAI.Models.NodeSetup with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.NodeSetup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nodeSetup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.NodeSetup</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Setup auf allen Serverknoten im Cluster ausgeführt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeStateCounts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts NodeStateCounts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts NodeStateCounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.NodeStateCounts" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeStateCounts As NodeStateCounts" />
      <MemberSignature Language="F#" Value="member this.NodeStateCounts : Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.NodeStateCounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nodeStateCounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Status der verschiedenen Knoten im Cluster ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ProvisioningState ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.BatchAI.Models.ProvisioningState ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As ProvisioningState" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Microsoft.Azure.Management.BatchAI.Models.ProvisioningState" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft gibt den Bereitstellungsstatus des Clusters an.
            </summary>
        <value>To be added.</value>
        <remarks>
            Mögliche Werte sind: Erstellen von - gibt an, dass der Cluster erstellt wird. erfolgreich – gibt an, dass der Cluster wurde erfolgreich erstellt wurde. Fehler – gibt an, dass es sich bei der Clustererstellung fehlgeschlagen ist. wird gelöscht – gibt an, dass der Cluster gelöscht wird.
            Folgende Werte sind möglich: "erstellen", "erfolgreich abgeschlossen", "fehlgeschlagen", "löschen"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ProvisioningStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ProvisioningStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.ProvisioningStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.ProvisioningStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Zeit bis Übergang in Bereitstellung Zustand des Clusters ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScaleSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ScaleSettings ScaleSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ScaleSettings ScaleSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.ScaleSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ScaleSettings As ScaleSettings" />
      <MemberSignature Language="F#" Value="member this.ScaleSettings : Microsoft.Azure.Management.BatchAI.Models.ScaleSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.ScaleSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scaleSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ScaleSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gewünschte Skalierung für den Cluster.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ResourceId Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ResourceId Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As ResourceId" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.BatchAI.Models.ResourceId with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.Subnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ResourceId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt den Bezeichner des Subnetzes an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccountSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings UserAccountSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings UserAccountSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.UserAccountSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccountSettings As UserAccountSettings" />
      <MemberSignature Language="F#" Value="member this.UserAccountSettings : Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.UserAccountSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.userAccountSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-Einstellungen für das Benutzerkonto des Compute-Knoten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.Cluster.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cluster.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration VirtualMachineConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration VirtualMachineConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.VirtualMachineConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineConfiguration As VirtualMachineConfiguration" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineConfiguration : Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.VirtualMachineConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualMachineConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-Einstellungen für Betriebssystem-Image und Datenvolumes bereitgestellt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VmPriority">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; VmPriority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; VmPriority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.VmPriority" />
      <MemberSignature Language="VB.NET" Value="Public Property VmPriority As Nullable(Of VmPriority)" />
      <MemberSignature Language="F#" Value="member this.VmPriority : Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.VmPriority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmPriority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder dedizierte Gruppen oder Lowpriority.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert ist vorgesehen. Der Knoten kann vorzeitig abrufen, während die Aufgabe ausgeführt wird, wenn Lowpriority ausgewählt ist. Dies eignet sich am besten, wenn die arbeitsauslastung prüfpunktausführung vorgenommen und neu gestartet werden kann. Folgende Werte sind möglich: "dediziertes", "Lowpriority"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Größe der virtuellen Computer im Cluster.
            </summary>
        <value>To be added.</value>
        <remarks>
            Alle virtuellen Computer in einem Cluster haben die gleiche Größe. Informationen zu den verfügbaren VM-Größen für Cluster, die mithilfe von Images von virtuellen Maschinen Marketplace (Siehe Größen für virtuelle Maschinen (Linux) oder Größen für virtuelle Computer (Windows). AI-Batch-Dienst unterstützt alle Azure-VM-Größen außer STANDARD_A0 und die mit Premium-Speicher (STANDARD_GS STANDARD_DS und STANDARD_DSV2-Serie).
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>