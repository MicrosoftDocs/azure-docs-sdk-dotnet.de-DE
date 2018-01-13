<Type Name="KeyValueStoreReplica+SecondaryNotificationMode" FullName="System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode">
  <TypeSignature Language="C#" Value="public enum KeyValueStoreReplica.SecondaryNotificationMode" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed KeyValueStoreReplica/SecondaryNotificationMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum KeyValueStoreReplica.SecondaryNotificationMode" />
  <TypeSignature Language="F#" Value="type KeyValueStoreReplica.SecondaryNotificationMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Gibt das Verhalten der <see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" /> und <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> für Replikate in der sekundären Rolle.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BlockSecondaryAck">
      <MemberSignature Language="C#" Value="BlockSecondaryAck" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode BlockSecondaryAck = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.BlockSecondaryAck" />
      <MemberSignature Language="VB.NET" Value="BlockSecondaryAck" />
      <MemberSignature Language="F#" Value="BlockSecondaryAck = 3" Usage="System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.BlockSecondaryAck" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>Das sekundäre Replikat nicht anwenden oder Replikationsvorgängen bis zum Bestätigen der <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> Rückrufmethode zurückgibt. Vorgänge werden nicht unbedingt Überarbeitungen wurden durch ein Quorum der Replikate zum Zeitpunkt, wenn, die der Rückruf aufgerufen wird.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Ein ungültiger sekundären Benachrichtigungsmodus. Für zukünftige Verwendung reserviert.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NonBlockingQuorumAcked">
      <MemberSignature Language="C#" Value="NonBlockingQuorumAcked" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode NonBlockingQuorumAcked = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.NonBlockingQuorumAcked" />
      <MemberSignature Language="VB.NET" Value="NonBlockingQuorumAcked" />
      <MemberSignature Language="F#" Value="NonBlockingQuorumAcked = 2" Usage="System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.NonBlockingQuorumAcked" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Das sekundäre Replikat möglicherweise bereits angewendet und Replikationsvorgängen bestätigt bei der <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> Rückrufmethode aufgerufen wird. Vorgänge sind garantiert Überarbeitungen wurde durch ein Quorum der Replikate von der Zeit, wenn, die der Rückruf aufgerufen wird.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode None = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 1" Usage="System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Sekundäre deaktiviert sind. Weder <see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" /> noch <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> aufgerufen wird.</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>