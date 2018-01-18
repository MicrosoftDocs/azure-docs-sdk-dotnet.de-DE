<Type Name="PartitionQuorumLossProgress" FullName="System.Fabric.PartitionQuorumLossProgress">
  <TypeSignature Language="C#" Value="public sealed class PartitionQuorumLossProgress : System.Fabric.TestCommandProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionQuorumLossProgress extends System.Fabric.TestCommandProgress" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PartitionQuorumLossProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionQuorumLossProgress&#xA;Inherits TestCommandProgress" />
  <TypeSignature Language="F#" Value="type PartitionQuorumLossProgress = class&#xA;    inherit TestCommandProgress" />
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
            <span data-ttu-id="ca714-101">Gibt Invoke Quorum Verlust Fortschritt Objekt zurück.</span><span class="sxs-lookup"><span data-stu-id="ca714-101">Returns Invoke quorum loss progress object.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="ca714-102">Diese Klasse gibt die TestCommandProgressState, Ergebnis (im abgeschlossen oder Faulted-Zustand), und der angegebenen Ausnahme (im Zustand "Faulted") Informationen zur Aktion Invoke Quorum verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="ca714-102">This class returns the TestCommandProgressState, Result (when in Completed or Faulted state), and Exception (when in Faulted state) information for the invoke quorum loss action.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public System.Fabric.Result.PartitionQuorumLossResult Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Result.PartitionQuorumLossResult Result" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PartitionQuorumLossProgress.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As PartitionQuorumLossResult" />
      <MemberSignature Language="F#" Value="member this.Result : System.Fabric.Result.PartitionQuorumLossResult" Usage="System.Fabric.PartitionQuorumLossProgress.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Result.PartitionQuorumLossResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca714-103">Ruft das Ergebnis der Aktion Invoke Quorum verloren gehen. Dies ist verfügbar, nur, wenn die Aktion im Zustand "abgeschlossen" oder "Faulted" befindet.</span><span class="sxs-lookup"><span data-stu-id="ca714-103">Gets the result of the invoke quorum loss action; this is avaliable only when the action is in Completed or Faulted state.</span></span>
            </summary>
        <value><span data-ttu-id="ca714-104">Das PartitionQuorumLossResult-Objekt.</span><span class="sxs-lookup"><span data-stu-id="ca714-104">The PartitionQuorumLossResult object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionQuorumLossProgress.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionQuorumLossProgress.ToString " />
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
            <span data-ttu-id="ca714-105">Gibt eine Zeichenfolgendarstellung der darin enthaltenen Informationen zurück</span><span class="sxs-lookup"><span data-stu-id="ca714-105">Returns a string representation of the contained information</span></span>
            </summary>
        <returns><span data-ttu-id="ca714-106">Eine Zeichenfolge, die Status, InvokeQuorumLossResult und Ausnahmeinformationen hat.</span><span class="sxs-lookup"><span data-stu-id="ca714-106">A string that has State, InvokeQuorumLossResult, and Exception information.</span></span>
            <span data-ttu-id="ca714-107">Status ist immer Presnt; jedoch je nach Status das Ergebnis und die Ausnahme möglicherweise nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="ca714-107">State is always presnt; but depending on State, the Result and the Exception may not be present.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>