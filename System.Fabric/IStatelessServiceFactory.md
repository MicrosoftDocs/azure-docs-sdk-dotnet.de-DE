<Type Name="IStatelessServiceFactory" FullName="System.Fabric.IStatelessServiceFactory">
  <TypeSignature Language="C#" Value="public interface IStatelessServiceFactory" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatelessServiceFactory" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatelessServiceFactory" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatelessServiceFactory" />
  <TypeSignature Language="F#" Value="type IStatelessServiceFactory = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt eine zustandslosen Diensts-Factory, die zum Erstellen von Instanzen eines bestimmten Typs von zustandslosen Diensts zuständig ist. </para>
    </summary>
    <remarks>
      <para>Zustandslosen Diensts Factorys registriert werden, die <see cref="T:System.Fabric.FabricRuntime" /> von Diensthosts über <see cref="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactory(System.String,System.Fabric.IStatelessServiceFactory)" /> oder <see cref="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactoryAsync(System.String,System.Fabric.IStatelessServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateInstance">
      <MemberSignature Language="C#" Value="public System.Fabric.IStatelessServiceInstance CreateInstance (string serviceTypeName, Uri serviceName, byte[] initializationData, Guid partitionId, long instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IStatelessServiceInstance CreateInstance(string serviceTypeName, class System.Uri serviceName, unsigned int8[] initializationData, valuetype System.Guid partitionId, int64 instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceFactory.CreateInstance(System.String,System.Uri,System.Byte[],System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateInstance (serviceTypeName As String, serviceName As Uri, initializationData As Byte(), partitionId As Guid, instanceId As Long) As IStatelessServiceInstance" />
      <MemberSignature Language="F#" Value="abstract member CreateInstance : string * Uri * byte[] * Guid * int64 -&gt; System.Fabric.IStatelessServiceInstance" Usage="iStatelessServiceFactory.CreateInstance (serviceTypeName, serviceName, initializationData, partitionId, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IStatelessServiceInstance</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="instanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>Der Diensttyp, den Service Fabric anfordert, erstellt werden.</para>
        </param>
        <param name="serviceName">
          <para>Die <c>Fabric: / name</c> (Uri) des Diensts, der dieses Replikat zugeordnet ist. </para>
        </param>
        <param name="initializationData">
          <para>Ein Bytearray, das die Initialisierungsdaten enthält, die ursprünglich als Teil des Diensts übergeben wurde <see cref="T:System.Fabric.Description.ServiceDescription" />.</para>
        </param>
        <param name="partitionId">
          <para>Die Partition-ID (GUID) der dieses Replikat zugeordnet ist. </para>
        </param>
        <param name="instanceId">
          <para>Die Replikat-ID für dieses Replikat vom Typ <see cref="T:System.Int64" />.</para>
        </param>
        <summary>
          <para>Erstellt eine zustandslosen Dienstinstanz für einen bestimmten Dienst. Diese Methode wird von Service Fabric aufgerufen.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Fabric.IStatelessServiceInstance" />zurück.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>