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
            Das Context-Objekt verwendet, um den Zustand in den Stream erhalten bleiben.
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
        <param name="source">So kopieren Sie die vorhandene Prüfpunktdatei</param>
        <summary>
            Erstellt einen neuen Prüfpunkt aus einen vorhandenen Prüfpunkt.
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
        <param name="partitionId">Die Partitions-ID für den Prüfpunkt</param>
        <summary>
            Erstellt einen neuen Prüfpunkt für eine bestimmte Partition-ID.
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
        <param name="partitionId">Die Partitions-ID für den Prüfpunkt</param>
        <param name="offset">Verarbeitet der Offset für die letzte(n)<see cref="T:Microsoft.Azure.EventHubs.EventData" /></param>
        <param name="sequenceNumber">Die Sequenznummer der zuletzt verarbeitet<see cref="T:Microsoft.Azure.EventHubs.EventData" /></param>
        <summary>
            Erstellt einen neuen Prüfpunkt für einen bestimmten Partitions-ID, mit der Anzahl von Offset und die Sequenznummer.
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
            Ruft ab oder legt den Offset des letzten verarbeiteten <see cref="T:Microsoft.Azure.EventHubs.EventData" />.
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
            Ruft die Partitions-ID für den entsprechenden Prüfpunkt.
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
            Ruft ab oder legt die Sequenznummer der letzten verarbeiteten <see cref="T:Microsoft.Azure.EventHubs.EventData" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>