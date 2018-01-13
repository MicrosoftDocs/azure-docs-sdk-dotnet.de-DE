<Type Name="GatewayInformation" FullName="System.Fabric.GatewayInformation">
  <TypeSignature Language="C#" Value="public sealed class GatewayInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit GatewayInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.GatewayInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class GatewayInformation" />
  <TypeSignature Language="F#" Value="type GatewayInformation = class" />
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
      <para><span data-ttu-id="e02c5-101">Enthält Informationen zur Kennzeichnung von eines Service Fabric-Knotens im Cluster an.</span><span class="sxs-lookup"><span data-stu-id="e02c5-101">Contains information identifying a Service Fabric node in the cluster.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeAddress">
      <MemberSignature Language="C#" Value="public string NodeAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.GatewayInformation.NodeAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeAddress As String" />
      <MemberSignature Language="F#" Value="member this.NodeAddress : string" Usage="System.Fabric.GatewayInformation.NodeAddress" />
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
          <para><span data-ttu-id="e02c5-102">Ruft die Adresse, die Service Fabric-Clients, beim Verbinden mit diesem Knoten (wie in der Cluster-Manifest angegeben verwenden).</span><span class="sxs-lookup"><span data-stu-id="e02c5-102">Gets the address that Service Fabric clients use when connecting to this node (as specified in the Cluster Manifest).</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e02c5-103">Die Adresse, die Service Fabric-Clients, beim Verbinden mit diesem Knoten (wie in der Cluster-Manifest angegeben verwenden).</span><span class="sxs-lookup"><span data-stu-id="e02c5-103">The address that Service Fabric clients use when connecting to this node (as specified in the Cluster Manifest).</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeId">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeId NodeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.NodeId NodeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.GatewayInformation.NodeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeId As NodeId" />
      <MemberSignature Language="F#" Value="member this.NodeId : System.Fabric.NodeId" Usage="System.Fabric.GatewayInformation.NodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e02c5-104">Der eindeutige Bezeichner von Service Fabric intern verwendet wird, um einen Knoten zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="e02c5-104">The unique identifier used internally by Service Fabric to identify a node.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="e02c5-105">Gibt <see cref="T:System.Fabric.NodeId" />zurück.</span><span class="sxs-lookup"><span data-stu-id="e02c5-105">Returns <see cref="T:System.Fabric.NodeId" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeInstanceId">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger NodeInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger NodeInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.GatewayInformation.NodeInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeInstanceId As BigInteger" />
      <MemberSignature Language="F#" Value="member this.NodeInstanceId : System.Numerics.BigInteger" Usage="System.Fabric.GatewayInformation.NodeInstanceId" />
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
          <para><span data-ttu-id="e02c5-106">Die Instanz von einem Service Fabric-Knoten ändert, wenn der Knoten neu gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="e02c5-106">The instance of a Service Fabric node changes when the node is restarted.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e02c5-107">Gibt <see cref="T:System.Numerics.BigInteger" />zurück.</span><span class="sxs-lookup"><span data-stu-id="e02c5-107">Returns <see cref="T:System.Numerics.BigInteger" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.GatewayInformation.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.GatewayInformation.NodeName" />
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
          <para><span data-ttu-id="e02c5-108">Der angezeigte Name des Service Fabric-Knotens (definiert in den Cluster Manifest) verwendet, um die Knoten-ID zu generieren.</span><span class="sxs-lookup"><span data-stu-id="e02c5-108">The friendly name of the Service Fabric node (defined in the Cluster Manifest) used to generate the NodeId.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e02c5-109">Gibt <see cref="T:System.String" />zurück.</span><span class="sxs-lookup"><span data-stu-id="e02c5-109">Returns <see cref="T:System.String" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>