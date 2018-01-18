<Type Name="CSMBackupSchedule" FullName="Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule">
  <TypeSignature Language="C#" Value="public class CSMBackupSchedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CSMBackupSchedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class CSMBackupSchedule" />
  <TypeSignature Language="F#" Value="type CSMBackupSchedule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="94155-101">Die Definition der CSM-BackupSchedule-Objekt.</span><span class="sxs-lookup"><span data-stu-id="94155-101">The definition of CSM BackupSchedule object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CSMBackupSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="94155-102">Initialisiert eine neue Instanz der CSMBackupSchedule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="94155-102">Initializes a new instance of the CSMBackupSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CSMBackupSchedule (string backupType, string scheduleRun, System.Collections.Generic.IList&lt;DateTime&gt; scheduleRunTimes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupType, string scheduleRun, class System.Collections.Generic.IList`1&lt;valuetype System.DateTime&gt; scheduleRunTimes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule.#ctor(System.String,System.String,System.Collections.Generic.IList{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (backupType As String, scheduleRun As String, scheduleRunTimes As IList(Of DateTime))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule : string * string * System.Collections.Generic.IList&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule" Usage="new Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule (backupType, scheduleRun, scheduleRunTimes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupType" Type="System.String" />
        <Parameter Name="scheduleRun" Type="System.String" />
        <Parameter Name="scheduleRunTimes" Type="System.Collections.Generic.IList&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="backupType">To be added.</param>
        <param name="scheduleRun">To be added.</param>
        <param name="scheduleRunTimes">To be added.</param>
        <summary>
            <span data-ttu-id="94155-103">Initialisiert eine neue Instanz der CSMBackupSchedule-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="94155-103">Initializes a new instance of the CSMBackupSchedule class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupType">
      <MemberSignature Language="C#" Value="public string BackupType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule.BackupType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupType As String" />
      <MemberSignature Language="F#" Value="member this.BackupType : string with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule.BackupType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94155-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="94155-104">Required.</span></span> <span data-ttu-id="94155-105">BackupType von ProtectionPolicy.</span><span class="sxs-lookup"><span data-stu-id="94155-105">BackupType of ProtectionPolicy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleRun">
      <MemberSignature Language="C#" Value="public string ScheduleRun { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScheduleRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule.ScheduleRun" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduleRun As String" />
      <MemberSignature Language="F#" Value="member this.ScheduleRun : string with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule.ScheduleRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94155-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="94155-106">Required.</span></span> <span data-ttu-id="94155-107">ScheduleRun von ProtectionPolicy.</span><span class="sxs-lookup"><span data-stu-id="94155-107">ScheduleRun of ProtectionPolicy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleRunDays">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;DayOfWeek&gt; ScheduleRunDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.DayOfWeek&gt; ScheduleRunDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule.ScheduleRunDays" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduleRunDays As IList(Of DayOfWeek)" />
      <MemberSignature Language="F#" Value="member this.ScheduleRunDays : System.Collections.Generic.IList&lt;DayOfWeek&gt; with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule.ScheduleRunDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.DayOfWeek&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94155-108">Optional.</span><span class="sxs-lookup"><span data-stu-id="94155-108">Optional.</span></span> <span data-ttu-id="94155-109">ScheduleRunDays von ProtectionPolicy.</span><span class="sxs-lookup"><span data-stu-id="94155-109">ScheduleRunDays of ProtectionPolicy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleRunTimes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;DateTime&gt; ScheduleRunTimes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.DateTime&gt; ScheduleRunTimes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule.ScheduleRunTimes" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduleRunTimes As IList(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ScheduleRunTimes : System.Collections.Generic.IList&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule.ScheduleRunTimes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94155-110">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="94155-110">Required.</span></span> <span data-ttu-id="94155-111">ScheduleRunTimes von ProtectionPolicy.</span><span class="sxs-lookup"><span data-stu-id="94155-111">ScheduleRunTimes of ProtectionPolicy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>