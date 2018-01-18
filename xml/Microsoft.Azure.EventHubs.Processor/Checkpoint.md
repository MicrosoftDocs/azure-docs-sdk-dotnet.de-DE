<Type Name="Checkpoint" FullName="Microsoft.Azure.EventHubs.Processor.Checkpoint">
  <TypeSignature Language="C#" Value="public class Checkpoint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Checkpoint extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.Checkpoint" />
  <TypeSignature Language="VB.NET" Value="Public Class Checkpoint" />
  <TypeSignature Language="F#" Value="type Checkpoint = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5fb1d-101">Das Context-Objekt verwendet, um den Zustand in den Stream erhalten bleiben.</span><span class="sxs-lookup"><span data-stu-id="5fb1d-101">The context object used to preserve state in the stream.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Checkpoint (Microsoft.Azure.EventHubs.Processor.Checkpoint source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.EventHubs.Processor.Checkpoint source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.Checkpoint.#ctor(Microsoft.Azure.EventHubs.Processor.Checkpoint)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (source As Checkpoint)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.Checkpoint : Microsoft.Azure.EventHubs.Processor.Checkpoint -&gt; Microsoft.Azure.EventHubs.Processor.Checkpoint" Usage="new Microsoft.Azure.EventHubs.Processor.Checkpoint source" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.EventHubs.Processor.Checkpoint" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="5fb1d-102">So kopieren Sie die vorhandene Prüfpunktdatei</span><span class="sxs-lookup"><span data-stu-id="5fb1d-102">The existing checkpoint to copy</span></span></param>
        <summary>
            <span data-ttu-id="5fb1d-103">Erstellt einen neuen Prüfpunkt aus einen vorhandenen Prüfpunkt.</span><span class="sxs-lookup"><span data-stu-id="5fb1d-103">Creates a new Checkpoint from an existing checkpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Checkpoint (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.Checkpoint.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.Checkpoint : string -&gt; Microsoft.Azure.EventHubs.Processor.Checkpoint" Usage="new Microsoft.Azure.EventHubs.Processor.Checkpoint partitionId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="5fb1d-104">Die Partitions-ID für den Prüfpunkt</span><span class="sxs-lookup"><span data-stu-id="5fb1d-104">The partition ID for the checkpoint</span></span></param>
        <summary>
            <span data-ttu-id="5fb1d-105">Erstellt einen neuen Prüfpunkt für eine bestimmte Partition-ID.</span><span class="sxs-lookup"><span data-stu-id="5fb1d-105">Creates a new Checkpoint for a particular partition ID.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Checkpoint (string partitionId, string offset, long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionId, string offset, int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.Checkpoint.#ctor(System.String,System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionId As String, offset As String, sequenceNumber As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.Checkpoint : string * string * int64 -&gt; Microsoft.Azure.EventHubs.Processor.Checkpoint" Usage="new Microsoft.Azure.EventHubs.Processor.Checkpoint (partitionId, offset, sequenceNumber)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="offset" Type="System.String" />
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="5fb1d-106">Die Partitions-ID für den Prüfpunkt</span><span class="sxs-lookup"><span data-stu-id="5fb1d-106">The partition ID for the checkpoint</span></span></param>
        <param name="offset"><span data-ttu-id="5fb1d-107">Verarbeitet der Offset für die letzte(n)<see cref="T:Microsoft.Azure.EventHubs.EventData" /></span><span class="sxs-lookup"><span data-stu-id="5fb1d-107">The offset for the last processed <see cref="T:Microsoft.Azure.EventHubs.EventData" /></span></span></param>
        <param name="sequenceNumber"><span data-ttu-id="5fb1d-108">Die Sequenznummer der zuletzt verarbeitet<see cref="T:Microsoft.Azure.EventHubs.EventData" /></span><span class="sxs-lookup"><span data-stu-id="5fb1d-108">The sequence number of the last processed <see cref="T:Microsoft.Azure.EventHubs.EventData" /></span></span></param>
        <summary>
            <span data-ttu-id="5fb1d-109">Erstellt einen neuen Prüfpunkt für einen bestimmten Partitions-ID, mit der Anzahl von Offset und die Sequenznummer.</span><span class="sxs-lookup"><span data-stu-id="5fb1d-109">Creates a new Checkpoint for a particular partition ID, with the offset and sequence number.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offset">
      <MemberSignature Language="C#" Value="public string Offset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.Checkpoint.Offset" />
      <MemberSignature Language="VB.NET" Value="Public Property Offset As String" />
      <MemberSignature Language="F#" Value="member this.Offset : string with get, set" Usage="Microsoft.Azure.EventHubs.Processor.Checkpoint.Offset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fb1d-110">Ruft ab oder legt den Offset des letzten verarbeiteten <see cref="T:Microsoft.Azure.EventHubs.EventData" />.</span><span class="sxs-lookup"><span data-stu-id="5fb1d-110">Gets or sets the offset of the last processed <see cref="T:Microsoft.Azure.EventHubs.EventData" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.Checkpoint.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.Azure.EventHubs.Processor.Checkpoint.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fb1d-111">Ruft die Partitions-ID für den entsprechenden Prüfpunkt.</span><span class="sxs-lookup"><span data-stu-id="5fb1d-111">Gets the partition ID for the corresponding checkpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.Checkpoint.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64 with get, set" Usage="Microsoft.Azure.EventHubs.Processor.Checkpoint.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fb1d-112">Ruft ab oder legt die Sequenznummer der letzten verarbeiteten <see cref="T:Microsoft.Azure.EventHubs.EventData" />.</span><span class="sxs-lookup"><span data-stu-id="5fb1d-112">Gets or sets the sequence number of the last processed <see cref="T:Microsoft.Azure.EventHubs.EventData" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>