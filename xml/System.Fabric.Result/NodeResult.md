<Type Name="NodeResult" FullName="System.Fabric.Result.NodeResult">
  <TypeSignature Language="C#" Value="public class NodeResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit NodeResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.NodeResult" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeResult" />
  <TypeSignature Language="F#" Value="type NodeResult = class" />
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
            <span data-ttu-id="c6975-101">Gibt Knoten-Ergebnisobjekt.</span><span class="sxs-lookup"><span data-stu-id="c6975-101">Returns Node result object.</span></span> 
            </summary>
    <remarks>
            <span data-ttu-id="c6975-102">Diese Klasse gibt die "nodename" und NodeInstanceId zurück.</span><span class="sxs-lookup"><span data-stu-id="c6975-102">This class returns nodeName and nodeInstanceId.</span></span> <span data-ttu-id="c6975-103">Diese Klasse ist Teil von RestartNode StartNode, stopnode-Aufruf steht Aktionen Struktur ergeben.</span><span class="sxs-lookup"><span data-stu-id="c6975-103">This class is part of RestartNode, StartNode, StopNode actions result structure.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeInstance">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger NodeInstance { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger NodeInstance" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.NodeResult.NodeInstance" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeInstance As BigInteger" />
      <MemberSignature Language="F#" Value="member this.NodeInstance : System.Numerics.BigInteger" Usage="System.Fabric.Result.NodeResult.NodeInstance" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Numerics.BigInteger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6975-104">Ruft die Instanz-Id von Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="c6975-104">Gets node instance id.</span></span>
            </summary>
        <value><span data-ttu-id="c6975-105">Die Instanz-Id von Knoten.</span><span class="sxs-lookup"><span data-stu-id="c6975-105">The node instance id.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.NodeResult.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Result.NodeResult.NodeName" />
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
            <span data-ttu-id="c6975-106">Ruft Name des Knotens ab.</span><span class="sxs-lookup"><span data-stu-id="c6975-106">Gets node name.</span></span>
            </summary>
        <value><span data-ttu-id="c6975-107">Der Knotenname.</span><span class="sxs-lookup"><span data-stu-id="c6975-107">The node name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.NodeResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeResult.ToString " />
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
            <span data-ttu-id="c6975-108">Gibt eine Zeichenfolge wie zurück: "" nodename ":" string "," NodeInstance: BigInteger "</span><span class="sxs-lookup"><span data-stu-id="c6975-108">Returns a string like: "NodeName: string, NodeInstance: BigInteger"</span></span>
            </summary>
        <returns><span data-ttu-id="c6975-109">Eine Zeichenfolge</span><span class="sxs-lookup"><span data-stu-id="c6975-109">A string</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>