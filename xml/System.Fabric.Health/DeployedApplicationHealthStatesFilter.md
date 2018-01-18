<Type Name="DeployedApplicationHealthStatesFilter" FullName="System.Fabric.Health.DeployedApplicationHealthStatesFilter">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealthStatesFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealthStatesFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationHealthStatesFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealthStatesFilter" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthStatesFilter = class" />
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
      <para><span data-ttu-id="aa40e-101">Stellt den Filter für <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="aa40e-101">Represents the filter for <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> objects.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="aa40e-102">Der Filter kann verwendet werden, <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> an der bereitgestellten Anwendung untergeordnete Elemente zurückgegeben werden sollen, im Rahmen des <see cref="T:System.Fabric.Health.ApplicationHealth" />.</span><span class="sxs-lookup"><span data-stu-id="aa40e-102">The filter can be used in <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> to specify which deployed application children should be returned as part of <see cref="T:System.Fabric.Health.ApplicationHealth" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedApplicationHealthStatesFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthStatesFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="aa40e-103">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.DeployedApplicationHealthStatesFilter" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="aa40e-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.DeployedApplicationHealthStatesFilter" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public long HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStatesFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As Long" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : int64 with get, set" Usage="System.Fabric.Health.DeployedApplicationHealthStatesFilter.HealthStateFilter" />
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
          <para><span data-ttu-id="aa40e-104">ALS VERALTET MARKIERT.</span><span class="sxs-lookup"><span data-stu-id="aa40e-104">DEPRECATED.</span></span> <span data-ttu-id="aa40e-105">Ruft ab oder legt ihn fest des Filters für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="aa40e-105">Gets or sets the filter for the aggregated health state of the <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> entries in the collection.</span></span> <span data-ttu-id="aa40e-106">Stellt einen Wert, der von Membern oder bitweisen Kombinationen von Elementen der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span><span class="sxs-lookup"><span data-stu-id="aa40e-106">Represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="aa40e-107">Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="aa40e-107">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> entries in the collection.</span></span></para>
        </value>
        <remarks><span data-ttu-id="aa40e-108">Diese Eigenschaft ist veraltet.</span><span class="sxs-lookup"><span data-stu-id="aa40e-108">This property is obsolete.</span></span> <span data-ttu-id="aa40e-109">Verwenden Sie stattdessen <see cref="P:System.Fabric.Health.DeployedApplicationHealthStatesFilter.HealthStateFilterValue" />.</span><span class="sxs-lookup"><span data-stu-id="aa40e-109">Use <see cref="P:System.Fabric.Health.DeployedApplicationHealthStatesFilter.HealthStateFilterValue" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilterValue">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilterValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilterValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStatesFilter.HealthStateFilterValue" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilterValue As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilterValue : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.DeployedApplicationHealthStatesFilter.HealthStateFilterValue" />
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
            <span data-ttu-id="aa40e-110">Ruft ab oder legt ihn fest des Filters für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="aa40e-110">Gets or sets the filter for the aggregated health state of the <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="aa40e-111">Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> Einträge.</span><span class="sxs-lookup"><span data-stu-id="aa40e-111">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> entries.</span></span></value>
        <remarks><span data-ttu-id="aa40e-112">Die Eingabesammlung wird gefiltert, dass nur Einträge zurückgegeben, die den gewünschten Zustand zu berücksichtigen.</span><span class="sxs-lookup"><span data-stu-id="aa40e-112">The input collection is filtered to return only entries that respect the desired health state.</span></span> <span data-ttu-id="aa40e-113">Der Filter stellt einen Wert, der von Membern oder bitweisen Kombinationen von Elementen der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span><span class="sxs-lookup"><span data-stu-id="aa40e-113">The filter represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthStatesFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedApplicationHealthStatesFilter.ToString " />
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
            <span data-ttu-id="aa40e-114">Gibt eine Zeichenfolgendarstellung des Filters zurück.</span><span class="sxs-lookup"><span data-stu-id="aa40e-114">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="aa40e-115">Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Health.DeployedApplicationHealthStatesFilter" />.</span><span class="sxs-lookup"><span data-stu-id="aa40e-115">A string representation of the <see cref="T:System.Fabric.Health.DeployedApplicationHealthStatesFilter" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>