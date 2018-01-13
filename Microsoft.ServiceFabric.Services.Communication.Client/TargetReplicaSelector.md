<Type Name="TargetReplicaSelector" FullName="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector">
  <TypeSignature Language="C#" Value="public enum TargetReplicaSelector" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TargetReplicaSelector extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
  <TypeSignature Language="VB.NET" Value="Public Enum TargetReplicaSelector" />
  <TypeSignature Language="F#" Value="type TargetReplicaSelector = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            Diese Enumeration gibt an, wie der Zielreplikat oder die Instanz gewählt werden sollte, wenn einen Kommunikationskanal für eine bestimmte Partition zu erstellen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector Default = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Hiermit wird die Standardoption für diese Enumeration.
            Wenn der Dienstpartition zustandsbehaftete ist, bedeutet dies, dass es sich bei dieser Kommunikationskanal mit dem primären Replikat hergestellt werden soll.
            Wenn der Dienstpartition zustandslos ist, bedeutet dies, dass es sich bei der Kommunikationskanal mit einer zufälligen zustandslose Instanz hergestellt werden soll.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="PrimaryReplica">
      <MemberSignature Language="C#" Value="PrimaryReplica" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector PrimaryReplica = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica" />
      <MemberSignature Language="VB.NET" Value="PrimaryReplica" />
      <MemberSignature Language="F#" Value="PrimaryReplica = 0" Usage="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Hiermit wird den Standardwert dieser Enumeration für Partitionen mit einem zustandsbehafteten Dienst. Dies gibt an, dass es sich bei der Kommunikationskanal mit dem primären Replikat hergestellt werden soll.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RandomInstance">
      <MemberSignature Language="C#" Value="RandomInstance" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector RandomInstance = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomInstance" />
      <MemberSignature Language="VB.NET" Value="RandomInstance" />
      <MemberSignature Language="F#" Value="RandomInstance = 0" Usage="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomInstance" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Hiermit wird den Standardwert dieser Enumeration für statusfreien Dienst Partitionen. Dies gibt an, dass der Kommunikationskanal mit einer zufälligen zustandslose Instanz hergestellt werden soll.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RandomReplica">
      <MemberSignature Language="C#" Value="RandomReplica" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector RandomReplica = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomReplica" />
      <MemberSignature Language="VB.NET" Value="RandomReplica" />
      <MemberSignature Language="F#" Value="RandomReplica = 1" Usage="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomReplica" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Bei einem zustandsbehafteten Dienst Partitionen Dies weist darauf hin, Kommunikationskanal für hergestellt werden kann, für jedes Replikat im ausgewählt zufällige - (d. h.) Primary oder Secondary sein.
            Dies gilt nicht für statusfreien Dienst Partitionen
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RandomSecondaryReplica">
      <MemberSignature Language="C#" Value="RandomSecondaryReplica" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector RandomSecondaryReplica = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomSecondaryReplica" />
      <MemberSignature Language="VB.NET" Value="RandomSecondaryReplica" />
      <MemberSignature Language="F#" Value="RandomSecondaryReplica = 2" Usage="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomSecondaryReplica" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Bei einem zustandsbehafteten Dienst Partitionen bedeutet dies, dass es sich bei diesem Kommunikationskanal für an ein sekundäres Replikat in zufälligen ausgewählt wurde hergestellt werden kann.
            Dies gilt nicht für statusfreien Dienst Partitionen
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>