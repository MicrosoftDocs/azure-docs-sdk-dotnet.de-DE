<Type Name="PartitionAccessStatus" FullName="System.Fabric.PartitionAccessStatus">
  <TypeSignature Language="C#" Value="public enum PartitionAccessStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed PartitionAccessStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PartitionAccessStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum PartitionAccessStatus" />
  <TypeSignature Language="F#" Value="type PartitionAccessStatus = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Listet die Zugriffsstatus der Partition an. </para>
    </summary>
    <remarks>
      <para>
        <see cref="T:System.Fabric.PartitionAccessStatus" />wird verwendet, um zu überprüfen, dass ein Schreib- oder Lesevorgang zulässig ist. Beim dienstreplikate eine Clientanforderung behandeln sollten sie überprüfen, ob das System in einem Zustand befindet, die Verarbeitung ermöglicht. Durch Überprüfen der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" /> oder <see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" /> nach Bedarf, kann das Replikat von Bedingungen, die korrekte Ausführung verhindert benachrichtigt werden. Beachten Sie, die Schreibvorgänge möglicherweise eine Ausnahme aus dem Replicator für eine der folgenden Bedingungen weiterhin angezeigt, weil die Bedingung zwischen ändern kann die <see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" /> Kontrollkästchen und der Aufruf von <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />. </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Granted">
      <MemberSignature Language="C#" Value="Granted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus Granted = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.Granted" />
      <MemberSignature Language="VB.NET" Value="Granted" />
      <MemberSignature Language="F#" Value="Granted = 1" Usage="System.Fabric.PartitionAccessStatus.Granted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass der Lese- oder Schreibberechtigungen Vorgang Zugriff erteilt, und der Vorgang ist nicht zulässig. </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.PartitionAccessStatus.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass der Zugriffsstatus Lese- oder Schreibberechtigungen Vorgang ungültig ist. Dieser Wert wird nicht an den Aufrufer zurückgegeben.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NotPrimary">
      <MemberSignature Language="C#" Value="NotPrimary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus NotPrimary = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.NotPrimary" />
      <MemberSignature Language="VB.NET" Value="NotPrimary" />
      <MemberSignature Language="F#" Value="NotPrimary = 3" Usage="System.Fabric.PartitionAccessStatus.NotPrimary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass diese Clientanforderung von einem Replikat empfangen wurde, die nicht über ein primäres Replikat handelt. Die Schreib- oder Lesevorgang kann nicht zu diesem Replikat ausgeführt werden. Der Client sollte versuchen naming Service zu verwenden, um das richtige primären Replikat zu identifizieren.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NoWriteQuorum">
      <MemberSignature Language="C#" Value="NoWriteQuorum" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus NoWriteQuorum = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.NoWriteQuorum" />
      <MemberSignature Language="VB.NET" Value="NoWriteQuorum" />
      <MemberSignature Language="F#" Value="NoWriteQuorum = 4" Usage="System.Fabric.PartitionAccessStatus.NoWriteQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass kein Quorum Schreibzugriff verfügbar ist und daher keine Schreibvorgang akzeptiert werden kann. Der Client sollte es sich um den Vorgang in diesem Replikat wiederholen.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ReconfigurationPending">
      <MemberSignature Language="C#" Value="ReconfigurationPending" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus ReconfigurationPending = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.ReconfigurationPending" />
      <MemberSignature Language="VB.NET" Value="ReconfigurationPending" />
      <MemberSignature Language="F#" Value="ReconfigurationPending = 2" Usage="System.Fabric.PartitionAccessStatus.ReconfigurationPending" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass der Client später erneut versuchen soll, da eine Neukonfiguration ausgeführt wird. Nachdem die Neukonfiguration abgeschlossen ist, wird ein neuer Status, die weitere Anleitungen zurückgegeben. Der Client sollte wiederholen Sie den Vorgang in diesem Replikat</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>