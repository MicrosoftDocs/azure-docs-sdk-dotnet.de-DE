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
            Stellt eine Anforderung zum Wiederherstellen einer sicherungs.
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
            Initialisiert eine neue Instanz der RestoreBackupRequest-Klasse.
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
            Initialisiert eine neue Instanz der RestoreBackupRequest-Klasse mit erforderlichen Argumenten.
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
            Erforderlich. Dies ist der BackupSet zum Auslösen der Wiederherstellung aus.
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
            Optional. Der momentaufnahmebezeichner. Dies muss null sein, für den Fall, dass die vollständige Sicherung wiederhergestellt werden muss und ungleich Null festgelegt, wenn eine bestimmte Momentaufnahme wiederherstellen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>