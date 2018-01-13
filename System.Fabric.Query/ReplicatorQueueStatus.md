<Type Name="ReplicatorQueueStatus" FullName="System.Fabric.Query.ReplicatorQueueStatus">
  <TypeSignature Language="C#" Value="public sealed class ReplicatorQueueStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicatorQueueStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ReplicatorQueueStatus" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicatorQueueStatus" />
  <TypeSignature Language="F#" Value="type ReplicatorQueueStatus = class" />
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
      <para>Bietet verschiedene Statistiken der Warteschlange, die in der Service Fabric-Replikator verwendet.</para>
    </summary>
    <remarks>
      <para>Abhängig von der Rolle der Replikator (<see cref="F:System.Fabric.ReplicaRole.Primary" /> oder <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />), die Eigenschaften in dieser Art bedeuten, dass unterschiedliche Dinge.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicatorQueueStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ReplicatorQueueStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.ReplicatorQueueStatus" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommittedSequenceNumber">
      <MemberSignature Language="C#" Value="public long CommittedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CommittedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.CommittedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CommittedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.CommittedSequenceNumber : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.CommittedSequenceNumber" />
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
          <para>Finden Sie unter "Hinweise".</para>
        </summary>
        <value>
          <para>Die Sequenznummer ein Commit ausgeführt wurde.</para>
        </value>
        <remarks>
          <list type="number">
            <item>
              <description>
                <para>
                  <see cref="F:System.Fabric.ReplicaRole.Primary" />– Stellt die höchste Sequenznummer für die ein <b>Quorum</b> der sekundären Replikate die Operation angewendet haben.</para>
              </description>
            </item>
            <item>
              <description>
                <para>
                  <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />– Stellt die höchste Sequenznummer, die vom sekundären Replikator vom primären Server empfangen wurde.</para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompletedSequenceNumber">
      <MemberSignature Language="C#" Value="public long CompletedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CompletedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.CompletedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CompletedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.CompletedSequenceNumber : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.CompletedSequenceNumber" />
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
          <para>Finden Sie unter "Hinweise".</para>
        </summary>
        <value>
          <para>Die abgeschlossene Sequenznummer.</para>
        </value>
        <remarks>
          <list type="number">
            <item>
              <description>
                <para>
                  <see cref="F:System.Fabric.ReplicaRole.Primary" />– Stellt die höchste Sequenznummer für die <b>alle</b> die sekundären Replikate die Operation angewendet haben.</para>
              </description>
            </item>
            <item>
              <description>
                <para>
                  <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />– Stellt die höchste Sequenznummer, die vom Dienst Replikat Benutzer angewendet wurde.</para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="FirstSequenceNumber">
      <MemberSignature Language="C#" Value="public long FirstSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 FirstSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.FirstSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FirstSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.FirstSequenceNumber : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.FirstSequenceNumber" />
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
          <para>Finden Sie unter "Hinweise".</para>
        </summary>
        <value>
          <para>Die erste Sequenznummer.</para>
        </value>
        <remarks>
          <list type="number">
            <item>
              <description>
                <para>
                  <see cref="F:System.Fabric.ReplicaRole.Primary" />– Stellt die kleinste Sequenznummer des Vorgangs, der in der Warteschlange vorhanden ist. Der Wert ist identisch mit <see cref="P:System.Fabric.Query.ReplicatorQueueStatus.CompletedSequenceNumber" />, da der primäre Replikator Vorgänge verwirft, nach Empfang eine Bestätigung von den sekundären Replikaten.</para>
              </description>
            </item>
            <item>
              <description>
                <para>
                  <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />– Enthält die Sequenznummer des ersten Vorgangs, der in der Warteschlange verfügbar ist.</para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.LastSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastSequenceNumber : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.LastSequenceNumber" />
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
          <para>Finden Sie unter "Hinweise".</para>
        </summary>
        <value>
          <para>Die letzte Sequenznummer.</para>
        </value>
        <remarks>
          <list type="number">
            <item>
              <description>
                <para>
                  <see cref="F:System.Fabric.ReplicaRole.Primary" />– Stellt die aktuelle Sequenznummer des Vorgangs, der in der Warteschlange verfügbar ist.</para>
              </description>
            </item>
            <item>
              <description>
                <para>
                  <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />– Stellt die aktuelle Sequenznummer des Vorgangs, der in der Warteschlange verfügbar ist.</para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="QueueMemorySize">
      <MemberSignature Language="C#" Value="public long QueueMemorySize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 QueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.QueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueueMemorySize As Long" />
      <MemberSignature Language="F#" Value="member this.QueueMemorySize : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.QueueMemorySize" />
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
          <para>Ruft die Anzahl der virtuellen Speicherbytes, die von der Warteschlange verwendet wird.</para>
        </summary>
        <value>
          <para>Die Anzahl der virtuellen Arbeitsspeicherbytes, die von der Warteschlange verwendet wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueueUtilizationPercentage">
      <MemberSignature Language="C#" Value="public long QueueUtilizationPercentage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 QueueUtilizationPercentage" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.QueueUtilizationPercentage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueueUtilizationPercentage As Long" />
      <MemberSignature Language="F#" Value="member this.QueueUtilizationPercentage : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.QueueUtilizationPercentage" />
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
          <para>Ruft die Auslastung der Warteschlange ab.</para>
        </summary>
        <value>
          <para>Die Auslastung der Warteschlange.</para>
        </value>
        <remarks>
          <para>Der Wert "0" gibt an, dass die Warteschlange leer ist und ein Wert von "100" gibt an, dass die Warteschlange voll ist.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>