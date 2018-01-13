<Type Name="QuorumLossMode" FullName="System.Fabric.QuorumLossMode">
  <TypeSignature Language="C#" Value="public enum QuorumLossMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed QuorumLossMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.QuorumLossMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum QuorumLossMode" />
  <TypeSignature Language="F#" Value="type QuorumLossMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="3372a-101">Typ des QuorumLoss, die aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="3372a-101">Type of QuorumLoss that will be invoked.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllReplicas">
      <MemberSignature Language="C#" Value="AllReplicas" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.QuorumLossMode AllReplicas = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.QuorumLossMode.AllReplicas" />
      <MemberSignature Language="VB.NET" Value="AllReplicas" />
      <MemberSignature Language="F#" Value="AllReplicas = 2" Usage="System.Fabric.QuorumLossMode.AllReplicas" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.QuorumLossMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary><span data-ttu-id="3372a-102">Vollständige quorummodus Verlust: alle Replikate für eine Partition, die ausgeschaltet wird, führt dies eine Quorum dienstunterbrechung.</span><span class="sxs-lookup"><span data-stu-id="3372a-102">Full Quorum loss mode : All replicas for a partition will be down that will cause a quorum loss.</span></span> </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.QuorumLossMode Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.QuorumLossMode.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.QuorumLossMode.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.QuorumLossMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3372a-103">Reserviert.</span><span class="sxs-lookup"><span data-stu-id="3372a-103">Reserved.</span></span>  <span data-ttu-id="3372a-104">Übergeben Sie diesen Wert nicht an die API.</span><span class="sxs-lookup"><span data-stu-id="3372a-104">Do not pass into API.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="QuorumReplicas">
      <MemberSignature Language="C#" Value="QuorumReplicas" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.QuorumLossMode QuorumReplicas = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.QuorumLossMode.QuorumReplicas" />
      <MemberSignature Language="VB.NET" Value="QuorumReplicas" />
      <MemberSignature Language="F#" Value="QuorumReplicas = 1" Usage="System.Fabric.QuorumLossMode.QuorumReplicas" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.QuorumLossMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="3372a-105">Partielle quorummodus Verlust: minimale Anzahl von Replikaten für eine Partition, die ausgeschaltet wird, führt dies eine Quorum dienstunterbrechung.</span><span class="sxs-lookup"><span data-stu-id="3372a-105">Partial Quorum loss mode : Minimum number of replicas for a partition will be down that will cause a quorum loss.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>