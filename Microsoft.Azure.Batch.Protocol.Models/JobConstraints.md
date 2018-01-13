<Type Name="JobConstraints" FullName="Microsoft.Azure.Batch.Protocol.Models.JobConstraints">
  <TypeSignature Language="C#" Value="public class JobConstraints" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobConstraints extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobConstraints" />
  <TypeSignature Language="VB.NET" Value="Public Class JobConstraints" />
  <TypeSignature Language="F#" Value="type JobConstraints = class" />
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
            Die ausführungseinschränkungen für einen Auftrag.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobConstraints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobConstraints.#ctor" />
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
            Initialisiert eine neue Instanz der Klasse "jobconstraints".
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobConstraints (Nullable&lt;TimeSpan&gt; maxWallClockTime = null, Nullable&lt;int&gt; maxTaskRetryCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; maxWallClockTime, valuetype System.Nullable`1&lt;int32&gt; maxTaskRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobConstraints.#ctor(System.Nullable{System.TimeSpan},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional maxWallClockTime As Nullable(Of TimeSpan) = null, Optional maxTaskRetryCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobConstraints : Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobConstraints" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobConstraints (maxWallClockTime, maxTaskRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxWallClockTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxTaskRetryCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="maxWallClockTime">Die maximal verstrichene Zeit, die der Auftrag ausgeführt werden kann, gemessen ab dem Zeitpunkt der Erstellung des Auftrags.</param>
        <param name="maxTaskRetryCount">Die maximale Anzahl der Häufigkeit, mit die jede Aufgabe wiederholt werden kann. Der Batch-Dienst wiederholt einen Task, wenn sein Exitcode ungleich null ist.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse "jobconstraints".
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTaskRetryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTaskRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobConstraints.MaxTaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTaskRetryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTaskRetryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobConstraints.MaxTaskRetryCount" />
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
            Ruft ab oder legt die maximale Anzahl der Häufigkeit, mit die jede Aufgabe wiederholt werden kann.
            Der Batch-Dienst wiederholt einen Task, wenn sein Exitcode ungleich null ist.
            </summary>
        <value>To be added.</value>
        <remarks>
            Beachten Sie, dass dieser Wert die Anzahl der Wiederholungen ausdrücklich steuert.
            Der Batch-Dienst wird jede Aufgabe einmal versucht, und kann bis zu diesem Limit dann wiederholen. Wenn beispielsweise die maximale Anzahl von Wiederholungsversuchen 3 ist, versucht der Batch-Dienst einen Task bis zu viermal (ein erster Versuch und drei Wiederholungsversuche). Wenn die maximale Anzahl von Wiederholungsversuchen 0 ist, wiederholt der Batch-Dienst Tasks nicht.
            Wenn die maximale Anzahl von Wiederholungsversuchen -1 ist, wiederholt der Batch-Dienst Tasks unbegrenzt. Der Standardwert ist 0 (keine Wiederholungsversuche).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxWallClockTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaxWallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaxWallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobConstraints.MaxWallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxWallClockTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaxWallClockTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobConstraints.MaxWallClockTime" />
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
            Ruft ab oder legt die maximale Zeitspanne, die der Auftrag ausgeführt werden kann, gemessen ab dem Zeitpunkt der Erstellung des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn der Auftrag nicht innerhalb des Zeitlimits abgeschlossen wird, beendet der Batch-Dienst diese und alle Aufgaben, die noch ausgeführt werden. In diesem Fall wird der Grund für die Beendigung MaxWallClockTimeExpiry sein. Wenn diese Eigenschaft nicht angegeben wird, ist es nicht zeitlich begrenzt auf, wie lange der Auftrag ausgeführt werden kann.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>