<Type Name="ApplicationTypeApplicationsHealthEvaluation" FullName="System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class ApplicationTypeApplicationsHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationTypeApplicationsHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationTypeApplicationsHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type ApplicationTypeApplicationsHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para>
            Stellt die integritätsevaluierung für Anwendungen eines Anwendungstyps dar.
            </para>
    </summary>
    <remarks>
      <para>Anwendungen vom Typ "Application" Auswertung zurückgegeben werden kann, Rückkehr Cluster integritätsauswertung "fehlerhaft" aggregierte Integritätsstatus, entweder <see cref="F:System.Fabric.Health.HealthState.Error" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />.
            Es enthält die auswertungen der Clientintegrität für jede Anwendung "fehlerhaft" des Anwendungstyps enthalten, die aktuellen aggregierte Integritätsstatus ausgewirkt haben.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation.ApplicationTypeName" />
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
          <para>
            Ruft den Typnamen der Anwendung ab.
            </para>
        </summary>
        <value>
          <para>Der Name des Anwendungstyps.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyApplications { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation.MaxPercentUnhealthyApplications" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentUnhealthyApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyApplications : byte" Usage="System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation.MaxPercentUnhealthyApplications" />
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
          <para>
            Ruft die maximal zulässige Prozentsatz fehlerhafter Anwendungen für den Anwendungstyp, angegeben als Eintrag in <see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />.
            </para>
        </summary>
        <value>
          <para>Die maximal zulässige Prozentsatz fehlerhafter Anwendungen für den Anwendungstyp.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation.TotalCount" />
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
          <para>
            Ruft die Gesamtzahl der Anwendungen des Anwendungstyps im Health Store gefunden.
            </para>
        </summary>
        <value>
          <para>Die Gesamtanzahl von Anwendungen des Anwendungstyps.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.ApplicationTypeApplicationsHealthEvaluation.UnhealthyEvaluations" />
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
          <para>
            Ruft die Liste der fehlerhaften auswertungen, die zu der aggregierte Integritätszustand geführt hat.
            </para>
        </summary>
        <value>
          <para>Die Liste der fehlerhaften auswertungen für den angegebenen Anwendungstyp.</para>
        </value>
        <remarks> Schließt alle fehlerhaften <see cref="T:System.Fabric.Health.ApplicationHealthEvaluation" /> diesen Anwendungstyp, die die zusammengefasste Integrität ausgewirkt haben.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>