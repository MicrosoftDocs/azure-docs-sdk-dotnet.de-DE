<Type Name="NodeHealthStatesFilter" FullName="System.Fabric.Health.NodeHealthStatesFilter">
  <TypeSignature Language="C#" Value="public sealed class NodeHealthStatesFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeHealthStatesFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.NodeHealthStatesFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeHealthStatesFilter" />
  <TypeSignature Language="F#" Value="type NodeHealthStatesFilter = class" />
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
      <para><span data-ttu-id="b584e-101">Stellt den Filter für <see cref="T:System.Fabric.Health.NodeHealthState" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="b584e-101">Represents the filter for <see cref="T:System.Fabric.Health.NodeHealthState" /> objects.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="b584e-102">Der Filter kann verwendet werden, <see cref="T:System.Fabric.Description.ClusterHealthQueryDescription" /> an, welcher Knoten untergeordnete Elemente des Clusters zurückgegeben werden soll, im Rahmen des <see cref="T:System.Fabric.Health.ClusterHealth" />.</span><span class="sxs-lookup"><span data-stu-id="b584e-102">The filter can be used in <see cref="T:System.Fabric.Description.ClusterHealthQueryDescription" /> to specify which node children of the cluster should be returned as part of <see cref="T:System.Fabric.Health.ClusterHealth" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeHealthStatesFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.NodeHealthStatesFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="b584e-103">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.NodeHealthStatesFilter" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b584e-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.NodeHealthStatesFilter" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public long HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodeHealthStatesFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As Long" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : int64 with get, set" Usage="System.Fabric.Health.NodeHealthStatesFilter.HealthStateFilter" />
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
          <para><span data-ttu-id="b584e-104">ALS VERALTET MARKIERT.</span><span class="sxs-lookup"><span data-stu-id="b584e-104">DEPRECATED.</span></span> <span data-ttu-id="b584e-105">Ruft ab oder legt ihn fest des Filters für den aggregierten Zustand der <see cref="T:System.Fabric.Health.NodeHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="b584e-105">Gets or sets the filter for the aggregated health state of the <see cref="T:System.Fabric.Health.NodeHealthState" /> entries in the collection.</span></span> <span data-ttu-id="b584e-106">Stellt einen Wert, der von Membern oder bitweisen Kombinationen von Elementen der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span><span class="sxs-lookup"><span data-stu-id="b584e-106">Represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b584e-107">Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.NodeHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="b584e-107">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.NodeHealthState" /> entries in the collection.</span></span> <span data-ttu-id="b584e-108">Stellt einen Wert, der von Membern oder bitweisen Kombinationen von Elementen der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span><span class="sxs-lookup"><span data-stu-id="b584e-108">Represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></para>
        </value>
        <remarks><span data-ttu-id="b584e-109">Diese Eigenschaft ist veraltet.</span><span class="sxs-lookup"><span data-stu-id="b584e-109">This property is obsolete.</span></span> <span data-ttu-id="b584e-110">Verwenden Sie stattdessen <see cref="P:System.Fabric.Health.NodeHealthStatesFilter.HealthStateFilterValue" />.</span><span class="sxs-lookup"><span data-stu-id="b584e-110">Use <see cref="P:System.Fabric.Health.NodeHealthStatesFilter.HealthStateFilterValue" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilterValue">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilterValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilterValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodeHealthStatesFilter.HealthStateFilterValue" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilterValue As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilterValue : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.NodeHealthStatesFilter.HealthStateFilterValue" />
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
            <span data-ttu-id="b584e-111">Ruft ab oder legt ihn fest des Filters für den aggregierten Zustand der <see cref="T:System.Fabric.Health.NodeHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="b584e-111">Gets or sets the filter for the aggregated health state of the <see cref="T:System.Fabric.Health.NodeHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="b584e-112">Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.NodeHealthState" /> Einträge.</span><span class="sxs-lookup"><span data-stu-id="b584e-112">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.NodeHealthState" /> entries.</span></span></value>
        <remarks><span data-ttu-id="b584e-113">Die Eingabesammlung wird gefiltert, dass nur Einträge zurückgegeben, die den gewünschten Zustand zu berücksichtigen.</span><span class="sxs-lookup"><span data-stu-id="b584e-113">The input collection is filtered to return only entries that respect the desired health state.</span></span> <span data-ttu-id="b584e-114">Der Filter stellt einen Wert, der von Membern oder bitweisen Kombinationen von Elementen der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span><span class="sxs-lookup"><span data-stu-id="b584e-114">The filter represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.NodeHealthStatesFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeHealthStatesFilter.ToString " />
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
            <span data-ttu-id="b584e-115">Gibt eine Zeichenfolgendarstellung des Filters zurück.</span><span class="sxs-lookup"><span data-stu-id="b584e-115">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="b584e-116">Eine Zeichenfolgendarstellung des Filters.</span><span class="sxs-lookup"><span data-stu-id="b584e-116">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>