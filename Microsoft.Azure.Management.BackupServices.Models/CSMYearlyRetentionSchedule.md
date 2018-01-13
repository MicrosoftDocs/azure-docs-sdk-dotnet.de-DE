<Type Name="CSMYearlyRetentionSchedule" FullName="Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule">
  <TypeSignature Language="C#" Value="public class CSMYearlyRetentionSchedule : Microsoft.Azure.Management.BackupServices.Models.CSMRetentionScheduleBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CSMYearlyRetentionSchedule extends Microsoft.Azure.Management.BackupServices.Models.CSMRetentionScheduleBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class CSMYearlyRetentionSchedule&#xA;Inherits CSMRetentionScheduleBase" />
  <TypeSignature Language="F#" Value="type CSMYearlyRetentionSchedule = class&#xA;    inherit CSMRetentionScheduleBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.BackupServices.Models.CSMRetentionScheduleBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Definition eines CSMYearlyRetentionSchedule-Objekts.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CSMYearlyRetentionSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CSMYearlyRetentionSchedule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonthsOfYear">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BackupServices.Models.Month&gt; MonthsOfYear { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Management.BackupServices.Models.Month&gt; MonthsOfYear" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.MonthsOfYear" />
      <MemberSignature Language="VB.NET" Value="Public Property MonthsOfYear As IList(Of Month)" />
      <MemberSignature Language="F#" Value="member this.MonthsOfYear : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BackupServices.Models.Month&gt; with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.MonthsOfYear" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BackupServices.Models.Month&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Liste der Monate des Jahres jährliche Aufbewahrungsrichtlinie.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionScheduleDaily">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.Models.CSMDailyRetentionFormat RetentionScheduleDaily { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.Models.CSMDailyRetentionFormat RetentionScheduleDaily" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.RetentionScheduleDaily" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionScheduleDaily As CSMDailyRetentionFormat" />
      <MemberSignature Language="F#" Value="member this.RetentionScheduleDaily : Microsoft.Azure.Management.BackupServices.Models.CSMDailyRetentionFormat with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.RetentionScheduleDaily" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.CSMDailyRetentionFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Tägliche Beibehaltung-Format für monatliche Aufbewahrungsrichtlinie.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionScheduleType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.Models.RetentionScheduleFormat RetentionScheduleType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.BackupServices.Models.RetentionScheduleFormat RetentionScheduleType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.RetentionScheduleType" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionScheduleType As RetentionScheduleFormat" />
      <MemberSignature Language="F#" Value="member this.RetentionScheduleType : Microsoft.Azure.Management.BackupServices.Models.RetentionScheduleFormat with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.RetentionScheduleType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.RetentionScheduleFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Für die Aufbewahrungsrichtlinie für die monatliche Beibehaltung-ScheduleType.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionScheduleWeekly">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.Models.CSMWeeklyRetentionFormat RetentionScheduleWeekly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.Models.CSMWeeklyRetentionFormat RetentionScheduleWeekly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.RetentionScheduleWeekly" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionScheduleWeekly As CSMWeeklyRetentionFormat" />
      <MemberSignature Language="F#" Value="member this.RetentionScheduleWeekly : Microsoft.Azure.Management.BackupServices.Models.CSMWeeklyRetentionFormat with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.RetentionScheduleWeekly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.CSMWeeklyRetentionFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Wöchentliche Beibehaltung-Format für monatliche Aufbewahrungsrichtlinie.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>