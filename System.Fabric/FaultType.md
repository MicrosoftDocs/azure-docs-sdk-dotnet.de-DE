<Type Name="FaultType" FullName="System.Fabric.FaultType">
  <TypeSignature Language="C#" Value="public enum FaultType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed FaultType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FaultType" />
  <TypeSignature Language="VB.NET" Value="Public Enum FaultType" />
  <TypeSignature Language="F#" Value="type FaultType = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Gibt den Typ des Fehlers, der ein Dienst meldet: ungültig, vorübergehend oder dauerhaft. </para>
    </summary>
    <remarks>
      <para>Dienste können Fehler während der Laufzeit per melden die <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> Methode, um den Typ des Fehlers anzugeben.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.FaultType Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FaultType.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.FaultType.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FaultType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Der Typ ist ungültig.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Permanent">
      <MemberSignature Language="C#" Value="Permanent" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.FaultType Permanent = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FaultType.Permanent" />
      <MemberSignature Language="VB.NET" Value="Permanent" />
      <MemberSignature Language="F#" Value="Permanent = 1" Usage="System.Fabric.FaultType.Permanent" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FaultType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Ein dauerhafter Fehler ist ein Fehler, dem das Replikat von wiederhergestellt werden kann. Diese Art von Fehler gibt an, dass das Replikat kann keine weitere Bearbeitung vornehmen und entfernt und ersetzt. </para>
        </summary>
        <remarks>
          <para>Ein Beispiel für einen dauerhaften Fehler wäre eine permanente zustandsbehaftete Dienst, der versucht, Informationen auf den Datenträger schreibt und feststellt, dass der Datenträger entfernt wurde oder wurde nicht verwendbar. Aufrufen von <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> und ein Ergebnis dauerhaften Fehler im Dienst über abgebrochen reporting <languageKeyword>IStatefulServiceReplica.</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.Abort" /> oder <languageKeyword>IStatelessServiceInstance.</languageKeyword><see cref="M:System.Fabric.IStatelessServiceInstance.Abort" /> ohne die Möglichkeit, Status oder abgeschlossener Vorgänge ordnungsgemäß bereinigen. Daher, wenn eine Bereinigung ausführen oder andere langer erforderlich ist, sie sollten ausgeführt werden vor dem <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> aufgerufen wird. Beachten Sie, dass die Unterscheidung zwischen permanente und flüchtige Fehler hauptsächlich für beständige zustandsbehaftete Dienste nützlich ist. Abgesehen von der Aufruffolge sind die Auswirkungen auf andere Diensttypen identisch: das Replikat oder eine Instanz entfernt wird, alle Zustände an dieses Replikat oder Instanz verloren gegangen ist und das Replikat oder eine Instanz wird neu erstellt, möglicherweise in einem anderen Speicherort.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Transient">
      <MemberSignature Language="C#" Value="Transient" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.FaultType Transient = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FaultType.Transient" />
      <MemberSignature Language="VB.NET" Value="Transient" />
      <MemberSignature Language="F#" Value="Transient = 2" Usage="System.Fabric.FaultType.Transient" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FaultType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Ein vorübergehender Fehler gibt an, dass einige temporäre Bedingung verhindert, das Replikat dass von weiteren Fortschritte oder weitere benutzeranforderungen verarbeiten. </para>
        </summary>
        <remarks>
          <para>Ein Beispiel eines vorübergehenden Fehlers ist ein Dienst, der feststellt, dass ein Teil des Datenbankzustands oder einige Referenzdatei ist beschädigt, doch repariert werden kann, wäre der Dienst erneut initialisiert werden. Der Dienst in diesem Fall verwendet die <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> Methode, um einen vorübergehenden Fehler zu melden. Einen vorübergehenden Fehler Reporting schließt den Dienst über <languageKeyword>IStatefulServiceReplica.</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.CloseAsync(System.Threading.CancellationToken)" /> oder <languageKeyword>IStatelessServiceInstance.</languageKeyword> <see cref="M:System.Fabric.IStatelessServiceInstance.CloseAsync(System.Threading.CancellationToken)" />. Beachten Sie, dass für Zustandslose und zustandsbehaftete Dienste volatile vorübergehende Fehler nicht sehr nützlich sind, da über den Fehler nicht beibehalten wird. Für diese Dienste ist, ob vorübergehende oder dauerhafte Fehlern verwendet abhängig, ob der Dienst ordnungsgemäß asynchron with Cleanup, geschlossen oder mit einer synchronen nicht ordnungsgemäß geschlossen werden sollte <languageKeyword>IStatefulServiceReplica.</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.Abort" /> oder <languageKeyword>IStatelessServiceInstance.</languageKeyword><see cref="M:System.Fabric.IStatelessServiceInstance.Abort" /> -Methode.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>