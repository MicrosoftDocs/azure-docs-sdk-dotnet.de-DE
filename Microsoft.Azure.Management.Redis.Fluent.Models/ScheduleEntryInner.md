<Type Name="ScheduleEntryInner" FullName="Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner">
  <TypeSignature Language="C#" Value="public class ScheduleEntryInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScheduleEntryInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ScheduleEntryInner" />
  <TypeSignature Language="F#" Value="type ScheduleEntryInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Patch für Zeitplaneintrag für eine Premium-Redis-Cache.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleEntryInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ScheduleEntryInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleEntryInner (Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek dayOfWeek, int startHourUtc, Nullable&lt;TimeSpan&gt; maintenanceWindow = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek dayOfWeek, int32 startHourUtc, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; maintenanceWindow) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.#ctor(Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek,System.Int32,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner : Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek * int * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner" Usage="new Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner (dayOfWeek, startHourUtc, maintenanceWindow)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dayOfWeek" Type="Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek" />
        <Parameter Name="startHourUtc" Type="System.Int32" />
        <Parameter Name="maintenanceWindow" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="dayOfWeek">Tag der Woche, wenn ein Cache Patch angewendet werden kann. Folgende Werte sind möglich: "Montag", "Dienstag", "Mittwoch", "Donnerstag", "Freitag", "Samstag" und "Sonntag", "Täglich", "Wochenende"</param>
        <param name="startHourUtc">Starten Sie die Stunde nach der Cache Patchen starten kann.</param>
        <param name="maintenanceWindow">ISO8601-Zeitspanne angeben, wie viel Zeit Cache Patchen ergreifen kann. </param>
        <summary>
            Initialisiert eine neue Instanz der ScheduleEntryInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DayOfWeek">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek DayOfWeek { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek DayOfWeek" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.DayOfWeek" />
      <MemberSignature Language="VB.NET" Value="Public Property DayOfWeek As DayOfWeek" />
      <MemberSignature Language="F#" Value="member this.DayOfWeek : Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.DayOfWeek" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dayOfWeek")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Tag der Woche, wenn ein Cache Patch angewendet werden kann. Folgende Werte sind möglich: "Montag", "Dienstag", "Mittwoch", "Donnerstag", "Freitag", "Samstag" und "Sonntag", "Täglich", "Wochenende"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaintenanceWindow">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaintenanceWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaintenanceWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.MaintenanceWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property MaintenanceWindow As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaintenanceWindow : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.MaintenanceWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maintenanceWindow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest ISO8601 Timespan-Angabe, wie viel Zeit Cache Patchen ergreifen kann.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartHourUtc">
      <MemberSignature Language="C#" Value="public int StartHourUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StartHourUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.StartHourUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property StartHourUtc As Integer" />
      <MemberSignature Language="F#" Value="member this.StartHourUtc : int with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.StartHourUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startHourUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Startuhrzeit nach welcher Cache Patchen starten kann.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="scheduleEntryInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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