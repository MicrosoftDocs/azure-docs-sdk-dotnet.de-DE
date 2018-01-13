<Type Name="RestoreBackupRequest" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest">
  <TypeSignature Language="C#" Value="public class RestoreBackupRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RestoreBackupRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class RestoreBackupRequest" />
  <TypeSignature Language="F#" Value="type RestoreBackupRequest = class" />
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
            <span data-ttu-id="07aa1-101">Stellt eine Anforderung zum Wiederherstellen einer sicherungs.</span><span class="sxs-lookup"><span data-stu-id="07aa1-101">Represents a request to restore a backup.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreBackupRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="07aa1-102">Initialisiert eine neue Instanz der RestoreBackupRequest-Klasse.</span><span class="sxs-lookup"><span data-stu-id="07aa1-102">Initializes a new instance of the RestoreBackupRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreBackupRequest (string backupSetId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupSetId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (backupSetId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest : string -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupSetId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupSetId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupSetId">To be added.</param>
        <summary>
            <span data-ttu-id="07aa1-103">Initialisiert eine neue Instanz der RestoreBackupRequest-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="07aa1-103">Initializes a new instance of the RestoreBackupRequest class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSetId">
      <MemberSignature Language="C#" Value="public string BackupSetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupSetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest.BackupSetId" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupSetId As String" />
      <MemberSignature Language="F#" Value="member this.BackupSetId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest.BackupSetId" />
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
            <span data-ttu-id="07aa1-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="07aa1-104">Required.</span></span> <span data-ttu-id="07aa1-105">Dies ist der BackupSet zum Auslösen der Wiederherstellung aus.</span><span class="sxs-lookup"><span data-stu-id="07aa1-105">This is the BackupSet to trigger Recovery from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotId">
      <MemberSignature Language="C#" Value="public string SnapshotId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SnapshotId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest.SnapshotId" />
      <MemberSignature Language="VB.NET" Value="Public Property SnapshotId As String" />
      <MemberSignature Language="F#" Value="member this.SnapshotId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest.SnapshotId" />
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
            <span data-ttu-id="07aa1-106">Optional.</span><span class="sxs-lookup"><span data-stu-id="07aa1-106">Optional.</span></span> <span data-ttu-id="07aa1-107">Der momentaufnahmebezeichner.</span><span class="sxs-lookup"><span data-stu-id="07aa1-107">The snapshot identifier.</span></span> <span data-ttu-id="07aa1-108">Dies muss null sein, für den Fall, dass die vollständige Sicherung wiederhergestellt werden muss und ungleich Null festgelegt, wenn eine bestimmte Momentaufnahme wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="07aa1-108">This must be null in case the complete backup set needs to be restored and non-null if restoring a particular snapshot.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>