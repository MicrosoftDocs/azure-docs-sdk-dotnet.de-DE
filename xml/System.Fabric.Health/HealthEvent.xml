<Type Name="HealthEvent" FullName="System.Fabric.Health.HealthEvent">
  <TypeSignature Language="C#" Value="public sealed class HealthEvent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HealthEvent extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthEvent" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HealthEvent" />
  <TypeSignature Language="F#" Value="type HealthEvent = class" />
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
      <para><span data-ttu-id="2f3f4-101">Stellt Integritätsinformationen für eine Integrität-Entität, z. B. Cluster, Anwendung oder Knoten mit zusätzlichen Metadaten, die vom Health Manager hinzugefügt gemeldet.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-101">Represents health information reported on a health entity, such as cluster, application or node, with additional metadata added by the Health Manager.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="2f3f4-102">Integritätsereignisse werden von integritätsabfragen zurückgegeben, wie z. B. <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-102">Health events are returned by health queries such as <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />.</span></span>
            <span data-ttu-id="2f3f4-103">Sie enthalten <see cref="T:System.Fabric.Health.HealthInformation" /> gesendet, Clientintegritäts-Managers in einem <see cref="T:System.Fabric.Health.HealthReport" />.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-103">They contain <see cref="T:System.Fabric.Health.HealthInformation" /> sent to Health Manager in a <see cref="T:System.Fabric.Health.HealthReport" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthInformation">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthInformation HealthInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthInformation HealthInformation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.HealthInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthInformation As HealthInformation" />
      <MemberSignature Language="F#" Value="member this.HealthInformation : System.Fabric.Health.HealthInformation" Usage="System.Fabric.Health.HealthEvent.HealthInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2f3f4-104">Ruft die Zustandsinformationen, die in Health Store in gesendet wurde eine <see cref="T:System.Fabric.Health.HealthReport" />.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-104">Gets the health information that was sent to health store in a <see cref="T:System.Fabric.Health.HealthReport" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2f3f4-105">Die Zustandsinformationen, die in Health Store in gesendet wurde eine <see cref="T:System.Fabric.Health.HealthReport" />.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-105">The health information that was sent to health store in a <see cref="T:System.Fabric.Health.HealthReport" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsExpired">
      <MemberSignature Language="C#" Value="public bool IsExpired { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsExpired" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.IsExpired" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsExpired As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsExpired : bool" Usage="System.Fabric.Health.HealthEvent.IsExpired" />
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
          <para><span data-ttu-id="2f3f4-106">Ruft einen Wert, der angibt, ob das integritätsereignis abgelaufen ist.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-106">Gets a value that indicates whether the health event has expired.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="2f3f4-107"><languageKeyword>"true"</languageKeyword> ist das integritätsereignis abgelaufen; <languageKeyword>"false"</languageKeyword> , wenn das integritätsereignis nicht zur Zeit abgelaufen war ausgewertet, der Health Store die Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-107"><languageKeyword>true</languageKeyword> if the health event has expired; <languageKeyword>false</languageKeyword> if the health event was not expired at the time the health store evaluated the query.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="2f3f4-108">Ein Ereignis kann nur ablaufen, wenn RemoveWhenExpired auf „false“ festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-108">An event can be expired only if RemoveWhenExpired is false.</span></span>
            <span data-ttu-id="2f3f4-109">Andernfalls wird das Ereignis von der Abfrage nicht zurückgegeben und aus dem Speicher entfernt.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-109">Otherwise, the event is not returned by query and is removed from the store.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastErrorTransitionAt">
      <MemberSignature Language="C#" Value="public DateTime LastErrorTransitionAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastErrorTransitionAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastErrorTransitionAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastErrorTransitionAt : DateTime" Usage="System.Fabric.Health.HealthEvent.LastErrorTransitionAt" />
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
          <para><span data-ttu-id="2f3f4-110">Wenn die aktuelle <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> ist <see cref="F:System.Fabric.Health.HealthState.Error" />, gibt der Zeitpunkt, an dem der Bericht zur Integrität ersten wurde, gemeldet, mit <see cref="F:System.Fabric.Health.HealthState.Error" />.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-110">If the current <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> is <see cref="F:System.Fabric.Health.HealthState.Error" />, returns the time at which the health report was first reported with <see cref="F:System.Fabric.Health.HealthState.Error" />.</span></span> <span data-ttu-id="2f3f4-111">Für die regelmäßige Berichterstattung viele Berichte mit demselben Status möglicherweise generiert wurden.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-111">For periodic reporting, many reports with the same state may have been generated.</span></span></para>
          <para><span data-ttu-id="2f3f4-112">Wenn die aktuelle <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> ist <see cref="F:System.Fabric.Health.HealthState.Ok" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />, gibt die Zeit, an dem der Zustand des zuletzt im <see cref="F:System.Fabric.Health.HealthState.Error" />, bevor der Übergang in ein anderes.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-112">If the current <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> is <see cref="F:System.Fabric.Health.HealthState.Ok" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />, returns the time at which the health state was last in <see cref="F:System.Fabric.Health.HealthState.Error" />, before transitioning to a different state.</span></span> <span data-ttu-id="2f3f4-113">Wenn die <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> war noch nie <see cref="F:System.Fabric.Health.HealthState.Error" />, der Wert wird System.DateTime.FromFileTimeUtc(0) sein.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-113">If the <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> has never been <see cref="F:System.Fabric.Health.HealthState.Error" />, the value will be System.DateTime.FromFileTimeUtc(0).</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2f3f4-114">Gibt <see cref="T:System.DateTime" /> darstellt, die letzte Übergang Time (UTC) mit <see cref="F:System.Fabric.Health.HealthState.Error" />.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-114">Returns <see cref="T:System.DateTime" /> representing the last transition time (UTC) involving <see cref="F:System.Fabric.Health.HealthState.Error" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="2f3f4-115">Die Felder Übergang <see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" /> Geben Sie den Verlauf der Integrität Zustandsübergänge für das Ereignis.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-115">The transition fields, <see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" /> give the history of the health state transitions for the event.</span></span>
            <span data-ttu-id="2f3f4-116">Sie können auf intelligentere Warnungen oder Ereignisinformationen "Versionsgeschichte" Integrität verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-116">They can be used for smarter alerts or "historical" health event information.</span></span> <span data-ttu-id="2f3f4-117">Sie ermöglichen Szenarien wie z. B.: <list type="bullet"> <item> <para>warnen, wenn eine Eigenschaft zur Warnung/Fehler für mehr als X Minuten wurde. Dies vermeidet Warnungen auf vorübergehende Bedingungen. Beispielsweise kann eine Warnung, wenn der Integritätsstatus für mehr als fünf Minuten Warnung wurde wurde übersetzt werden, in ("healthstate" Warnung "und" jetzt - LastWarningTransitionTime == &gt; 5 Minuten).</para> </item> <item> <para>Warnung nur bei Bedingungen, die in den letzten geändert haben X Minuten. Ein Bericht vor dem angegebenen Zeitpunkt bereits Fehlers war, kann ignoriert werden, da es bereits zuvor signalisiert wurde. </para> </item> <item> <para>, Wenn eine Eigenschaft, die zwischen den Warnungs- und umschalten ist, zu bestimmen, wie lange sie "fehlerhaft" (d. h. nicht OK) wurde. Beispielsweise kann eine Warnung, wenn die Eigenschaft nicht mehr als fünf Minuten fehlerfrei wurde in übersetzt werden ("healthstate"! = Ok und Now - LastOkTransitionTime &gt; 5 Minuten).</para></item></list></span><span class="sxs-lookup"><span data-stu-id="2f3f4-117">They enable scenarios such as: <list type="bullet"><item><para>Alert when a property has been at warning/error for more than X minutes. This avoids alerts on temporary conditions. For example, an alert if the health state has been warning for more than five minutes can be translated into (HealthState == Warning and Now - LastWarningTransitionTime &gt; 5 minutes).</para></item><item><para>Alert only on conditions that have changed in the last X minutes. If a report was already at error before the specified time, it can be ignored because it was already signaled previously.</para></item><item><para>If a property is toggling between warning and error, determine how long it has been unhealthy (i.e. not OK). For example, an alert if the property hasn't been healthy for more than five minutes can be translated into (HealthState != Ok and Now - LastOkTransitionTime &gt; 5 minutes).</para></item></list></span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedUtcTimestamp">
      <MemberSignature Language="C#" Value="public DateTime LastModifiedUtcTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastModifiedUtcTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.LastModifiedUtcTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedUtcTimestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastModifiedUtcTimestamp : DateTime" Usage="System.Fabric.Health.HealthEvent.LastModifiedUtcTimestamp" />
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
          <para><span data-ttu-id="2f3f4-118">Ruft das Datum und die Uhrzeit der letzten der Bericht zur Integrität von dem Health Store Änderung.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-118">Gets the date and time when the health report was last modified by the health store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2f3f4-119">Das Datum und Uhrzeit der letzten der Bericht zur Integrität von dem Health Store Änderung.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-119">The date and time when the health report was last modified by the health store.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastOkTransitionAt">
      <MemberSignature Language="C#" Value="public DateTime LastOkTransitionAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastOkTransitionAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastOkTransitionAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastOkTransitionAt : DateTime" Usage="System.Fabric.Health.HealthEvent.LastOkTransitionAt" />
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
          <para><span data-ttu-id="2f3f4-120">Wenn die aktuelle <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> ist <see cref="F:System.Fabric.Health.HealthState.Ok" />, gibt der Zeitpunkt, an dem der Bericht zur Integrität ersten wurde, gemeldet, mit <see cref="F:System.Fabric.Health.HealthState.Ok" />.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-120">If the current <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> is <see cref="F:System.Fabric.Health.HealthState.Ok" />, returns the time at which the health report was first reported with <see cref="F:System.Fabric.Health.HealthState.Ok" />.</span></span> <span data-ttu-id="2f3f4-121">Für die regelmäßige Berichterstattung viele Berichte mit demselben Status möglicherweise generiert wurden.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-121">For periodic reporting, many reports with the same state may have been generated.</span></span></para>
          <para><span data-ttu-id="2f3f4-122">Wenn die aktuelle <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> ist <see cref="F:System.Fabric.Health.HealthState.Error" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />, gibt die Zeit, an dem der Zustand des zuletzt im <see cref="F:System.Fabric.Health.HealthState.Ok" />, bevor der Übergang in ein anderes.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-122">If the current <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> is <see cref="F:System.Fabric.Health.HealthState.Error" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />, returns the time at which the health state was last in <see cref="F:System.Fabric.Health.HealthState.Ok" />, before transitioning to a different state.</span></span> <span data-ttu-id="2f3f4-123">Wenn die <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> war noch nie <see cref="F:System.Fabric.Health.HealthState.Ok" />, der Wert wird System.DateTime.FromFileTimeUtc(0) sein.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-123">If the <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> has never been <see cref="F:System.Fabric.Health.HealthState.Ok" />, the value will be System.DateTime.FromFileTimeUtc(0).</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2f3f4-124">Gibt <see cref="T:System.DateTime" /> darstellt, die letzte Übergang Time (UTC) mit <see cref="F:System.Fabric.Health.HealthState.Ok" />.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-124">Returns <see cref="T:System.DateTime" /> representing the last transition time (UTC) involving <see cref="F:System.Fabric.Health.HealthState.Ok" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="2f3f4-125">Die Felder Übergang <see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" /> Geben Sie den Verlauf der Integrität Zustandsübergänge für das Ereignis.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-125">The transition fields, <see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" /> give the history of the health state transitions for the event.</span></span>
            <span data-ttu-id="2f3f4-126">Sie können auf intelligentere Warnungen oder Ereignisinformationen "Versionsgeschichte" Integrität verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-126">They can be used for smarter alerts or "historical" health event information.</span></span> <span data-ttu-id="2f3f4-127">Sie ermöglichen Szenarien wie z. B.: <list type="bullet"> <item> <para>warnen, wenn eine Eigenschaft zur Warnung/Fehler für mehr als X Minuten wurde. Dies vermeidet Warnungen auf vorübergehende Bedingungen. Beispielsweise kann eine Warnung, wenn der Integritätsstatus für mehr als fünf Minuten Warnung wurde wurde übersetzt werden, in ("healthstate" Warnung "und" jetzt - LastWarningTransitionTime == &gt; 5 Minuten).</para> </item> <item> <para>Warnung nur bei Bedingungen, die in den letzten geändert haben X Minuten. Ein Bericht vor dem angegebenen Zeitpunkt bereits Fehlers war, kann ignoriert werden, da es bereits zuvor signalisiert wurde. </para> </item> <item> <para>, Wenn eine Eigenschaft, die zwischen den Warnungs- und umschalten ist, zu bestimmen, wie lange sie "fehlerhaft" (d. h. nicht OK) wurde. Beispielsweise kann eine Warnung, wenn die Eigenschaft nicht mehr als fünf Minuten fehlerfrei wurde in übersetzt werden ("healthstate"! = Ok und Now - LastOkTransitionTime &gt; 5 Minuten).</para></item></list></span><span class="sxs-lookup"><span data-stu-id="2f3f4-127">They enable scenarios such as: <list type="bullet"><item><para>Alert when a property has been at warning/error for more than X minutes. This avoids alerts on temporary conditions. For example, an alert if the health state has been warning for more than five minutes can be translated into (HealthState == Warning and Now - LastWarningTransitionTime &gt; 5 minutes).</para></item><item><para>Alert only on conditions that have changed in the last X minutes. If a report was already at error before the specified time, it can be ignored because it was already signaled previously.</para></item><item><para>If a property is toggling between warning and error, determine how long it has been unhealthy (i.e. not OK). For example, an alert if the property hasn't been healthy for more than five minutes can be translated into (HealthState != Ok and Now - LastOkTransitionTime &gt; 5 minutes).</para></item></list></span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastWarningTransitionAt">
      <MemberSignature Language="C#" Value="public DateTime LastWarningTransitionAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastWarningTransitionAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastWarningTransitionAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastWarningTransitionAt : DateTime" Usage="System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />
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
          <para><span data-ttu-id="2f3f4-128">Wenn die aktuelle <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> ist <see cref="F:System.Fabric.Health.HealthState.Warning" />, gibt der Zeitpunkt, an dem der Bericht zur Integrität ersten wurde, gemeldet, mit <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-128">If the current <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> is <see cref="F:System.Fabric.Health.HealthState.Warning" />, returns the time at which the health report was first reported with <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span> <span data-ttu-id="2f3f4-129">Für die regelmäßige Berichterstattung viele Berichte mit demselben Status möglicherweise generiert wurden.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-129">For periodic reporting, many reports with the same state may have been generated.</span></span></para>
          <para><span data-ttu-id="2f3f4-130">Wenn die aktuelle <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> ist <see cref="F:System.Fabric.Health.HealthState.Ok" /> oder <see cref="F:System.Fabric.Health.HealthState.Error" />, gibt die Zeit, an dem der Zustand des zuletzt im <see cref="F:System.Fabric.Health.HealthState.Warning" />, bevor der Übergang in ein anderes.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-130">If the current <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> is <see cref="F:System.Fabric.Health.HealthState.Ok" /> or <see cref="F:System.Fabric.Health.HealthState.Error" />, returns the time at which the health state was last in <see cref="F:System.Fabric.Health.HealthState.Warning" />, before transitioning to a different state.</span></span> <span data-ttu-id="2f3f4-131">Wenn die <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> war noch nie <see cref="F:System.Fabric.Health.HealthState.Warning" />, der Wert wird System.DateTime.FromFileTimeUtc(0) sein.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-131">If the <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> has never been <see cref="F:System.Fabric.Health.HealthState.Warning" />, the value will be System.DateTime.FromFileTimeUtc(0).</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2f3f4-132">Gibt <see cref="T:System.DateTime" /> darstellt, die letzte Übergang Time (UTC) mit <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-132">Returns <see cref="T:System.DateTime" /> representing the last transition time (UTC) involving <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="2f3f4-133">Die Felder Übergang <see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" /> Geben Sie den Verlauf der Integrität Zustandsübergänge für das Ereignis.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-133">The transition fields, <see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" /> give the history of the health state transitions for the event.</span></span>
            <span data-ttu-id="2f3f4-134">Sie können auf intelligentere Warnungen oder Ereignisinformationen "Versionsgeschichte" Integrität verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-134">They can be used for smarter alerts or "historical" health event information.</span></span> <span data-ttu-id="2f3f4-135">Sie ermöglichen Szenarien wie z. B.: <list type="bullet"> <item> <para>warnen, wenn eine Eigenschaft zur Warnung/Fehler für mehr als X Minuten wurde. Dies vermeidet Warnungen auf vorübergehende Bedingungen. Beispielsweise kann eine Warnung, wenn der Integritätsstatus für mehr als fünf Minuten Warnung wurde wurde übersetzt werden, in ("healthstate" Warnung "und" jetzt - LastWarningTransitionTime == &gt; 5 Minuten).</para> </item> <item> <para>Warnung nur bei Bedingungen, die in den letzten geändert haben X Minuten. Ein Bericht vor dem angegebenen Zeitpunkt bereits Fehlers war, kann ignoriert werden, da es bereits zuvor signalisiert wurde. </para> </item> <item> <para>, Wenn eine Eigenschaft, die zwischen den Warnungs- und umschalten ist, zu bestimmen, wie lange sie "fehlerhaft" (d. h. nicht OK) wurde. Beispielsweise kann eine Warnung, wenn die Eigenschaft nicht mehr als fünf Minuten fehlerfrei wurde in übersetzt werden ("healthstate"! = Ok und Now - LastOkTransitionTime &gt; 5 Minuten).</para></item></list></span><span class="sxs-lookup"><span data-stu-id="2f3f4-135">They enable scenarios such as: <list type="bullet"><item><para>Alert when a property has been at warning/error for more than X minutes. This avoids alerts on temporary conditions. For example, an alert if the health state has been warning for more than five minutes can be translated into (HealthState == Warning and Now - LastWarningTransitionTime &gt; 5 minutes).</para></item><item><para>Alert only on conditions that have changed in the last X minutes. If a report was already at error before the specified time, it can be ignored because it was already signaled previously.</para></item><item><para>If a property is toggling between warning and error, determine how long it has been unhealthy (i.e. not OK). For example, an alert if the property hasn't been healthy for more than five minutes can be translated into (HealthState != Ok and Now - LastOkTransitionTime &gt; 5 minutes).</para></item></list></span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceUtcTimestamp">
      <MemberSignature Language="C#" Value="public DateTime SourceUtcTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime SourceUtcTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.SourceUtcTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceUtcTimestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.SourceUtcTimestamp : DateTime" Usage="System.Fabric.Health.HealthEvent.SourceUtcTimestamp" />
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
          <para><span data-ttu-id="2f3f4-136">Ruft das Datum und Uhrzeit, wann der Bericht zur Integrität von der Quelle gesendet wurde.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-136">Gets the date and time when the health report was sent by the source.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2f3f4-137">Datum und Uhrzeit, wann der Bericht zur Integrität von der Quelle gesendet wurde.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-137">The date and time when the health report was sent by the source.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthEvent.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="healthEvent.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2f3f4-138">Ruft eine Zeichenfolgendarstellung der integritätsereignis ab.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-138">Gets a string representation of the health event.</span></span>
            </summary>
        <returns><span data-ttu-id="2f3f4-139">Eine Zeichenfolgendarstellung der integritätsereignis.</span><span class="sxs-lookup"><span data-stu-id="2f3f4-139">A string representation of the health event.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>