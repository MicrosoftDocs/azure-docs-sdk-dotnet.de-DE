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
            <span data-ttu-id="9ceb8-101">Diese Enumeration gibt an, wie der Zielreplikat oder die Instanz gewählt werden sollte, wenn einen Kommunikationskanal für eine bestimmte Partition zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="9ceb8-101">This enumeration specifies how the target replica or instance should be chosen when creating a communication channel for a particular partition.</span></span>
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
            <span data-ttu-id="9ceb8-102">Hiermit wird die Standardoption für diese Enumeration.</span><span class="sxs-lookup"><span data-stu-id="9ceb8-102">This specifies the default option for this enum.</span></span>
            <span data-ttu-id="9ceb8-103">Wenn der Dienstpartition zustandsbehaftete ist, bedeutet dies, dass es sich bei dieser Kommunikationskanal mit dem primären Replikat hergestellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="9ceb8-103">If the service partition is stateful, this indicates that communication channel should be established to the primary replica.</span></span>
            <span data-ttu-id="9ceb8-104">Wenn der Dienstpartition zustandslos ist, bedeutet dies, dass es sich bei der Kommunikationskanal mit einer zufälligen zustandslose Instanz hergestellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="9ceb8-104">If the service partition is stateless, this indicates that the communication channel should be established to a random stateless instance.</span></span>
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
            <span data-ttu-id="9ceb8-105">Hiermit wird den Standardwert dieser Enumeration für Partitionen mit einem zustandsbehafteten Dienst.</span><span class="sxs-lookup"><span data-stu-id="9ceb8-105">This specifies the default value of this enum for stateful service partitions.</span></span> <span data-ttu-id="9ceb8-106">Dies gibt an, dass es sich bei der Kommunikationskanal mit dem primären Replikat hergestellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="9ceb8-106">This indicates that the communication channel should be established to the primary replica.</span></span>
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
            <span data-ttu-id="9ceb8-107">Hiermit wird den Standardwert dieser Enumeration für statusfreien Dienst Partitionen.</span><span class="sxs-lookup"><span data-stu-id="9ceb8-107">This specifies the default value of this enum for stateless service partitions.</span></span> <span data-ttu-id="9ceb8-108">Dies gibt an, dass der Kommunikationskanal mit einer zufälligen zustandslose Instanz hergestellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="9ceb8-108">This indicates that the communication channel should be established to a random stateless instance.</span></span>
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
            <span data-ttu-id="9ceb8-109">Bei einem zustandsbehafteten Dienst Partitionen Dies weist darauf hin, Kommunikationskanal für hergestellt werden kann, für jedes Replikat im ausgewählt zufällige - (d. h.) Primary oder Secondary sein.</span><span class="sxs-lookup"><span data-stu-id="9ceb8-109">For stateful service partitions, this indicates that communication channel can be established for to any replica chosen in random - (i.e) primary or secondary.</span></span>
            <span data-ttu-id="9ceb8-110">Dies gilt nicht für statusfreien Dienst Partitionen</span><span class="sxs-lookup"><span data-stu-id="9ceb8-110">This is not valid for stateless service partitions</span></span>
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
            <span data-ttu-id="9ceb8-111">Bei einem zustandsbehafteten Dienst Partitionen bedeutet dies, dass es sich bei diesem Kommunikationskanal für an ein sekundäres Replikat in zufälligen ausgewählt wurde hergestellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="9ceb8-111">For stateful service partitions, this indicates that communication channel can be established for to any secondary replica chosen in random.</span></span>
            <span data-ttu-id="9ceb8-112">Dies gilt nicht für statusfreien Dienst Partitionen</span><span class="sxs-lookup"><span data-stu-id="9ceb8-112">This is not valid for stateless service partitions</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>