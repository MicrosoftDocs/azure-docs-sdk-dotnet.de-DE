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
            <span data-ttu-id="7ff9e-101">Gibt ein NodeTransitionProgress-Objekt.</span><span class="sxs-lookup"><span data-stu-id="7ff9e-101">Returns NodeTransitionProgress object.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="7ff9e-102">Diese Klasse gibt die TestCommandProgressState, Ergebnis (im abgeschlossen oder Faulted-Zustand), und der angegebenen Ausnahme (im Zustand "Faulted") Informationen für den Knoten-Übergang-Befehl.</span><span class="sxs-lookup"><span data-stu-id="7ff9e-102">This class returns the TestCommandProgressState, Result (when in Completed or Faulted state), and Exception (when in Faulted state) information for the node transition command.</span></span>
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
            <span data-ttu-id="7ff9e-103">Ruft das Ergebnis des Befehls Übergang Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="7ff9e-103">Gets the result of the node transition command.</span></span>
            <span data-ttu-id="7ff9e-104">Dies ist verfügbar, nur, wenn die Aktion im Zustand "abgeschlossen" oder "Faulted" befindet.</span><span class="sxs-lookup"><span data-stu-id="7ff9e-104">This is avaliable only when the action is in Completed or Faulted state.</span></span>
            </summary>
        <value><span data-ttu-id="7ff9e-105">Das NodeCommandResult-Objekt.</span><span class="sxs-lookup"><span data-stu-id="7ff9e-105">The NodeCommandResult object.</span></span></value>
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
            <span data-ttu-id="7ff9e-106">Gibt eine Zeichenfolgendarstellung der darin enthaltenen Informationen zurück</span><span class="sxs-lookup"><span data-stu-id="7ff9e-106">Returns a string representation of the contained information</span></span>
            </summary>
        <returns><span data-ttu-id="7ff9e-107">Eine Zeichenfolge, die Status, InvokeDataLossResult und Ausnahmeinformationen hat.</span><span class="sxs-lookup"><span data-stu-id="7ff9e-107">A string that has State, InvokeDataLossResult, and Exception information.</span></span>
            <span data-ttu-id="7ff9e-108">Status ist immer Presnt; jedoch je nach Status das Ergebnis und die Ausnahme möglicherweise nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7ff9e-108">State is always presnt; but depending on State, the Result and the Exception may not be present.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>