<Type Name="ScheduleRecurrence" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence">
  <TypeSignature Language="C#" Value="public class ScheduleRecurrence" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScheduleRecurrence extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence" />
  <TypeSignature Language="VB.NET" Value="Public Class ScheduleRecurrence" />
  <TypeSignature Language="F#" Value="type ScheduleRecurrence = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Der Zeitplan für Wiederholungen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleRecurrence ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse ScheduleRecurrence an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleRecurrence (Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType recurrenceType, int recurrenceValue, System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; weeklyDaysList = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType recurrenceType, int32 recurrenceValue, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; weeklyDaysList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType,System.Int32,System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek}})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence : Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType * int * System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence (recurrenceType, recurrenceValue, weeklyDaysList)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="recurrenceType" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType" />
        <Parameter Name="recurrenceValue" Type="System.Int32" />
        <Parameter Name="weeklyDaysList" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="recurrenceType">Der Wiederholungstyp. Folgende Werte sind möglich: "Minuten", "Stündlich", "Täglich", "Wöchentlich"</param>
        <param name="recurrenceValue">Der Wiederholungswert für.</param>
        <param name="weeklyDaysList">Die Liste mit Tagen Woche. Gilt nur für Zeitpläne Wiederholungstyp "wöchentlich".</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse ScheduleRecurrence an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecurrenceType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType RecurrenceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType RecurrenceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.RecurrenceType" />
      <MemberSignature Language="VB.NET" Value="Public Property RecurrenceType As RecurrenceType" />
      <MemberSignature Language="F#" Value="member this.RecurrenceType : Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.RecurrenceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recurrenceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Wiederholungstyp fest. Folgende Werte sind möglich: "Minuten", "Stündlich", "Täglich", "Wöchentlich"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecurrenceValue">
      <MemberSignature Language="C#" Value="public int RecurrenceValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RecurrenceValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.RecurrenceValue" />
      <MemberSignature Language="VB.NET" Value="Public Property RecurrenceValue As Integer" />
      <MemberSignature Language="F#" Value="member this.RecurrenceValue : int with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.RecurrenceValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recurrenceValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Wiederholungswert für fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="scheduleRecurrence.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Member MemberName="WeeklyDaysList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; WeeklyDaysList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; WeeklyDaysList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.WeeklyDaysList" />
      <MemberSignature Language="VB.NET" Value="Public Property WeeklyDaysList As IList(Of Nullable(Of DayOfWeek))" />
      <MemberSignature Language="F#" Value="member this.WeeklyDaysList : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.WeeklyDaysList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="weeklyDaysList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste mit Tagen der Woche. Gilt nur für Zeitpläne Wiederholungstyp "wöchentlich".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>