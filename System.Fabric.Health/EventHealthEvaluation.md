<Type Name="EventHealthEvaluation" FullName="System.Fabric.Health.EventHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class EventHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.EventHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type EventHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para>Bewertung der Netzwerkintegrität stellt eine <see cref="T:System.Fabric.Health.HealthEvent" />. Zurückgegeben werden kann, Bewertung der Integrität einer Entität Rückkehr <see cref="F:System.Fabric.Health.HealthState.Error" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ConsiderWarningAsError">
      <MemberSignature Language="C#" Value="public bool ConsiderWarningAsError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ConsiderWarningAsError" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EventHealthEvaluation.ConsiderWarningAsError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsiderWarningAsError As Boolean" />
      <MemberSignature Language="F#" Value="member this.ConsiderWarningAsError : bool" Usage="System.Fabric.Health.EventHealthEvaluation.ConsiderWarningAsError" />
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
          <para>Ruft <see cref="T:System.Boolean" /> , der angibt, ob Warnungen mit den gleichen Schweregrad als Fehler behandelt werden. Das Feld wird in der Integritätsrichtlinie zur Bewertung der Entität angegeben.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn Warnungen als Fehler behandelt werden, andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvent">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEvent UnhealthyEvent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEvent UnhealthyEvent" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EventHealthEvaluation.UnhealthyEvent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvent As HealthEvent" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvent : System.Fabric.Health.HealthEvent" Usage="System.Fabric.Health.EventHealthEvaluation.UnhealthyEvent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthEvent</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Details "fehlerhaft"-Ereignis ab.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.Health.HealthEvent" /> , die dem aktuellen aggregierte Integritätsstatus geführt hat.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>