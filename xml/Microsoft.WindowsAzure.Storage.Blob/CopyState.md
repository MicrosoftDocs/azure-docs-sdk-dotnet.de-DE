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
            <span data-ttu-id="9f059-101">Stellt die Attribute eines Kopiervorgangs dar.</span><span class="sxs-lookup"><span data-stu-id="9f059-101">Represents the attributes of a copy operation.</span></span>
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
            <span data-ttu-id="9f059-102">Ruft die Anzahl der Bytes im Vorgang bisher kopiert.</span><span class="sxs-lookup"><span data-stu-id="9f059-102">Gets the number of bytes copied in the operation so far.</span></span>
            </summary>
        <value><span data-ttu-id="9f059-103">Die Anzahl der Bytes im Vorgang bisher kopiert oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="9f059-103">The number of bytes copied in the operation so far, or <c>null</c>.</span></span></value>
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
            <span data-ttu-id="9f059-104">Ruft die Zeit ab, der Kopiervorgang abgeschlossen wurde, und gibt an, ob aufgrund eines erfolgreichen Kopiervorgangs, des Abbruchs des Vorgangs oder eines Fehlers war.</span><span class="sxs-lookup"><span data-stu-id="9f059-104">Gets the time the copy operation completed, and indicates whether completion was due to a successful copy, the cancelling of the operation, or a failure.</span></span>
            </summary>
        <value><span data-ttu-id="9f059-105">Ein <see cref="T:System.DateTimeOffset" /> , der die Abschlusszeit enthält oder <c>null</c> , wenn der Vorgang nicht abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="9f059-105">A <see cref="T:System.DateTimeOffset" /> containing the completion time, or <c>null</c> if the operation has not completed.</span></span></value>
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
            <span data-ttu-id="9f059-106">Ruft die ID des Vorgangs zum Kopieren ab.</span><span class="sxs-lookup"><span data-stu-id="9f059-106">Gets the ID of the copy operation.</span></span>
            </summary>
        <value><span data-ttu-id="9f059-107">Eine Kopie-ID-Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="9f059-107">A copy ID string.</span></span></value>
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
            <span data-ttu-id="9f059-108">Ruft die momentaufnahmezeit inkrementelle Ziel für die letzte inkrementelle Kopie ab, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9f059-108">Gets the incremental destination snapshot time for the latest incremental copy, if present.</span></span>
            </summary>
        <value><span data-ttu-id="9f059-109">Ein <see cref="T:System.DateTimeOffset" /> Zeit für die letzte inkrementelle Kopie mit dem Ziel snapshot oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="9f059-109">A <see cref="T:System.DateTimeOffset" /> containing the destination snapshot time for the latest incremental copy, or <c>null</c>.</span></span></value>
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
            <span data-ttu-id="9f059-110">Ruft den Quell-URI eines Kopiervorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="9f059-110">Gets the source URI of a copy operation.</span></span>
            </summary>
        <value><span data-ttu-id="9f059-111">Ein <see cref="T:System.Uri" /> , der die Quelle eines Kopiervorgangs angibt oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="9f059-111">A <see cref="T:System.Uri" /> indicating the source of a copy operation, or <c>null</c>.</span></span></value>
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
            <span data-ttu-id="9f059-112">Ruft den Status des Kopiervorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="9f059-112">Gets the status of the copy operation.</span></span>
            </summary>
        <value><span data-ttu-id="9f059-113">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CopyStatus" /> Enumeration, die den Status des Vorgangs angibt.</span><span class="sxs-lookup"><span data-stu-id="9f059-113">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CopyStatus" /> enumeration indicating the status of the operation.</span></span></value>
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
            <span data-ttu-id="9f059-114">Ruft die Beschreibung des aktuellen Status ab, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9f059-114">Gets the description of the current status, if any.</span></span>
            </summary>
        <value><span data-ttu-id="9f059-115">Eine statusbeschreibungszeichenfolge oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="9f059-115">A status description string, or <c>null</c>.</span></span></value>
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
            <span data-ttu-id="9f059-116">Ruft die Gesamtanzahl der Bytes in der Quelle der Kopie.</span><span class="sxs-lookup"><span data-stu-id="9f059-116">Gets the total number of bytes in the source of the copy.</span></span>
            </summary>
        <value><span data-ttu-id="9f059-117">Die Anzahl der Bytes in der Quelle oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="9f059-117">The number of bytes in the source, or <c>null</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>