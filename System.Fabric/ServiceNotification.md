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
      <para>Stellt eine Dienst-Benachrichtigung mit Details zu einem Dienst, dessen Endpunkte Replikaten bzw. Instanzen geändert haben. Benachrichtigungen werden gesendet, von der <see cref="E:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationFilterMatched" /> Ereignis.</para>
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
          <para>Ruft die neuen Replikaten bzw. Instanzen Endpunkte, die vom Dienst veröffentlicht wurde. Die Auflistung ist nicht leer, wenn der Dienst gelöscht wurde.</para>
        </summary>
        <value>
          <para>Eine Liste der Endpunkte, die vom Dienst veröffentlicht wurde.</para>
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
          <para>Ruft die Partitions-ID des Diensts ab.</para>
        </summary>
        <value>
          <para>Die Partitions-ID.</para>
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
          <para>Ruft die ausführliche Partitionsinformationen für den Dienst ab. Diese Eigenschaft kann in bestimmten Fällen null sein, in dem ausführliche Partitionsinformationen nicht verfügbar ist – z. B. wenn der Dienst Benachrichtigungsereignis für ein Ereignis einer Löschung wird.</para>
        </summary>
        <value>
          <para>Die detaillierte Partitionsinformationen des Diensts.</para>
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
          <para>Ruft den Namen des Diensts ab.</para>
        </summary>
        <value>
          <para>Der Name des Diensts.</para>
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
          <para>Ruft die Version dieses Ereignisses Benachrichtigung ab. Die Version kann verwendet werden, um alle zwei Benachrichtigungsereignisse zu sortieren.</para>
        </summary>
        <value>
          <para>Die Version des dieses Benachrichtigungsereignis.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>