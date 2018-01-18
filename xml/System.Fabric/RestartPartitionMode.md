<Type Name="RestartPartitionMode" FullName="System.Fabric.RestartPartitionMode">
  <TypeSignature Language="C#" Value="public enum RestartPartitionMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed RestartPartitionMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.RestartPartitionMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum RestartPartitionMode" />
  <TypeSignature Language="F#" Value="type RestartPartitionMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="2bf45-101">Die Enumeration übergebenen RestartPartition-API, um anzugeben, welche Replikate neu gestartet werden müssen</span><span class="sxs-lookup"><span data-stu-id="2bf45-101">The enum passed into the RestartPartition API to specify what replicas need to be restarted</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllReplicasOrInstances">
      <MemberSignature Language="C#" Value="AllReplicasOrInstances" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.RestartPartitionMode AllReplicasOrInstances = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.RestartPartitionMode.AllReplicasOrInstances" />
      <MemberSignature Language="VB.NET" Value="AllReplicasOrInstances" />
      <MemberSignature Language="F#" Value="AllReplicasOrInstances = 1" Usage="System.Fabric.RestartPartitionMode.AllReplicasOrInstances" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RestartPartitionMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2bf45-102">Alle Replikate oder Instanzen in der Partition auf einmal neu gestartet</span><span class="sxs-lookup"><span data-stu-id="2bf45-102">All replicas or instances in the partition are restarted at once</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.RestartPartitionMode Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.RestartPartitionMode.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.RestartPartitionMode.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RestartPartitionMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2bf45-103">Reserviert.</span><span class="sxs-lookup"><span data-stu-id="2bf45-103">Reserved.</span></span>  <span data-ttu-id="2bf45-104">Übergeben Sie diesen Wert nicht an die API.</span><span class="sxs-lookup"><span data-stu-id="2bf45-104">Do not pass into API.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="OnlyActiveSecondaries">
      <MemberSignature Language="C#" Value="OnlyActiveSecondaries" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.RestartPartitionMode OnlyActiveSecondaries = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.RestartPartitionMode.OnlyActiveSecondaries" />
      <MemberSignature Language="VB.NET" Value="OnlyActiveSecondaries" />
      <MemberSignature Language="F#" Value="OnlyActiveSecondaries = 2" Usage="System.Fabric.RestartPartitionMode.OnlyActiveSecondaries" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RestartPartitionMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2bf45-105">Nur die sekundären Replikate wieder gestartet werden.</span><span class="sxs-lookup"><span data-stu-id="2bf45-105">Only the secondary replicas are restarted.</span></span> <span data-ttu-id="2bf45-106">Diese Option kann nur für zustandsbehaftete Dienste verwendet werden, und vermeidet Datenverluste</span><span class="sxs-lookup"><span data-stu-id="2bf45-106">This option can only be used for stateful services and avoids data loss</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>