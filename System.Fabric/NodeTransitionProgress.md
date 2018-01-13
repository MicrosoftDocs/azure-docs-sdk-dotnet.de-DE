<Type Name="NodeTransitionProgress" FullName="System.Fabric.NodeTransitionProgress">
  <TypeSignature Language="C#" Value="public sealed class NodeTransitionProgress : System.Fabric.TestCommandProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeTransitionProgress extends System.Fabric.TestCommandProgress" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NodeTransitionProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeTransitionProgress&#xA;Inherits TestCommandProgress" />
  <TypeSignature Language="F#" Value="type NodeTransitionProgress = class&#xA;    inherit TestCommandProgress" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.TestCommandProgress</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Gibt ein NodeTransitionProgress-Objekt.
            </summary>
    <remarks>
            Diese Klasse gibt die TestCommandProgressState, Ergebnis (im abgeschlossen oder Faulted-Zustand), und der angegebenen Ausnahme (im Zustand "Faulted") Informationen für den Knoten-Übergang-Befehl.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public System.Fabric.Result.NodeCommandResult Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Result.NodeCommandResult Result" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeTransitionProgress.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As NodeCommandResult" />
      <MemberSignature Language="F#" Value="member this.Result : System.Fabric.Result.NodeCommandResult" Usage="System.Fabric.NodeTransitionProgress.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Result.NodeCommandResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Ergebnis des Befehls Übergang Knoten ab.
            Dies ist verfügbar, nur, wenn die Aktion im Zustand "abgeschlossen" oder "Faulted" befindet.
            </summary>
        <value>Das NodeCommandResult-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeTransitionProgress.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeTransitionProgress.ToString " />
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
            Gibt eine Zeichenfolgendarstellung der darin enthaltenen Informationen zurück
            </summary>
        <returns>Eine Zeichenfolge, die Status, InvokeDataLossResult und Ausnahmeinformationen hat.
            Status ist immer Presnt; jedoch je nach Status das Ergebnis und die Ausnahme möglicherweise nicht vorhanden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>