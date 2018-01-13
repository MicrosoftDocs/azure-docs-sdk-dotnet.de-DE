<Type Name="EventData" FullName="Microsoft.Azure.EventHubs.EventData">
  <TypeSignature Language="C#" Value="public class EventData : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventData extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventData" />
  <TypeSignature Language="VB.NET" Value="Public Class EventData&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type EventData = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Die Datenstruktur, die das Ereignis wird gesendet an und Empfangen von EventHubs kapseln.
            Jede Partition EventHubs kann als Datenstrom von EventData visuell dargestellt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (ArraySegment&lt;byte&gt; arraySegment);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.ArraySegment`1&lt;unsigned int8&gt; arraySegment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventData.#ctor(System.ArraySegment{System.Byte})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (arraySegment As ArraySegment(Of Byte))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventData : ArraySegment&lt;byte&gt; -&gt; Microsoft.Azure.EventHubs.EventData" Usage="new Microsoft.Azure.EventHubs.EventData arraySegment" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="arraySegment" Type="System.ArraySegment&lt;System.Byte&gt;" />
      </Parameters>
      <Docs>
        <param name="arraySegment">Die Nutzlast Bytes, die Offset und die Länge, die an den Event Hub gesendet werden.</param>
        <summary>
            Erstellen von EventData an Event Hub senden.
            Ist der normale Muster zum Erstellen einer EventData senden: <para>ich.  Serialisieren Sie die sendende ApplicationEvent in Bytes an Event Hub gesendet werden. </para> <para>Ii. Wenn komplexe Serialisierungslogik beteiligt ist (z. B.: mehrere Typen von Daten)-Hinzufügen einer Verwendung des Hinweises die <see cref="P:Microsoft.Azure.EventHubs.EventData.Properties" /> für den Consumer.</para></summary>
        <remarks>To be added.</remarks>
        <example>Beispielcode:
            <code>
            EventData eventData = new EventData(new ArraySegment&lt;byte&gt;(eventBytes, offset, count));
            eventData.Properties["eventType"] = "com.microsoft.azure.monitoring.EtlEvent";
            await partitionSender.SendAsync(eventData);
            </code></example>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (byte[] array);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] array) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventData.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (array As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventData : byte[] -&gt; Microsoft.Azure.EventHubs.EventData" Usage="new Microsoft.Azure.EventHubs.EventData array" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="array" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="array">Die tatsächliche Nutzlast von Daten in Bytes, die an den Event Hub gesendet werden.</param>
        <summary>
            Erstellen von EventData an Event Hub senden.
            Ist der normale Muster zum Erstellen einer EventData senden: <para>ich. Serialisieren Sie die sendende ApplicationEvent an EventHubs gesendet werden, in Bytes. </para> <para>Ii. Wenn komplexe Serialisierungslogik beteiligt ist (z. B.: mehrere Typen von Daten)-Hinzufügen einer Verwendung des Hinweises die <see cref="P:Microsoft.Azure.EventHubs.EventData.Properties" /> für den Consumer.</para></summary>
        <remarks>To be added.</remarks>
        <example>Beispielcode:
            <code>
            EventData eventData = new EventData(telemetryEventBytes);
            eventData.Properties["eventType"] = "com.microsoft.azure.monitoring.EtlEvent";
            await partitionSender.SendAsync(eventData);
            </code></example>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public ArraySegment&lt;byte&gt; Body { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ArraySegment`1&lt;unsigned int8&gt; Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventData.Body" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Body As ArraySegment(Of Byte)" />
      <MemberSignature Language="F#" Value="member this.Body : ArraySegment&lt;byte&gt;" Usage="Microsoft.Azure.EventHubs.EventData.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ArraySegment&lt;System.Byte&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Rufen Sie tatsächliche Nutzlast/Daten von EventData umschlossen wird.
            Dies sollte verwendet werden, nach dem Empfang von EventData mit <see cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventData.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="eventData.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt die Ressourcen, die an der Ereignisdaten frei
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventData.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.EventHubs.EventData.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Eigenschaftenbehälter für die Anwendung
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemProperties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection SystemProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.EventHubs.EventData/SystemPropertiesCollection SystemProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventData.SystemProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SystemProperties As EventData.SystemPropertiesCollection" />
      <MemberSignature Language="F#" Value="member this.SystemProperties : Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection" Usage="Microsoft.Azure.EventHubs.EventData.SystemProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventData+SystemPropertiesCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            SystemProperties, die vom EventHubService aufgefüllt werden.
            Wie diese vom Dienst aufgefüllt werden, sind sie nur auf eine empfangene EventData vorhanden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>