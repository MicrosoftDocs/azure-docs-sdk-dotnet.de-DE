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
            Gibt Invoke Datenobjekt Verlust Status zurück.
            </summary>
    <remarks>
            Diese Klasse gibt die TestCommandProgressState, Ergebnis (im abgeschlossen oder Faulted-Zustand), und der angegebenen Ausnahme (im Zustand "Faulted") Informationen zur Aktion Invoke Daten verloren gehen.
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
            Ruft das Ergebnis der Aktion Invoke Daten verloren gehen. Dies ist verfügbar, nur, wenn die Aktion im Zustand "abgeschlossen" oder "Faulted" befindet.
            </summary>
        <value>Das PartitionDataLossResult-Objekt.</value>
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
            Gibt eine Zeichenfolgendarstellung der darin enthaltenen Informationen zurück
            </summary>
        <returns>Eine Zeichenfolge, die Status, InvokeDataLossResult und Ausnahmeinformationen hat.
            Status ist immer Presnt; jedoch je nach Status das Ergebnis und die Ausnahme möglicherweise nicht vorhanden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>