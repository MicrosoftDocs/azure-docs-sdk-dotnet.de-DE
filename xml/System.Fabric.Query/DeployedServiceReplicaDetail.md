<Type Name="DeployedServiceReplicaDetail" FullName="System.Fabric.Query.DeployedServiceReplicaDetail">
  <TypeSignature Language="C#" Value="public abstract class DeployedServiceReplicaDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit DeployedServiceReplicaDetail extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedServiceReplicaDetail" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class DeployedServiceReplicaDetail" />
  <TypeSignature Language="F#" Value="type DeployedServiceReplicaDetail = class" />
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
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.DeployedStatefulServiceReplicaDetail))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.DeployedStatelessServiceInstanceDetail))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="86957-101">Stellt ein Replikat ausgeführt wird, im Codepaket.</span><span class="sxs-lookup"><span data-stu-id="86957-101">Represents a replica running in the code package.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected internal DeployedServiceReplicaDetail (System.Fabric.Query.ServiceKind serviceKind);" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Query.ServiceKind serviceKind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceReplicaDetail.#ctor(System.Fabric.Query.ServiceKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Query.DeployedServiceReplicaDetail : System.Fabric.Query.ServiceKind -&gt; System.Fabric.Query.DeployedServiceReplicaDetail" Usage="new System.Fabric.Query.DeployedServiceReplicaDetail serviceKind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceKind" Type="System.Fabric.Query.ServiceKind" />
      </Parameters>
      <Docs>
        <param name="serviceKind">
          <para><span data-ttu-id="86957-102">Der Typ des Diensts</span><span class="sxs-lookup"><span data-stu-id="86957-102">The type of the service</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="86957-103">Instanziiert eine <see cref="T:System.Fabric.Query.DeployedServiceReplicaDetail" /> Objekt mit beliebigen angegebenen Dienst.</span><span class="sxs-lookup"><span data-stu-id="86957-103">Instantiates a <see cref="T:System.Fabric.Query.DeployedServiceReplicaDetail" /> object with specified service kind.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentServiceOperation">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceOperationName CurrentServiceOperation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceOperationName CurrentServiceOperation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplicaDetail.CurrentServiceOperation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentServiceOperation As ServiceOperationName" />
      <MemberSignature Language="F#" Value="member this.CurrentServiceOperation : System.Fabric.Query.ServiceOperationName" Usage="System.Fabric.Query.DeployedServiceReplicaDetail.CurrentServiceOperation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceOperationName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="86957-104">Ruft ab oder legt den aktuellen API-Aufruf, der auf dem Replikat ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="86957-104">Gets or sets the current API call that is being executed on the replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="86957-105">Der aktuellen API-Aufruf, der auf dem Replikat ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="86957-105">The current API call that is being executed on the replica.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentServiceOperationStartTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime CurrentServiceOperationStartTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CurrentServiceOperationStartTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplicaDetail.CurrentServiceOperationStartTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentServiceOperationStartTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.CurrentServiceOperationStartTimeUtc : DateTime" Usage="System.Fabric.Query.DeployedServiceReplicaDetail.CurrentServiceOperationStartTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="86957-106">Ruft ab oder legt die Startzeit für die aktuelle Dienstvorgang im UTC-Format.</span><span class="sxs-lookup"><span data-stu-id="86957-106">Gets or sets the start time of the current service operation in UTC format.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="86957-107">Die Startzeit des aktuellen Dienstvorgangs im UTC-Format.</span><span class="sxs-lookup"><span data-stu-id="86957-107">The start time of the current service operation in UTC format.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplicaDetail.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Query.DeployedServiceReplicaDetail.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="86957-108">Ruft ab oder legt die Partitions-Id, die dieses Replikat zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="86957-108">Gets or sets the partition id associated with this replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="86957-109">Die Partitions-Id, die dieses Replikat zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="86957-109">The partition id associated with this replica.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportedLoad">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt; ReportedLoad { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.LoadMetricReport&gt; ReportedLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplicaDetail.ReportedLoad" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReportedLoad As IList(Of LoadMetricReport)" />
      <MemberSignature Language="F#" Value="member this.ReportedLoad : System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt;" Usage="System.Fabric.Query.DeployedServiceReplicaDetail.ReportedLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="86957-110">Ruft ab oder legt die Last, die von diesem Replikat gemeldet.</span><span class="sxs-lookup"><span data-stu-id="86957-110">Gets or sets the load reported by this replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="86957-111">Die Last, die von diesem Replikat gemeldet.</span><span class="sxs-lookup"><span data-stu-id="86957-111">The load reported by this replica.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceKind ServiceKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceKind ServiceKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplicaDetail.ServiceKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceKind As ServiceKind" />
      <MemberSignature Language="F#" Value="member this.ServiceKind : System.Fabric.Query.ServiceKind" Usage="System.Fabric.Query.DeployedServiceReplicaDetail.ServiceKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="86957-112">Ruft den Typ des Diensts ab</span><span class="sxs-lookup"><span data-stu-id="86957-112">Gets the type of the service</span></span> 
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="86957-113">Die Art des Diensts, der den Typ des Diensts darstellt dieses Replikat angehört</span><span class="sxs-lookup"><span data-stu-id="86957-113">The service kind representing the type of the service this replica belongs to</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="86957-114">Anhand des Werts dieser Eigenschaft möglich dieses Objekts Downcasted DeployedStatefulServiceReplicaDetail oder DeployedStatelessServiceInstanceDetail</span><span class="sxs-lookup"><span data-stu-id="86957-114">Based on the value of this property this object can be downcasted to DeployedStatefulServiceReplicaDetail or DeployedStatelessServiceInstanceDetail</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplicaDetail.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Query.DeployedServiceReplicaDetail.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="86957-115">Ruft ab oder legt den Dienstnamen, zu dem dieses Replikat gehört.</span><span class="sxs-lookup"><span data-stu-id="86957-115">Gets or sets the service name to which this replica belongs.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="86957-116">Der Dienstname, zu der dieses Replikat gehört.</span><span class="sxs-lookup"><span data-stu-id="86957-116">The service name to which this replica belongs.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>