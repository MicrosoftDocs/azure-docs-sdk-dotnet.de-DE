<Type Name="BackupPolicy" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy">
  <TypeSignature Language="C#" Value="public class BackupPolicy : Microsoft.WindowsAzure.Management.StorSimple.Models.CisBaseObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupPolicy extends Microsoft.WindowsAzure.Management.StorSimple.Models.CisBaseObject" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupPolicy&#xA;Inherits CisBaseObject" />
  <TypeSignature Language="F#" Value="type BackupPolicy = class&#xA;    inherit CisBaseObject" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Management.StorSimple.Models.CisBaseObject</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dc914-101">Die Informationen auf der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dc914-101">The information on backup policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc914-102">Initialisiert eine neue Instanz der BackupPolicy-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dc914-102">Initializes a new instance of the BackupPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicyCreationType">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyCreationType BackupPolicyCreationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyCreationType BackupPolicyCreationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy.BackupPolicyCreationType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupPolicyCreationType As BackupPolicyCreationType" />
      <MemberSignature Language="F#" Value="member this.BackupPolicyCreationType : Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyCreationType with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy.BackupPolicyCreationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyCreationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc914-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dc914-103">Required.</span></span> <span data-ttu-id="dc914-104">Der Typ der Erstellung der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dc914-104">The type of the backup policy creation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBackup">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastBackup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastBackup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy.LastBackup" />
      <MemberSignature Language="VB.NET" Value="Public Property LastBackup As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastBackup : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy.LastBackup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc914-105">Optional.</span><span class="sxs-lookup"><span data-stu-id="dc914-105">Optional.</span></span> <span data-ttu-id="dc914-106">Die Uhrzeit der vorherigen Sicherung.</span><span class="sxs-lookup"><span data-stu-id="dc914-106">The previous backup time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextBackup">
      <MemberSignature Language="C#" Value="public DateTime NextBackup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime NextBackup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy.NextBackup" />
      <MemberSignature Language="VB.NET" Value="Public Property NextBackup As DateTime" />
      <MemberSignature Language="F#" Value="member this.NextBackup : DateTime with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy.NextBackup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc914-107">Optional.</span><span class="sxs-lookup"><span data-stu-id="dc914-107">Optional.</span></span> <span data-ttu-id="dc914-108">Die Uhrzeit der nächsten Sicherung.</span><span class="sxs-lookup"><span data-stu-id="dc914-108">The next backup time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchedulesCount">
      <MemberSignature Language="C#" Value="public long SchedulesCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SchedulesCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy.SchedulesCount" />
      <MemberSignature Language="VB.NET" Value="Public Property SchedulesCount As Long" />
      <MemberSignature Language="F#" Value="member this.SchedulesCount : int64 with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy.SchedulesCount" />
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
            <span data-ttu-id="dc914-109">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dc914-109">Required.</span></span> <span data-ttu-id="dc914-110">Die Anzahl von Sicherungszeitplänen unter diese Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dc914-110">The count of backup schedules under this backup policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SSMHostName">
      <MemberSignature Language="C#" Value="public string SSMHostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SSMHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy.SSMHostName" />
      <MemberSignature Language="VB.NET" Value="Public Property SSMHostName As String" />
      <MemberSignature Language="F#" Value="member this.SSMHostName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy.SSMHostName" />
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
            <span data-ttu-id="dc914-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dc914-111">Required.</span></span> <span data-ttu-id="dc914-112">Der Name des StorSimple Manager-Hosts.</span><span class="sxs-lookup"><span data-stu-id="dc914-112">The name of the StorSimple Manager host.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumesCount">
      <MemberSignature Language="C#" Value="public long VolumesCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 VolumesCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy.VolumesCount" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumesCount As Long" />
      <MemberSignature Language="F#" Value="member this.VolumesCount : int64 with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy.VolumesCount" />
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
            <span data-ttu-id="dc914-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dc914-113">Required.</span></span> <span data-ttu-id="dc914-114">Die Anzahl der Volumes, die unter der diese Sicherungsrichtlinie abgedeckt werden.</span><span class="sxs-lookup"><span data-stu-id="dc914-114">The count of volumes covered under this backup policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>