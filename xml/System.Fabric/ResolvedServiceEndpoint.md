<Type Name="ResolvedServiceEndpoint" FullName="System.Fabric.ResolvedServiceEndpoint">
  <TypeSignature Language="C#" Value="public sealed class ResolvedServiceEndpoint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ResolvedServiceEndpoint extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ResolvedServiceEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ResolvedServiceEndpoint" />
  <TypeSignature Language="F#" Value="type ResolvedServiceEndpoint = class" />
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
      <para><span data-ttu-id="be883-101">Stellt einen aufgelösten Dienstendpunkt enthält Informationen zu der Rolle "Replikat" Partition und die Adresse, der er überwacht.</span><span class="sxs-lookup"><span data-stu-id="be883-101">Represents a resolved service endpoint, which contains information about service partition replica role and the address it listens to.</span></span></para>
    </summary>
    <remarks>
      <para>
            <span data-ttu-id="be883-102">Die aufgelöste Dienst-Endpunkte zurückgegeben werden, von <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />, im Rahmen des <see cref="T:System.Fabric.ResolvedServicePartition" />.</span><span class="sxs-lookup"><span data-stu-id="be883-102">The resolved service endpoints are returned from <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />, as part of <see cref="T:System.Fabric.ResolvedServicePartition" />.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public string Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServiceEndpoint.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As String" />
      <MemberSignature Language="F#" Value="member this.Address : string" Usage="System.Fabric.ResolvedServiceEndpoint.Address" />
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
          <para><span data-ttu-id="be883-103">Ruft die Adresse für den Endpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="be883-103">Gets the address for the endpoint.</span></span>
            <span data-ttu-id="be883-104">Die dienstreplikats ermöglicht diese Zeichenfolge auf Service Fabric, damit Benutzer wissen, wo es erreicht werden kann.</span><span class="sxs-lookup"><span data-stu-id="be883-104">The service replica gives this string to Service Fabric to let users know where it can be reached.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="be883-105">Die Adresse für den Endpunkt, in denen die dienstreplikats oder einer Instanz erreicht werden kann.</span><span class="sxs-lookup"><span data-stu-id="be883-105">The address for the endpoint where the service replica or instance can be reached.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Role">
      <MemberSignature Language="C#" Value="public System.Fabric.ServiceEndpointRole Role { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ServiceEndpointRole Role" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServiceEndpoint.Role" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Role As ServiceEndpointRole" />
      <MemberSignature Language="F#" Value="member this.Role : System.Fabric.ServiceEndpointRole" Usage="System.Fabric.ResolvedServiceEndpoint.Role" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServiceEndpointRole</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="be883-106">Ruft die Rolle eines Dienstendpunkts ab.</span><span class="sxs-lookup"><span data-stu-id="be883-106">Gets the role of a service endpoint.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="be883-107">Die Rolle eines Dienstendpunkts.</span><span class="sxs-lookup"><span data-stu-id="be883-107">The role of a service endpoint.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="be883-108">Die <see cref="T:System.Fabric.ServiceEndpointRole" /> wird von einem Client verwendet, um zu bestimmen, welche Dienstinstanz oder auswählen und Herstellen einer Verbindung mit Replikat.</span><span class="sxs-lookup"><span data-stu-id="be883-108">The <see cref="T:System.Fabric.ServiceEndpointRole" /> is used by a client to determine which service instance or replica to select and connect to.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>