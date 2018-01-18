<Type Name="PartitionDataLossProgress" FullName="System.Fabric.PartitionDataLossProgress">
  <TypeSignature Language="C#" Value="public sealed class PartitionDataLossProgress : System.Fabric.TestCommandProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionDataLossProgress extends System.Fabric.TestCommandProgress" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PartitionDataLossProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionDataLossProgress&#xA;Inherits TestCommandProgress" />
  <TypeSignature Language="F#" Value="type PartitionDataLossProgress = class&#xA;    inherit TestCommandProgress" />
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
            <span data-ttu-id="ec9d7-101">Gibt Invoke Datenobjekt Verlust Status zurück.</span><span class="sxs-lookup"><span data-stu-id="ec9d7-101">Returns Invoke data loss progress object.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="ec9d7-102">Diese Klasse gibt die TestCommandProgressState, Ergebnis (im abgeschlossen oder Faulted-Zustand), und der angegebenen Ausnahme (im Zustand "Faulted") Informationen zur Aktion Invoke Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="ec9d7-102">This class returns the TestCommandProgressState, Result (when in Completed or Faulted state), and Exception (when in Faulted state) information for the invoke data loss action.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public System.Fabric.Result.PartitionDataLossResult Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Result.PartitionDataLossResult Result" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PartitionDataLossProgress.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As PartitionDataLossResult" />
      <MemberSignature Language="F#" Value="member this.Result : System.Fabric.Result.PartitionDataLossResult" Usage="System.Fabric.PartitionDataLossProgress.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Result.PartitionDataLossResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec9d7-103">Ruft das Ergebnis der Aktion Invoke Daten verloren gehen. Dies ist verfügbar, nur, wenn die Aktion im Zustand "abgeschlossen" oder "Faulted" befindet.</span><span class="sxs-lookup"><span data-stu-id="ec9d7-103">Gets the result of the invoke data loss action; this is avaliable only when the action is in Completed or Faulted state.</span></span>
            </summary>
        <value><span data-ttu-id="ec9d7-104">Das PartitionDataLossResult-Objekt.</span><span class="sxs-lookup"><span data-stu-id="ec9d7-104">The PartitionDataLossResult object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionDataLossProgress.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionDataLossProgress.ToString " />
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
            <span data-ttu-id="ec9d7-105">Gibt eine Zeichenfolgendarstellung der darin enthaltenen Informationen zurück</span><span class="sxs-lookup"><span data-stu-id="ec9d7-105">Returns a string representation of the contained information</span></span>
            </summary>
        <returns><span data-ttu-id="ec9d7-106">Eine Zeichenfolge, die Status, InvokeDataLossResult und Ausnahmeinformationen hat.</span><span class="sxs-lookup"><span data-stu-id="ec9d7-106">A string that has State, InvokeDataLossResult, and Exception information.</span></span>
            <span data-ttu-id="ec9d7-107">Status ist immer Presnt; jedoch je nach Status das Ergebnis und die Ausnahme möglicherweise nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="ec9d7-107">State is always presnt; but depending on State, the Result and the Exception may not be present.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>