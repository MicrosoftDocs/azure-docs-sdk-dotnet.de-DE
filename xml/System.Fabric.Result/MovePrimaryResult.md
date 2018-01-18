<Type Name="MovePrimaryResult" FullName="System.Fabric.Result.MovePrimaryResult">
  <TypeSignature Language="C#" Value="public class MovePrimaryResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MovePrimaryResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.MovePrimaryResult" />
  <TypeSignature Language="VB.NET" Value="Public Class MovePrimaryResult" />
  <TypeSignature Language="F#" Value="type MovePrimaryResult = class" />
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
            <span data-ttu-id="34b89-101">Stellt eine Verschiebung primäres Replikat-Ergebnisobjekt dar.</span><span class="sxs-lookup"><span data-stu-id="34b89-101">Represents a move primary replica result object.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="34b89-102">Diese Klasse gibt zurück, der "nodename" und SelectedPartition-Informationen, die für die Verschiebung primäres Replikat Aktion aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="34b89-102">This class returns the nodeName and SelectedPartition information for which move primary replica action was called.</span></span> 
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.MovePrimaryResult.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Result.MovePrimaryResult.NodeName" />
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
            <span data-ttu-id="34b89-103">Ruft Name des Knotens ab.</span><span class="sxs-lookup"><span data-stu-id="34b89-103">Gets node name.</span></span>
            </summary>
        <value><span data-ttu-id="34b89-104">Der Knotenname.</span><span class="sxs-lookup"><span data-stu-id="34b89-104">The node name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectedPartition">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedPartition SelectedPartition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedPartition SelectedPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.MovePrimaryResult.SelectedPartition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedPartition As SelectedPartition" />
      <MemberSignature Language="F#" Value="member this.SelectedPartition : System.Fabric.SelectedPartition" Usage="System.Fabric.Result.MovePrimaryResult.SelectedPartition" />
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
            <span data-ttu-id="34b89-105">Ruft die ausgewählte Partition ab.</span><span class="sxs-lookup"><span data-stu-id="34b89-105">Gets the selected partition.</span></span>
            </summary>
        <value><span data-ttu-id="34b89-106">Das SelectedPartition-Objekt.</span><span class="sxs-lookup"><span data-stu-id="34b89-106">The SelectedPartition object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.MovePrimaryResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="movePrimaryResult.ToString " />
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
            <span data-ttu-id="34b89-107">Die "nodename" Formate und SelectedPartition in eine Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="34b89-107">Formats NodeName and SelectedPartition into a string.</span></span>
            </summary>
        <returns><span data-ttu-id="34b89-108">Die formatierte Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="34b89-108">The formatted string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>