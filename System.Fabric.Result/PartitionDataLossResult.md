<Type Name="PartitionDataLossResult" FullName="System.Fabric.Result.PartitionDataLossResult">
  <TypeSignature Language="C#" Value="public sealed class PartitionDataLossResult : System.Fabric.Result.TestCommandResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit PartitionDataLossResult extends System.Fabric.Result.TestCommandResult" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.PartitionDataLossResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionDataLossResult&#xA;Inherits TestCommandResult" />
  <TypeSignature Language="F#" Value="type PartitionDataLossResult = class&#xA;    inherit TestCommandResult" />
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
            Gibt Invoke Data Loss-Ergebnisobjekt.
            </summary>
    <remarks>
            Diese Klasse gibt die SelectedPartition-Informationen für die Daten verloren gehen Aktion aufrufen, aufgerufen wurde.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="SelectedPartition">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedPartition SelectedPartition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedPartition SelectedPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.PartitionDataLossResult.SelectedPartition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedPartition As SelectedPartition" />
      <MemberSignature Language="F#" Value="member this.SelectedPartition : System.Fabric.SelectedPartition" Usage="System.Fabric.Result.PartitionDataLossResult.SelectedPartition" />
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
            Ruft die ausgewählte Partition ab.
            </summary>
        <value>Das SelectedPartition-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.PartitionDataLossResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionDataLossResult.ToString " />
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