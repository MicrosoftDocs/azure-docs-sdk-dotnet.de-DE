<Type Name="PartitionManagerOptions" FullName="Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions">
  <TypeSignature Language="C#" Value="public class PartitionManagerOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PartitionManagerOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class PartitionManagerOptions" />
  <TypeSignature Language="F#" Value="type PartitionManagerOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Optionen zum Steuern der verschiedene Aspekte der Partition Verteilung im <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" /> Instanz.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionManagerOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions.LeaseDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseDuration : TimeSpan with get, set" Usage="Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions.LeaseDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Intervall für die die Lease für Azure-Blob erstellt wird, eine Event Hub-Partition darstellt.  Wenn die Lease innerhalb dieses Zeitraums nicht erneuert wird, bewirkt ablaufen und den Besitz der Partition wird in einen anderen verschieben <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" /> Instanz.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewInterval">
      <MemberSignature Language="C#" Value="public TimeSpan RenewInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RenewInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions.RenewInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RenewInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RenewInterval : TimeSpan with get, set" Usage="Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions.RenewInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erneuerungsintervall für alle Leases für Partitionen, die derzeit von reservierten <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" /> Instanz.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>