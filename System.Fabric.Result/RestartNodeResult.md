<Type Name="RestartNodeResult" FullName="System.Fabric.Result.RestartNodeResult">
  <TypeSignature Language="C#" Value="public class RestartNodeResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RestartNodeResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.RestartNodeResult" />
  <TypeSignature Language="VB.NET" Value="Public Class RestartNodeResult" />
  <TypeSignature Language="F#" Value="type RestartNodeResult = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5cdff-101">Gibt Neustart Knoten-Ergebnisobjekt.</span><span class="sxs-lookup"><span data-stu-id="5cdff-101">Returns Restart node result object.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="5cdff-102">Diese Klasse gibt die SelectedReplica und NodeResult für RestartNode-Aktion zurück.</span><span class="sxs-lookup"><span data-stu-id="5cdff-102">This class returns the SelectedReplica and NodeResult for RestartNode Action.</span></span>  
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeResult">
      <MemberSignature Language="C#" Value="public System.Fabric.Result.NodeResult NodeResult { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Result.NodeResult NodeResult" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartNodeResult.NodeResult" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeResult As NodeResult" />
      <MemberSignature Language="F#" Value="member this.NodeResult : System.Fabric.Result.NodeResult" Usage="System.Fabric.Result.RestartNodeResult.NodeResult" />
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
        <ReturnType>System.Fabric.Result.NodeResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5cdff-103">Ruft die NodeResult ab.</span><span class="sxs-lookup"><span data-stu-id="5cdff-103">Gets the NodeResult.</span></span>
            </summary>
        <value><span data-ttu-id="5cdff-104">Das NodeResult-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5cdff-104">The NodeResult object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectedReplica">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedReplica SelectedReplica { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedReplica SelectedReplica" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartNodeResult.SelectedReplica" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedReplica As SelectedReplica" />
      <MemberSignature Language="F#" Value="member this.SelectedReplica : System.Fabric.SelectedReplica" Usage="System.Fabric.Result.RestartNodeResult.SelectedReplica" />
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
        <ReturnType>System.Fabric.SelectedReplica</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5cdff-105">Ruft die SelectedReplica ab.</span><span class="sxs-lookup"><span data-stu-id="5cdff-105">Gets the SelectedReplica.</span></span>
            <span data-ttu-id="5cdff-106">SelectedReplica werden keine für den Fall, dass die Prüfbarkeit RestartNode-Aktion mithilfe der Knotenname ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="5cdff-106">SelectedReplica will be none in case the RestartNode Testability action was performed using node name.</span></span>
            </summary>
        <value><span data-ttu-id="5cdff-107">Das SelectedReplica-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5cdff-107">The SelectedReplica object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.RestartNodeResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="restartNodeResult.ToString " />
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
            <span data-ttu-id="5cdff-108">Formate NodeResult und SelectedReplica in eine Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="5cdff-108">Formats NodeResult and SelectedReplica into a string.</span></span>
            </summary>
        <returns><span data-ttu-id="5cdff-109">Die formatierte Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="5cdff-109">The formatted string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>