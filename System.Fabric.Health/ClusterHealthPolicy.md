<Type Name="ClusterHealthPolicy" FullName="System.Fabric.Health.ClusterHealthPolicy">
  <TypeSignature Language="C#" Value="public class ClusterHealthPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterHealthPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ClusterHealthPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterHealthPolicy" />
  <TypeSignature Language="F#" Value="type ClusterHealthPolicy = class" />
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
      <para>Definiert eine Integritätsrichtlinie, die zur Bewertung der Integritäts des Clusters oder eines Clusterknotens.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ClusterHealthPolicy" />-Klasse.</para>
        </summary>
        <remarks>Standardmäßig werden keine Fehler oder Warnungen toleriert werden.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationTypeHealthPolicyMap ApplicationTypeHealthPolicyMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationTypeHealthPolicyMap ApplicationTypeHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthPolicy.ApplicationTypeHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeHealthPolicyMap As ApplicationTypeHealthPolicyMap" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeHealthPolicyMap : System.Fabric.Health.ApplicationTypeHealthPolicyMap" Usage="System.Fabric.Health.ClusterHealthPolicy.ApplicationTypeHealthPolicyMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationTypeHealthPolicyMap</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft die Zuordnung mit MaxPercentUnhealthyApplications pro Anwendung Typnamen ab. 
            </para>
        </summary>
        <value>
          <para>Anwendung Integrität Richtlinie Typzuordnung mit MaxPercentUnhealthyApplications pro Name des Anwendungstyps.</para>
        </value>
        <remarks>
          <para>Anwendung Integrität Richtlinie Typzuordnung kann während integritätsevaluierung Cluster verwendet werden, um spezielle Anwendungstypen zu beschreiben. Standardmäßig werden alle Anwendungen in einem Pool versetzt und mit ausgewertet <see cref="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />. Wenn eine oder mehrere Anwendungstypen speziell sind und müssen Sitzungsschlüsseln auf eine andere Weise behandelt außerhalb des globalen Pools und anhand der Prozentsätze mit ihrer Anwendung Typnamen in der Zuordnung verknüpfte ausgewertet. Beispielsweise enthält ein Cluster Tausende von Anwendungen mit unterschiedlichen Typen und wenige Steueranwendungsinstanzen eines besonderen Anwendungstyps. Die Steueranwendungen dürfen niemals einen Fehlerstatus aufweisen. Daher können Benutzer angeben, globale MaxPercentUnhealthyApplications 20 % tolerieren einige, aber für die Anwendung vom Typ "ControlApplicationType" die MaxPercentUnhealthyApplications auf 0 festgelegt. Wenn einige der zahlreichen Anwendungen fehlerhaft sind, aber unter dem globalen Prozentsatz für fehlerhafte Anwendungen liegen, wird der Cluster mit einer Warnung ausgewertet. Der Integritätszustand „Warnung“ wirkt sich nicht auf ein Clusterupgrade oder auf andere Überwachungen aus, die durch den Integritätszustand „Fehler“ ausgelöst werden. Aber auch nur ein einziges Steuerelement Anwendung Fehler stellen Cluster Integritätsfehler, welche Rollback kann oder zu verhindern, dass eine clusterupgrade würde. </para>&gt;<para>Für die Anwendungstypen, die in der Zuordnung definiert wird, werden alle Anwendungsinstanzen aus den globalen Pool Anwendungen übernommen. Sie werden anhand des speziellen MaxPercentUnhealthyApplications-Werts aus der Zuordnung basierend auf der Gesamtanzahl von Anwendungen des Anwendungstyps ausgewertet. Alle übrigen Anwendungen verbleiben in den globalen Pool und mit MaxPercentUnhealthyApplications ausgewertet werden. </para> <para>Um Einträge für die bestimmte Anwendungstypen im clustermanifest zu definieren, FabricSettings fügen Sie Einträge für den Parameter mit dem Namen gebildet, indem das Präfix "ApplicationTypeMaxPercentUnhealthyApplications-" gefolgt von Name des Anwendungstyps. </para> <para>Wenn keine Richtlinie für einen Anwendungstyp angegeben wird, ist die Standardeinstellung MaxPercentUnhealthyApplications zur Auswertung verwendet.</para> <para>Die Anwendung Typ integritätsauswertung erfolgt nur, wenn der Cluster mit EnableApplicationTypeHealthEvaluation konfiguriert ist <languageKeyword>"true"</languageKeyword>. Die Einstellung ist standardmäßig deaktiviert.</para></remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsiderWarningAsError">
      <MemberSignature Language="C#" Value="public bool ConsiderWarningAsError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ConsiderWarningAsError" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthPolicy.ConsiderWarningAsError" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsiderWarningAsError As Boolean" />
      <MemberSignature Language="F#" Value="member this.ConsiderWarningAsError : bool with get, set" Usage="System.Fabric.Health.ClusterHealthPolicy.ConsiderWarningAsError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt einen <see cref="T:System.Boolean" /> , der bestimmt, ob Berichte mit Status "Warnung" mit den gleichen Schweregrad als Fehler behandelt werden sollen.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn Berichte mit Status "Warnung" als Fehler behandelt werden sollen <languageKeyword>"false"</languageKeyword> Wenn Warnungen nicht als Fehler behandelt werden sollen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyApplications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyApplications : byte with get, set" Usage="System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die maximal zulässigen Prozentsatz fehlerhafter Anwendungen.</para>
        </summary>
        <value>
          <para>Die maximal zulässige Prozentsatz fehlerhafter Anwendungen. Zulässige Werte sind ganzzahlige Werte von 0 bis 100.</para>
        </value>
        <remarks>
          <para>
            Der Prozentsatz entspricht dem maximalen tolerierten Prozentsatz an Anwendungen, die fehlerhaft sein können, bevor der Cluster als fehlerhaft behandelt wird. Wird der Prozentsatz eingehalten, gibt es aber mindestens eine fehlerhafte Anwendung, wird die Integrität als „Warning“ ausgewertet.
            Dies wird durch Dividieren der Anzahl der fehlerhaften Anwendungen über die Gesamtzahl der Anwendungen, die im Cluster ist, mit Ausnahme von Anwendungstypen, die in enthalten sind alle Anwendungen bereitgestellt berechnet die <see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />.
            Die Berechnung wird aufgerundet, um einen Fehler bei einer kleinen Anzahl von Anwendungen zu tolerieren. Standardprozentsatz : null.
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyNodes : byte with get, set" Usage="System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die maximal zulässigen Prozentsatz fehlerhafter Knoten.</para>
        </summary>
        <value>
          <para>Die maximal zulässige Prozentsatz fehlerhafter Knoten. Zulässige Werte sind ganzzahlige Werte von 0 bis 100.</para>
        </value>
        <remarks>
          <para>
            Der Prozentsatz entspricht dem maximalen tolerierten Prozentsatz an Knoten, die fehlerhaft sein können, bevor der Cluster als fehlerhaft behandelt wird. Wird der Prozentsatz eingehalten, gibt es aber mindestens einen fehlerhaften Knoten, wird die Integrität als „Warning“ ausgewertet.
            Dies wird durch Dividieren der Anzahl der fehlerhaften Knoten über die Gesamtanzahl der Knoten im Cluster berechnet.
            Die Berechnung wird aufgerundet, um einen Fehler auf einer kleinen Anzahl von Knoten zu tolerieren. Standardprozentsatz : null.
            </para>
          <para>Beim Konfigurieren dieses Prozentsatzes muss berücksichtigt werden, dass in großen Clustern immer einige Knoten inaktiv oder aufgrund von Wartungsarbeiten nicht verfügbar sind.</para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthPolicy.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterHealthPolicy.ToString " />
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
            Ruft eine Zeichenfolgendarstellung der clusterintegritätsrichtlinie ab.
            </summary>
        <returns>Eine Zeichenfolgendarstellung der clusterintegritätsrichtlinie.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>