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
            Die Enumeration übergebenen RestartPartition-API, um anzugeben, welche Replikate neu gestartet werden müssen
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
            Alle Replikate oder Instanzen in der Partition auf einmal neu gestartet
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
            Reserviert.  Übergeben Sie diesen Wert nicht an die API.
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
            Nur die sekundären Replikate wieder gestartet werden. Diese Option kann nur für zustandsbehaftete Dienste verwendet werden, und vermeidet Datenverluste
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>