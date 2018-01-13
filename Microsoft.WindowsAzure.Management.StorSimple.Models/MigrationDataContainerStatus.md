<Type Name="MigrationDataContainerStatus" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus">
  <TypeSignature Language="C#" Value="public class MigrationDataContainerStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MigrationDataContainerStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class MigrationDataContainerStatus" />
  <TypeSignature Language="F#" Value="type MigrationDataContainerStatus = class" />
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
            Diese Klasse die darstellt Status der Volume-Container (Cloud-Konfiguration) migriert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrationDataContainerStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der MigrationDataContainerStatus-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet&gt; BackupSets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet&gt; BackupSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.BackupSets" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupSets As IList(Of MigrationBackupSet)" />
      <MemberSignature Language="F#" Value="member this.BackupSets : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.BackupSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Ruft ab oder legt den Status der sämtliche Sicherungsaufgaben migriert wird, für den angegebenen volumecontainer
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudConfigurationName">
      <MemberSignature Language="C#" Value="public string CloudConfigurationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CloudConfigurationName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.CloudConfigurationName" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudConfigurationName As String" />
      <MemberSignature Language="F#" Value="member this.CloudConfigurationName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.CloudConfigurationName" />
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
            Erforderlich. Ruft ab oder legt den Namen des volumecontainers
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageInfo">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo MessageInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo MessageInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.MessageInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageInfo As HcsMessageInfo" />
      <MemberSignature Language="F#" Value="member this.MessageInfo : Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.MessageInfo" />
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
            Erforderlich. Ruft ab oder legt die Volume-Container Ebene Nachricht oder die Empfehlung, in der Regel auf, wenn ein Fehler, während der Migration aufgetreten ist
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentageCompleted">
      <MemberSignature Language="C#" Value="public int PercentageCompleted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PercentageCompleted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.PercentageCompleted" />
      <MemberSignature Language="VB.NET" Value="Public Property PercentageCompleted As Integer" />
      <MemberSignature Language="F#" Value="member this.PercentageCompleted : int with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.PercentageCompleted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Ruft ab oder legt ihn fest Prozentsatz der Migration abgeschlossen wurde
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As MigrationStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Ruft ab oder legt ihn fest Status der migration
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>