<Type Name="ServiceCorrelationScheme" FullName="System.Fabric.Description.ServiceCorrelationScheme">
  <TypeSignature Language="C#" Value="public enum ServiceCorrelationScheme" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServiceCorrelationScheme extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceCorrelationScheme" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServiceCorrelationScheme" />
  <TypeSignature Language="F#" Value="type ServiceCorrelationScheme = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="d6f11-101">Gibt an, dass dieser Dienst mit einem anderen Dienst zugeordnet ist, und die Beziehung mit diesem Dienst beschreibt.</span><span class="sxs-lookup"><span data-stu-id="d6f11-101">Indicates that this service is associated with another service, and describes the relationship with that service.</span></span></para>
    </summary>
    <remarks>
      <para />
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Affinity">
      <MemberSignature Language="C#" Value="Affinity" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceCorrelationScheme Affinity = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceCorrelationScheme.Affinity" />
      <MemberSignature Language="VB.NET" Value="Affinity" />
      <MemberSignature Language="F#" Value="Affinity = 1" Usage="System.Fabric.Description.ServiceCorrelationScheme.Affinity" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d6f11-102">Gibt an, dass dieser Dienst eine Affinität mit einem anderen Dienst verfügt.</span><span class="sxs-lookup"><span data-stu-id="d6f11-102">Indicates that this service has an affinity relationship with another service.</span></span> <span data-ttu-id="d6f11-103">Für die Abwärtskompatibilität zur Verfügung gestellt, sollten Sie die Optionen ausgerichtet oder NonAlignedAffinity ausgehandelt.</span><span class="sxs-lookup"><span data-stu-id="d6f11-103">Provided for backwards compatibility, consider preferring the Aligned or NonAlignedAffinity options.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="AlignedAffinity">
      <MemberSignature Language="C#" Value="AlignedAffinity" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceCorrelationScheme AlignedAffinity = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceCorrelationScheme.AlignedAffinity" />
      <MemberSignature Language="VB.NET" Value="AlignedAffinity" />
      <MemberSignature Language="F#" Value="AlignedAffinity = 2" Usage="System.Fabric.Description.ServiceCorrelationScheme.AlignedAffinity" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d6f11-104">Angeglichene Affinität wird sichergestellt, dass der primäre Partitionen der kategorisierten Dienste auf demselben Knoten angeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="d6f11-104">Aligned affinity ensures that the primaries of the partitions of the affinitized services are collocated on the same nodes.</span></span> <span data-ttu-id="d6f11-105">Dies ist die Standardeinstellung und ist identisch mit das Schema "Affinität" auswählen.</span><span class="sxs-lookup"><span data-stu-id="d6f11-105">This is the default and is the same as selecting the “Affinity” scheme.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceCorrelationScheme Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceCorrelationScheme.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Description.ServiceCorrelationScheme.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d6f11-106">Ein Schema ungültige Korrelation.</span><span class="sxs-lookup"><span data-stu-id="d6f11-106">An invalid correlation scheme.</span></span> <span data-ttu-id="d6f11-107">kann nicht verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="d6f11-107">Cannot be used.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NonAlignedAffinity">
      <MemberSignature Language="C#" Value="NonAlignedAffinity" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceCorrelationScheme NonAlignedAffinity = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceCorrelationScheme.NonAlignedAffinity" />
      <MemberSignature Language="VB.NET" Value="NonAlignedAffinity" />
      <MemberSignature Language="F#" Value="NonAlignedAffinity = 3" Usage="System.Fabric.Description.ServiceCorrelationScheme.NonAlignedAffinity" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d6f11-108">Nicht angeglichene Affinität wird sichergestellt, dass alle Replikate der einzelnen Dienste auf demselben Knoten platziert werden.</span><span class="sxs-lookup"><span data-stu-id="d6f11-108">Non-Aligned affinity guarantees that all replicas of each service will be placed on the same nodes.</span></span> <span data-ttu-id="d6f11-109">Im Gegensatz zu Affinität ausgerichtet kann dies nicht garantiert, dass die Replikate der bestimmten Rolle zusammengestellt werden.</span><span class="sxs-lookup"><span data-stu-id="d6f11-109">Unlike Aligned Affinity, this does not guarantee that replicas of particular role will be collocated.</span></span> </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>