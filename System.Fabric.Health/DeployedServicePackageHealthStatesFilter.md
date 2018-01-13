<Type Name="DeployedServicePackageHealthStatesFilter" FullName="System.Fabric.Health.DeployedServicePackageHealthStatesFilter">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealthStatesFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealthStatesFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackageHealthStatesFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealthStatesFilter" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthStatesFilter = class" />
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
      <para><span data-ttu-id="97eb4-101">Stellt den Filter für <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="97eb4-101">Represents the filter for <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> objects.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="97eb4-102">Der Filter kann verwendet werden, <see cref="T:System.Fabric.Description.DeployedApplicationHealthQueryDescription" /> an, welche bereitgestelltes Dienstpaket untergeordnete Elemente zurückgegeben werden soll, im Rahmen des <see cref="T:System.Fabric.Health.DeployedApplicationHealth" />.</span><span class="sxs-lookup"><span data-stu-id="97eb4-102">The filter can be used in <see cref="T:System.Fabric.Description.DeployedApplicationHealthQueryDescription" /> to specify which deployed service package children should be returned as part of <see cref="T:System.Fabric.Health.DeployedApplicationHealth" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthStatesFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStatesFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="97eb4-103">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStatesFilter" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="97eb4-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStatesFilter" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public long HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStatesFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As Long" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : int64 with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStatesFilter.HealthStateFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This property is obsolete. Use HealthStateFilterValue instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="97eb4-104">ALS VERALTET MARKIERT.</span><span class="sxs-lookup"><span data-stu-id="97eb4-104">DEPRECATED.</span></span> <span data-ttu-id="97eb4-105">Ruft ab oder legt ihn fest des Filters für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="97eb4-105">Gets or sets the filter for the aggregated health state of the <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> entries in the collection.</span></span> <span data-ttu-id="97eb4-106">Stellt einen Wert, der von Membern oder bitweisen Kombinationen von Elementen der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span><span class="sxs-lookup"><span data-stu-id="97eb4-106">Represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="97eb4-107">Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="97eb4-107">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> entries in the collection.</span></span></para>
        </value>
        <remarks><span data-ttu-id="97eb4-108">Diese Eigenschaft ist veraltet.</span><span class="sxs-lookup"><span data-stu-id="97eb4-108">This property is obsolete.</span></span> <span data-ttu-id="97eb4-109">Verwenden Sie stattdessen <see cref="P:System.Fabric.Health.ApplicationHealthStatesFilter.HealthStateFilterValue" />.</span><span class="sxs-lookup"><span data-stu-id="97eb4-109">Use <see cref="P:System.Fabric.Health.ApplicationHealthStatesFilter.HealthStateFilterValue" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilterValue">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilterValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilterValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStatesFilter.HealthStateFilterValue" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilterValue As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilterValue : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStatesFilter.HealthStateFilterValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStateFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="97eb4-110">Ruft ab oder legt ihn fest des Filters für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="97eb4-110">Gets or sets the filter for the aggregated health state of the <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="97eb4-111">Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> Einträge.</span><span class="sxs-lookup"><span data-stu-id="97eb4-111">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> entries.</span></span></value>
        <remarks><span data-ttu-id="97eb4-112">Die Eingabesammlung wird gefiltert, dass nur Einträge zurückgegeben, die den gewünschten Zustand zu berücksichtigen.</span><span class="sxs-lookup"><span data-stu-id="97eb4-112">The input collection is filtered to return only entries that respect the desired health state.</span></span> <span data-ttu-id="97eb4-113">Der Filter stellt einen Wert, der von Membern oder bitweisen Kombinationen von Elementen der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span><span class="sxs-lookup"><span data-stu-id="97eb4-113">The filter represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStatesFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedServicePackageHealthStatesFilter.ToString " />
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
            <span data-ttu-id="97eb4-114">Gibt eine Zeichenfolgendarstellung des Filters zurück.</span><span class="sxs-lookup"><span data-stu-id="97eb4-114">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="97eb4-115">Eine Zeichenfolgendarstellung des Filters.</span><span class="sxs-lookup"><span data-stu-id="97eb4-115">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>