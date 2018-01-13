<Type Name="NodeUpgradeProgress" FullName="System.Fabric.NodeUpgradeProgress">
  <TypeSignature Language="C#" Value="public sealed class NodeUpgradeProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeUpgradeProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NodeUpgradeProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeUpgradeProgress" />
  <TypeSignature Language="F#" Value="type NodeUpgradeProgress = class" />
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
      <para>Enthält die Pfade für die Details zum upgradeverlauf eines Knotens an.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeUpgradeProgress.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.NodeUpgradeProgress.NodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Namen des Knotens mit Details zum upgradeverlauf ab.</para>
        </summary>
        <value>
          <para>Der Name des Knotens mit Details zum upgradeverlauf.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PendingSafetyChecks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.UpgradeSafetyCheck&gt; PendingSafetyChecks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.UpgradeSafetyCheck&gt; PendingSafetyChecks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeUpgradeProgress.PendingSafetyChecks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PendingSafetyChecks As IList(Of UpgradeSafetyCheck)" />
      <MemberSignature Language="F#" Value="member this.PendingSafetyChecks : System.Collections.Generic.IList&lt;System.Fabric.UpgradeSafetyCheck&gt;" Usage="System.Fabric.NodeUpgradeProgress.PendingSafetyChecks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.UpgradeSafetyCheck&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Liste der sicherheitsüberprüfungen, die Service Fabric derzeit auf den entsprechenden Knoten ausgeführt werden.</para>
        </summary>
        <value>
          <para>Die Liste der sicherheitsüberprüfungen, die Service Fabric, die derzeit auf dem entsprechenden Knoten ausgeführt wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradePhase">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeUpgradePhase UpgradePhase { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.NodeUpgradePhase UpgradePhase" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeUpgradeProgress.UpgradePhase" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradePhase As NodeUpgradePhase" />
      <MemberSignature Language="F#" Value="member this.UpgradePhase : System.Fabric.NodeUpgradePhase" Usage="System.Fabric.NodeUpgradeProgress.UpgradePhase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeUpgradePhase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Phase des Upgrades des Knotens ab.</para>
        </summary>
        <value>
          <para>Die Phase des Upgrades des Knotens.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>