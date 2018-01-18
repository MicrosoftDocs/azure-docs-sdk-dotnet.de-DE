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
      <para><span data-ttu-id="a6002-101">Bewertung der Netzwerkintegrität stellt eine <see cref="T:System.Fabric.Health.HealthEvent" />.</span><span class="sxs-lookup"><span data-stu-id="a6002-101">Represents health evaluation of a <see cref="T:System.Fabric.Health.HealthEvent" />.</span></span> <span data-ttu-id="a6002-102">Zurückgegeben werden kann, Bewertung der Integrität einer Entität Rückkehr <see cref="F:System.Fabric.Health.HealthState.Error" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span><span class="sxs-lookup"><span data-stu-id="a6002-102">Can be returned when evaluating health of an entity returns <see cref="F:System.Fabric.Health.HealthState.Error" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span></para>
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
          <para><span data-ttu-id="a6002-103">Ruft <see cref="T:System.Boolean" /> , der angibt, ob Warnungen mit den gleichen Schweregrad als Fehler behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="a6002-103">Gets <see cref="T:System.Boolean" /> that indicates whether warnings are treated with the same severity as errors.</span></span> <span data-ttu-id="a6002-104">Das Feld wird in der Integritätsrichtlinie zur Bewertung der Entität angegeben.</span><span class="sxs-lookup"><span data-stu-id="a6002-104">The field is specified in the health policy used to evaluate the entity.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="a6002-105"><languageKeyword>"true"</languageKeyword> Wenn Warnungen als Fehler behandelt werden, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="a6002-105"><languageKeyword>true</languageKeyword> if warnings are treated as errors; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
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
          <para><span data-ttu-id="a6002-106">Ruft die Details "fehlerhaft"-Ereignis ab.</span><span class="sxs-lookup"><span data-stu-id="a6002-106">Gets the unhealthy event details.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="a6002-107">Die <see cref="T:System.Fabric.Health.HealthEvent" /> , die dem aktuellen aggregierte Integritätsstatus geführt hat.</span><span class="sxs-lookup"><span data-stu-id="a6002-107">The <see cref="T:System.Fabric.Health.HealthEvent" /> that led to current aggregated health state.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>