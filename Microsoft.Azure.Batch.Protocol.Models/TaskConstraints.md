<Type Name="TaskConstraints" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints">
  <TypeSignature Language="C#" Value="public class TaskConstraints" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskConstraints extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskConstraints" />
  <TypeSignature Language="F#" Value="type TaskConstraints = class" />
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
            Ausführungseinschränkungen eine Aufgabe zuweisen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskConstraints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.#ctor" />
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
            Initialisiert eine neue Instanz der TaskConstraints-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskConstraints (Nullable&lt;TimeSpan&gt; maxWallClockTime = null, Nullable&lt;TimeSpan&gt; retentionTime = null, Nullable&lt;int&gt; maxTaskRetryCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; maxWallClockTime, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; retentionTime, valuetype System.Nullable`1&lt;int32&gt; maxTaskRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.#ctor(System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional maxWallClockTime As Nullable(Of TimeSpan) = null, Optional retentionTime As Nullable(Of TimeSpan) = null, Optional maxTaskRetryCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskConstraints : Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskConstraints (maxWallClockTime, retentionTime, maxTaskRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxWallClockTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="retentionTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxTaskRetryCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="maxWallClockTime">Die maximal verstrichene Zeit, die der Task ausgeführt werden kann, gemessen ab dem Zeitpunkt der Task beginnt. Wenn die Aufgabe nicht innerhalb des Zeitlimits abgeschlossen wird, der Batch-Dienst beendet wird.</param>
        <param name="retentionTime">Die minimale Zeit, das Task-Verzeichnis auf dem Computeknoten beizubehalten, wo es ab dem Zeitpunkt Lief, Ausführung abgeschlossen ist. Nach dieser Zeit kann der Batch-Dienst das Task-Verzeichnis und seinen gesamten Inhalt löschen.</param>
        <param name="maxTaskRetryCount">Gibt an, wie oft der Task maximal wiederholt werden kann. Der Batch-Dienst wiederholt einen Task, wenn sein Exitcode ungleich null ist.</param>
        <summary>
            Initialisiert eine neue Instanz der TaskConstraints-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTaskRetryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTaskRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.MaxTaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTaskRetryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTaskRetryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.MaxTaskRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTaskRetryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl der Häufigkeit, mit die der Vorgang wiederholt werden kann.
            Der Batch-Dienst wiederholt einen Task, wenn sein Exitcode ungleich null ist.
            </summary>
        <value>To be added.</value>
        <remarks>
            Beachten Sie, dass dieser Wert die Anzahl der Wiederholungen ausdrücklich steuert.
            Der Batch-Dienst wiederholt den Task einmal und kann ihn anschließend bis zu diesem Grenzwert wiederholen. Beispielsweise ist die maximale Anzahl von Wiederholungsversuchen 3, Batch versucht die Aufgabe bis zu 4 Mal (einen ersten Versuch und 3 Wiederholungen). Wenn die maximale Anzahl von Wiederholungsversuchen 0 ist, wird der Batch-Dienst nicht die Aufgabe erneut versucht. Wenn die maximale Anzahl wiederholen ist-1, die Batch-Dienst Wiederholungen der Task unbegrenzt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxWallClockTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaxWallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaxWallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.MaxWallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxWallClockTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaxWallClockTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.MaxWallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxWallClockTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Zeitspanne, die der Task ausgeführt werden kann, gemessen ab dem Zeitpunkt, den der Task beginnt. Wenn die Aufgabe nicht innerhalb des Zeitlimits abgeschlossen wird, der Batch-Dienst beendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn dies nicht angegeben wird, ist es nicht zeitlich begrenzt auf, wie lange der Vorgang ausgeführt werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetentionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetentionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.RetentionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetentionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.RetentionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die minimale Zeit, das Task-Verzeichnis auf dem Computeknoten beizubehalten, auf dem ausgeführt, ab dem Zeitpunkt, die Ausführung abgeschlossen ist.
            Nach dieser Zeit kann der Batch-Dienst das Task-Verzeichnis und seinen gesamten Inhalt löschen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die Standardeinstellung ist unendlich, d. h. das Verzeichnis Aufgabe werden beibehalten, bis die Compute-Knoten entfernt oder ein reimaging ausgeführt wird.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>