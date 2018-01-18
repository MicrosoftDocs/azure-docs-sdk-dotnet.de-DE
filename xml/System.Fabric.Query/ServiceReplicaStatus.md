<Type Name="ServiceReplicaStatus" FullName="System.Fabric.Query.ServiceReplicaStatus">
  <TypeSignature Language="C#" Value="public enum ServiceReplicaStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServiceReplicaStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ServiceReplicaStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServiceReplicaStatus" />
  <TypeSignature Language="F#" Value="type ServiceReplicaStatus = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="c72e1-101">Gibt den Status des Replikats.</span><span class="sxs-lookup"><span data-stu-id="c72e1-101">Specifies the status of the replica.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Down">
      <MemberSignature Language="C#" Value="Down" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus Down = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.Down" />
      <MemberSignature Language="VB.NET" Value="Down" />
      <MemberSignature Language="F#" Value="Down = 4" Usage="System.Fabric.Query.ServiceReplicaStatus.Down" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="c72e1-102">Replikat ist nicht aktiv.</span><span class="sxs-lookup"><span data-stu-id="c72e1-102">Replica is down.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Dropped">
      <MemberSignature Language="C#" Value="Dropped" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus Dropped = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.Dropped" />
      <MemberSignature Language="VB.NET" Value="Dropped" />
      <MemberSignature Language="F#" Value="Dropped = 5" Usage="System.Fabric.Query.ServiceReplicaStatus.Dropped" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="c72e1-103">Replikat wird gelöscht.</span><span class="sxs-lookup"><span data-stu-id="c72e1-103">Replica is dropped.</span></span> <span data-ttu-id="c72e1-104">Dies bedeutet, dass das Replikat aus der Replikatgruppe entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="c72e1-104">This means that the replica has been removed from the replica set.</span></span> <span data-ttu-id="c72e1-105">Wenn es beibehalten wird, wurde seinen Status gelöscht.</span><span class="sxs-lookup"><span data-stu-id="c72e1-105">If it is persisted, its state has been deleted.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="InBuild">
      <MemberSignature Language="C#" Value="InBuild" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus InBuild = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.InBuild" />
      <MemberSignature Language="VB.NET" Value="InBuild" />
      <MemberSignature Language="F#" Value="InBuild = 1" Usage="System.Fabric.Query.ServiceReplicaStatus.InBuild" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="c72e1-106">Replikat wird erstellt.</span><span class="sxs-lookup"><span data-stu-id="c72e1-106">Replica is being built.</span></span> <span data-ttu-id="c72e1-107">Dies bedeutet, dass ein primäres Replikat auf dieses Replikat seeding ist.</span><span class="sxs-lookup"><span data-stu-id="c72e1-107">This means that a primary replica is seeding this replica.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Query.ServiceReplicaStatus.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="c72e1-108">Ungültig</span><span class="sxs-lookup"><span data-stu-id="c72e1-108">Invalid.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Ready">
      <MemberSignature Language="C#" Value="Ready" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus Ready = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.Ready" />
      <MemberSignature Language="VB.NET" Value="Ready" />
      <MemberSignature Language="F#" Value="Ready = 3" Usage="System.Fabric.Query.ServiceReplicaStatus.Ready" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="c72e1-109">Replikat ist bereit.</span><span class="sxs-lookup"><span data-stu-id="c72e1-109">Replica is ready.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Standby">
      <MemberSignature Language="C#" Value="Standby" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus Standby = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.Standby" />
      <MemberSignature Language="VB.NET" Value="Standby" />
      <MemberSignature Language="F#" Value="Standby = 2" Usage="System.Fabric.Query.ServiceReplicaStatus.Standby" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="c72e1-110">Das Replikat neu gestartet wurde, und wird als Reservesystem arbeitet gehalten.</span><span class="sxs-lookup"><span data-stu-id="c72e1-110">The replica has restarted and it is being kept as a standby.</span></span>
            </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>