<Type Name="NodeImpact" FullName="System.Fabric.Repair.NodeImpact">
  <TypeSignature Language="C#" Value="public sealed class NodeImpact" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeImpact extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.NodeImpact" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeImpact" />
  <TypeSignature Language="F#" Value="type NodeImpact = class" />
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
      <para><span data-ttu-id="da2cc-101">Beschreibt den erwartete Auswirkung einer Reparatur zu einem bestimmten Knoten.</span><span class="sxs-lookup"><span data-stu-id="da2cc-101">Describes the expected impact of a repair to a particular node.</span></span></para>
      <para><span data-ttu-id="da2cc-102">Diese Klasse unterstützt die Service Fabric-Plattform. Es ist nicht vorgesehen, direkt aus Ihrem Code aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="da2cc-102">This class supports the Service Fabric platform; it is not meant to be called directly from your code.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeImpact ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeImpact.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="da2cc-103">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Repair.NodeImpact" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="da2cc-103">Initializes a new instance of the <see cref="T:System.Fabric.Repair.NodeImpact" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeImpact (string nodeName, System.Fabric.Repair.NodeImpactLevel impactLevel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nodeName, valuetype System.Fabric.Repair.NodeImpactLevel impactLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeImpact.#ctor(System.String,System.Fabric.Repair.NodeImpactLevel)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nodeName As String, impactLevel As NodeImpactLevel)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Repair.NodeImpact : string * System.Fabric.Repair.NodeImpactLevel -&gt; System.Fabric.Repair.NodeImpact" Usage="new System.Fabric.Repair.NodeImpact (nodeName, impactLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="impactLevel" Type="System.Fabric.Repair.NodeImpactLevel" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="da2cc-104">Der Name des betroffenen Knoten.</span><span class="sxs-lookup"><span data-stu-id="da2cc-104">The name of the impacted node.</span></span></para>
        </param>
        <param name="impactLevel">
          <para><span data-ttu-id="da2cc-105">Die Ebene der Auswirkungen erwartet.</span><span class="sxs-lookup"><span data-stu-id="da2cc-105">The level of impact expected.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="da2cc-106">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Repair.NodeImpact" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="da2cc-106">Initializes a new instance of the <see cref="T:System.Fabric.Repair.NodeImpact" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImpactLevel">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.NodeImpactLevel ImpactLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Repair.NodeImpactLevel ImpactLevel" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.NodeImpact.ImpactLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ImpactLevel As NodeImpactLevel" />
      <MemberSignature Language="F#" Value="member this.ImpactLevel : System.Fabric.Repair.NodeImpactLevel with get, set" Usage="System.Fabric.Repair.NodeImpact.ImpactLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.NodeImpactLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="da2cc-107">Ruft ab oder legt fest, Auswirkungen erwartet.</span><span class="sxs-lookup"><span data-stu-id="da2cc-107">Gets or sets the level of impact expected.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="da2cc-108">Die Ebene der Auswirkungen erwartet.</span><span class="sxs-lookup"><span data-stu-id="da2cc-108">The level of impact expected.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.NodeImpact.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string with get, set" Usage="System.Fabric.Repair.NodeImpact.NodeName" />
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
          <para><span data-ttu-id="da2cc-109">Ruft ab oder legt den Namen des betroffenen Knotens fest.</span><span class="sxs-lookup"><span data-stu-id="da2cc-109">Gets or sets the name of the impacted node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="da2cc-110">Der Name des betroffenen Knoten.</span><span class="sxs-lookup"><span data-stu-id="da2cc-110">The name of the impacted node.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeImpact.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeImpact.ToString " />
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
          <para><span data-ttu-id="da2cc-111">Konvertiert den Wert des aktuellen Objekts in eine Zeichenfolgendarstellung.</span><span class="sxs-lookup"><span data-stu-id="da2cc-111">Converts the value of the current object to a string representation.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="da2cc-112">Eine Zeichenfolgendarstellung der Name und die Auswirkungen auf Knotenebene.</span><span class="sxs-lookup"><span data-stu-id="da2cc-112">A string representation of the node name and impact level.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>