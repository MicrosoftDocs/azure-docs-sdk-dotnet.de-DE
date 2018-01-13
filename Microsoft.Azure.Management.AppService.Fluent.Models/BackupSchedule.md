<Type Name="BackupSchedule" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule">
  <TypeSignature Language="C#" Value="public class BackupSchedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupSchedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupSchedule" />
  <TypeSignature Language="F#" Value="type BackupSchedule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Beschreibung des einen Sicherungszeitplan. Beschreibt, wie oft soll die Sicherung ausgeführt werden und wie die Aufbewahrungsrichtlinie sein soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der BackupSchedule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupSchedule (int frequencyInterval, Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit frequencyUnit, bool keepAtLeastOneBackup, int retentionPeriodInDays, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; lastExecutionTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 frequencyInterval, valuetype Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit frequencyUnit, bool keepAtLeastOneBackup, int32 retentionPeriodInDays, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastExecutionTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.#ctor(System.Int32,Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit,System.Boolean,System.Int32,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule : int * Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit * bool * int * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule (frequencyInterval, frequencyUnit, keepAtLeastOneBackup, retentionPeriodInDays, startTime, lastExecutionTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="frequencyInterval" Type="System.Int32" />
        <Parameter Name="frequencyUnit" Type="Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit" />
        <Parameter Name="keepAtLeastOneBackup" Type="System.Boolean" />
        <Parameter Name="retentionPeriodInDays" Type="System.Int32" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastExecutionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="frequencyInterval">Wie oft soll die Sicherung ausgeführt werden (z. B. für wöchentliche Sicherung sollte dies auf 7 festgelegt werden und FrequencyUnit sollte festgelegt werden, auf den Tag)</param>
        <param name="frequencyUnit">Die Zeiteinheit für die Häufigkeit die Sicherung ausgeführt werden soll (z. B. für wöchentliche Sicherung sollte festgelegt werden auf den Tag und FrequencyInterval auf 7 festgelegt werden). Folgende Werte sind möglich: 'Tag', 'Hour'</param>
        <param name="keepAtLeastOneBackup">True, wenn die Aufbewahrungsrichtlinie immer mindestens eine Sicherung im Speicherkonto, unabhängig davon beibehalten soll wie alt ist. "false" andernfalls.</param>
        <param name="retentionPeriodInDays">Nach wie vielen Tagen Sicherungen gelöscht werden sollen.</param>
        <param name="startTime">Wenn der Zeitplan beginnen soll.</param>
        <param name="lastExecutionTime">Zuletzt bei diesen Zeitplan ausgelöst wurde.</param>
        <summary>
            Initialisiert eine neue Instanz der BackupSchedule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrequencyInterval">
      <MemberSignature Language="C#" Value="public int FrequencyInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrequencyInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.FrequencyInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property FrequencyInterval As Integer" />
      <MemberSignature Language="F#" Value="member this.FrequencyInterval : int with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.FrequencyInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="frequencyInterval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest, wie oft die Sicherung ausgeführt werden soll (z. B. für wöchentliche Sicherung sollte dies auf 7 festgelegt werden und FrequencyUnit sollte festgelegt werden, auf den Tag)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrequencyUnit">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit FrequencyUnit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit FrequencyUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.FrequencyUnit" />
      <MemberSignature Language="VB.NET" Value="Public Property FrequencyUnit As FrequencyUnit" />
      <MemberSignature Language="F#" Value="member this.FrequencyUnit : Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.FrequencyUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="frequencyUnit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die Zeiteinheit wie oft die Sicherung ausgeführt werden soll (z. B. für wöchentliche Sicherung sollte festgelegt werden auf den Tag und FrequencyInterval auf 7 festgelegt werden). Folgende Werte sind möglich: 'Tag', 'Hour'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAtLeastOneBackup">
      <MemberSignature Language="C#" Value="public bool KeepAtLeastOneBackup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool KeepAtLeastOneBackup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.KeepAtLeastOneBackup" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAtLeastOneBackup As Boolean" />
      <MemberSignature Language="F#" Value="member this.KeepAtLeastOneBackup : bool with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.KeepAtLeastOneBackup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keepAtLeastOneBackup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest "true", wenn die Aufbewahrungsrichtlinie immer mindestens eine Sicherung im Speicherkonto, unabhängig davon beibehalten soll wie alt ist. "false" andernfalls.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastExecutionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastExecutionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastExecutionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.LastExecutionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastExecutionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastExecutionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.LastExecutionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastExecutionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die zuletzt bei diesen Zeitplan ausgelöst wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionPeriodInDays">
      <MemberSignature Language="C#" Value="public int RetentionPeriodInDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RetentionPeriodInDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.RetentionPeriodInDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionPeriodInDays As Integer" />
      <MemberSignature Language="F#" Value="member this.RetentionPeriodInDays : int with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.RetentionPeriodInDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionPeriodInDays")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest, nach wie vielen Tagen Sicherungen gelöscht werden sollen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, wenn der Zeitplan beginnen soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="backupSchedule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
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