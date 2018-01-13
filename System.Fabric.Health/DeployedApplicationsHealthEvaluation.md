<Type Name="DeployedApplicationsHealthEvaluation" FullName="System.Fabric.Health.DeployedApplicationsHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationsHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationsHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationsHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationsHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type DeployedApplicationsHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para>Stellt integritätsauswertung bereitgestellter Anwendungen mit auswertungen der Clientintegrität für jede "fehlerhaft" bereitgestellte Anwendung, die aktuellen aggregierte Integritätsstatus ausgewirkt haben. Zurückgegeben werden kann, beim Auswerten der Anwendungsintegrität und der aggregierte Integritätszustand entweder ist <see cref="F:System.Fabric.Health.HealthState.Error" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MaxPercentUnhealthyDeployedApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyDeployedApplications { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyDeployedApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationsHealthEvaluation.MaxPercentUnhealthyDeployedApplications" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentUnhealthyDeployedApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyDeployedApplications : byte" Usage="System.Fabric.Health.DeployedApplicationsHealthEvaluation.MaxPercentUnhealthyDeployedApplications" />
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
          <para>Ein <see cref="T:System.Byte" /> Anwendungen bereitgestellt, die die maximal zulässige Prozentsatz fehlerhafter darstellt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationsHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.DeployedApplicationsHealthEvaluation.TotalCount" />
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
          <para>Ruft die Gesamtanzahl der von der Anwendung bereitgestellten Anwendungen im Health Store an.</para>
        </summary>
        <value>
          <para>Ein <see cref="T:System.Int64" /> Anwendungen von der Anwendung im Health Store bereitgestellt, die die Gesamtzahl der darstellt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationsHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.DeployedApplicationsHealthEvaluation.UnhealthyEvaluations" />
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
          <para>Eine Liste der fehlerhaften auswertungen, die dem aktuellen aggregierte Integritätsstatus geführt hat.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>