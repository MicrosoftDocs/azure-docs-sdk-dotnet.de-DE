<Type Name="BackupInfo" FullName="Microsoft.ServiceFabric.Data.BackupInfo">
  <TypeSignature Language="C#" Value="public class BackupInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.BackupInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupInfo" />
  <TypeSignature Language="F#" Value="type BackupInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Enthält Informationen zu der Sicherung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupInfo (string directory, Microsoft.ServiceFabric.Data.BackupOption option, Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string directory, valuetype Microsoft.ServiceFabric.Data.BackupOption option, valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupInfo.#ctor(System.String,Microsoft.ServiceFabric.Data.BackupOption,Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (directory As String, option As BackupOption, version As BackupInfo.BackupVersion)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.BackupInfo : string * Microsoft.ServiceFabric.Data.BackupOption * Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion -&gt; Microsoft.ServiceFabric.Data.BackupInfo" Usage="new Microsoft.ServiceFabric.Data.BackupInfo (directory, option, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="directory" Type="System.String" />
        <Parameter Name="option" Type="Microsoft.ServiceFabric.Data.BackupOption" />
        <Parameter Name="version" Type="Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion" />
      </Parameters>
      <Docs>
        <param name="directory">Der Ordnerpfad, der die Sicherung enthält.</param>
        <param name="option">
          <cref name="BackupOption" />die zum Speichern der Sicherung verwendet wurde.</param>
        <param name="version">
          <cref name="BackupVersion" />der Sicherung.</param>
        <summary>
            Initialisiert eine neue Instanz der <cref name="BackupInfo" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupInfo (string directory, Microsoft.ServiceFabric.Data.BackupOption option, Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion version, Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion startBackupVersion, Guid backupId, Guid parentBackupId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string directory, valuetype Microsoft.ServiceFabric.Data.BackupOption option, valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion version, valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion startBackupVersion, valuetype System.Guid backupId, valuetype System.Guid parentBackupId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupInfo.#ctor(System.String,Microsoft.ServiceFabric.Data.BackupOption,Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion,Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion,System.Guid,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (directory As String, option As BackupOption, version As BackupInfo.BackupVersion, startBackupVersion As BackupInfo.BackupVersion, backupId As Guid, parentBackupId As Guid)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.BackupInfo : string * Microsoft.ServiceFabric.Data.BackupOption * Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion * Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion * Guid * Guid -&gt; Microsoft.ServiceFabric.Data.BackupInfo" Usage="new Microsoft.ServiceFabric.Data.BackupInfo (directory, option, version, startBackupVersion, backupId, parentBackupId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="directory" Type="System.String" />
        <Parameter Name="option" Type="Microsoft.ServiceFabric.Data.BackupOption" />
        <Parameter Name="version" Type="Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion" />
        <Parameter Name="startBackupVersion" Type="Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion" />
        <Parameter Name="backupId" Type="System.Guid" />
        <Parameter Name="parentBackupId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="directory">Der Ordnerpfad, der die Sicherung enthält.</param>
        <param name="option">
          <cref name="BackupOption" />die zum Speichern der Sicherung verwendet wurde.</param>
        <param name="version">
          <cref name="BackupVersion" />der Sicherung.</param>
        <param name="startBackupVersion">
          <cref name="BackupVersion" />der erste logische Protokolldatensatz in der Sicherung.</param>
        <param name="backupId">Die ID der Sicherung.</param>
        <param name="parentBackupId">ID der entsprechenden bei inkrementellen Sicherungen "GUID.Empty" vollständige Sicherung für den Fall, dass dies ist eine vollständige Sicherung.</param>
        <summary>
            Initialisiert eine neue Instanz der <cref name="BackupInfo" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupId">
      <MemberSignature Language="C#" Value="public Guid BackupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid BackupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupInfo.BackupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupId As Guid" />
      <MemberSignature Language="F#" Value="member this.BackupId : Guid" Usage="Microsoft.ServiceFabric.Data.BackupInfo.BackupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Backup-Id ab
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Directory">
      <MemberSignature Language="C#" Value="public string Directory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Directory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupInfo.Directory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Directory As String" />
      <MemberSignature Language="F#" Value="member this.Directory : string" Usage="Microsoft.ServiceFabric.Data.BackupInfo.Directory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Verzeichnis, in dem die Sicherung erstellt wurde. 
            </summary>
        <value>Das Verzeichnis, das die Sicherung enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Option">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.BackupOption Option { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.BackupOption Option" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupInfo.Option" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Option As BackupOption" />
      <MemberSignature Language="F#" Value="member this.Option : Microsoft.ServiceFabric.Data.BackupOption" Usage="Microsoft.ServiceFabric.Data.BackupInfo.Option" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.BackupOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Sicherungsoption verwendet.
            </summary>
        <value>Die <cref name="BackupOption" /> , der zum Speichern der Sicherung verwendet wurde.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParentBackupId">
      <MemberSignature Language="C#" Value="public Guid ParentBackupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid ParentBackupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupInfo.ParentBackupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ParentBackupId As Guid" />
      <MemberSignature Language="F#" Value="member this.ParentBackupId : Guid" Usage="Microsoft.ServiceFabric.Data.BackupInfo.ParentBackupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die ID des übergeordneten Elements-Sicherung
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartBackupVersion">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion StartBackupVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion StartBackupVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupInfo.StartBackupVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartBackupVersion As BackupInfo.BackupVersion" />
      <MemberSignature Language="F#" Value="member this.StartBackupVersion : Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion" Usage="Microsoft.ServiceFabric.Data.BackupInfo.StartBackupVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die erste Epoche und LSN in der Sicherung
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupInfo.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="backupInfo.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt eine Zeichenfolge, die diese Instanz darstellt.
            </summary>
        <returns>Eine Zeichenfolge, die diese Instanz darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupInfo.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As BackupInfo.BackupVersion" />
      <MemberSignature Language="F#" Value="member this.Version : Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion" Usage="Microsoft.ServiceFabric.Data.BackupInfo.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das aktuelle Epoche und LSN, die in der Sicherung enthalten.
            </summary>
        <value>
          <cref name="BackupVersion" />der Sicherung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>