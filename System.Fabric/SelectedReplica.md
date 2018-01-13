<Type Name="SelectedReplica" FullName="System.Fabric.SelectedReplica">
  <TypeSignature Language="C#" Value="public class SelectedReplica : IEquatable&lt;System.Fabric.SelectedReplica&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SelectedReplica extends System.Object implements class System.IEquatable`1&lt;class System.Fabric.SelectedReplica&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.SelectedReplica" />
  <TypeSignature Language="VB.NET" Value="Public Class SelectedReplica&#xA;Implements IEquatable(Of SelectedReplica)" />
  <TypeSignature Language="F#" Value="type SelectedReplica = class&#xA;    interface IEquatable&lt;SelectedReplica&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;System.Fabric.SelectedReplica&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Gibt ausgewählt Replikatobjekt ReplicaSelector Prüfbarkeit API verwenden.
            </summary>
    <remarks> 
            Diese Klasse gibt Informationen über das ausgewählte Replikat mit der Replikat-Selektor Prüfbarkeit API ausgewählt. Wenn die ReplicaSelector generiert wurde, mithilfe der Überladung RandomOf wird diese Klasse mit dem ReplicaOrInstance-ID und PartitionSelector für das ausgewählte Replikat aufgefüllt
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (System.Fabric.SelectedReplica other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class System.Fabric.SelectedReplica other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.SelectedReplica.Equals(System.Fabric.SelectedReplica)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As SelectedReplica) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : System.Fabric.SelectedReplica -&gt; bool" Usage="selectedReplica.Equals other" />
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
        <Parameter Name="other" Type="System.Fabric.SelectedReplica" />
      </Parameters>
      <Docs>
        <param name="other">Eine ausgewählte Replikat, das dem aktuellen SelectedReplica ist, verglichen werden soll.</param>
        <summary>
            Vergleicht diese SelectedReplica mit anderen SelectedReplica an.
            </summary>
        <returns>True, wenn ReplicaOrInstanceId und SelectedPartition, der zwei SelectedReplica Objekte entsprechen. Andernfalls wird "false" zurückgegeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="public static readonly System.Fabric.SelectedReplica None;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class System.Fabric.SelectedReplica None" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SelectedReplica.None" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly None As SelectedReplica " />
      <MemberSignature Language="F#" Value=" staticval mutable None : System.Fabric.SelectedReplica" Usage="System.Fabric.SelectedReplica.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SelectedReplica</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt keine Replikat-Selektor. 
            </summary>
        <remarks>
            Eine SelectedReplica werden keine für eine beliebige Prüfbarkeit API mit Überladungen der keine Instanz-Id und Partition replikatselektor als Eingabe akzeptiert. Wenn RestartNodeAsync aufgerufen wird, beispielsweise mit der "nodename" Überladung anstelle von ReplicaSelector. Zurückgegeben von ReplicaSelector keine in diesem Fall kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaOrInstanceId">
      <MemberSignature Language="C#" Value="public long ReplicaOrInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaOrInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.SelectedReplica.ReplicaOrInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaOrInstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaOrInstanceId : int64" Usage="System.Fabric.SelectedReplica.ReplicaOrInstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Replikat oder die Instanz-ID ab
            </summary>
        <value>
          <para>Gibt das Replikat oder eine Instanz-ID für diese SelectedReplica</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectedPartition">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedPartition SelectedPartition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedPartition SelectedPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.SelectedReplica.SelectedPartition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedPartition As SelectedPartition" />
      <MemberSignature Language="F#" Value="member this.SelectedPartition : System.Fabric.SelectedPartition" Usage="System.Fabric.SelectedReplica.SelectedPartition" />
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
            Ruft ausgewählte partition 
            </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.SelectedReplica" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.SelectedReplica.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="selectedReplica.ToString " />
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
            Gibt eine Zeichenfolgendarstellung des Objekts SelectedReplica zurück
            </summary>
        <returns>Eine Zeichenfolge mit dem Format: ReplicaOrInstanceId = &lt;ReplicaOrInstanceId&gt;, SelectedPartition = &lt;SelectedPartition&gt;</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>