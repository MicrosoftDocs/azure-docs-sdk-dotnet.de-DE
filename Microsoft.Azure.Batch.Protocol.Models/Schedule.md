<Type Name="Schedule" FullName="Microsoft.Azure.Batch.Protocol.Models.Schedule">
  <TypeSignature Language="C#" Value="public class Schedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Schedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.Schedule" />
  <TypeSignature Language="VB.NET" Value="Public Class Schedule" />
  <TypeSignature Language="F#" Value="type Schedule = class" />
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
            Der Zeitplan entsprechend, den Aufträge erstellt werden soll
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Schedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.Schedule.#ctor" />
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
            Initialisiert eine neue Instanz der Klasse Zeitplan an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Schedule (Nullable&lt;DateTime&gt; doNotRunUntil = null, Nullable&lt;DateTime&gt; doNotRunAfter = null, Nullable&lt;TimeSpan&gt; startWindow = null, Nullable&lt;TimeSpan&gt; recurrenceInterval = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; doNotRunUntil, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; doNotRunAfter, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; startWindow, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; recurrenceInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.Schedule.#ctor(System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional doNotRunUntil As Nullable(Of DateTime) = null, Optional doNotRunAfter As Nullable(Of DateTime) = null, Optional startWindow As Nullable(Of TimeSpan) = null, Optional recurrenceInterval As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.Schedule : Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.Schedule" Usage="new Microsoft.Azure.Batch.Protocol.Models.Schedule (doNotRunUntil, doNotRunAfter, startWindow, recurrenceInterval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="doNotRunUntil" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="doNotRunAfter" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="startWindow" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="recurrenceInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="doNotRunUntil">Die früheste Uhrzeit, an dem ein Auftrag unter diesem Auftragszeitplan erstellt werden kann.</param>
        <param name="doNotRunAfter">Eine Uhrzeit, nach der kein Auftrag unter diesem Auftragszeitplan erstellt wird. Der Zeitplan wird in den abgeschlossenen Zustand verschoben, sobald diese Frist überschritten ist und es kein aktiver Auftrag unter diesem Auftragszeitplan ist.</param>
        <param name="startWindow">Das Zeitintervall sollte ab dem Zeitpunkt, zu dem gemäß dem Zeitplan einen Auftrag, erstellt werden, in dem ein Auftrag erstellt werden muss.</param>
        <param name="recurrenceInterval">Das Zeitintervall zwischen den Startzeiten von zwei aufeinander folgenden Aufträgen unter der Auftragszeitplan. Zeitplan für einen Auftrag kann zu einem beliebigen Zeitpunkt höchstens einen aktiven Auftrag unter sich haben.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse Zeitplan an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DoNotRunAfter">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DoNotRunAfter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DoNotRunAfter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Schedule.DoNotRunAfter" />
      <MemberSignature Language="VB.NET" Value="Public Property DoNotRunAfter As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DoNotRunAfter : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Schedule.DoNotRunAfter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="doNotRunAfter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert einen Zeitpunkt nach dem kein Auftrag unter diesem Auftragszeitplan erstellt wird. Der Zeitplan wird in den abgeschlossenen Zustand verschoben, sobald diese Frist überschritten ist und es kein aktiver Auftrag unter diesem Auftragszeitplan ist.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn Sie eine Zeit DoNotRunAfter nicht angeben und Sie einen Zeitplan für wiederkehrende Aufträge erstellen, wird der Auftragszeitplan aktiv bleibt, bis Sie explizit beenden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DoNotRunUntil">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DoNotRunUntil { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DoNotRunUntil" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Schedule.DoNotRunUntil" />
      <MemberSignature Language="VB.NET" Value="Public Property DoNotRunUntil As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DoNotRunUntil : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Schedule.DoNotRunUntil" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="doNotRunUntil")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den frühesten Zeitpunkt, an dem ein Auftrag unter diesem Auftragszeitplan erstellt werden kann.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn Sie keine DoNotRunUntil Zeit angeben, wird der Zeitplan bereit, um Aufträge sofort zu erstellen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RecurrenceInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RecurrenceInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RecurrenceInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Schedule.RecurrenceInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RecurrenceInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RecurrenceInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Schedule.RecurrenceInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recurrenceInterval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Zeitintervall zwischen den Startzeiten von zwei aufeinander folgenden Aufträgen unter der Auftragszeitplan fest. Zeitplan für einen Auftrag kann zu einem beliebigen Zeitpunkt höchstens einen aktiven Auftrag unter sich haben.
            </summary>
        <value>To be added.</value>
        <remarks>
            Zeitplan für einen Auftrag einem bestimmten Zeitpunkt höchstens einen aktiven Auftrag unter sich haben kann, wenn Sie jetzt einen neuen Auftrag unter Zeitplan für einen Auftrag erstellen, aber der vorherige Auftrag noch ausgeführt wird, wird der Batch-Dienst nicht den neuen Auftrag erstellen, bis der vorherige Auftrag abgeschlossen ist. Wenn der vorherige Auftrag nicht innerhalb des Zeitraums "startwindow" neue RecurrenceInterval beendet wird, wird kein neuer Auftrag für dieses Intervall geplant. Für wiederkehrende Aufträge sollten Sie normalerweise eine JobManagerTask in die jobspecification wirken angeben. Wenn Sie nicht JobManagerTask verwenden, benötigen Sie einen externen Prozess überwachen, wann Aufträge erstellt werden, Hinzufügen von Tasks Aufträge aus, und beenden die Aufträge für die nächste Wiederholung bereit. Die Standardeinstellung ist, dass der Zeitplan nicht wiederholt werden kann: ein Auftrag erstellt, in der "startwindow" nach der Zeit DoNotRunUntil und der Zeitplan ist abgeschlossen, sobald der Auftrag abgeschlossen ist. Der Mindestwert ist 1 Minute. Wenn Sie einen niedrigeren Wert angeben, weist der Batch-Dienst den Zeitplan mit einem Fehler zurück; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartWindow">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; StartWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; StartWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Schedule.StartWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property StartWindow As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartWindow : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Schedule.StartWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startWindow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Zeitintervall ab dem Zeitpunkt, zu dem gemäß dem Zeitplan, dass ein Auftrag erstellt werden soll, in dem ein Auftrag erstellt werden muss.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn ein Auftrag nicht innerhalb des Intervalls für "startwindow" erstellt wird, ist "Verkaufschance" verloren. bis die nächste Wiederholung des Zeitplans wird kein Agentauftrag erstellt werden. Wenn der Zeitplan wiederholt wird, und die "startwindow" länger als das Wiederholungsintervall ist, entspricht dies eine unendliche "startwindow", da Auftrags, due in einem RecurrenceInterval ist, nicht in der nächsten Wiederholungsintervall übernommen wird. Der Standardwert ist unendlich. Der Mindestwert ist 1 Minute. Wenn Sie einen niedrigeren Wert angeben, weist der Batch-Dienst den Zeitplan mit einem Fehler zurück; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung).
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>