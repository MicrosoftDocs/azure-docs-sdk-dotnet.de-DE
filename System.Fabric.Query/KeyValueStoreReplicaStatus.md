<Type Name="KeyValueStoreReplicaStatus" FullName="System.Fabric.Query.KeyValueStoreReplicaStatus">
  <TypeSignature Language="C#" Value="public sealed class KeyValueStoreReplicaStatus : System.Fabric.Query.ReplicaStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit KeyValueStoreReplicaStatus extends System.Fabric.Query.ReplicaStatus" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.KeyValueStoreReplicaStatus" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class KeyValueStoreReplicaStatus&#xA;Inherits ReplicaStatus" />
  <TypeSignature Language="F#" Value="type KeyValueStoreReplicaStatus = class&#xA;    inherit ReplicaStatus" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.ReplicaStatus</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Fragt den Status für ein Schlüssel/Wert-Speicher-Replikat
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyNotificationCurrentKeyFilter">
      <MemberSignature Language="C#" Value="public string CopyNotificationCurrentKeyFilter { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CopyNotificationCurrentKeyFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.KeyValueStoreReplicaStatus.CopyNotificationCurrentKeyFilter" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CopyNotificationCurrentKeyFilter As String" />
      <MemberSignature Language="F#" Value="member this.CopyNotificationCurrentKeyFilter : string" Usage="System.Fabric.Query.KeyValueStoreReplicaStatus.CopyNotificationCurrentKeyFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, die neuesten Schlüssel Präfix Filters an, während der Enumeration der <see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" /> Rückruf. NULL, wenn keine ausstehenden Rückruf vorhanden ist.
            </summary>
        <value>Der Präfix-Filter.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyNotificationCurrentProgress">
      <MemberSignature Language="C#" Value="public long CopyNotificationCurrentProgress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CopyNotificationCurrentProgress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.KeyValueStoreReplicaStatus.CopyNotificationCurrentProgress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CopyNotificationCurrentProgress As Long" />
      <MemberSignature Language="F#" Value="member this.CopyNotificationCurrentProgress : int64" Usage="System.Fabric.Query.KeyValueStoreReplicaStatus.CopyNotificationCurrentProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, der aktuelle Anzahl der Schlüssel aufgelistet, die während der <see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" /> Rückruf. 0, wenn keine ausstehenden Rückruf.
            </summary>
        <value>Die Anzahl der Schlüssel.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseLogicalSizeEstimate">
      <MemberSignature Language="C#" Value="public long DatabaseLogicalSizeEstimate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DatabaseLogicalSizeEstimate" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.KeyValueStoreReplicaStatus.DatabaseLogicalSizeEstimate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseLogicalSizeEstimate As Long" />
      <MemberSignature Language="F#" Value="member this.DatabaseLogicalSizeEstimate : int64" Usage="System.Fabric.Query.KeyValueStoreReplicaStatus.DatabaseLogicalSizeEstimate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, der logischen geschätzte Größe der zugrunde liegenden Datenbank ab.
            </summary>
        <value>Die geschätzte logischen Datenbankgröße in Bytes.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseRowCountEstimate">
      <MemberSignature Language="C#" Value="public long DatabaseRowCountEstimate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DatabaseRowCountEstimate" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.KeyValueStoreReplicaStatus.DatabaseRowCountEstimate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseRowCountEstimate As Long" />
      <MemberSignature Language="F#" Value="member this.DatabaseRowCountEstimate : int64" Usage="System.Fabric.Query.KeyValueStoreReplicaStatus.DatabaseRowCountEstimate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, der geschätzten Anzahl von Zeilen in der zugrunde liegenden Datenbank ab.
            </summary>
        <value>Die geschätzte Anzahl von Zeilen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusDetails">
      <MemberSignature Language="C#" Value="public string StatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDetails" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.KeyValueStoreReplicaStatus.StatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.StatusDetails : string" Usage="System.Fabric.Query.KeyValueStoreReplicaStatus.StatusDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, die aktuelle Statusdetails, (sofern vorhanden) des Replikats.
            </summary>
        <value>Der Status.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>