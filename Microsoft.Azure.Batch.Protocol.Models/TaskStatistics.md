<Type Name="TaskStatistics" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskStatistics">
  <TypeSignature Language="C#" Value="public class TaskStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskStatistics" />
  <TypeSignature Language="F#" Value="type TaskStatistics = class" />
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
            Statistiken zum Ressourceneinsatz während eines Vorgangs.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskStatistics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.#ctor" />
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
            Initialisiert eine neue Instanz der TaskStatistics-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskStatistics (string url, DateTime startTime, DateTime lastUpdateTime, TimeSpan userCPUTime, TimeSpan kernelCPUTime, TimeSpan wallClockTime, long readIOps, long writeIOps, double readIOGiB, double writeIOGiB, TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string url, valuetype System.DateTime startTime, valuetype System.DateTime lastUpdateTime, valuetype System.TimeSpan userCPUTime, valuetype System.TimeSpan kernelCPUTime, valuetype System.TimeSpan wallClockTime, int64 readIOps, int64 writeIOps, float64 readIOGiB, float64 writeIOGiB, valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.#ctor(System.String,System.DateTime,System.DateTime,System.TimeSpan,System.TimeSpan,System.TimeSpan,System.Int64,System.Int64,System.Double,System.Double,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As String, startTime As DateTime, lastUpdateTime As DateTime, userCPUTime As TimeSpan, kernelCPUTime As TimeSpan, wallClockTime As TimeSpan, readIOps As Long, writeIOps As Long, readIOGiB As Double, writeIOGiB As Double, waitTime As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskStatistics : string * DateTime * DateTime * TimeSpan * TimeSpan * TimeSpan * int64 * int64 * double * double * TimeSpan -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskStatistics" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskStatistics (url, startTime, lastUpdateTime, userCPUTime, kernelCPUTime, wallClockTime, readIOps, writeIOps, readIOGiB, writeIOGiB, waitTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="lastUpdateTime" Type="System.DateTime" />
        <Parameter Name="userCPUTime" Type="System.TimeSpan" />
        <Parameter Name="kernelCPUTime" Type="System.TimeSpan" />
        <Parameter Name="wallClockTime" Type="System.TimeSpan" />
        <Parameter Name="readIOps" Type="System.Int64" />
        <Parameter Name="writeIOps" Type="System.Int64" />
        <Parameter Name="readIOGiB" Type="System.Double" />
        <Parameter Name="writeIOGiB" Type="System.Double" />
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="url">Die URL der Statistik.</param>
        <param name="startTime">Die Startzeit des Zeitraums, der von den Statistiken abgedeckt.</param>
        <param name="lastUpdateTime">Der Zeitpunkt, an dem die Statistik zuletzt aktualisiert wurden. Alle Statistiken sind beschränkt auf den Bereich zwischen StartTime und LastUpdateTime.</param>
        <param name="userCPUTime">Die Gesamtzeit Modus CPU-Zeit (addierten auf alle Kerne und alle Serverknoten) vom Task verwendet.</param>
        <param name="kernelCPUTime">Die insgesamt Kernel-Modus CPU-Zeit (addierten auf alle Kerne und alle Serverknoten) vom Task verwendet.</param>
        <param name="wallClockTime">Die gesamtbetrachtungszeit des Vorgangs.</param>
        <param name="readIOps">Von der Aufgabe die Gesamtanzahl der Datenträger-Lesevorgänge.</param>
        <param name="writeIOps">Die Gesamtanzahl der Datenträger-Schreibvorgänge, die von der Aufgabe vorgenommen.</param>
        <param name="readIOGiB">Insgesamt Gibibytes, die von der Aufgabe vom Datenträger gelesen werden.</param>
        <param name="writeIOGiB">Die insgesamt Gibibytes, die von der Aufgabe auf den Datenträger geschrieben wird.</param>
        <param name="waitTime">Die gesamte Wartezeit der Aufgabe. Die Wartezeit für eine Aufgabe wird als die Zeitspanne zwischen dem Erstellen der Aufgabe und dem Start der Ausführung der Aufgabe definiert. (Wenn die Aufgabe aufgrund von Fehlern wiederholt wird, ist die Wartezeit der Zeit der letzten Ausführung der Aufgabe.)</param>
        <summary>
            Initialisiert eine neue Instanz der TaskStatistics-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KernelCPUTime">
      <MemberSignature Language="C#" Value="public TimeSpan KernelCPUTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan KernelCPUTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.KernelCPUTime" />
      <MemberSignature Language="VB.NET" Value="Public Property KernelCPUTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KernelCPUTime : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.KernelCPUTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kernelCPUTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den insgesamt Kernel-Modus CPU-Zeit (addierten auf alle Kerne und alle Serverknoten) vom Task verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.LastUpdateTime" />
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
    <Member MemberName="ReadIOGiB">
      <MemberSignature Language="C#" Value="public double ReadIOGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 ReadIOGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.ReadIOGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadIOGiB As Double" />
      <MemberSignature Language="F#" Value="member this.ReadIOGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.ReadIOGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="readIOGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die von der Aufgabe vom Datenträger gelesenen insgesamt Gibibytes.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadIOps">
      <MemberSignature Language="C#" Value="public long ReadIOps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReadIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.ReadIOps" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadIOps As Long" />
      <MemberSignature Language="F#" Value="member this.ReadIOps : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.ReadIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="readIOps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Gesamtanzahl der Datenträger-Lesevorgänge, die von der Aufgabe.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.StartTime" />
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
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die URL der Statistik.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserCPUTime">
      <MemberSignature Language="C#" Value="public TimeSpan UserCPUTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UserCPUTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.UserCPUTime" />
      <MemberSignature Language="VB.NET" Value="Public Property UserCPUTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UserCPUTime : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.UserCPUTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userCPUTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Gesamtzeit Modus CPU-Zeit (addierten auf alle Kerne und alle Serverknoten) vom Task verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskStatistics.Validate " />
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
    <Member MemberName="WaitTime">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.WaitTime" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTime : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.WaitTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="waitTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die gesamte Wartezeit der Aufgabe. Die Wartezeit für eine Aufgabe wird als die Zeitspanne zwischen dem Erstellen der Aufgabe und dem Start der Ausführung der Aufgabe definiert. (Wenn die Aufgabe aufgrund von Fehlern wiederholt wird, ist die Wartezeit der Zeit der letzten Ausführung der Aufgabe.)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WallClockTime">
      <MemberSignature Language="C#" Value="public TimeSpan WallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.WallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property WallClockTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WallClockTime : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.WallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="wallClockTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die gesamtbetrachtungszeit des Vorgangs.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die gesamtbetrachtungszeit wird von den Beginn des Tasks ausführen auf einem Serverknoten, wenn er abgeschlossen verstrichene Zeit (oder zum Zeitpunkt letzten Statistiken wurden aktualisiert, wenn die Aufgabe wurde nicht abgeschlossen war).
            Wenn der Vorgang wiederholt wurde, schließt dies die gesamtbetrachtungszeit alle Wiederholungen der Aufgabe.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteIOGiB">
      <MemberSignature Language="C#" Value="public double WriteIOGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 WriteIOGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.WriteIOGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteIOGiB As Double" />
      <MemberSignature Language="F#" Value="member this.WriteIOGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.WriteIOGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="writeIOGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der insgesamt Gibibytes, die von der Aufgabe auf den Datenträger geschrieben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteIOps">
      <MemberSignature Language="C#" Value="public long WriteIOps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 WriteIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.WriteIOps" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteIOps As Long" />
      <MemberSignature Language="F#" Value="member this.WriteIOps : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskStatistics.WriteIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="writeIOps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Gesamtanzahl der Datenträger-Schreibvorgänge, die von der Aufgabe vorgenommen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>