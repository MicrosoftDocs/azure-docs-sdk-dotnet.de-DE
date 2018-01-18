<Type Name="RollingUpgradeMonitoringPolicy" FullName="System.Fabric.Description.RollingUpgradeMonitoringPolicy">
  <TypeSignature Language="C#" Value="public class RollingUpgradeMonitoringPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RollingUpgradeMonitoringPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.RollingUpgradeMonitoringPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class RollingUpgradeMonitoringPolicy" />
  <TypeSignature Language="F#" Value="type RollingUpgradeMonitoringPolicy = class" />
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
      <para><span data-ttu-id="520dc-101">Stellt eine Klasse, ein paralleles Upgrade Überwachen der Richtlinie zu kapseln.</span><span class="sxs-lookup"><span data-stu-id="520dc-101">Represents a class to encapsulate a rolling upgrade monitoring policy.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RollingUpgradeMonitoringPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.RollingUpgradeMonitoringPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="520dc-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.RollingUpgradeMonitoringPolicy" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="520dc-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.RollingUpgradeMonitoringPolicy" /> class.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="520dc-103">Die Initialisierung legt die Eigenschaften der <see cref="T:System.Fabric.Description.RollingUpgradeMonitoringPolicy" /> Klasse mit den folgenden Standardeinstellungen.</span><span class="sxs-lookup"><span data-stu-id="520dc-103">The initialization sets the properties of the <see cref="T:System.Fabric.Description.RollingUpgradeMonitoringPolicy" /> class with the following defaults.</span></span></para>
          <para><span data-ttu-id="520dc-104">Eigenschaft</span><span class="sxs-lookup"><span data-stu-id="520dc-104">Property</span></span></para>
          <para><span data-ttu-id="520dc-105">Standardwert</span><span class="sxs-lookup"><span data-stu-id="520dc-105">Default value</span></span></para>
          <list type="table">
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />
                </para>
              </term>
              <description>
                <para>
                  <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" />
                </para>
                <para><span data-ttu-id="520dc-106">Dieser Wert geändert werden muss oder eine <see cref="T:System.ArgumentException" /> wird vor Beginn des Upgrades ausgelöst werden.</span><span class="sxs-lookup"><span data-stu-id="520dc-106">This value must be changed or a <see cref="T:System.ArgumentException" /> will be thrown before the upgrade begins.</span></span></para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />
                </para>
              </term>
              <description>
                <para>
                  <see cref="F:System.TimeSpan.Zero" />
                </para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />
                </para>
              </term>
              <description>
                <para>
                  <span data-ttu-id="520dc-107"><see cref="T:System.TimeSpan" />Wert, der standardmäßig auf 120 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="520dc-107"><see cref="T:System.TimeSpan" /> value that defaults to 120 seconds.</span></span>
                    </para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />
                </para>
              </term>
              <description>
                <para><span data-ttu-id="520dc-108">600 Sekunden</span><span class="sxs-lookup"><span data-stu-id="520dc-108">600 seconds</span></span></para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />
                </para>
              </term>
              <description>
                <para><span data-ttu-id="520dc-109">TimeSpan.FromSeconds ("uint". "MaxValue")</span><span class="sxs-lookup"><span data-stu-id="520dc-109">TimeSpan.FromSeconds(uint.MaxValue)</span></span></para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />
                </para>
              </term>
              <description>
                <para><span data-ttu-id="520dc-110">TimeSpan.FromSeconds ("uint". "MaxValue")</span><span class="sxs-lookup"><span data-stu-id="520dc-110">TimeSpan.FromSeconds(uint.MaxValue)</span></span></para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureAction">
      <MemberSignature Language="C#" Value="public System.Fabric.UpgradeFailureAction FailureAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.UpgradeFailureAction FailureAction" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureAction As UpgradeFailureAction" />
      <MemberSignature Language="F#" Value="member this.FailureAction : System.Fabric.UpgradeFailureAction with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeFailureAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="520dc-111">Ruft ab oder legt die Aktion an, wenn das Upgrade fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="520dc-111">Gets or sets the action to take if an upgrade fails.</span></span> <span data-ttu-id="520dc-112">Der Standardwert lautet <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" />.</span><span class="sxs-lookup"><span data-stu-id="520dc-112">The default is <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="520dc-113">Die Aktion an, wenn das Upgrade fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="520dc-113">The action to take if an upgrade fails.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="520dc-114">Die <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> -Eigenschaft muss geändert werden, von der Standardeinstellung <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" /> oder ein <see cref="T:System.ArgumentException" /> wird vor Beginn des Upgrades ausgelöst werden.</span><span class="sxs-lookup"><span data-stu-id="520dc-114">The <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> property must be changed from the default of <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" /> or a <see cref="T:System.ArgumentException" /> will be thrown before the upgrade begins.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="520dc-115">Die <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />-Eigenschaft ist auf <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" /> festgelegt.</span><span class="sxs-lookup"><span data-stu-id="520dc-115">The <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> property is set to <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" />.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckRetryTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckRetryTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckRetryTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />
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
          <para><span data-ttu-id="520dc-116">Ruft ab oder legt die Länge der Zeit, die Integrität kann fehlschlagen überprüft, fortlaufend, bevor das Upgrade fehlschlägt und die angegebene Aktion <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> auftritt.</span><span class="sxs-lookup"><span data-stu-id="520dc-116">Gets or sets the length of time that health checks can fail continuously before the upgrade fails and the action specified by <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> occurs.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="520dc-117">Die Zeitdauer, die integritätsprüfungen fortlaufend ausgeführt werden können.</span><span class="sxs-lookup"><span data-stu-id="520dc-117">The length of time that health checks can fail continuously.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="520dc-118">Der Standardwert ist 600 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="520dc-118">The default is 600 seconds.</span></span> <span data-ttu-id="520dc-119">Festlegen von <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" /> zu <see cref="F:System.TimeSpan.Zero" /> führt dazu, nur einen einzelnen integritätsprüfung durchgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="520dc-119">Setting <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" /> to <see cref="F:System.TimeSpan.Zero" /> will result in only a single health check.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckStableDuration">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckStableDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckStableDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckStableDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckStableDuration : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />
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
          <para><span data-ttu-id="520dc-120">Ruft ab oder legt die Zeitspanne, die Integrität erfüllen muss überprüft, fortlaufend, bevor das Upgrade auf die nächste upgradedomäne durchgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="520dc-120">Gets or sets the length of time that health checks must pass continuously before the upgrade proceeds to the next upgrade domain.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="520dc-121">Die Zeitdauer, die fortlaufend Systemdiagnosen übergeben müssen.</span><span class="sxs-lookup"><span data-stu-id="520dc-121">The length of time that health checks must pass continuously.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="520dc-122">Der Standardwert ist 120 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="520dc-122">The default is 120 seconds.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckWaitDuration">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckWaitDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckWaitDuration : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />
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
          <para><span data-ttu-id="520dc-123">Ruft ab oder legt die Länge der Wartezeit nach Abschluss einer upgradedomäne vor dem Ausführen von integritätsprüfungen fest.</span><span class="sxs-lookup"><span data-stu-id="520dc-123">Gets or sets the length of time to wait after completing an upgrade domain before performing health checks.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="520dc-124">Die Länge der Wartezeit nach Abschluss einer upgradedomäne vor dem Ausführen von integritätsprüfungen.</span><span class="sxs-lookup"><span data-stu-id="520dc-124">The length of time to wait after completing an upgrade domain before performing health checks.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="520dc-125">Der Standardwert lautet <see cref="F:System.TimeSpan.Zero" />.</span><span class="sxs-lookup"><span data-stu-id="520dc-125">The default is <see cref="F:System.TimeSpan.Zero" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeDomainTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeDomainTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeDomainTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />
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
          <para><span data-ttu-id="520dc-126">Ruft ab oder legt die Länge der Zeit, die die Verarbeitung von keine der upgradedomänen vor dem Upgrade ein Fehler auftritt und die angegebene Aktion <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> auftritt.</span><span class="sxs-lookup"><span data-stu-id="520dc-126">Gets or sets the length of time that the processing of any upgrade domain can take before the upgrade fails and the action specified by <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> occurs.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="520dc-127">Das Timeout für keine der upgradedomänen.</span><span class="sxs-lookup"><span data-stu-id="520dc-127">The timeout for any upgrade domain.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="520dc-128">Die Standardeinstellung ist TimeSpan.FromSeconds ("uint". "MaxValue").</span><span class="sxs-lookup"><span data-stu-id="520dc-128">The default is TimeSpan.FromSeconds(uint.MaxValue).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />
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
          <para><span data-ttu-id="520dc-129">Ruft ab oder legt die Länge der Zeit, die das gesamte Upgrade vor dem Upgrade ein Fehler auftritt und die angegebene Aktion <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> auftritt.</span><span class="sxs-lookup"><span data-stu-id="520dc-129">Gets or sets the length of time that the overall upgrade can take before the upgrade fails and the action specified by <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> occurs.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="520dc-130">Der timeoutgesamtwert für das Upgrade.</span><span class="sxs-lookup"><span data-stu-id="520dc-130">The upgrade timeout.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="520dc-131">Die Standardeinstellung ist TimeSpan.FromSeconds ("uint". "MaxValue").</span><span class="sxs-lookup"><span data-stu-id="520dc-131">The default is TimeSpan.FromSeconds(uint.MaxValue).</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>