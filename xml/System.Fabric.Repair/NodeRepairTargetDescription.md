<Type Name="NodeRepairTargetDescription" FullName="System.Fabric.Repair.NodeRepairTargetDescription">
  <TypeSignature Language="C#" Value="public sealed class NodeRepairTargetDescription : System.Fabric.Repair.RepairTargetDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeRepairTargetDescription extends System.Fabric.Repair.RepairTargetDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.NodeRepairTargetDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeRepairTargetDescription&#xA;Inherits RepairTargetDescription" />
  <TypeSignature Language="F#" Value="type NodeRepairTargetDescription = class&#xA;    inherit RepairTargetDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Repair.RepairTargetDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="0f96c-101">Beschreibt die Liste der Knoten, die das Ziel einer Aktion zum Reparieren.</span><span class="sxs-lookup"><span data-stu-id="0f96c-101">Describes the list of nodes targeted by a repair action.</span></span></para>
      <para><span data-ttu-id="0f96c-102">Diese Klasse unterstützt die Service Fabric-Plattform. Es ist nicht vorgesehen, direkt aus Ihrem Code aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0f96c-102">This class supports the Service Fabric platform; it is not meant to be called directly from your code.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeRepairTargetDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeRepairTargetDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="0f96c-103">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.Repair.NodeRepairTargetDescription" /> -Klasse mit einer leeren Liste der Knotennamen.</span><span class="sxs-lookup"><span data-stu-id="0f96c-103">Initializes a new instance of the <see cref="T:System.Fabric.Repair.NodeRepairTargetDescription" /> class with an empty list of node names.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeRepairTargetDescription (System.Collections.Generic.IEnumerable&lt;string&gt; nodeNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; nodeNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeRepairTargetDescription.#ctor(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nodeNames As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new System.Fabric.Repair.NodeRepairTargetDescription : seq&lt;string&gt; -&gt; System.Fabric.Repair.NodeRepairTargetDescription" Usage="new System.Fabric.Repair.NodeRepairTargetDescription nodeNames" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeNames" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeNames">
          <para><span data-ttu-id="0f96c-104">Die Auflistung, deren Elemente in die neue Liste kopiert werden.</span><span class="sxs-lookup"><span data-stu-id="0f96c-104">The collection whose elements are copied to the new list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0f96c-105">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Repair.NodeRepairTargetDescription" />-Klasse, die aus der angegebenen Auflistung kopierte Elemente enthält.</span><span class="sxs-lookup"><span data-stu-id="0f96c-105">Initializes a new instance of the <see cref="T:System.Fabric.Repair.NodeRepairTargetDescription" /> class that contains elements copied from the specified collection.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeRepairTargetDescription (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeRepairTargetDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nodeName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Repair.NodeRepairTargetDescription : string -&gt; System.Fabric.Repair.NodeRepairTargetDescription" Usage="new System.Fabric.Repair.NodeRepairTargetDescription nodeName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="0f96c-106">Der Name des Knotens zur Liste hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="0f96c-106">The name of the node to be added to the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0f96c-107">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.Repair.NodeRepairTargetDescription" /> Klasse, die der Name des angegebenen Knotens als das einzige Element in der Knotenliste enthält.</span><span class="sxs-lookup"><span data-stu-id="0f96c-107">Initializes a new instance of the <see cref="T:System.Fabric.Repair.NodeRepairTargetDescription" /> class that contains the given node name as the only element in its node list.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Nodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Nodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Nodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.NodeRepairTargetDescription.Nodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Nodes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Nodes : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.Repair.NodeRepairTargetDescription.Nodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0f96c-108">Ruft die Liste der Knotennamen ab.</span><span class="sxs-lookup"><span data-stu-id="0f96c-108">Gets the list of node names.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0f96c-109">Eine Liste von Knoten verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="0f96c-109">A list of node names.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeRepairTargetDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeRepairTargetDescription.ToString " />
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
          <para><span data-ttu-id="0f96c-110">Konvertiert den Wert des aktuellen Objekts in eine Zeichenfolgendarstellung.</span><span class="sxs-lookup"><span data-stu-id="0f96c-110">Converts the value of the current object to a string representation.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0f96c-111">Eine Zeichenfolgendarstellung des Werts der <see cref="P:System.Fabric.Repair.NodeRepairTargetDescription.Nodes" />.</span><span class="sxs-lookup"><span data-stu-id="0f96c-111">A string representation of the value of <see cref="P:System.Fabric.Repair.NodeRepairTargetDescription.Nodes" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>