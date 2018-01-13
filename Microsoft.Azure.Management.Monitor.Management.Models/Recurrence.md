<Type Name="Recurrence" FullName="Microsoft.Azure.Management.Monitor.Management.Models.Recurrence">
  <TypeSignature Language="C#" Value="public class Recurrence" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Recurrence extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.Recurrence" />
  <TypeSignature Language="VB.NET" Value="Public Class Recurrence" />
  <TypeSignature Language="F#" Value="type Recurrence = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die wiederholten Uhrzeiten, an denen dieses Profil beginnt. Dieses Element wird nicht verwendet werden, wenn das FixedDate-Element verwendet wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Recurrence ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.Recurrence.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse Wiederholung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Recurrence (Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency frequency, Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule schedule);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency frequency, class Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule schedule) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.Recurrence.#ctor(Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency,Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (frequency As RecurrenceFrequency, schedule As RecurrentSchedule)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.Recurrence : Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency * Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule -&gt; Microsoft.Azure.Management.Monitor.Management.Models.Recurrence" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.Recurrence (frequency, schedule)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="frequency" Type="Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency" />
        <Parameter Name="schedule" Type="Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule" />
      </Parameters>
      <Docs>
        <param name="frequency">die wiederholungshäufigkeit. Wie oft das zeitplanprofil in Kraft treten soll. Dieser Wert muss Woche, d. h., jede Woche den gleichen Satz von Profilen haben wird. Folgende Werte sind möglich: 'None', 'Second', 'Minute', 'Hour', 'Tag', 'Week', 'Month', 'Year'</param>
        <param name="schedule">Die planungseinschränkungen für den Beginn des Profils.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse Wiederholung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Frequency">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency Frequency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency Frequency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.Recurrence.Frequency" />
      <MemberSignature Language="VB.NET" Value="Public Property Frequency As RecurrenceFrequency" />
      <MemberSignature Language="F#" Value="member this.Frequency : Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.Recurrence.Frequency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="frequency")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die wiederholungshäufigkeit fest. Wie oft das zeitplanprofil in Kraft treten soll. Dieser Wert muss Woche, d. h., jede Woche den gleichen Satz von Profilen haben wird. Folgende Werte sind möglich: 'None', 'Second', 'Minute', 'Hour', 'Tag', 'Week', 'Month', 'Year'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule Schedule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule Schedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.Recurrence.Schedule" />
      <MemberSignature Language="VB.NET" Value="Public Property Schedule As RecurrentSchedule" />
      <MemberSignature Language="F#" Value="member this.Schedule : Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.Recurrence.Schedule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schedule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die planungseinschränkungen für den Beginn des Profils.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.Recurrence.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="recurrence.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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