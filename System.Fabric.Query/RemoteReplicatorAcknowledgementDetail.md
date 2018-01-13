<Type Name="RemoteReplicatorAcknowledgementDetail" FullName="System.Fabric.Query.RemoteReplicatorAcknowledgementDetail">
  <TypeSignature Language="C#" Value="public sealed class RemoteReplicatorAcknowledgementDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RemoteReplicatorAcknowledgementDetail extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RemoteReplicatorAcknowledgementDetail" />
  <TypeSignature Language="F#" Value="type RemoteReplicatorAcknowledgementDetail = class" />
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
            Ausführliche Informationen Bestätigung bezieht sich auf eine Replikation oder die Kopie-Datenstrom. Mitglied<see cref="T:System.Fabric.Query.RemoteReplicatorStatus" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RemoteReplicatorAcknowledgementDetail ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageApplyDuration">
      <MemberSignature Language="C#" Value="public TimeSpan AverageApplyDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AverageApplyDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.AverageApplyDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AverageApplyDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AverageApplyDuration : TimeSpan" Usage="System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.AverageApplyDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die durchschnittliche Dauer für das Anwenden von Vorgängen
            </summary>
        <value>
          <para>Stellt der Durchschnitt gelten Dauer für eine remote-Replikator-Instanz.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageReceiveDuration">
      <MemberSignature Language="C#" Value="public TimeSpan AverageReceiveDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AverageReceiveDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.AverageReceiveDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AverageReceiveDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AverageReceiveDuration : TimeSpan" Usage="System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.AverageReceiveDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die durchschnittliche Dauer für den Empfang von Bestätigungen für Vorgänge
            </summary>
        <value>
          <para>Stellt der Durchschnitt erhalten Dauer für eine remote-Replikator-Instanz.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotReceivedCount">
      <MemberSignature Language="C#" Value="public long NotReceivedCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NotReceivedCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.NotReceivedCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NotReceivedCount As Long" />
      <MemberSignature Language="F#" Value="member this.NotReceivedCount : int64" Usage="System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.NotReceivedCount" />
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
            Ruft die Anzahl der Vorgänge, die noch nicht empfangen
            </summary>
        <value>
          <para>Gibt die Anzahl von Vorgängen, die von einem remote-Replikator noch nicht empfangen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceivedAndNotAppliedCount">
      <MemberSignature Language="C#" Value="public long ReceivedAndNotAppliedCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReceivedAndNotAppliedCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.ReceivedAndNotAppliedCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceivedAndNotAppliedCount As Long" />
      <MemberSignature Language="F#" Value="member this.ReceivedAndNotAppliedCount : int64" Usage="System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.ReceivedAndNotAppliedCount" />
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
            Ruft die Anzahl der Vorgänge empfangen und nicht angewendet.
            </summary>
        <value>
          <para>Gibt die Anzahl von Vorgängen empfangen und von einem remote-Replikator noch nicht angewendet.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>