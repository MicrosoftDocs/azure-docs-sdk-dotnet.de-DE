<Type Name="RemoteReplicatorStatus" FullName="System.Fabric.Query.RemoteReplicatorStatus">
  <TypeSignature Language="C#" Value="public sealed class RemoteReplicatorStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RemoteReplicatorStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.RemoteReplicatorStatus" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RemoteReplicatorStatus" />
  <TypeSignature Language="F#" Value="type RemoteReplicatorStatus = class" />
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
      <para>Stellt den Status der sekundären Replikator aus Sicht der primären Replikator dar.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RemoteReplicatorStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.RemoteReplicatorStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.RemoteReplicatorStatus" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsInBuild">
      <MemberSignature Language="C#" Value="public bool IsInBuild { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsInBuild" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.IsInBuild" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsInBuild As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsInBuild : bool" Usage="System.Fabric.Query.RemoteReplicatorStatus.IsInBuild" />
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
          <para>Ruft einen Wert, der angibt, ob das sekundäre Replikat wird gerade erstellt wird.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn das sekundäre Replikat gerade erstellt wurde, andernfalls wird <languageKeyword>"false"</languageKeyword>.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAcknowledgementProcessedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastAcknowledgementProcessedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastAcknowledgementProcessedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.LastAcknowledgementProcessedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAcknowledgementProcessedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastAcknowledgementProcessedTimeUtc : DateTime" Usage="System.Fabric.Query.RemoteReplicatorStatus.LastAcknowledgementProcessedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Zeitstempel der letzten (in UTC) Wenn eine Bestätigung vom sekundären Replikator in der primären verarbeitet wurde.</para>
        </summary>
        <value>
          <para>Der letzte Zeitstempel in der primären eine Bestätigung vom sekundären Replikator verarbeitet wurde.</para>
        </value>
        <remarks>
          <para>UTC-0 stellt einen ungültigen Wert dar, der angibt, dass keine Bestätigungsnachrichten jemals verarbeitet wurden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAppliedCopySequenceNumber">
      <MemberSignature Language="C#" Value="public long LastAppliedCopySequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastAppliedCopySequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.LastAppliedCopySequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAppliedCopySequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastAppliedCopySequenceNumber : int64" Usage="System.Fabric.Query.RemoteReplicatorStatus.LastAppliedCopySequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Höchste Kopie Vorgang ruft die Sequenznummer ab, der die sekundäre Datenbank den Zustand angewendet hat.</para>
        </summary>
        <value>
          <para>Die höchste Kopie Vorgang Sequenznummer, die die sekundäre Datenbank den Zustand angewendet hat.</para>
        </value>
        <remarks>
          <para>Der Wert "1", kann ignoriert werden, da er gibt an, dass der Kopiervorgang abgeschlossen ist.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAppliedReplicationSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastAppliedReplicationSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastAppliedReplicationSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.LastAppliedReplicationSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAppliedReplicationSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastAppliedReplicationSequenceNumber : int64" Usage="System.Fabric.Query.RemoteReplicatorStatus.LastAppliedReplicationSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Höchste Replikation Vorgang ruft die Sequenznummer ab, der die sekundäre Datenbank den Zustand angewendet hat.</para>
        </summary>
        <value>
          <para>Die höchste Replikation Vorgang Sequenznummer, die die sekundäre Datenbank den Zustand angewendet hat.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastReceivedCopySequenceNumber">
      <MemberSignature Language="C#" Value="public long LastReceivedCopySequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastReceivedCopySequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.LastReceivedCopySequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastReceivedCopySequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastReceivedCopySequenceNumber : int64" Usage="System.Fabric.Query.RemoteReplicatorStatus.LastReceivedCopySequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Höchste Kopie Vorgang ruft die Sequenznummer ab, der die sekundäre Datenbank vom primären Server empfangen hat.</para>
        </summary>
        <value>
          <para>Die höchste Kopie Vorgang Sequenznummer, die die sekundäre Datenbank vom primären Server empfangen hat.</para>
        </value>
        <remarks>
          <para>Der Wert "1", kann ignoriert werden, da er gibt an, dass der Kopiervorgang abgeschlossen ist.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastReceivedReplicationSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastReceivedReplicationSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastReceivedReplicationSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.LastReceivedReplicationSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastReceivedReplicationSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastReceivedReplicationSequenceNumber : int64" Usage="System.Fabric.Query.RemoteReplicatorStatus.LastReceivedReplicationSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Höchste Replikation Vorgang ruft die Sequenznummer ab, der die sekundäre Datenbank vom primären Server empfangen hat.</para>
        </summary>
        <value>
          <para>Die höchste Replikation Vorgang Sequenznummer, die die sekundäre Datenbank vom primären Server empfangen hat.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteReplicatorAcknowledgementStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.RemoteReplicatorAcknowledgementStatus RemoteReplicatorAcknowledgementStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.RemoteReplicatorAcknowledgementStatus RemoteReplicatorAcknowledgementStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.RemoteReplicatorAcknowledgementStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteReplicatorAcknowledgementStatus As RemoteReplicatorAcknowledgementStatus" />
      <MemberSignature Language="F#" Value="member this.RemoteReplicatorAcknowledgementStatus : System.Fabric.Query.RemoteReplicatorAcknowledgementStatus" Usage="System.Fabric.Query.RemoteReplicatorStatus.RemoteReplicatorAcknowledgementStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.RemoteReplicatorAcknowledgementStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Bestätigung Zahlen enthält, für jeden remote Replikatoren</para>
          <para>Die Werte sind abhängig von den Status der Replikate. InBuild-Replikaten enthält Werte, die über kopieren können, während aktive Replias nicht wird.</para>
        </summary>
        <value>
          <para>RemoteReplicatorAcknowledgementStatus-Objekt, die Details in Bezug auf die Replikation und kopieren Sie Stream-Bestätigung enthält. Weitere Informationen finden Sie unter <see cref="T:System.Fabric.Query.RemoteReplicatorAcknowledgementStatus" /> . </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaId">
      <MemberSignature Language="C#" Value="public long ReplicaId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.ReplicaId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaId : int64" Usage="System.Fabric.Query.RemoteReplicatorStatus.ReplicaId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Replikat-ID der sekundären Datenbank ab.</para>
        </summary>
        <value>
          <para>Die Replikat-ID</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>