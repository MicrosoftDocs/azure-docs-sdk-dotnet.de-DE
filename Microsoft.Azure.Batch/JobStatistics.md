<Type Name="JobStatistics" FullName="Microsoft.Azure.Batch.JobStatistics">
  <TypeSignature Language="C#" Value="public class JobStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class JobStatistics" />
  <TypeSignature Language="F#" Value="type JobStatistics = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Statistiken zum Ressourceneinsatz während des Auftrags.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FailedTaskCount">
      <MemberSignature Language="C#" Value="public long FailedTaskCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 FailedTaskCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.FailedTaskCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailedTaskCount As Long" />
      <MemberSignature Language="F#" Value="member this.FailedTaskCount : int64" Usage="Microsoft.Azure.Batch.JobStatistics.FailedTaskCount" />
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
            Ruft die Gesamtanzahl der Taskfehler im Auftrag.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KernelCpuTime">
      <MemberSignature Language="C#" Value="public TimeSpan KernelCpuTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan KernelCpuTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.KernelCpuTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KernelCpuTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KernelCpuTime : TimeSpan" Usage="Microsoft.Azure.Batch.JobStatistics.KernelCpuTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die gesamten Kernel CPU-Zeit im (pro Kern) aller Aufgaben im Auftrag ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime" Usage="Microsoft.Azure.Batch.JobStatistics.LastUpdateTime" />
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
            Ruft den Zeitpunkt, an dem die Statistik zuletzt aktualisiert wurden. Alle Statistiken sind beschränkt auf den Bereich zwischen <see cref="P:Microsoft.Azure.Batch.JobStatistics.StartTime" /> und diesen Wert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadIOGiB">
      <MemberSignature Language="C#" Value="public double ReadIOGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 ReadIOGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.ReadIOGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadIOGiB As Double" />
      <MemberSignature Language="F#" Value="member this.ReadIOGiB : double" Usage="Microsoft.Azure.Batch.JobStatistics.ReadIOGiB" />
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
            Ruft die gesamte Gibibytes e/a-Lesevorgängen aller Aufgaben im Auftrag vom Datenträger ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadIOps">
      <MemberSignature Language="C#" Value="public long ReadIOps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReadIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.ReadIOps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadIOps As Long" />
      <MemberSignature Language="F#" Value="member this.ReadIOps : int64" Usage="Microsoft.Azure.Batch.JobStatistics.ReadIOps" />
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
            Ruft die Gesamtanzahl der Datenträger-Lesevorgänge aller Aufgaben im Auftrag ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.JobStatistics.StartTime" />
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
    <Member MemberName="SucceededTaskCount">
      <MemberSignature Language="C#" Value="public long SucceededTaskCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SucceededTaskCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.SucceededTaskCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SucceededTaskCount As Long" />
      <MemberSignature Language="F#" Value="member this.SucceededTaskCount : int64" Usage="Microsoft.Azure.Batch.JobStatistics.SucceededTaskCount" />
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
            Ruft die Gesamtzahl der Aufgaben im Auftrag während des angegebenen Zeitraums erfolgreich abgeschlossen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskRetryCount">
      <MemberSignature Language="C#" Value="public long TaskRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.TaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskRetryCount As Long" />
      <MemberSignature Language="F#" Value="member this.TaskRetryCount : int64" Usage="Microsoft.Azure.Batch.JobStatistics.TaskRetryCount" />
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
            Ruft die Gesamtanzahl der Wiederholungen Aufgabe im Auftrag.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.JobStatistics.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die URL der der Auftragsstatistik ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserCpuTime">
      <MemberSignature Language="C#" Value="public TimeSpan UserCpuTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UserCpuTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.UserCpuTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserCpuTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UserCpuTime : TimeSpan" Usage="Microsoft.Azure.Batch.JobStatistics.UserCpuTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Gesamtzeit CPU-Zeit im (pro Kern) aller Aufgaben im Auftrag ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitTime">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.WaitTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WaitTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTime : TimeSpan" Usage="Microsoft.Azure.Batch.JobStatistics.WaitTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Gesamtwartezeit für alle Aufgaben im Auftrag. Die Wartezeit für eine Aufgabe wird als die Zeitspanne zwischen dem Erstellen der Aufgabe und dem Start der Ausführung der Aufgabe definiert. (Wenn die Aufgabe aufgrund von Fehlern wiederholt wird, ist die Wartezeit der Zeit der letzten Ausführung der Aufgabe.)
            </summary>
        <value>To be added.</value>
        <remarks>
            Dieser Wert wird nur in der lebensdauerstatistiken Konto gemeldet.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WallClockTime">
      <MemberSignature Language="C#" Value="public TimeSpan WallClockTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.WallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WallClockTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WallClockTime : TimeSpan" Usage="Microsoft.Azure.Batch.JobStatistics.WallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die gesamte verstrichene Zeit ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteIOGiB">
      <MemberSignature Language="C#" Value="public double WriteIOGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 WriteIOGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.WriteIOGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteIOGiB As Double" />
      <MemberSignature Language="F#" Value="member this.WriteIOGiB : double" Usage="Microsoft.Azure.Batch.JobStatistics.WriteIOGiB" />
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
            Ruft die gesamte Gibibytes e/a durch alle Aufgaben im Auftrag auf den Datenträger geschrieben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteIOps">
      <MemberSignature Language="C#" Value="public long WriteIOps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 WriteIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.WriteIOps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteIOps As Long" />
      <MemberSignature Language="F#" Value="member this.WriteIOps : int64" Usage="Microsoft.Azure.Batch.JobStatistics.WriteIOps" />
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
            Ruft die Gesamtzahl der Schreibvorgänge auf Datenträger durch alle Aufgaben im Auftrag vorgenommen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>