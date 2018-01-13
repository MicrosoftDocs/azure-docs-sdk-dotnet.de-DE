<Type Name="UpgradeDomainDeployedApplicationsHealthEvaluation" FullName="System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class UpgradeDomainDeployedApplicationsHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UpgradeDomainDeployedApplicationsHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UpgradeDomainDeployedApplicationsHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type UpgradeDomainDeployedApplicationsHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthEvaluation</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt die integritätsauswertung für die bereitgestellten Anwendungen einer Anwendung in einer upgradedomäne mit auswertungen der Clientintegrität für jede "fehlerhaft" bereitgestellte Anwendung, die aktuellen aggregierte Integritätsstatus ausgewirkt haben.
            </para>
    </summary>
    <remarks>Zurückgegeben werden kann, wenn die Auswertung von Anwendungsintegrität während der Cluster oder einer Anwendung ein Upgrade und der aggregierte Integritätszustand entweder ist <see cref="F:System.Fabric.Health.HealthState.Error" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MaxPercentUnhealthyDeployedApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyDeployedApplications { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyDeployedApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation.MaxPercentUnhealthyDeployedApplications" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentUnhealthyDeployedApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyDeployedApplications : byte" Usage="System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation.MaxPercentUnhealthyDeployedApplications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die maximal zulässige Prozentsatz fehlerhafter bereitgestellten Anwendungen aus dem <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />.</para>
        </summary>
        <value>
          <para>Die maximal zulässige Prozentsatz fehlerhafter bereitgestellte Anwendungen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation.TotalCount" />
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
          <para>Ruft die Gesamtzahl der bereitgestellten Anwendungen der aktuellen Anwendung in der aktuellen upgradedomäne.</para>
        </summary>
        <value>
          <para>Die Gesamtanzahl der bereitgestellten Anwendungen von der aktuellen Anwendung in der aktuellen upgradedomäne.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation.UnhealthyEvaluations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Liste der fehlerhaften auswertungen, die zu der aggregierte Integritätszustand geführt hat. Schließt alle fehlerhaften <see cref="T:System.Fabric.Health.DeployedApplicationHealthEvaluation" /> , die die zusammengefasste Integrität beeinträchtigt.</para>
        </summary>
        <value>
          <para>Die fehlerhaften auswertungen, die dem aktuellen aggregierte Integritätsstatus geführt hat.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainName">
      <MemberSignature Language="C#" Value="public string UpgradeDomainName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeDomainName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation.UpgradeDomainName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomainName As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainName : string" Usage="System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation.UpgradeDomainName" />
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
          <para>Ruft den Namen der upgradedomäne, in denen die Anwendungsintegrität derzeit ausgewertet wird.</para>
        </summary>
        <value>
          <para>Der Name der upgradedomäne.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>