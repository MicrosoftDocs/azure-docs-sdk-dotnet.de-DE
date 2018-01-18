<Type Name="NodeHealthState" FullName="System.Fabric.Health.NodeHealthState">
  <TypeSignature Language="C#" Value="public sealed class NodeHealthState : System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeHealthState extends System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.NodeHealthState" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeHealthState&#xA;Inherits EntityHealthState" />
  <TypeSignature Language="F#" Value="type NodeHealthState = class&#xA;    inherit EntityHealthState" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealthState</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="aa073-101">Stellt den Integritätsstatus eines Knotens, der die Knoten-ID und der aggregierte Integritätszustand enthält.</span><span class="sxs-lookup"><span data-stu-id="aa073-101">Represents the health state of a node, which contains the node identifier and its aggregated health state.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodeHealthState.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.NodeHealthState.NodeName" />
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
          <para><span data-ttu-id="aa073-102">Ruft den Namen des Knotens ab.</span><span class="sxs-lookup"><span data-stu-id="aa073-102">Gets the name of the node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="aa073-103">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="aa073-103">The name of the node.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.NodeHealthState.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeHealthState.ToString " />
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
            <span data-ttu-id="aa073-104">Erstellt eine zeichenfolgenbeschreibung der Zustand des Knotens an.</span><span class="sxs-lookup"><span data-stu-id="aa073-104">Creates a string description of the node health state.</span></span>
            </summary>
        <returns><span data-ttu-id="aa073-105">Zeichenfolgenbeschreibung des der <see cref="T:System.Fabric.Health.NodeHealthState" />.</span><span class="sxs-lookup"><span data-stu-id="aa073-105">String description of the <see cref="T:System.Fabric.Health.NodeHealthState" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>