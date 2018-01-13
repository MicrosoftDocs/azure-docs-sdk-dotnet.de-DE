<Type Name="CopyState" FullName="Microsoft.WindowsAzure.Storage.Blob.CopyState">
  <TypeSignature Language="C#" Value="public sealed class CopyState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CopyState extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.CopyState" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CopyState" />
  <TypeSignature Language="F#" Value="type CopyState = class" />
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
            Stellt die Attribute eines Kopiervorgangs dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CopyState ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CopyState.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BytesCopied">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; BytesCopied { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; BytesCopied" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CopyState.BytesCopied" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BytesCopied As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.BytesCopied : Nullable&lt;int64&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.CopyState.BytesCopied" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Bytes im Vorgang bisher kopiert.
            </summary>
        <value>Die Anzahl der Bytes im Vorgang bisher kopiert oder <c>null</c>.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompletionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; CompletionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; CompletionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CopyState.CompletionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CompletionTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.CompletionTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.CopyState.CompletionTime" />
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
            Ruft die Zeit ab, der Kopiervorgang abgeschlossen wurde, und gibt an, ob aufgrund eines erfolgreichen Kopiervorgangs, des Abbruchs des Vorgangs oder eines Fehlers war.
            </summary>
        <value>Ein <see cref="T:System.DateTimeOffset" /> , der die Abschlusszeit enthält oder <c>null</c> , wenn der Vorgang nicht abgeschlossen wurde.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyId">
      <MemberSignature Language="C#" Value="public string CopyId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CopyId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CopyState.CopyId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CopyId As String" />
      <MemberSignature Language="F#" Value="member this.CopyId : string" Usage="Microsoft.WindowsAzure.Storage.Blob.CopyState.CopyId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die ID des Vorgangs zum Kopieren ab.
            </summary>
        <value>Eine Kopie-ID-Zeichenfolge.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationSnapshotTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; DestinationSnapshotTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; DestinationSnapshotTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CopyState.DestinationSnapshotTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DestinationSnapshotTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.DestinationSnapshotTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.CopyState.DestinationSnapshotTime" />
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
            Ruft die momentaufnahmezeit inkrementelle Ziel für die letzte inkrementelle Kopie ab, falls vorhanden.
            </summary>
        <value>Ein <see cref="T:System.DateTimeOffset" /> Zeit für die letzte inkrementelle Kopie mit dem Ziel snapshot oder <c>null</c>.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public Uri Source { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CopyState.Source" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Source As Uri" />
      <MemberSignature Language="F#" Value="member this.Source : Uri" Usage="Microsoft.WindowsAzure.Storage.Blob.CopyState.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Quell-URI eines Kopiervorgangs ab.
            </summary>
        <value>Ein <see cref="T:System.Uri" /> , der die Quelle eines Kopiervorgangs angibt oder <c>null</c>.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CopyStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.CopyStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CopyState.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As CopyStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.WindowsAzure.Storage.Blob.CopyStatus" Usage="Microsoft.WindowsAzure.Storage.Blob.CopyState.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CopyStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status des Kopiervorgangs ab.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CopyStatus" /> Enumeration, die den Status des Vorgangs angibt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusDescription">
      <MemberSignature Language="C#" Value="public string StatusDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CopyState.StatusDescription" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusDescription As String" />
      <MemberSignature Language="F#" Value="member this.StatusDescription : string" Usage="Microsoft.WindowsAzure.Storage.Blob.CopyState.StatusDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Beschreibung des aktuellen Status ab, sofern vorhanden.
            </summary>
        <value>Eine statusbeschreibungszeichenfolge oder <c>null</c>.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; TotalBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; TotalBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CopyState.TotalBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.TotalBytes : Nullable&lt;int64&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.CopyState.TotalBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Gesamtanzahl der Bytes in der Quelle der Kopie.
            </summary>
        <value>Die Anzahl der Bytes in der Quelle oder <c>null</c>.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>