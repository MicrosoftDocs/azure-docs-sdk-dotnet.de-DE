<Type Name="MoveSecondaryResult" FullName="System.Fabric.Result.MoveSecondaryResult">
  <TypeSignature Language="C#" Value="public class MoveSecondaryResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MoveSecondaryResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.MoveSecondaryResult" />
  <TypeSignature Language="VB.NET" Value="Public Class MoveSecondaryResult" />
  <TypeSignature Language="F#" Value="type MoveSecondaryResult = class" />
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
            <span data-ttu-id="82997-101">Stellt verschieben sekundäres Replikat-Ergebnisobjekt.</span><span class="sxs-lookup"><span data-stu-id="82997-101">Represents move secondary replica result object.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="82997-102">Diese Klasse gibt CurrentSecondaryNodeName, zurück, auf dem sekundären Replikat vorhanden war vor dem verschieben, NewSecondaryNodeName, in dem die SelectedReplica verschoben wird, und SelectedPartition Informationen, die das ausgewählte sekundäre Replikat darstellt.</span><span class="sxs-lookup"><span data-stu-id="82997-102">This class returns currentSecondaryNodeName, where secondary replica was present before movement, newSecondaryNodeName where the SelectedReplica is moved and SelectedPartition information that represents the selected secondary replica.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="CurrentSecondaryNodeName">
      <MemberSignature Language="C#" Value="public string CurrentSecondaryNodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentSecondaryNodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.MoveSecondaryResult.CurrentSecondaryNodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentSecondaryNodeName As String" />
      <MemberSignature Language="F#" Value="member this.CurrentSecondaryNodeName : string" Usage="System.Fabric.Result.MoveSecondaryResult.CurrentSecondaryNodeName" />
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
            <span data-ttu-id="82997-103">Ruft die aktuellen der Knotenname für das sekundäre Zielreplikat ab.</span><span class="sxs-lookup"><span data-stu-id="82997-103">Gets current node name for the target secondary replica.</span></span>
            </summary>
        <value><span data-ttu-id="82997-104">Der Knotenname für das sekundäre Zielreplikat.</span><span class="sxs-lookup"><span data-stu-id="82997-104">The node name for the target secondary replica.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NewSecondaryNodeName">
      <MemberSignature Language="C#" Value="public string NewSecondaryNodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NewSecondaryNodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.MoveSecondaryResult.NewSecondaryNodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NewSecondaryNodeName As String" />
      <MemberSignature Language="F#" Value="member this.NewSecondaryNodeName : string" Usage="System.Fabric.Result.MoveSecondaryResult.NewSecondaryNodeName" />
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
            <span data-ttu-id="82997-105">Ruft ab, der Name des Knotens, auf dem sekundären Replikat verschoben wird.</span><span class="sxs-lookup"><span data-stu-id="82997-105">Gets node name where secondary replica will move to.</span></span>
            </summary>
        <value><span data-ttu-id="82997-106">Der Name des Knotens, in denen das sekundäre Zielreplikat verschoben wird.</span><span class="sxs-lookup"><span data-stu-id="82997-106">The name of the node where the target secondary replica will move to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectedPartition">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedPartition SelectedPartition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedPartition SelectedPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.MoveSecondaryResult.SelectedPartition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedPartition As SelectedPartition" />
      <MemberSignature Language="F#" Value="member this.SelectedPartition : System.Fabric.SelectedPartition" Usage="System.Fabric.Result.MoveSecondaryResult.SelectedPartition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SelectedPartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82997-107">Ruft die ausgewählte Partition ab.</span><span class="sxs-lookup"><span data-stu-id="82997-107">Gets the selected partition.</span></span>
            </summary>
        <value><span data-ttu-id="82997-108">Das SelectedPartition-Objekt.</span><span class="sxs-lookup"><span data-stu-id="82997-108">The SelectedPartition object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.MoveSecondaryResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="moveSecondaryResult.ToString " />
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
            <span data-ttu-id="82997-109">Formate CurrentSecondaryNodeName, NewSecondaryNodeName und SelectedPartition in eine Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="82997-109">Formats CurrentSecondaryNodeName, NewSecondaryNodeName, and SelectedPartition into a string.</span></span>
            </summary>
        <returns><span data-ttu-id="82997-110">Die formatierte Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="82997-110">The formatted string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>