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
      <para>Stellt eine zustandsbehaftete dienstfactory, die für das Erstellen von Replikaten, der einen bestimmten Typ von einem zustandsbehafteten Dienst zuständig ist. Mit einem zustandsbehafteten Dienst Factorys registriert sind die <see cref="T:System.Fabric.FabricRuntime" /> von Diensthosts über <see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactory(System.String,System.Fabric.IStatefulServiceFactory)" /> oder <see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactoryAsync(System.String,System.Fabric.IStatefulServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />.</para>
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
          <para>Der Diensttyp, den Service Fabric anfordert, erstellt werden.</para>
        </param>
        <param name="serviceName">
          <para>Der Fabric: / name (Uri) des Diensts, der dieses Replikat zugeordnet ist.</para>
        </param>
        <param name="initializationData">
          <para>Ein Bytearray, das die Initialisierungsdaten enthält, die ursprünglich als Teil des Diensts übergeben wurde <see cref="T:System.Fabric.Description.ServiceDescription" />.</para>
        </param>
        <param name="partitionId">
          <para>Die Partitions-ID des Typs, der eine GUID, die dieses Replikat zugeordnet ist.</para>
        </param>
        <param name="replicaId">
          <para>Die Replikat-ID vom Typ long für dieses Replikat. </para>
        </param>
        <summary>
          <para>Von Service Fabric zum Erstellen eines zustandsbehafteten dienstreplikats für einen bestimmten Dienst aufgerufen.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Fabric.IStatefulServiceReplica" />zurück.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>