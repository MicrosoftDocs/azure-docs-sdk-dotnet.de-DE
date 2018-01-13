<Type Name="NodeStopDescription" FullName="System.Fabric.Description.NodeStopDescription">
  <TypeSignature Language="C#" Value="public sealed class NodeStopDescription : System.Fabric.Description.NodeTransitionDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeStopDescription extends System.Fabric.Description.NodeTransitionDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.NodeStopDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeStopDescription&#xA;Inherits NodeTransitionDescription" />
  <TypeSignature Language="F#" Value="type NodeStopDescription = class&#xA;    inherit NodeTransitionDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.NodeTransitionDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Beschreibt Informationen dazu, wie ein Knoten sollten mit StartNodeTransitionAsync() beendet.  
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeStopDescription (Guid operationId, string nodeName, System.Numerics.BigInteger nodeInstanceId, int stopDurationInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid operationId, string nodeName, valuetype System.Numerics.BigInteger nodeInstanceId, int32 stopDurationInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.NodeStopDescription.#ctor(System.Guid,System.String,System.Numerics.BigInteger,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (operationId As Guid, nodeName As String, nodeInstanceId As BigInteger, stopDurationInSeconds As Integer)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.NodeStopDescription : Guid * string * System.Numerics.BigInteger * int -&gt; System.Fabric.Description.NodeStopDescription" Usage="new System.Fabric.Description.NodeStopDescription (operationId, nodeName, nodeInstanceId, stopDurationInSeconds)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstanceId" Type="System.Numerics.BigInteger" />
        <Parameter Name="stopDurationInSeconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="operationId">Eine Guid, um diesen Vorgang zu identifizieren.  Dies sollte eindeutig sein und sollte nicht mit anderen Vorgängen verwendet werden.</param>
        <param name="nodeName">Der Name des Knotens zum Starten oder beenden.  Der Name kann über GetNodeListAsync() ermittelt werden.</param>
        <param name="nodeInstanceId">Die Knoten-Id des Zielknotens.  Dies kann durch GetNodeListAsync() ermittelt werden.</param>
        <param name="stopDurationInSeconds">Die Dauer den Knoten erhalten bleiben beendet.  Nach Ablauf dieser Zeit wird der Knoten automatisch wieder da sind.  Die Einheiten wird in Sekunden angegeben.  Der Mindestwert beträgt 600, der Höchstwert beträgt 14400.</param>
        <summary>
            Erstellt eine NodeTransitionDescription, die Informationen zu einem Knoten beenden beschreibt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopDurationInSeconds">
      <MemberSignature Language="C#" Value="public int StopDurationInSeconds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StopDurationInSeconds" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.NodeStopDescription.StopDurationInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StopDurationInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.StopDurationInSeconds : int" Usage="System.Fabric.Description.NodeStopDescription.StopDurationInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Dauer den Knoten erhalten bleiben beendet.  Nach Ablauf dieser Zeit wird der Knoten automatisch wieder da sind.  Die Einheiten wird in Sekunden angegeben.  Der Mindestwert beträgt 600, der Höchstwert beträgt 14400.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.NodeStopDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeStopDescription.ToString " />
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
            Gibt eine Zeichenfolgendarstellung des Objekts an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>