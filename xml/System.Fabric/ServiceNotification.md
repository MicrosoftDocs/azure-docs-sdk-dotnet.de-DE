<Type Name="ServiceNotification" FullName="System.Fabric.ServiceNotification">
  <TypeSignature Language="C#" Value="public sealed class ServiceNotification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceNotification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServiceNotification" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceNotification" />
  <TypeSignature Language="F#" Value="type ServiceNotification = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="ac470-101">Stellt eine Dienst-Benachrichtigung mit Details zu einem Dienst, dessen Endpunkte Replikaten bzw. Instanzen geändert haben.</span><span class="sxs-lookup"><span data-stu-id="ac470-101">Represents a service notification containing details about a service whose replica or instance endpoints have changed.</span></span> <span data-ttu-id="ac470-102">Benachrichtigungen werden gesendet, von der <see cref="E:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationFilterMatched" /> Ereignis.</span><span class="sxs-lookup"><span data-stu-id="ac470-102">Notifications are dispatched by the <see cref="E:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationFilterMatched" /> event.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt; Endpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;class System.Fabric.ResolvedServiceEndpoint&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceNotification.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoints As ICollection(Of ResolvedServiceEndpoint)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt;" Usage="System.Fabric.ServiceNotification.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ac470-103">Ruft die neuen Replikaten bzw. Instanzen Endpunkte, die vom Dienst veröffentlicht wurde.</span><span class="sxs-lookup"><span data-stu-id="ac470-103">Gets the new replica or instance endpoints published by the service.</span></span> <span data-ttu-id="ac470-104">Die Auflistung ist nicht leer, wenn der Dienst gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="ac470-104">The collection will be empty if the service has been deleted.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ac470-105">Eine Liste der Endpunkte, die vom Dienst veröffentlicht wurde.</span><span class="sxs-lookup"><span data-stu-id="ac470-105">A list of endpoints published by the service.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceNotification.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.ServiceNotification.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ac470-106">Ruft die Partitions-ID des Diensts ab.</span><span class="sxs-lookup"><span data-stu-id="ac470-106">Gets the partition ID of the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ac470-107">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="ac470-107">The partition ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionInfo">
      <MemberSignature Language="C#" Value="public System.Fabric.ServicePartitionInformation PartitionInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ServicePartitionInformation PartitionInfo" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceNotification.PartitionInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionInfo As ServicePartitionInformation" />
      <MemberSignature Language="F#" Value="member this.PartitionInfo : System.Fabric.ServicePartitionInformation" Usage="System.Fabric.ServiceNotification.PartitionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ac470-108">Ruft die ausführliche Partitionsinformationen für den Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="ac470-108">Gets the detailed partition information for the service.</span></span> <span data-ttu-id="ac470-109">Diese Eigenschaft kann in bestimmten Fällen null sein, in dem ausführliche Partitionsinformationen nicht verfügbar ist – z. B. wenn der Dienst Benachrichtigungsereignis für ein Ereignis einer Löschung wird.</span><span class="sxs-lookup"><span data-stu-id="ac470-109">This property can be null in certain cases where detailed partition information is unavailable - such as when the service notification event is for a service deletion event.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ac470-110">Die detaillierte Partitionsinformationen des Diensts.</span><span class="sxs-lookup"><span data-stu-id="ac470-110">The detailed partition information of the service.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceNotification.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.ServiceNotification.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ac470-111">Ruft den Namen des Diensts ab.</span><span class="sxs-lookup"><span data-stu-id="ac470-111">Gets the name of the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ac470-112">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="ac470-112">The name of the service.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public System.Fabric.ServiceEndpointsVersion Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ServiceEndpointsVersion Version" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceNotification.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As ServiceEndpointsVersion" />
      <MemberSignature Language="F#" Value="member this.Version : System.Fabric.ServiceEndpointsVersion" Usage="System.Fabric.ServiceNotification.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServiceEndpointsVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ac470-113">Ruft die Version dieses Ereignisses Benachrichtigung ab.</span><span class="sxs-lookup"><span data-stu-id="ac470-113">Gets the version of this notification event.</span></span> <span data-ttu-id="ac470-114">Die Version kann verwendet werden, um alle zwei Benachrichtigungsereignisse zu sortieren.</span><span class="sxs-lookup"><span data-stu-id="ac470-114">The version can be used to order any two notification events.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ac470-115">Die Version des dieses Benachrichtigungsereignis.</span><span class="sxs-lookup"><span data-stu-id="ac470-115">The version of this notification event.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>