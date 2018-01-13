<Type Name="NodeDeactivationIntent" FullName="System.Fabric.NodeDeactivationIntent">
  <TypeSignature Language="C#" Value="public enum NodeDeactivationIntent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed NodeDeactivationIntent extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NodeDeactivationIntent" />
  <TypeSignature Language="VB.NET" Value="Public Enum NodeDeactivationIntent" />
  <TypeSignature Language="F#" Value="type NodeDeactivationIntent = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Beschreibt den Grund, warum der Knoten deaktiviert wird.</para>
    </summary>
    <remarks>
      <para>
                Die <see cref="T:System.Fabric.NodeDeactivationIntent" /> Enumeration dient als Teil der <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.DeactivateNodeAsync(System.String,System.Fabric.NodeDeactivationIntent)" /> Methode. </para>
      <para>
                Service Fabric verwendet diese Informationen, die richtigen Aktionen an den Knoten, um ein ordnungsgemäßes Herunterfahren des Knotens bereitstellen. Die Absichten weisen eine allgemeine Progression bzw. Schweregrade. </para>
      <para>
                Eine Deaktivierung, die mit einer Absicht gestartet wird, kann auf nachfolgende höhere Ebenen des Absicht erhöht werden. Die allgemeine Abfolge dieser Progression ist: anhalten, neu starten, beenden, "forcestop".</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.NodeDeactivationIntent.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass eine Datei deaktivierungsabsicht ungültig ist. Dieser Wert wird nicht verwendet.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Pause">
      <MemberSignature Language="C#" Value="Pause" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent Pause = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.Pause" />
      <MemberSignature Language="VB.NET" Value="Pause" />
      <MemberSignature Language="F#" Value="Pause = 1" Usage="System.Fabric.NodeDeactivationIntent.Pause" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass der Knoten angehalten werden soll. </para>
        </summary>
        <remarks>
          <para>
                Wenn diese Absicht verwendet wird, wird verhindert, dass Service Fabric Änderungen an den angegebenen Knoten. Keine neuen Replikate auf dem Knoten platziert werden, und vorhandene Replikate nicht verschoben oder heruntergefahren werden.</para>
          <para>
                Die <see cref="F:System.Fabric.NodeDeactivationIntent.Pause" /> Absicht ist nützlich, wenn eine oder mehrere Replikate auf einem Knoten Probleme auftreten, und dieser Knoten hat, zur weiteren Untersuchung isoliert werden müssen</para>
          <para> 
                Diese Untersuchung kann den Zugriff auf den Remotecomputer zum Untersuchen von Aktivitäten wie das lokale-Protokolle und Speicherabbilder dauert beobachten von anderen Informationen enthalten. </para>
          <para>
                Der Zweck dieser Modus wird versucht, den Knoten beibehält, sodass zusätzliche Debuggen unter denselben Umständen können, die vorhanden waren ausgeführt werden, als der Fehler auftrat.</para>
          <para>
                Beachten Sie, dass die Angabe von diesem Modus nicht garantiert, dass alle Änderungen an den Knoten verhindert werden können. </para>
          <para>
                Replikate auf dem Knoten stürzt möglicherweise ab, nachdem die Absicht, halten den Knoten empfangen wurde. </para>
          <para>
                Ein weiteres Beispiel möglicherweise Fehler in einem anderen Speicherort im Cluster ein sekundäres Replikat auf dem Knoten mit dem primären Replikat höher gestuft werden.</para>
          <para>
                In diesem Modus wird Service Fabric Platzierung und Ausgleichen von Ressourcen auf dem Zielknoten deaktivieren</para>
          <para>
                Darüber hinaus Sicherheitsprüfungen (finden Sie unter <see cref="T:System.Fabric.SafetyCheckKind" />) ausgeführt wird. Service Fabric</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveData">
      <MemberSignature Language="C#" Value="RemoveData" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent RemoveData = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.RemoveData" />
      <MemberSignature Language="VB.NET" Value="RemoveData" />
      <MemberSignature Language="F#" Value="RemoveData = 3" Usage="System.Fabric.NodeDeactivationIntent.RemoveData" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass die Absicht des Knotens ein reimaging durchführen. Service Fabric ist den Knoten nicht erstellt: Diese Aktion erfolgt außerhalb von Service Fabric.</para>
        </summary>
        <remarks>
          <para>
                Wenn Fabric-Dienst diese Absicht empfängt, es wird sichergestellt, die: </para>
          <para>
                In diesem Modus verhindert, dass Service Fabric neue Replikate, die auf dem Knoten platziert wird. Service Fabric darüber hinaus werden folgende Aktionen ausgeführt: </para>
          <para>
                Deaktivieren der Platzierung und Ressourcenausgleich auf dem Zielknoten</para>
          <para>
                Verschieben Sie alle Sichern von Replikaten aus dem Knoten. </para>
          <para>
                Für Instanzen ohne Status impliziert dies erstellen eine andere Instanz auf einem anderen Knoten</para>
          <para>
                Für Replikate zustandsbehaftete Dienste ist ein Ersatz-Replikat auf einem anderen Knoten erstellt (wenn genügend Kapazität im Cluster)</para>
          <para>
                Wenn das Replikat ein primäres Replikat ist, ist das primäre vor dem Erstellen der Ersatz einige andere aktive sekundäre Kopie der Partition vorgenommen werden.</para>
          <para>
                Zustandsbehaftete Replikate auf dem Knoten Benachrichtigungen senden, deren Zustand bereinigt und schließen.</para>
          <para>
                Führt eine Teilmenge von sicherheitsüberprüfungen durch, die sicherstellen, dass als Ergebnis dauert dieser Knoten keine Daten verloren gehen können.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveNode">
      <MemberSignature Language="C#" Value="RemoveNode" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent RemoveNode = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.RemoveNode" />
      <MemberSignature Language="VB.NET" Value="RemoveNode" />
      <MemberSignature Language="F#" Value="RemoveNode = 4" Usage="System.Fabric.NodeDeactivationIntent.RemoveNode" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass der Knoten außer Betrieb gesetzt werden wurde und wird nicht erwartet zurückgibt. Service Fabric ist außer Betrieb, die Knoten - dadurch erfolgt außerhalb von Service Fabric.</para>
        </summary>
        <remarks>
          <para>
                Wenn Fabric-Dienst diese Absicht empfängt, es wird sichergestellt, die: </para>
          <para>
                In diesem Modus verhindert, dass Service Fabric neue Replikate, die auf dem Knoten platziert wird. Service Fabric darüber hinaus werden folgende Aktionen ausgeführt: </para>
          <para>
                Deaktivieren der Platzierung und Ressourcenausgleich auf dem Zielknoten</para>
          <para>
                Verschieben Sie alle Sichern von Replikaten aus dem Knoten. </para>
          <para>
                Für Instanzen ohne Status impliziert dies erstellen eine andere Instanz auf einem anderen Knoten</para>
          <para>
                Für Replikate zustandsbehaftete Dienste ist ein Ersatz-Replikat auf einem anderen Knoten erstellt (wenn genügend Kapazität im Cluster)</para>
          <para>
                Wenn das Replikat ein primäres Replikat ist, ist das primäre vor dem Erstellen der Ersatz einige andere aktive sekundäre Kopie der Partition vorgenommen werden.</para>
          <para>
                Zustandsbehaftete Replikate auf dem Knoten Benachrichtigungen senden, deren Zustand bereinigt und schließen.</para>
          <para>
                Führt eine Teilmenge von sicherheitsüberprüfungen durch, die sicherstellen, dass als Ergebnis dauert dieser Knoten keine Daten verloren gehen können.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Restart">
      <MemberSignature Language="C#" Value="Restart" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent Restart = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.Restart" />
      <MemberSignature Language="VB.NET" Value="Restart" />
      <MemberSignature Language="F#" Value="Restart = 2" Usage="System.Fabric.NodeDeactivationIntent.Restart" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass die Absicht für den Knoten nach kurzer Zeit neu gestartet werden. Service Fabric nicht den Knoten neu gestartet: Diese Aktion erfolgt außerhalb von Service Fabric.</para>
        </summary>
        <remarks>
          <para>
                Ein Knoten kann z. B. beendet werden soll, führen Sie ein Betriebssystem oder einer Aktualisierung der Service Fabric-Code. </para>
          <para>
                In diesem Modus verhindert, dass Service Fabric neue Replikate, die auf dem Knoten platziert wird. Service Fabric darüber hinaus werden folgende Aktionen ausgeführt: </para>
          <para>
                Deaktivieren der Platzierung und Ressourcenausgleich auf dem Zielknoten</para>
          <para>
                Führt sicherheitsüberprüfungen durch. Die <see cref="F:System.Fabric.SafetyCheckKind.WaitForPrimaryPlacement" /> sicherheitsüberprüfung für diese Absicht nicht ausgeführt wird. </para>
          <para>
                Schließen Sie alle Replikate und Instanzen, die auf den Knoten ausgeführt wird.</para>
          <para>
                Hinweis: Sobald von Replikaten und Instanzen schließen wird Service Fabric reaktiv Ersatz für Replikate zustandsbehaftete volatile Dienste und zustandslose Dienste erstellen. </para>
          <para>
                Für Persisted Replikate auf dem Knoten, neue Replikate sind <b>nicht</b> erstellt werden, da die Absicht auf diesem Knoten neu zu starten und nach dem Neustart des persistenten Status wiederhergestellt ist. Wenn der Knoten aktiviert ist, werden die Replikate geöffnet.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>