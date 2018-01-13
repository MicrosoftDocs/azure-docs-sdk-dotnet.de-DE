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
      <para><span data-ttu-id="b8756-101">Gibt das Verhalten der <see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" /> und <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> für Replikate in der sekundären Rolle.</span><span class="sxs-lookup"><span data-stu-id="b8756-101">Specifies the behavior of <see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" /> and <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> for replicas in the secondary role.</span></span></para>
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
          <para><span data-ttu-id="b8756-102">Das sekundäre Replikat nicht anwenden oder Replikationsvorgängen bis zum Bestätigen der <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> Rückrufmethode zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="b8756-102">The secondary replica will not apply or acknowledge replication operations until the <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> callback method returns.</span></span> <span data-ttu-id="b8756-103">Vorgänge werden nicht unbedingt Überarbeitungen wurden durch ein Quorum der Replikate zum Zeitpunkt, wenn, die der Rückruf aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="b8756-103">Operations are not guaranteed to have been acked by a quorum of replicas at the time the callback is invoked.</span></span></para>
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
          <para><span data-ttu-id="b8756-104">Ein ungültiger sekundären Benachrichtigungsmodus.</span><span class="sxs-lookup"><span data-stu-id="b8756-104">An invalid secondary notification mode.</span></span> <span data-ttu-id="b8756-105">Für zukünftige Verwendung reserviert.</span><span class="sxs-lookup"><span data-stu-id="b8756-105">Reserved for future use.</span></span></para>
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
          <para><span data-ttu-id="b8756-106">Das sekundäre Replikat möglicherweise bereits angewendet und Replikationsvorgängen bestätigt bei der <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> Rückrufmethode aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="b8756-106">The secondary replica may have already applied and acknowledged replication operations when the <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> callback method is invoked.</span></span> <span data-ttu-id="b8756-107">Vorgänge sind garantiert Überarbeitungen wurde durch ein Quorum der Replikate von der Zeit, wenn, die der Rückruf aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="b8756-107">Operations are guaranteed to have been acked by a quorum of replicas by the time the callback is invoked.</span></span></para>
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
          <para><span data-ttu-id="b8756-108">Sekundäre deaktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="b8756-108">Secondary notifications are disabled.</span></span> <span data-ttu-id="b8756-109">Weder <see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" /> noch <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="b8756-109">Neither <see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" /> nor <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> will be invoked.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>