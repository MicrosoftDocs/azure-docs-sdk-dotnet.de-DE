<Type Name="CSMMonthlyRetentionSchedule" FullName="Microsoft.Azure.Management.BackupServices.Models.CSMMonthlyRetentionSchedule">
  <TypeSignature Language="C#" Value="public class CSMMonthlyRetentionSchedule : Microsoft.Azure.Management.BackupServices.Models.CSMRetentionScheduleBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CSMMonthlyRetentionSchedule extends Microsoft.Azure.Management.BackupServices.Models.CSMRetentionScheduleBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.Models.CSMMonthlyRetentionSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class CSMMonthlyRetentionSchedule&#xA;Inherits CSMRetentionScheduleBase" />
  <TypeSignature Language="F#" Value="type CSMMonthlyRetentionSchedule = class&#xA;    inherit CSMRetentionScheduleBase" />
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
            <span data-ttu-id="41803-101">Die Definition eines CSMMonthlyRetentionSchedule-Objekts.</span><span class="sxs-lookup"><span data-stu-id="41803-101">The definition of a CSMMonthlyRetentionSchedule object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CSMMonthlyRetentionSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.Models.CSMMonthlyRetentionSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="41803-102">Initialisiert eine neue Instanz der CSMMonthlyRetentionSchedule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="41803-102">Initializes a new instance of the CSMMonthlyRetentionSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionScheduleDaily">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.Models.CSMDailyRetentionFormat RetentionScheduleDaily { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.Models.CSMDailyRetentionFormat RetentionScheduleDaily" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMMonthlyRetentionSchedule.RetentionScheduleDaily" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionScheduleDaily As CSMDailyRetentionFormat" />
      <MemberSignature Language="F#" Value="member this.RetentionScheduleDaily : Microsoft.Azure.Management.BackupServices.Models.CSMDailyRetentionFormat with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMMonthlyRetentionSchedule.RetentionScheduleDaily" />
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
            <span data-ttu-id="41803-103">Optional.</span><span class="sxs-lookup"><span data-stu-id="41803-103">Optional.</span></span> <span data-ttu-id="41803-104">Tägliche Beibehaltung-Format für monatliche Aufbewahrungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="41803-104">Daily Retention Format for monthly retention policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionScheduleType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.Models.RetentionScheduleFormat RetentionScheduleType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.BackupServices.Models.RetentionScheduleFormat RetentionScheduleType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMMonthlyRetentionSchedule.RetentionScheduleType" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionScheduleType As RetentionScheduleFormat" />
      <MemberSignature Language="F#" Value="member this.RetentionScheduleType : Microsoft.Azure.Management.BackupServices.Models.RetentionScheduleFormat with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMMonthlyRetentionSchedule.RetentionScheduleType" />
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
            <span data-ttu-id="41803-105">Optional.</span><span class="sxs-lookup"><span data-stu-id="41803-105">Optional.</span></span> <span data-ttu-id="41803-106">Für die Aufbewahrungsrichtlinie für die monatliche Beibehaltung-ScheduleType.</span><span class="sxs-lookup"><span data-stu-id="41803-106">Retention ScheduleType for monthly retention policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionScheduleWeekly">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.Models.CSMWeeklyRetentionFormat RetentionScheduleWeekly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.Models.CSMWeeklyRetentionFormat RetentionScheduleWeekly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMMonthlyRetentionSchedule.RetentionScheduleWeekly" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionScheduleWeekly As CSMWeeklyRetentionFormat" />
      <MemberSignature Language="F#" Value="member this.RetentionScheduleWeekly : Microsoft.Azure.Management.BackupServices.Models.CSMWeeklyRetentionFormat with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMMonthlyRetentionSchedule.RetentionScheduleWeekly" />
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
            <span data-ttu-id="41803-107">Optional.</span><span class="sxs-lookup"><span data-stu-id="41803-107">Optional.</span></span> <span data-ttu-id="41803-108">Wöchentliche Beibehaltung-Format für monatliche Aufbewahrungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="41803-108">Weekly Retention format for monthly retention policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>