<Type Name="ResourceStatistics" FullName="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics">
  <TypeSignature Language="C#" Value="public class ResourceStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceStatistics" />
  <TypeSignature Language="F#" Value="type ResourceStatistics = class" />
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
            Statistiken in Bezug auf die ressourcenbelegung durch Serverknoten in einem Pool an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceStatistics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ResourceStatistics-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceStatistics (DateTime startTime, DateTime lastUpdateTime, double avgCPUPercentage, double avgMemoryGiB, double peakMemoryGiB, double avgDiskGiB, double peakDiskGiB, long diskReadIOps, long diskWriteIOps, double diskReadGiB, double diskWriteGiB, double networkReadGiB, double networkWriteGiB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime startTime, valuetype System.DateTime lastUpdateTime, float64 avgCPUPercentage, float64 avgMemoryGiB, float64 peakMemoryGiB, float64 avgDiskGiB, float64 peakDiskGiB, int64 diskReadIOps, int64 diskWriteIOps, float64 diskReadGiB, float64 diskWriteGiB, float64 networkReadGiB, float64 networkWriteGiB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.#ctor(System.DateTime,System.DateTime,System.Double,System.Double,System.Double,System.Double,System.Double,System.Int64,System.Int64,System.Double,System.Double,System.Double,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startTime As DateTime, lastUpdateTime As DateTime, avgCPUPercentage As Double, avgMemoryGiB As Double, peakMemoryGiB As Double, avgDiskGiB As Double, peakDiskGiB As Double, diskReadIOps As Long, diskWriteIOps As Long, diskReadGiB As Double, diskWriteGiB As Double, networkReadGiB As Double, networkWriteGiB As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics : DateTime * DateTime * double * double * double * double * double * int64 * int64 * double * double * double * double -&gt; Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics" Usage="new Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics (startTime, lastUpdateTime, avgCPUPercentage, avgMemoryGiB, peakMemoryGiB, avgDiskGiB, peakDiskGiB, diskReadIOps, diskWriteIOps, diskReadGiB, diskWriteGiB, networkReadGiB, networkWriteGiB)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="lastUpdateTime" Type="System.DateTime" />
        <Parameter Name="avgCPUPercentage" Type="System.Double" />
        <Parameter Name="avgMemoryGiB" Type="System.Double" />
        <Parameter Name="peakMemoryGiB" Type="System.Double" />
        <Parameter Name="avgDiskGiB" Type="System.Double" />
        <Parameter Name="peakDiskGiB" Type="System.Double" />
        <Parameter Name="diskReadIOps" Type="System.Int64" />
        <Parameter Name="diskWriteIOps" Type="System.Int64" />
        <Parameter Name="diskReadGiB" Type="System.Double" />
        <Parameter Name="diskWriteGiB" Type="System.Double" />
        <Parameter Name="networkReadGiB" Type="System.Double" />
        <Parameter Name="networkWriteGiB" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="startTime">Die Startzeit des Zeitraums, der von den Statistiken abgedeckt.</param>
        <param name="lastUpdateTime">Der Zeitpunkt, an dem die Statistik zuletzt aktualisiert wurden. Alle Statistiken sind beschränkt auf den Bereich zwischen StartTime und LastUpdateTime.</param>
        <param name="avgCPUPercentage">Die durchschnittliche CPU-Nutzung auf allen Knoten im Pool (in Prozent pro Knoten).</param>
        <param name="avgMemoryGiB">Die durchschnittliche speicherauslastung in gib betragen auf allen Knoten im Pool.</param>
        <param name="peakMemoryGiB">Die größte speicherauslastung in gib betragen über alle Knoten im Pool.</param>
        <param name="avgDiskGiB">Die durchschnittliche verwendeter Speicherplatz in gib betragen auf allen Knoten im Pool.</param>
        <param name="peakDiskGiB">Die Bedarfsspitzen für das verwendete Speicherplatz in gib betragen auf allen Knoten im Pool.</param>
        <param name="diskReadIOps">Die Gesamtanzahl der Datenträger-Lesevorgänge in allen Knoten im Pool.</param>
        <param name="diskWriteIOps">Die Gesamtanzahl der Datenträger-Schreibvorgänge in allen Knoten im Pool.</param>
        <param name="diskReadGiB">Die Gesamtmenge der Daten in gib betragen des Datenträgers liest in allen Knoten im Pool.</param>
        <param name="diskWriteGiB">Die Gesamtmenge der Daten in gib betragen des Datenträgers schreibt in allen Knoten im Pool.</param>
        <param name="networkReadGiB">Die Gesamtmenge der Daten in gib betragen, des Netzwerks liest in allen Knoten im Pool.</param>
        <param name="networkWriteGiB">Die Gesamtmenge der Daten in gib betragen, des Netzwerks schreibt in allen Knoten im Pool.</param>
        <summary>
            Initialisiert eine neue Instanz der ResourceStatistics-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvgCPUPercentage">
      <MemberSignature Language="C#" Value="public double AvgCPUPercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 AvgCPUPercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.AvgCPUPercentage" />
      <MemberSignature Language="VB.NET" Value="Public Property AvgCPUPercentage As Double" />
      <MemberSignature Language="F#" Value="member this.AvgCPUPercentage : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.AvgCPUPercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="avgCPUPercentage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die durchschnittliche CPU-Nutzung auf allen Knoten im Pool (in Prozent pro Knoten).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvgDiskGiB">
      <MemberSignature Language="C#" Value="public double AvgDiskGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 AvgDiskGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.AvgDiskGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property AvgDiskGiB As Double" />
      <MemberSignature Language="F#" Value="member this.AvgDiskGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.AvgDiskGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="avgDiskGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt fest durchschnittliche verwendete Speicherplatz in gib betragen in allen Knoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvgMemoryGiB">
      <MemberSignature Language="C#" Value="public double AvgMemoryGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 AvgMemoryGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.AvgMemoryGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property AvgMemoryGiB As Double" />
      <MemberSignature Language="F#" Value="member this.AvgMemoryGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.AvgMemoryGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="avgMemoryGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Im abruft oder festlegt durchschnittlichen arbeitsspeichernutzung gib betragen auf allen Knoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskReadGiB">
      <MemberSignature Language="C#" Value="public double DiskReadGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DiskReadGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.DiskReadGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskReadGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DiskReadGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.DiskReadGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskReadGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Gesamtmenge der Daten in gib betragen, der Lesevorgänge vom Datenträger in allen Knoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskReadIOps">
      <MemberSignature Language="C#" Value="public long DiskReadIOps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DiskReadIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.DiskReadIOps" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskReadIOps As Long" />
      <MemberSignature Language="F#" Value="member this.DiskReadIOps : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.DiskReadIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskReadIOps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Gesamtzahl der Datenträgerlesevorgänge über alle Knoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskWriteGiB">
      <MemberSignature Language="C#" Value="public double DiskWriteGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DiskWriteGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.DiskWriteGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskWriteGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DiskWriteGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.DiskWriteGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskWriteGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Gesamtmenge der Daten in gib betragen Schreibvorgänge auf dem Datenträger in allen Knoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskWriteIOps">
      <MemberSignature Language="C#" Value="public long DiskWriteIOps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DiskWriteIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.DiskWriteIOps" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskWriteIOps As Long" />
      <MemberSignature Language="F#" Value="member this.DiskWriteIOps : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.DiskWriteIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskWriteIOps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Gesamtanzahl der Datenträger-Schreibvorgänge in allen Knoten im Pool fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.LastUpdateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastUpdateTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit, an der die Statistik zuletzt aktualisiert wurden.
            Alle Statistiken sind beschränkt auf den Bereich zwischen StartTime und LastUpdateTime.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkReadGiB">
      <MemberSignature Language="C#" Value="public double NetworkReadGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 NetworkReadGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.NetworkReadGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkReadGiB As Double" />
      <MemberSignature Language="F#" Value="member this.NetworkReadGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.NetworkReadGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkReadGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Gesamtmenge der Daten in gib betragen der Netzwerklesevorgänge in allen Knoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkWriteGiB">
      <MemberSignature Language="C#" Value="public double NetworkWriteGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 NetworkWriteGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.NetworkWriteGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkWriteGiB As Double" />
      <MemberSignature Language="F#" Value="member this.NetworkWriteGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.NetworkWriteGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkWriteGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Gesamtmenge der Daten in gib betragen von Netzwerkschreibvorgängen in allen Knoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeakDiskGiB">
      <MemberSignature Language="C#" Value="public double PeakDiskGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 PeakDiskGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.PeakDiskGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property PeakDiskGiB As Double" />
      <MemberSignature Language="F#" Value="member this.PeakDiskGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.PeakDiskGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="peakDiskGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Im abruft oder festlegt den Peak verwendet Speicherplatz gib betragen auf allen Knoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeakMemoryGiB">
      <MemberSignature Language="C#" Value="public double PeakMemoryGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 PeakMemoryGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.PeakMemoryGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property PeakMemoryGiB As Double" />
      <MemberSignature Language="F#" Value="member this.PeakMemoryGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.PeakMemoryGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="peakMemoryGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt fest spitzenauslastung des Arbeitsspeichers in gib betragen in allen Knoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Startzeit des Zeitraums, der von den Statistiken abgedeckt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceStatistics.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>