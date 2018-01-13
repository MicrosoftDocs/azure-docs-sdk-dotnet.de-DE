<Type Name="GeoReplicationStats" FullName="Microsoft.WindowsAzure.Storage.Shared.Protocol.GeoReplicationStats">
  <TypeSignature Language="C#" Value="public sealed class GeoReplicationStats" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit GeoReplicationStats extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.GeoReplicationStats" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class GeoReplicationStats" />
  <TypeSignature Language="F#" Value="type GeoReplicationStats = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die georeplikationsstatistiken darstellende Klasse.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="LastSyncTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; LastSyncTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; LastSyncTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.GeoReplicationStats.LastSyncTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastSyncTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.LastSyncTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.GeoReplicationStats.LastSyncTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Uhrzeit der letzten Synchronisierung.
            </summary>
        <value>Die letzte Synchronisierungszeit.</value>
        <remarks>Alle primären Schreibvorgänge, die vorhergehenden dieser Wert sind garantiert für Lesevorgänge verfügbar. Primäre Schreibvorgänge, die Zeit nach diesem Zeitpunkt möglicherweise nicht oder nicht komplett verfügbar für Lesevorgänge.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Shared.Protocol.GeoReplicationStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.GeoReplicationStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.GeoReplicationStats.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As GeoReplicationStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.WindowsAzure.Storage.Shared.Protocol.GeoReplicationStatus" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.GeoReplicationStats.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.GeoReplicationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Status der geografischen Replikation fest.
            </summary>
        <value>Der Status der geografischen Replikation.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>