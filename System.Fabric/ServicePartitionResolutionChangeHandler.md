<Type Name="ServicePartitionResolutionChangeHandler" FullName="System.Fabric.ServicePartitionResolutionChangeHandler">
  <TypeSignature Language="C#" Value="public delegate void ServicePartitionResolutionChangeHandler(FabricClient source, long handlerId, ServicePartitionResolutionChange args);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServicePartitionResolutionChangeHandler extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServicePartitionResolutionChangeHandler" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Sub ServicePartitionResolutionChangeHandler(source As FabricClient, handlerId As Long, args As ServicePartitionResolutionChange)" />
  <TypeSignature Language="F#" Value="type ServicePartitionResolutionChangeHandler = delegate of FabricClient * int64 * ServicePartitionResolutionChange -&gt; unit" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="source" Type="System.Fabric.FabricClient" />
    <Parameter Name="handlerId" Type="System.Int64" />
    <Parameter Name="args" Type="System.Fabric.ServicePartitionResolutionChange" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Void</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="source">
      <para>Ein Verweis auf die <see cref="T:System.Fabric.FabricClient" /> Instanz, die den Endpunkt empfangen change-Ereignis.</para>
    </param>
    <param name="handlerId">
      <para>Die ID von zurückgegebenen <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.Fabric.ServicePartitionResolutionChangeHandler)" /> Wenn der Handler registriert wurde.</para>
    </param>
    <param name="args">
      <para>Ereignisargumente, die Details für das Ereignis enthält. <seealso cref="T:System.Fabric.ServicePartitionResolutionChange" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
    </param>
    <summary>
      <para>Ein Delegattyp, für die clientseitige Rückrufe, die für Benutzercode vorgenommen werden, wenn die Endpunkte der Änderungen am Dienst oder eine Ausnahme auftritt, während der Prozess Endpunktinformationen zur Laufzeit aktualisiert werden soll.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
</Type>