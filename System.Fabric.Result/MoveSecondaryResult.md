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
            Stellt verschieben sekundäres Replikat-Ergebnisobjekt.
            </summary>
    <remarks>
            Diese Klasse gibt CurrentSecondaryNodeName, zurück, auf dem sekundären Replikat vorhanden war vor dem verschieben, NewSecondaryNodeName, in dem die SelectedReplica verschoben wird, und SelectedPartition Informationen, die das ausgewählte sekundäre Replikat darstellt.
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
            Ruft die aktuellen der Knotenname für das sekundäre Zielreplikat ab.
            </summary>
        <value>Der Knotenname für das sekundäre Zielreplikat.</value>
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
            Ruft ab, der Name des Knotens, auf dem sekundären Replikat verschoben wird.
            </summary>
        <value>Der Name des Knotens, in denen das sekundäre Zielreplikat verschoben wird.</value>
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
            Ruft die ausgewählte Partition ab.
            </summary>
        <value>Das SelectedPartition-Objekt.</value>
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
            Formate CurrentSecondaryNodeName, NewSecondaryNodeName und SelectedPartition in eine Zeichenfolge.
            </summary>
        <returns>Die formatierte Zeichenfolge.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>