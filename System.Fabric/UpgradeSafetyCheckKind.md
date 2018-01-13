<Type Name="UpgradeSafetyCheckKind" FullName="System.Fabric.UpgradeSafetyCheckKind">
  <TypeSignature Language="C#" Value="public enum UpgradeSafetyCheckKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed UpgradeSafetyCheckKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.UpgradeSafetyCheckKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum UpgradeSafetyCheckKind" />
  <TypeSignature Language="F#" Value="type UpgradeSafetyCheckKind = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Listet die <see cref="T:System.Fabric.UpgradeSafetyCheck" /> , wird während des Upgrades für einen Knoten ausgeführt wird.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EnsureAvailability">
      <MemberSignature Language="C#" Value="EnsureAvailability" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind EnsureAvailability = int32(7)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.EnsureAvailability" />
      <MemberSignature Language="VB.NET" Value="EnsureAvailability" />
      <MemberSignature Language="F#" Value="EnsureAvailability = 7" Usage="System.Fabric.UpgradeSafetyCheckKind.EnsureAvailability" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, entweder eine zustandslose Dienstpartition auf den Knoten mit genau einer Instanz vorhanden ist, oder dass ein primäres Replikat auf dem Knoten für den Partition einen quorumsverlust darstellt. In beiden Fällen führt die Replikate aufgrund Upgrade heruntergefahren nichtverfügbarkeit.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="EnsurePartitionQuorum">
      <MemberSignature Language="C#" Value="EnsurePartitionQuorum" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind EnsurePartitionQuorum = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.EnsurePartitionQuorum" />
      <MemberSignature Language="VB.NET" Value="EnsurePartitionQuorum" />
      <MemberSignature Language="F#" Value="EnsurePartitionQuorum = 2" Usage="System.Fabric.UpgradeSafetyCheckKind.EnsurePartitionQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass eine Partition für die Wenn wir das Replikat auf dem Knoten beenden quorumsverlust für diese Partition dadurch vorhanden ist.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="EnsureSeedNodeQuorum">
      <MemberSignature Language="C#" Value="EnsureSeedNodeQuorum" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind EnsureSeedNodeQuorum = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.EnsureSeedNodeQuorum" />
      <MemberSignature Language="VB.NET" Value="EnsureSeedNodeQuorum" />
      <MemberSignature Language="F#" Value="EnsureSeedNodeQuorum = 1" Usage="System.Fabric.UpgradeSafetyCheckKind.EnsureSeedNodeQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass wenn wir den Knoten Beenden klicken Sie dann diese im globalen Seed-Knoten quorumsverlust führt.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.UpgradeSafetyCheckKind.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass die Art der upgradesicherheitsüberprüfung ungültig ist. Dieser Wert wird nicht verwendet.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForInbuildReplica">
      <MemberSignature Language="C#" Value="WaitForInbuildReplica" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind WaitForInbuildReplica = int32(6)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.WaitForInbuildReplica" />
      <MemberSignature Language="VB.NET" Value="WaitForInbuildReplica" />
      <MemberSignature Language="F#" Value="WaitForInbuildReplica = 6" Usage="System.Fabric.UpgradeSafetyCheckKind.WaitForInbuildReplica" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, auf den Knoten, der über Kopiervorgang relevant ist entweder ein Replikat vorhanden ist, oder dass ein primäres Replikat auf dem Knoten, der Daten auf ein anderes Replikat kopiert werden. In beiden Fällen wird das Replikat auf dem Knoten aufgrund heruntergefahren, aktualisiert der Kopiervorgang abgebrochen.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForPrimaryPlacement">
      <MemberSignature Language="C#" Value="WaitForPrimaryPlacement" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind WaitForPrimaryPlacement = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.WaitForPrimaryPlacement" />
      <MemberSignature Language="VB.NET" Value="WaitForPrimaryPlacement" />
      <MemberSignature Language="F#" Value="WaitForPrimaryPlacement = 3" Usage="System.Fabric.UpgradeSafetyCheckKind.WaitForPrimaryPlacement" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass ein Replikat auf dem Knoten, der von diesem Knoten aufgrund verschoben wurde, zu aktualisieren. Service Fabric wartet jetzt für den primären wieder auf diesen Knoten verschoben werden.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForPrimarySwap">
      <MemberSignature Language="C#" Value="WaitForPrimarySwap" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind WaitForPrimarySwap = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.WaitForPrimarySwap" />
      <MemberSignature Language="VB.NET" Value="WaitForPrimarySwap" />
      <MemberSignature Language="F#" Value="WaitForPrimarySwap = 4" Usage="System.Fabric.UpgradeSafetyCheckKind.WaitForPrimarySwap" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass Service Fabric wartet ein primäres Replikat vor dem Beginn der Aktualisierung auf diesem Knoten aus dem Knoten verschoben werden.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForReconfiguration">
      <MemberSignature Language="C#" Value="WaitForReconfiguration" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind WaitForReconfiguration = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.WaitForReconfiguration" />
      <MemberSignature Language="VB.NET" Value="WaitForReconfiguration" />
      <MemberSignature Language="F#" Value="WaitForReconfiguration = 5" Usage="System.Fabric.UpgradeSafetyCheckKind.WaitForReconfiguration" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass ein Replikat auf dem Knoten, der an einer Neukonfiguration beteiligt ist. Service Fabric wartet darauf, dass eine Neukonfiguration vor dem Start abgeschlossen sein muss auf diesem Knoten Upgrades.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForResourceAvailability">
      <MemberSignature Language="C#" Value="WaitForResourceAvailability" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind WaitForResourceAvailability = int32(8)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.WaitForResourceAvailability" />
      <MemberSignature Language="VB.NET" Value="WaitForResourceAvailability" />
      <MemberSignature Language="F#" Value="WaitForResourceAvailability = 8" Usage="System.Fabric.UpgradeSafetyCheckKind.WaitForResourceAvailability" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass immer noch nicht genügend Kapazität für die Ressource kontrolliert Metriken, um das Upgrade fortzusetzen. Dies kann geschehen, für den Fall, dass Sie ein Dienstpaket Ressourcenverbrauch zunimmt. Service Fabric ist erfolgt, Aktionen, um sicherzustellen, dass der Knoten über ausreichend Kapazität verfügt. </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>