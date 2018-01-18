<Type Name="IStatefulServiceFactory" FullName="System.Fabric.IStatefulServiceFactory">
  <TypeSignature Language="C#" Value="public interface IStatefulServiceFactory" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatefulServiceFactory" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatefulServiceFactory" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatefulServiceFactory" />
  <TypeSignature Language="F#" Value="type IStatefulServiceFactory = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="a570e-101">Stellt eine zustandsbehaftete dienstfactory, die für das Erstellen von Replikaten, der einen bestimmten Typ von einem zustandsbehafteten Dienst zuständig ist.</span><span class="sxs-lookup"><span data-stu-id="a570e-101">Represents a stateful service factory that is responsible for creating replicas of a specific type of stateful service.</span></span> <span data-ttu-id="a570e-102">Mit einem zustandsbehafteten Dienst Factorys registriert sind die <see cref="T:System.Fabric.FabricRuntime" /> von Diensthosts über <see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactory(System.String,System.Fabric.IStatefulServiceFactory)" /> oder <see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactoryAsync(System.String,System.Fabric.IStatefulServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="a570e-102">Stateful service factories are registered with the <see cref="T:System.Fabric.FabricRuntime" /> by service hosts via <see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactory(System.String,System.Fabric.IStatefulServiceFactory)" /> or <see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactoryAsync(System.String,System.Fabric.IStatefulServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateReplica">
      <MemberSignature Language="C#" Value="public System.Fabric.IStatefulServiceReplica CreateReplica (string serviceTypeName, Uri serviceName, byte[] initializationData, Guid partitionId, long replicaId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IStatefulServiceReplica CreateReplica(string serviceTypeName, class System.Uri serviceName, unsigned int8[] initializationData, valuetype System.Guid partitionId, int64 replicaId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceFactory.CreateReplica(System.String,System.Uri,System.Byte[],System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateReplica (serviceTypeName As String, serviceName As Uri, initializationData As Byte(), partitionId As Guid, replicaId As Long) As IStatefulServiceReplica" />
      <MemberSignature Language="F#" Value="abstract member CreateReplica : string * Uri * byte[] * Guid * int64 -&gt; System.Fabric.IStatefulServiceReplica" Usage="iStatefulServiceFactory.CreateReplica (serviceTypeName, serviceName, initializationData, partitionId, replicaId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IStatefulServiceReplica</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="a570e-103">Der Diensttyp, den Service Fabric anfordert, erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="a570e-103">The service type that Service Fabric requests to be created.</span></span></para>
        </param>
        <param name="serviceName">
          <para><span data-ttu-id="a570e-104">Der Fabric: / name (Uri) des Diensts, der dieses Replikat zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="a570e-104">The fabric:/ name (Uri) of the service with which this replica is associated.</span></span></para>
        </param>
        <param name="initializationData">
          <para><span data-ttu-id="a570e-105">Ein Bytearray, das die Initialisierungsdaten enthält, die ursprünglich als Teil des Diensts übergeben wurde <see cref="T:System.Fabric.Description.ServiceDescription" />.</span><span class="sxs-lookup"><span data-stu-id="a570e-105">A byte array that contains the initialization data which was originally passed as a part of this service’s <see cref="T:System.Fabric.Description.ServiceDescription" />.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="a570e-106">Die Partitions-ID des Typs, der eine GUID, die dieses Replikat zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="a570e-106">The partition ID of type, a GUID, with which this replica is associated.</span></span></para>
        </param>
        <param name="replicaId">
          <para><span data-ttu-id="a570e-107">Die Replikat-ID vom Typ long für dieses Replikat.</span><span class="sxs-lookup"><span data-stu-id="a570e-107">The replica ID of type long for this replica.</span></span> </para>
        </param>
        <summary>
          <para><span data-ttu-id="a570e-108">Von Service Fabric zum Erstellen eines zustandsbehafteten dienstreplikats für einen bestimmten Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="a570e-108">Called by Service Fabric to create a stateful service replica for a particular service.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="a570e-109">Gibt <see cref="T:System.Fabric.IStatefulServiceReplica" />zurück.</span><span class="sxs-lookup"><span data-stu-id="a570e-109">Returns <see cref="T:System.Fabric.IStatefulServiceReplica" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>