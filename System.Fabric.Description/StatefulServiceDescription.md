<Type Name="StatefulServiceDescription" FullName="System.Fabric.Description.StatefulServiceDescription">
  <TypeSignature Language="C#" Value="public sealed class StatefulServiceDescription : System.Fabric.Description.ServiceDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatefulServiceDescription extends System.Fabric.Description.ServiceDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.StatefulServiceDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatefulServiceDescription&#xA;Inherits ServiceDescription" />
  <TypeSignature Language="F#" Value="type StatefulServiceDescription = class&#xA;    inherit ServiceDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServiceDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt das Erweitern <see cref="T:System.Fabric.Description.ServiceDescription" /> zum Bereitstellen zusätzlicher Informationen zum Erstellen von zustandsbehaftete Dienste erforderlich sind.</para>
    </summary>
    <remarks>
      <para />
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatefulServiceDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatefulServiceDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.StatefulServiceDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasPersistedState">
      <MemberSignature Language="C#" Value="public bool HasPersistedState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasPersistedState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.HasPersistedState" />
      <MemberSignature Language="VB.NET" Value="Public Property HasPersistedState As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasPersistedState : bool with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.HasPersistedState" />
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
          <para>Ruft ab oder legt einen Wert, der angibt, ob diese Instanz einen persistenten Zustand aufweist.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> , wenn die Instanz, wechselt, andernfalls beibehalten wurde <languageKeyword>"false"</languageKeyword>.</para>
        </value>
        <remarks>
          <para>Wenn eine <see cref="T:System.Fabric.FabricReplicator" /> an einem sekundären Replikat empfängt, einen Vorgang für einen permanenten Dienst, muss der Prinzipalserver wartet dabei für den Dienst zu bestätigen, dass die Daten persistent gespeichert wurde, bevor sie diese Bestätigung zurück an das primäre senden kann. Für nicht persistente Dienste kann der Vorgang sofort nach Erhalt bestätigt werden.</para>
          <para>Wenn ein Replikat der permanente Dienst ein Fehler auftritt, wird der Service Fabric nicht sofort dieses Replikat als verloren berücksichtigt, da für dieses Replikat der permanente Status noch vorhanden ist. Wenn das Replikat wiederhergestellt wird, kann es mit dem beibehaltenen Zustand neu erstellt. Im Gegensatz dazu ab, um ein Ersatz-Replikat sofort erstellen möglicherweise kostenintensive und unnötig, insbesondere, wenn die Fehler vorübergehend sind. Verwenden Sie zum Konfigurieren, wie lange Service Fabric warten soll, für die permanente Replikat her, bevor Sie ein neues Replikat für (Austausch) von Grund auf neu erstellen, die <see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" /> Parameter. Für nicht persistente Dienste (mit <see cref="P:System.Fabric.Description.StatefulServiceDescription.HasPersistedState" /> festgelegt <languageKeyword>"false"</languageKeyword>), Service Fabric beginnt sofort mit dem Erstellen eines neuen Replikats (da kein persistenten Zustand die Wiederherstellung, und daher kein Punkt beim Warten auf lokale Wiederherstellung ).</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MinReplicaSetSize">
      <MemberSignature Language="C#" Value="public int MinReplicaSetSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MinReplicaSetSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MinReplicaSetSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MinReplicaSetSize : int with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die zulässige Mindestgröße des Replikatsatzes Satz Größe für diesen Dienst fest.</para>
        </summary>
        <value>
          <para>Der kleinste zulässige Größe des Replikats für diesen Dienst.</para>
        </value>
        <remarks>
          <para>Definiert die minimale Anzahl der Replikate, die Service Fabric in eine Ansicht der Replikatgruppe für eine bestimmte Partition beibehalten werden sollen. Beispielsweise, wenn die <see cref="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" /> ist auf fünf (5) (fehlerfrei) normalerweise dann dort festgelegt werden fünf Replikate in der Ansicht des Replikatsatzes. Diese Zahl wird jedoch bei Ausfällen verringern. Die <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /> definiert die minimale Anzahl der Replikate in der Ansicht z. B. wenn die <see cref="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" /> werden fünf und die <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /> ist drei, und auch wenn drei gleichzeitiger Ausfälle (wodurch nur zwei verbleibenden Replikaten ausgeführt) werden, muss drei Replikate in der Ansicht der Replikatgruppe (zwei oben bzw. nach unten). Seit  
            verwendet mehrheitsquorummodus, der die Anzahl der Replikate, die in dieser Ansicht des mehrheitsquorummodus verwaltet die <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /> ist die minimale Maß an Zuverlässigkeit eines: im vorherigen Beispiel mit Ziel = 5 und Min = 3, mit 3 gleichzeitiger Ausfälle, es gibt zwei verbleibende einrichten Replikate (und ein nach unten), und die mehrheitsquorummodus 3 (die <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />) ist 2. Dies bedeutet, dass der primären weiterhin Vorgänge replizieren können, dass es sich bei das verbleibende sekundäre Replikat den Vorgang in der Reihenfolge für das Replikat angewendet werden muss (Partition) Fortschritte festlegen. Wenn die Anzahl von Replikaten unter der mehrheitsquorummodus von fällt die <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /> und weiteren Schreibvorgänge nicht zulässig sind.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="QuorumLossWaitDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; QuorumLossWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; QuorumLossWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.QuorumLossWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property QuorumLossWaitDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.QuorumLossWaitDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.QuorumLossWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die maximale Dauer in Sekunden, für die eine Partition in einem Zustand des quorumverlusts sein darf.</para>
        </summary>
        <value>
          <para>Die Wartedauer als ein <see cref="T:System.TimeSpan" /> Objekt.</para>
        </value>
        <remarks>
          <para>Wenn die Partition noch quorumsverlust nach Ablauf dieses Zeitraums wird, wird die Partition von quorumsverlusten wiederhergestellt, Hinblick auf die nach-unten Replikate als verloren. Beachten Sie, dass dies möglicherweise Datenverluste verursachen kann. Der Standardwert ist unendlich, und es wird nicht empfohlen, diesen Wert zu ändern.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaRestartWaitDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ReplicaRestartWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ReplicaRestartWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicaRestartWaitDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ReplicaRestartWaitDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die Dauer in Sekunden zwischen Wenn ein Replikat ausfällt und wann ein neues Replikat erstellt wird.</para>
        </summary>
        <value>
          <para>Die Dauer als ein <see cref="T:System.TimeSpan" /> Objekt.</para>
        </value>
        <remarks>
          <para>Ein Replikat der permanente ausfällt, wird dieser Zeitgeber gestartet.  Nach Ablauf der Evaluierung wird Service Fabric ein neues Replikat auf einem beliebigen Knoten im Cluster erstellt. Diese Konfiguration ist um unnötige Zustand Kopien zu reduzieren. Wenn eine beibehaltene Replikat ausfällt, wird das System wartet, dafür für wiederkehren <see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" /> Sekunden, bevor Sie ein neues Replikat die benötigen eine Kopie erstellen. Beachten Sie, dass ein Replikat, das nicht ausgeführt wird, nicht berücksichtigt wird verloren hat, noch.</para>
          <para>Der Standardwert ist 300 (Sekunden).</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StandByReplicaKeepDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; StandByReplicaKeepDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; StandByReplicaKeepDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.StandByReplicaKeepDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property StandByReplicaKeepDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StandByReplicaKeepDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.StandByReplicaKeepDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft auf oder legt die Definition wie lange StandBy-Replikaten beibehalten werden soll, bevor Sie entfernt werden.</para>
        </summary>
        <value>
          <para>Die Definition für wie lange StandBy-Replikaten beibehalten werden soll, bevor Sie entfernt werden.</para>
        </value>
        <remarks>
          <para>In einigen Fällen ein Replikat wird inaktiv sein länger als die <see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />. In diesen Fällen wird ein neues Replikat erstellt werden, um ihn zu ersetzen. In einigen Fällen wird jedoch zum Verlust nicht permanent ist und das Replikat der permanente schließlich wiederhergestellt. Nun bildet eine standbyreplikat. StandBy-Replikaten werden bevorzugt im Fall von nachfolgende Fehler oder Ressourcenausgleich für Aktionen, da sie bereits vorhanden ist und die verwendet werden können, um die Wiederherstellung zu beschleunigen, persistenten Status darstellen verwendet werden. Die <see cref="P:System.Fabric.Description.StatefulServiceDescription.StandByReplicaKeepDuration" /> definiert, wie lange eine solche StandBy-Replikaten beibehalten werden soll, bevor Sie entfernt werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetReplicaSetSize">
      <MemberSignature Language="C#" Value="public int TargetReplicaSetSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 TargetReplicaSetSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetReplicaSetSize As Integer" />
      <MemberSignature Language="F#" Value="member this.TargetReplicaSetSize : int with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> Ruft ab oder legt die Zielgröße des Replikatsatzes.</para>
        </summary>
        <value>
          <para>Die Zielgröße des Replikatsatzes.</para>
        </value>
        <remarks>
          <para>Die Anzahl der Replikate, die das System erstellt und verwaltet für jede Partition dieses Diensts.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>