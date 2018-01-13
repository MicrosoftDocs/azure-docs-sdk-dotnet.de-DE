<Type Name="ResourceStatistics" FullName="Microsoft.Azure.Batch.ResourceStatistics">
  <TypeSignature Language="C#" Value="public class ResourceStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ResourceStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceStatistics" />
  <TypeSignature Language="F#" Value="type ResourceStatistics = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Ressource statistische Daten für den Pool.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AverageCpuPercentage">
      <MemberSignature Language="C#" Value="public double AverageCpuPercentage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 AverageCpuPercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.AverageCpuPercentage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AverageCpuPercentage As Double" />
      <MemberSignature Language="F#" Value="member this.AverageCpuPercentage : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.AverageCpuPercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die durchschnittliche CPU-Nutzung auf allen Serverknoten im Pool (in Prozent pro Serverknoten) abgerufen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageDiskGiB">
      <MemberSignature Language="C#" Value="public double AverageDiskGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 AverageDiskGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.AverageDiskGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AverageDiskGiB As Double" />
      <MemberSignature Language="F#" Value="member this.AverageDiskGiB : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.AverageDiskGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die durchschnittliche verwendete Speicherplatz im Gibibytes auf allen Serverknoten im Pool abgerufen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageMemoryGiB">
      <MemberSignature Language="C#" Value="public double AverageMemoryGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 AverageMemoryGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.AverageMemoryGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AverageMemoryGiB As Double" />
      <MemberSignature Language="F#" Value="member this.AverageMemoryGiB : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.AverageMemoryGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die durchschnittliche speicherauslastung in Gibibytes auf allen Serverknoten im Pool abgerufen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskReadGiB">
      <MemberSignature Language="C#" Value="public double DiskReadGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DiskReadGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.DiskReadGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiskReadGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DiskReadGiB : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.DiskReadGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Gesamtmenge der Daten in Gibibytes der Lesevorgänge vom Datenträger in allen Computeknoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskReadIOps">
      <MemberSignature Language="C#" Value="public long DiskReadIOps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DiskReadIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.DiskReadIOps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiskReadIOps As Long" />
      <MemberSignature Language="F#" Value="member this.DiskReadIOps : int64" Usage="Microsoft.Azure.Batch.ResourceStatistics.DiskReadIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Gesamtzahl der Datenträgerlesevorgänge über alle Serverknoten im Pool ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskWriteGiB">
      <MemberSignature Language="C#" Value="public double DiskWriteGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DiskWriteGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.DiskWriteGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiskWriteGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DiskWriteGiB : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.DiskWriteGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Gesamtmenge der Daten in Gibibytes Schreibvorgänge auf dem Datenträger auf allen Serverknoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskWriteIOps">
      <MemberSignature Language="C#" Value="public long DiskWriteIOps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DiskWriteIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.DiskWriteIOps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiskWriteIOps As Long" />
      <MemberSignature Language="F#" Value="member this.DiskWriteIOps : int64" Usage="Microsoft.Azure.Batch.ResourceStatistics.DiskWriteIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Gesamtanzahl der Schreibvorgänge auf Datenträger auf allen Serverknoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime" Usage="Microsoft.Azure.Batch.ResourceStatistics.LastUpdateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitpunkt, an dem die Statistik zuletzt aktualisiert wurden. Alle Statistiken sind beschränkt auf den Bereich zwischen <see cref="P:Microsoft.Azure.Batch.ResourceStatistics.StartTime" /> und diesen Wert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkReadGiB">
      <MemberSignature Language="C#" Value="public double NetworkReadGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 NetworkReadGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.NetworkReadGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkReadGiB As Double" />
      <MemberSignature Language="F#" Value="member this.NetworkReadGiB : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.NetworkReadGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Gesamtmenge der Daten in Gibibytes der Netzwerklesevorgänge über alle Serverknoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkWriteGiB">
      <MemberSignature Language="C#" Value="public double NetworkWriteGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 NetworkWriteGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.NetworkWriteGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkWriteGiB As Double" />
      <MemberSignature Language="F#" Value="member this.NetworkWriteGiB : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.NetworkWriteGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Gesamtmenge der Daten in der Netzwerkschreibvorgängen Gibibytes über alle Serverknoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeakDiskGiB">
      <MemberSignature Language="C#" Value="public double PeakDiskGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 PeakDiskGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.PeakDiskGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PeakDiskGiB As Double" />
      <MemberSignature Language="F#" Value="member this.PeakDiskGiB : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.PeakDiskGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Peak verwendet Speicherplatz im Gibibytes über alle Serverknoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeakMemoryGiB">
      <MemberSignature Language="C#" Value="public double PeakMemoryGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 PeakMemoryGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.PeakMemoryGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PeakMemoryGiB As Double" />
      <MemberSignature Language="F#" Value="member this.PeakMemoryGiB : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.PeakMemoryGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Speicherverwendung im Gibibytes über alle Serverknoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.ResourceStatistics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Startzeit des Zeitraums, der von den Statistiken abgedeckt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>