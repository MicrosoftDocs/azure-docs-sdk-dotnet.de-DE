<Type Name="SimpleSchedulePolicy" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.SimpleSchedulePolicy">
  <TypeSignature Language="C#" Value="public class SimpleSchedulePolicy : Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SimpleSchedulePolicy extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.SimpleSchedulePolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class SimpleSchedulePolicy&#xA;Inherits SchedulePolicy" />
  <TypeSignature Language="F#" Value="type SimpleSchedulePolicy = class&#xA;    inherit SchedulePolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Einfache Richtlinie-Zeitplan.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleSchedulePolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.SimpleSchedulePolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SimpleSchedulePolicy-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleSchedulePolicy (string scheduleRunFrequency = null, System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; scheduleRunDays = null, System.Collections.Generic.IList&lt;Nullable&lt;DateTime&gt;&gt; scheduleRunTimes = null, Nullable&lt;int&gt; scheduleWeeklyFrequency = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string scheduleRunFrequency, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; scheduleRunDays, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype System.DateTime&gt;&gt; scheduleRunTimes, valuetype System.Nullable`1&lt;int32&gt; scheduleWeeklyFrequency) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.SimpleSchedulePolicy.#ctor(System.String,System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek}},System.Collections.Generic.IList{System.Nullable{System.DateTime}},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional scheduleRunFrequency As String = null, Optional scheduleRunDays As IList(Of Nullable(Of DayOfWeek)) = null, Optional scheduleRunTimes As IList(Of Nullable(Of DateTime)) = null, Optional scheduleWeeklyFrequency As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.SimpleSchedulePolicy : string * System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; * System.Collections.Generic.IList&lt;Nullable&lt;DateTime&gt;&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.SimpleSchedulePolicy" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.SimpleSchedulePolicy (scheduleRunFrequency, scheduleRunDays, scheduleRunTimes, scheduleWeeklyFrequency)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="scheduleRunFrequency" Type="System.String" />
        <Parameter Name="scheduleRunDays" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt;" />
        <Parameter Name="scheduleRunTimes" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;System.DateTime&gt;&gt;" />
        <Parameter Name="scheduleWeeklyFrequency" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="scheduleRunFrequency">Die Häufigkeit des Vorgangs Zeitplan gegen diese Richtlinien sind. Folgende Werte sind möglich: "Ungültig", "Daily", "Wöchentlich"</param>
        <param name="scheduleRunDays">Liste der Tage der Woche, die diesen Zeitplan ausgeführt werden.</param>
        <param name="scheduleRunTimes">Liste der Tageszeiten, muss dieser Zeitplan ausgeführt werden.</param>
        <param name="scheduleWeeklyFrequency">Jede Anzahl Wochen muss dieser Zeitplan ausgeführt werden.</param>
        <summary>
            Initialisiert eine neue Instanz der SimpleSchedulePolicy-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleRunDays">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; ScheduleRunDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; ScheduleRunDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.SimpleSchedulePolicy.ScheduleRunDays" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduleRunDays As IList(Of Nullable(Of DayOfWeek))" />
      <MemberSignature Language="F#" Value="member this.ScheduleRunDays : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.SimpleSchedulePolicy.ScheduleRunDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scheduleRunDays")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Tage der Woche, die diesen Zeitplan ausgeführt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleRunFrequency">
      <MemberSignature Language="C#" Value="public string ScheduleRunFrequency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScheduleRunFrequency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.SimpleSchedulePolicy.ScheduleRunFrequency" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduleRunFrequency As String" />
      <MemberSignature Language="F#" Value="member this.ScheduleRunFrequency : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.SimpleSchedulePolicy.ScheduleRunFrequency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scheduleRunFrequency")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Häufigkeit des Vorgangs Zeitplan gegen diese Richtlinien sind.
            Folgende Werte sind möglich: "Ungültig", "Daily", "Wöchentlich"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleRunTimes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;DateTime&gt;&gt; ScheduleRunTimes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype System.DateTime&gt;&gt; ScheduleRunTimes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.SimpleSchedulePolicy.ScheduleRunTimes" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduleRunTimes As IList(Of Nullable(Of DateTime))" />
      <MemberSignature Language="F#" Value="member this.ScheduleRunTimes : System.Collections.Generic.IList&lt;Nullable&lt;DateTime&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.SimpleSchedulePolicy.ScheduleRunTimes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scheduleRunTimes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;System.DateTime&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Tageszeiten, muss dieser Zeitplan ausgeführt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleWeeklyFrequency">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ScheduleWeeklyFrequency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ScheduleWeeklyFrequency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.SimpleSchedulePolicy.ScheduleWeeklyFrequency" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduleWeeklyFrequency As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ScheduleWeeklyFrequency : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.SimpleSchedulePolicy.ScheduleWeeklyFrequency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scheduleWeeklyFrequency")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest, an alle Anzahl Wochen, die diesen Zeitplan ausgeführt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>