<Type Name="SelectedPartition" FullName="System.Fabric.SelectedPartition">
  <TypeSignature Language="C#" Value="public class SelectedPartition : IEquatable&lt;System.Fabric.SelectedPartition&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SelectedPartition extends System.Object implements class System.IEquatable`1&lt;class System.Fabric.SelectedPartition&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.SelectedPartition" />
  <TypeSignature Language="VB.NET" Value="Public Class SelectedPartition&#xA;Implements IEquatable(Of SelectedPartition)" />
  <TypeSignature Language="F#" Value="type SelectedPartition = class&#xA;    interface IEquatable&lt;SelectedPartition&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;System.Fabric.SelectedPartition&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Gibt die ausgewählte Partition ist PartitionSelector FaultManagementClient-APIs verwenden. 
            </summary>
    <remarks> 
            Diese Klasse gibt Informationen über die Partition, die mithilfe von PartitionSelector Prüfbarkeit API ausgewählt wurde.
            Z. B. wenn die PartitionSelector erstellt wurde, mithilfe der RandomOf-Überladung, die diese Klasse Service und Partitions-Id des aufgefüllt wird die für die ausgewählte Partition
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (System.Fabric.SelectedPartition other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class System.Fabric.SelectedPartition other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.SelectedPartition.Equals(System.Fabric.SelectedPartition)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As SelectedPartition) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : System.Fabric.SelectedPartition -&gt; bool" Usage="selectedPartition.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.SelectedPartition" />
      </Parameters>
      <Docs>
        <param name="other">Eine ausgewählte Partition, die dem aktuellen SelectedPartition ist, verglichen werden soll.</param>
        <summary>
            Vergleicht diese SelectedPartition mit anderen SelectedPartition an.
            </summary>
        <returns>True, wenn beide und Partitions-ID der beiden service entsprechen SelectedPartition Objekte. Andernfalls wird "false" zurückgegeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="public static readonly System.Fabric.SelectedPartition None;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class System.Fabric.SelectedPartition None" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SelectedPartition.None" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly None As SelectedPartition " />
      <MemberSignature Language="F#" Value=" staticval mutable None : System.Fabric.SelectedPartition" Usage="System.Fabric.SelectedPartition.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SelectedPartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt zurück, dass keine Auswahl partitionieren.
            </summary>
        <remarks>
            Eine SelectedPartition sind für alle Prüfbarkeit API mit Überladungen, die keine Partition oder Replikat Auswahl als Eingabe akzeptiert. Beispiel, wenn RestartNodeAsync mit der "nodename" Überladung anstelle von ReplicaSelector aufgerufen wird, wird PartitionSelector zurückgegeben werden keine
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.SelectedPartition.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.SelectedPartition.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Partitions-ID als GUID ab
            </summary>
        <value>
            EINE GUID
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.SelectedPartition.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.SelectedPartition.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Dienstnamen als URI ab.
            </summary>
        <value>
            EIN URI
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.SelectedPartition.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="selectedPartition.ToString " />
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
            Ruft eine Zeichenfolgendarstellung des Objekts SelectedPartition
            </summary>
        <returns>Eine Zeichenfolge mit dem Format: Dienstname: &lt;Dienstname&gt;, Partitions-Id: &lt;Partitions-Id&gt;</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>