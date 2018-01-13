<Type Name="ApplicationsHealthEvaluation" FullName="System.Fabric.Health.ApplicationsHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class ApplicationsHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationsHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationsHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationsHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type ApplicationsHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para>Stellt die integritätsevaluierung für Anwendungen, die mit auswertungen der Clientintegrität für jede fehlerhafte Anwendung, die aktuellen aggregierte Integritätsstatus ausgewirkt haben.</para>
    </summary>
    <remarks>Die Auswertung Anwendungen zurückgegeben werden kann, während integritätsevaluierung für Cluster, bei der aggregierte Integritätszustand des Clusters entweder <see cref="F:System.Fabric.Health.HealthState.Error" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MaxPercentUnhealthyApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyApplications { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationsHealthEvaluation.MaxPercentUnhealthyApplications" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentUnhealthyApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyApplications : byte" Usage="System.Fabric.Health.ApplicationsHealthEvaluation.MaxPercentUnhealthyApplications" />
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
          <para>Ruft die maximal zulässige Prozentsatz fehlerhafter Anwendungen aus dem <see cref="T:System.Fabric.Health.ClusterHealthPolicy" />.</para>
        </summary>
        <value>
          <para>Die maximal zulässige Prozentsatz fehlerhafter Anwendungen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationsHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.ApplicationsHealthEvaluation.TotalCount" />
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
          <para>Ruft die Gesamtzahl der Anwendungen im Health Store an.</para>
        </summary>
        <value>
          <para>Eine <see cref="T:System.Int64" /> , die die Gesamtzahl der Anwendungen im Health Store darstellt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationsHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.ApplicationsHealthEvaluation.UnhealthyEvaluations" />
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
          <para>Ruft die Liste der fehlerhaften auswertungen, die zu der aggregierte Integritätszustand geführt hat.</para>
        </summary>
        <value>
          <para>Eine Liste der <see cref="T:System.Fabric.Health.HealthEvaluation" /> , die die fehlerhaften auswertungen, die dem aktuellen aggregierte Integritätsstatus geführt haben darstellt.</para>
        </value>
        <remarks>
            Schließt alle fehlerhaften <see cref="T:System.Fabric.Health.ApplicationHealthEvaluation" /> , die die zusammengefasste Integrität beeinträchtigt.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>