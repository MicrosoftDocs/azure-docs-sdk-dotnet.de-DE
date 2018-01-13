<Type Name="PartitionHealthStatesFilter" FullName="System.Fabric.Health.PartitionHealthStatesFilter">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealthStatesFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealthStatesFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionHealthStatesFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealthStatesFilter" />
  <TypeSignature Language="F#" Value="type PartitionHealthStatesFilter = class" />
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
      <para><span data-ttu-id="08734-101">Stellt den Filter für <see cref="T:System.Fabric.Health.PartitionHealthState" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="08734-101">Represents the filter for <see cref="T:System.Fabric.Health.PartitionHealthState" /> objects.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="08734-102">Der Filter kann verwendet werden, <see cref="T:System.Fabric.Description.ServiceHealthQueryDescription" /> an, welche Partition untergeordnete Elemente zurückgegeben werden soll, im Rahmen des <see cref="T:System.Fabric.Health.ServiceHealth" />.</span><span class="sxs-lookup"><span data-stu-id="08734-102">The filter can be used in <see cref="T:System.Fabric.Description.ServiceHealthQueryDescription" /> to specify which partition children should be returned as part of <see cref="T:System.Fabric.Health.ServiceHealth" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionHealthStatesFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthStatesFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="08734-103">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.PartitionHealthStatesFilter" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="08734-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.PartitionHealthStatesFilter" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public long HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStatesFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As Long" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : int64 with get, set" Usage="System.Fabric.Health.PartitionHealthStatesFilter.HealthStateFilter" />
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
          <para><span data-ttu-id="08734-104">ALS VERALTET MARKIERT.</span><span class="sxs-lookup"><span data-stu-id="08734-104">DEPRECATED.</span></span> <span data-ttu-id="08734-105">Ruft ab oder legt ihn fest des Filters für den aggregierten Zustand der <see cref="T:System.Fabric.Health.PartitionHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="08734-105">Gets or sets the filter for the aggregated health state of the <see cref="T:System.Fabric.Health.PartitionHealthState" /> entries in the collection.</span></span> <span data-ttu-id="08734-106">Stellt einen Wert, der von Membern oder bitweisen Kombinationen von Elementen der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span><span class="sxs-lookup"><span data-stu-id="08734-106">Represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="08734-107">Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.PartitionHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="08734-107">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.PartitionHealthState" /> entries in the collection.</span></span> <span data-ttu-id="08734-108">Der Wert stammt von Membern oder bitweisen Kombination von Membern der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span><span class="sxs-lookup"><span data-stu-id="08734-108">The value comes from members or bitwise combination of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></para>
        </value>
        <remarks><span data-ttu-id="08734-109">Diese Eigenschaft ist veraltet.</span><span class="sxs-lookup"><span data-stu-id="08734-109">This property is obsolete.</span></span> <span data-ttu-id="08734-110">Verwenden Sie stattdessen <see cref="P:System.Fabric.Health.PartitionHealthStatesFilter.HealthStateFilterValue" />.</span><span class="sxs-lookup"><span data-stu-id="08734-110">Use <see cref="P:System.Fabric.Health.PartitionHealthStatesFilter.HealthStateFilterValue" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilterValue">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilterValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilterValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStatesFilter.HealthStateFilterValue" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilterValue As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilterValue : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.PartitionHealthStatesFilter.HealthStateFilterValue" />
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
            <span data-ttu-id="08734-111">Ruft ab oder legt ihn fest des Filters für den aggregierten Zustand der <see cref="T:System.Fabric.Health.PartitionHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="08734-111">Gets or sets the filter for the aggregated health state of the <see cref="T:System.Fabric.Health.PartitionHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="08734-112">Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.PartitionHealthState" /> Einträge.</span><span class="sxs-lookup"><span data-stu-id="08734-112">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.PartitionHealthState" /> entries.</span></span></value>
        <remarks><span data-ttu-id="08734-113">Die Eingabesammlung wird gefiltert, dass nur Einträge zurückgegeben, die den gewünschten Zustand zu berücksichtigen.</span><span class="sxs-lookup"><span data-stu-id="08734-113">The input collection is filtered to return only entries that respect the desired health state.</span></span> <span data-ttu-id="08734-114">Der Filter stellt einen Wert, der von Membern oder bitweisen Kombinationen von Elementen der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span><span class="sxs-lookup"><span data-stu-id="08734-114">The filter represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthStatesFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionHealthStatesFilter.ToString " />
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
            <span data-ttu-id="08734-115">Gibt eine Zeichenfolgendarstellung des Filters zurück.</span><span class="sxs-lookup"><span data-stu-id="08734-115">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="08734-116">Eine Zeichenfolgendarstellung des Filters.</span><span class="sxs-lookup"><span data-stu-id="08734-116">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>