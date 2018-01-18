<Type Name="PartitionQuorumLossResult" FullName="System.Fabric.Result.PartitionQuorumLossResult">
  <TypeSignature Language="C#" Value="public class PartitionQuorumLossResult : System.Fabric.Result.TestCommandResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit PartitionQuorumLossResult extends System.Fabric.Result.TestCommandResult" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.PartitionQuorumLossResult" />
  <TypeSignature Language="VB.NET" Value="Public Class PartitionQuorumLossResult&#xA;Inherits TestCommandResult" />
  <TypeSignature Language="F#" Value="type PartitionQuorumLossResult = class&#xA;    inherit TestCommandResult" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Result.TestCommandResult</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="01dcc-101">Gibt Invoke Quorum Verlust-Ergebnisobjekt.</span><span class="sxs-lookup"><span data-stu-id="01dcc-101">Returns Invoke quorum loss result object.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="01dcc-102">Diese Klasse gibt SelectedPartition Informationen für das Aufrufen Quorumsverlust Aktion aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="01dcc-102">This class returns SelectedPartition information for which Invoke Quorum Loss action was called.</span></span> 
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="SelectedPartition">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedPartition SelectedPartition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedPartition SelectedPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.PartitionQuorumLossResult.SelectedPartition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedPartition As SelectedPartition" />
      <MemberSignature Language="F#" Value="member this.SelectedPartition : System.Fabric.SelectedPartition" Usage="System.Fabric.Result.PartitionQuorumLossResult.SelectedPartition" />
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
            <span data-ttu-id="01dcc-103">Ruft die Selecetd Partition ab.</span><span class="sxs-lookup"><span data-stu-id="01dcc-103">Gets selecetd partition.</span></span>
            </summary>
        <value><span data-ttu-id="01dcc-104">Das SelectedPartition-Objekt.</span><span class="sxs-lookup"><span data-stu-id="01dcc-104">The SelectedPartition object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.PartitionQuorumLossResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionQuorumLossResult.ToString " />
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
            <span data-ttu-id="01dcc-105">Gibt die Zeichenfolgendarstellung der darin enthaltenen Informationen zurück.</span><span class="sxs-lookup"><span data-stu-id="01dcc-105">Returns the string representation of the contained information.</span></span>
            </summary>
        <returns><span data-ttu-id="01dcc-106">Eine Zeichenfolge, enthält Informationen zu den SelectedPartition und (bedingt) über die Ausnahme</span><span class="sxs-lookup"><span data-stu-id="01dcc-106">A string containing information about the SelectedPartition and (conditionally) about the Exception</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>