<Type Name="ReplicatorOperationName" FullName="System.Fabric.Query.ReplicatorOperationName">
  <TypeSignature Language="C#" Value="public enum ReplicatorOperationName" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ReplicatorOperationName extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ReplicatorOperationName" />
  <TypeSignature Language="VB.NET" Value="Public Enum ReplicatorOperationName" />
  <TypeSignature Language="F#" Value="type ReplicatorOperationName = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="a520c-101">Stellt den Vorgang derzeit ausgeführt wird, vom Replikator, entweder über <see cref="T:System.Fabric.IReplicator" /> oder <see cref="T:System.Fabric.IPrimaryReplicator" /> Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="a520c-101">Represents the operation currently being executed by the Replicator, either via <see cref="T:System.Fabric.IReplicator" /> or <see cref="T:System.Fabric.IPrimaryReplicator" /> interface.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="Abort" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName Abort = int32(32)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.Abort" />
      <MemberSignature Language="VB.NET" Value="Abort" />
      <MemberSignature Language="F#" Value="Abort = 32" Usage="System.Fabric.Query.ReplicatorOperationName.Abort" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>32</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a520c-102">Replikator wird abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="a520c-102">Replicator is being aborted.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Build">
      <MemberSignature Language="C#" Value="Build" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName Build = int32(256)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.Build" />
      <MemberSignature Language="VB.NET" Value="Build" />
      <MemberSignature Language="F#" Value="Build = 256" Usage="System.Fabric.Query.ReplicatorOperationName.Build" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>256</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a520c-103">Replicator ist gerade dabei erstellen ein oder mehrere Replikate.</span><span class="sxs-lookup"><span data-stu-id="a520c-103">Replicator is in the process of building one or more replicas.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ChangeRole">
      <MemberSignature Language="C#" Value="ChangeRole" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName ChangeRole = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.ChangeRole" />
      <MemberSignature Language="VB.NET" Value="ChangeRole" />
      <MemberSignature Language="F#" Value="ChangeRole = 4" Usage="System.Fabric.Query.ReplicatorOperationName.ChangeRole" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a520c-104">Replikator wird gerade die Rolle ändern.</span><span class="sxs-lookup"><span data-stu-id="a520c-104">Replicator is in the process of changing its role.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Close">
      <MemberSignature Language="C#" Value="Close" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName Close = int32(16)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.Close" />
      <MemberSignature Language="VB.NET" Value="Close" />
      <MemberSignature Language="F#" Value="Close = 16" Usage="System.Fabric.Query.ReplicatorOperationName.Close" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>16</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a520c-105">Replikator wird geschlossen.</span><span class="sxs-lookup"><span data-stu-id="a520c-105">Replicator is closing.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Query.ReplicatorOperationName.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a520c-106">DEFAULT-Wert, wenn der Replikator noch nicht bereit ist.</span><span class="sxs-lookup"><span data-stu-id="a520c-106">Default value if the replicator is not yet ready.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName None = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 1" Usage="System.Fabric.Query.ReplicatorOperationName.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a520c-107">Replikator wird Vorgänge hinsichtlich der Service Fabric nicht ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="a520c-107">Replicator is not running any operation from Service Fabric perspective.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="OnDataLoss">
      <MemberSignature Language="C#" Value="OnDataLoss" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName OnDataLoss = int32(64)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.OnDataLoss" />
      <MemberSignature Language="VB.NET" Value="OnDataLoss" />
      <MemberSignature Language="F#" Value="OnDataLoss = 64" Usage="System.Fabric.Query.ReplicatorOperationName.OnDataLoss" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>64</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a520c-108">Replicator ist der Verlust der Datenbedingung behandeln, in denen möglicherweise der Dienst für die potenziell Zustand aus einer externen Quelle wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="a520c-108">Replicator is handling the data loss condition, where the user service may potentially be recovering state from an external source.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="Open" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName Open = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.Open" />
      <MemberSignature Language="VB.NET" Value="Open" />
      <MemberSignature Language="F#" Value="Open = 2" Usage="System.Fabric.Query.ReplicatorOperationName.Open" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a520c-109">Replikator offen ist.</span><span class="sxs-lookup"><span data-stu-id="a520c-109">Replicator is opening.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="UpdateEpoch">
      <MemberSignature Language="C#" Value="UpdateEpoch" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName UpdateEpoch = int32(8)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.UpdateEpoch" />
      <MemberSignature Language="VB.NET" Value="UpdateEpoch" />
      <MemberSignature Language="F#" Value="UpdateEpoch = 8" Usage="System.Fabric.Query.ReplicatorOperationName.UpdateEpoch" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a520c-110">Aufgrund einer Änderung in der Replikatgruppe können wird mit seiner Epoche Replikator aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="a520c-110">Due to a change in the replica set, replicator is being updated with its Epoch.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForCatchup">
      <MemberSignature Language="C#" Value="WaitForCatchup" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName WaitForCatchup = int32(128)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.WaitForCatchup" />
      <MemberSignature Language="VB.NET" Value="WaitForCatchup" />
      <MemberSignature Language="F#" Value="WaitForCatchup = 128" Usage="System.Fabric.Query.ReplicatorOperationName.WaitForCatchup" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>128</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a520c-111">Replikator wartet darauf, dass ein Quorum der Replikate, die auf den aktuellen Zustand aufgeholt werden.</span><span class="sxs-lookup"><span data-stu-id="a520c-111">Replicator is waiting for a quorum of replicas to be caught up to the latest state.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>