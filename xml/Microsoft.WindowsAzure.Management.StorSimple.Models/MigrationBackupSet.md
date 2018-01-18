<Type Name="MigrationBackupSet" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet">
  <TypeSignature Language="C#" Value="public class MigrationBackupSet" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MigrationBackupSet extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet" />
  <TypeSignature Language="VB.NET" Value="Public Class MigrationBackupSet" />
  <TypeSignature Language="F#" Value="type MigrationBackupSet = class" />
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
            <span data-ttu-id="47140-101">Diese Klasse die darstellt den Status der einzelnen Sicherungen, die zu migrierenden</span><span class="sxs-lookup"><span data-stu-id="47140-101">This class respresents the status of each backup being migrated</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrationBackupSet ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="47140-102">Initialisiert eine neue Instanz der MigrationBackupSet-Klasse.</span><span class="sxs-lookup"><span data-stu-id="47140-102">Initializes a new instance of the MigrationBackupSet class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicyName">
      <MemberSignature Language="C#" Value="public string BackupPolicyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupPolicyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet.BackupPolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupPolicyName As String" />
      <MemberSignature Language="F#" Value="member this.BackupPolicyName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet.BackupPolicyName" />
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
            <span data-ttu-id="47140-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="47140-103">Required.</span></span> <span data-ttu-id="47140-104">Ruft ab oder legt den Namen der Richtlinie (virtuelle Datenträgergruppe) für die Sicherung fest</span><span class="sxs-lookup"><span data-stu-id="47140-104">Gets or sets the name of the policy (virtual disk group) corresponding to the backup</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public DateTime CreationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property CreationTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreationTime : DateTime with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet.CreationTime" />
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
            <span data-ttu-id="47140-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="47140-105">Required.</span></span> <span data-ttu-id="47140-106">Ruft ab oder legt ihn fest Zeitpunkt der Erstellung der Sicherung</span><span class="sxs-lookup"><span data-stu-id="47140-106">Gets or sets the backup creation time</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Elements">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupElement&gt; Elements { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupElement&gt; Elements" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet.Elements" />
      <MemberSignature Language="VB.NET" Value="Public Property Elements As IList(Of MigrationBackupElement)" />
      <MemberSignature Language="F#" Value="member this.Elements : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupElement&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet.Elements" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupElement&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47140-107">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="47140-107">Required.</span></span> <span data-ttu-id="47140-108">Ruft ab oder legt die Sicherung Quelle Volume-details</span><span class="sxs-lookup"><span data-stu-id="47140-108">Gets or sets the backup's source volume details</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As HcsMessageInfo" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47140-109">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="47140-109">Required.</span></span> <span data-ttu-id="47140-110">Ruft ab oder legt die Sicherung Ebene Nachricht und die Empfehlung, die in der Regel bei Ausfällen aktualisiert</span><span class="sxs-lookup"><span data-stu-id="47140-110">Gets or sets the backup level message and recommendation, usually updated during failures</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.BackupStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.BackupStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As BackupStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.WindowsAzure.Management.StorSimple.Models.BackupStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.BackupStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47140-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="47140-111">Required.</span></span> <span data-ttu-id="47140-112">Ruft ab oder legt den Status der Sicherung migriert</span><span class="sxs-lookup"><span data-stu-id="47140-112">Gets or sets the status of the backup migrated</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>