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
            Gibt Invoke Quorum Verlust-Ergebnisobjekt.
            </summary>
    <remarks>
            Diese Klasse gibt SelectedPartition Informationen für das Aufrufen Quorumsverlust Aktion aufgerufen wurde. 
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
            Ruft die Selecetd Partition ab.
            </summary>
        <value>Das SelectedPartition-Objekt.</value>
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
            Gibt die Zeichenfolgendarstellung der darin enthaltenen Informationen zurück.
            </summary>
        <returns>Eine Zeichenfolge, enthält Informationen zu den SelectedPartition und (bedingt) über die Ausnahme </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>