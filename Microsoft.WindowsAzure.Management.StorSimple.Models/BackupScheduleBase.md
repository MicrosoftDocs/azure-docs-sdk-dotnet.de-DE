<Type Name="BackupScheduleBase" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase">
  <TypeSignature Language="C#" Value="public class BackupScheduleBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupScheduleBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupScheduleBase" />
  <TypeSignature Language="F#" Value="type BackupScheduleBase = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5960f-101">Diese Klasse stellt das Basisobjekt für ein Objekt mit Sicherungszeitplan - ohne-Id an.</span><span class="sxs-lookup"><span data-stu-id="5960f-101">This class represents the base object for a backup schedule object - without id.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupScheduleBase ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5960f-102">Initialisiert eine neue Instanz der BackupScheduleBase-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5960f-102">Initializes a new instance of the BackupScheduleBase class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupType">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.BackupType BackupType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.BackupType BackupType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.BackupType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupType As BackupType" />
      <MemberSignature Language="F#" Value="member this.BackupType : Microsoft.WindowsAzure.Management.StorSimple.Models.BackupType with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.BackupType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.BackupType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5960f-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5960f-103">Required.</span></span> <span data-ttu-id="5960f-104">Der Typ der Sicherung.</span><span class="sxs-lookup"><span data-stu-id="5960f-104">The type of the backup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recurrence">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence Recurrence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence Recurrence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.Recurrence" />
      <MemberSignature Language="VB.NET" Value="Public Property Recurrence As ScheduleRecurrence" />
      <MemberSignature Language="F#" Value="member this.Recurrence : Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.Recurrence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5960f-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5960f-105">Required.</span></span> <span data-ttu-id="5960f-106">Die Wiederholung dieses Zeitplans.</span><span class="sxs-lookup"><span data-stu-id="5960f-106">The recurrence of this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionCount">
      <MemberSignature Language="C#" Value="public long RetentionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 RetentionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.RetentionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionCount As Long" />
      <MemberSignature Language="F#" Value="member this.RetentionCount : int64 with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.RetentionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5960f-107">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5960f-107">Required.</span></span> <span data-ttu-id="5960f-108">Die Anzahl der Beibehaltungsdauer für Sicherungen von diesem Zeitplan.</span><span class="sxs-lookup"><span data-stu-id="5960f-108">Retention count for backups of this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public string StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As String" />
      <MemberSignature Language="F#" Value="member this.StartTime : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5960f-109">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5960f-109">Required.</span></span> <span data-ttu-id="5960f-110">Der StartTime für diesen Zeitplan.</span><span class="sxs-lookup"><span data-stu-id="5960f-110">The StartTime for this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As ScheduleStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5960f-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5960f-111">Required.</span></span> <span data-ttu-id="5960f-112">Der Status des Zeitplans</span><span class="sxs-lookup"><span data-stu-id="5960f-112">The status of the schedule</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>