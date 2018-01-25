<Type Name="ServiceTypeHealthPolicy" FullName="System.Fabric.Health.ServiceTypeHealthPolicy">
  <TypeSignature Language="C#" Value="public class ServiceTypeHealthPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceTypeHealthPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceTypeHealthPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceTypeHealthPolicy" />
  <TypeSignature Language="F#" Value="type ServiceTypeHealthPolicy = class" />
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
      <para><span data-ttu-id="54ded-101">Stellt die Integritätsrichtlinie, die zur Bewertung der Integritäts von Diensten, die zu einem Diensttyp gehören.</span><span class="sxs-lookup"><span data-stu-id="54ded-101">Represents the health policy used to evaluate the health of services belonging to a service type.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceTypeHealthPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceTypeHealthPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="54ded-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ServiceTypeHealthPolicy" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="54ded-102">Initializes a new instance of <see cref="T:System.Fabric.Health.ServiceTypeHealthPolicy" /> class.</span></span></para>
        </summary>
        <remarks><span data-ttu-id="54ded-103">Standardmäßig werden keine Fehler oder Warnungen toleriert werden.</span><span class="sxs-lookup"><span data-stu-id="54ded-103">By default, no errors or warnings are tolerated.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyPartitionsPerService">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyPartitionsPerService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyPartitionsPerService" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyPartitionsPerService" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyPartitionsPerService As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyPartitionsPerService : byte with get, set" Usage="System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyPartitionsPerService" />
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
          <para><span data-ttu-id="54ded-104">Ruft ab oder legt die maximal zulässigen Prozentsatz fehlerhafter Partitionen pro Dienst.</span><span class="sxs-lookup"><span data-stu-id="54ded-104">Gets or sets the maximum allowed percentage of unhealthy partitions per service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="54ded-105">Gibt die maximal zulässige Prozentsatz fehlerhafter Partitionen pro Dienst zurück.</span><span class="sxs-lookup"><span data-stu-id="54ded-105">Returns the maximum allowed percentage of unhealthy partitions per service.</span></span>
            <span data-ttu-id="54ded-106">Zulässige Werte sind <see cref="T:System.Byte" /> Werte von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="54ded-106">Allowed values are <see cref="T:System.Byte" /> values from zero to 100.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="54ded-107">Der Prozentsatz stellt den zulässigen maximalen Prozentsatz der Partitionen, die fehlerhaft sein kann, bevor der Dienst bei Fehler betrachtet wird.</span><span class="sxs-lookup"><span data-stu-id="54ded-107">The percentage represents the maximum tolerated percentage of partitions that can be unhealthy before the service is considered in error.</span></span> <span data-ttu-id="54ded-108">Wenn der Prozentsatz wird berücksichtigt, aber mindestens ein "fehlerhaft" Partition vorhanden ist, wird die Integrität als Warnung ausgewertet.</span><span class="sxs-lookup"><span data-stu-id="54ded-108">If the percentage is respected but there is at least one unhealthy partition, the health is evaluated as Warning.</span></span>
            <span data-ttu-id="54ded-109">Dies wird berechnet durch Dividieren der Anzahl der fehlerhaften Partitionen über die Gesamtanzahl der Partitionen im Dienst.</span><span class="sxs-lookup"><span data-stu-id="54ded-109">This is calculated by dividing the number of unhealthy partitions over the total number of partitions in the service.</span></span>
            <span data-ttu-id="54ded-110">Rundet auf die Berechnung auf kleinen Anzahl von Partitionen einen Ausfall tolerieren kann.</span><span class="sxs-lookup"><span data-stu-id="54ded-110">The computation rounds up to tolerate one failure on small numbers of partitions.</span></span> <span data-ttu-id="54ded-111">Standardprozentsatz : null.</span><span class="sxs-lookup"><span data-stu-id="54ded-111">Default percentage: zero.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="54ded-112">Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="54ded-112">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyReplicasPerPartition">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyReplicasPerPartition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyReplicasPerPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyReplicasPerPartition" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyReplicasPerPartition As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyReplicasPerPartition : byte with get, set" Usage="System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyReplicasPerPartition" />
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
          <para><span data-ttu-id="54ded-113">Ruft ab oder legt die maximal zulässigen Prozentsatz fehlerhafter Replikate pro Partition.</span><span class="sxs-lookup"><span data-stu-id="54ded-113">Gets or sets the maximum allowed percentage of unhealthy replicas per partition.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="54ded-114">Gibt die maximal zulässige Prozentsatz fehlerhafter Replikate pro Partition zurück.</span><span class="sxs-lookup"><span data-stu-id="54ded-114">Returns the maximum allowed percentage of unhealthy replicas per partition.</span></span>
            <span data-ttu-id="54ded-115">Zulässige Werte sind <see cref="T:System.Byte" /> Werte von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="54ded-115">Allowed values are <see cref="T:System.Byte" /> values from zero to 100.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="54ded-116">Der Prozentsatz stellt den zulässigen maximalen Prozentsatz der Replikate, die fehlerhaft sein kann, bevor die Partition bei Fehler betrachtet wird.</span><span class="sxs-lookup"><span data-stu-id="54ded-116">The percentage represents the maximum tolerated percentage of replicas that can be unhealthy before the partition is considered in error.</span></span> <span data-ttu-id="54ded-117">Wenn der Prozentsatz wird berücksichtigt, aber mindestens ein "fehlerhaft" Replikat vorhanden ist, wird die Integrität als Warnung ausgewertet.</span><span class="sxs-lookup"><span data-stu-id="54ded-117">If the percentage is respected but there is at least one unhealthy replica, the health is evaluated as Warning.</span></span>
            <span data-ttu-id="54ded-118">Dies wird durch Dividieren die Anzahl der fehlerhaften Replikate über die Anzahl von Replikaten in der Partition berechnet.</span><span class="sxs-lookup"><span data-stu-id="54ded-118">This is calculated by dividing the number of unhealthy replicas over the total number of replicas in the partition.</span></span>
            <span data-ttu-id="54ded-119">Rundet auf die Berechnung auf kleinere Mengen von Replikaten ein Ausfall tolerieren kann.</span><span class="sxs-lookup"><span data-stu-id="54ded-119">The computation rounds up to tolerate one failure on small numbers of replicas.</span></span> <span data-ttu-id="54ded-120">Standardprozentsatz : null.</span><span class="sxs-lookup"><span data-stu-id="54ded-120">Default percentage: zero.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="54ded-121">Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="54ded-121">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyServices">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyServices { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyServices" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyServices" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyServices As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyServices : byte with get, set" Usage="System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyServices" />
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
          <para><span data-ttu-id="54ded-122">Ruft ab oder legt die maximal zulässigen Prozentsatz fehlerhafter Dienste.</span><span class="sxs-lookup"><span data-stu-id="54ded-122">Gets or sets the maximum allowed percentage of unhealthy services.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="54ded-123">Gibt die maximal zulässige Prozentsatz fehlerhafter Dienste zurück.</span><span class="sxs-lookup"><span data-stu-id="54ded-123">Returns the maximum allowed percentage of unhealthy services.</span></span> <span data-ttu-id="54ded-124">Zulässige Werte sind <see cref="T:System.Byte" /> Werte von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="54ded-124">Allowed values are <see cref="T:System.Byte" /> values from zero to 100.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="54ded-125">Der Prozentsatz stellt den zulässigen maximalen Prozentsatz von Diensten, die fehlerhaft sein kann, bevor die Anwendung bei Fehler betrachtet wird.</span><span class="sxs-lookup"><span data-stu-id="54ded-125">The percentage represents the maximum tolerated percentage of services that can be unhealthy before the application is considered in error.</span></span> <span data-ttu-id="54ded-126">Wenn der Prozentsatz wird berücksichtigt, aber mindestens ein "fehlerhaft" Dienst vorhanden ist, wird die Integrität als Warnung ausgewertet.</span><span class="sxs-lookup"><span data-stu-id="54ded-126">If the percentage is respected but there is at least one unhealthy service, the health is evaluated as Warning.</span></span>
            <span data-ttu-id="54ded-127">Dies wird durch Division der "fehlerhaft" Dienste des Typs angegebenen Dienst über die Gesamtzahl der Dienste des Typs spezifischen Dienst berechnet.</span><span class="sxs-lookup"><span data-stu-id="54ded-127">This is calculated by dividing the number of unhealthy services of the specific service type over the total number of services of the specific service type.</span></span>
            <span data-ttu-id="54ded-128">Rundet auf die Berechnung auf kleinere Mengen von Services ein Ausfall tolerieren kann.</span><span class="sxs-lookup"><span data-stu-id="54ded-128">The computation rounds up to tolerate one failure on small numbers of services.</span></span> <span data-ttu-id="54ded-129">Standardprozentsatz : null.</span><span class="sxs-lookup"><span data-stu-id="54ded-129">Default percentage: zero.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="54ded-130">Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="54ded-130">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceTypeHealthPolicy.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceTypeHealthPolicy.ToString " />
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
            <span data-ttu-id="54ded-131">Ruft eine Zeichenfolgendarstellung der Integritätsrichtlinie für Service-Typ ab.</span><span class="sxs-lookup"><span data-stu-id="54ded-131">Gets a string representation of the service type health policy.</span></span>
            </summary>
        <returns><span data-ttu-id="54ded-132">Eine Zeichenfolgendarstellung der Integritätsrichtlinie für Service-Typ.</span><span class="sxs-lookup"><span data-stu-id="54ded-132">A string representation of the service type health policy.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>