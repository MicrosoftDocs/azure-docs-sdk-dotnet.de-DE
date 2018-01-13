<Type Name="StoreBackupInfo" FullName="System.Fabric.StoreBackupInfo">
  <TypeSignature Language="C#" Value="public sealed class StoreBackupInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StoreBackupInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.StoreBackupInfo" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StoreBackupInfo" />
  <TypeSignature Language="F#" Value="type StoreBackupInfo = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Enthält Informationen über die Sicherung erstellt, durch den Aufruf <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StoreBackupInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.StoreBackupInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupChainId">
      <MemberSignature Language="C#" Value="public Guid BackupChainId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid BackupChainId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.StoreBackupInfo.BackupChainId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupChainId As Guid" />
      <MemberSignature Language="F#" Value="member this.BackupChainId : Guid" Usage="System.Fabric.StoreBackupInfo.BackupChainId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft die ID der Backup-Kette, zu der diese Sicherung gehört. Eine Sicherung Kette enthält eine vollständige Sicherung und NULL oder mehr fortlaufenden inkrementelle Sicherung(en) und beginnt bei vollständige Sicherung. 
            </para>
        </summary>
        <value>
          <para>Die ID der sicherungskette.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupFolder">
      <MemberSignature Language="C#" Value="public string BackupFolder { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupFolder" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.StoreBackupInfo.BackupFolder" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupFolder As String" />
      <MemberSignature Language="F#" Value="member this.BackupFolder : string" Usage="System.Fabric.StoreBackupInfo.BackupFolder" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Ordner, in dem die Sicherung erstellt wurde.</para>
        </summary>
        <value>
          <para>Der Sicherungsordner</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupIndex">
      <MemberSignature Language="C#" Value="public long BackupIndex { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 BackupIndex" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.StoreBackupInfo.BackupIndex" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupIndex As Long" />
      <MemberSignature Language="F#" Value="member this.BackupIndex : int64" Usage="System.Fabric.StoreBackupInfo.BackupIndex" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft den Index dieser Sicherung in der Backup-Kette, zu der diese Sicherung gehört.
            Eine Sicherung Kette enthält eine vollständige Sicherung und NULL oder mehr fortlaufenden inkrementelle Sicherung(en).
            und beginnt bei der vollständigen Sicherung. Da die vollständige Sicherung die Kette beginnt, ist der Sicherung Index immer 0 (null).
            </para>
        </summary>
        <value>
          <para>Die Sicherung Index der aktuellen Sicherung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupOption">
      <MemberSignature Language="C#" Value="public System.Fabric.StoreBackupOption BackupOption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.StoreBackupOption BackupOption" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.StoreBackupInfo.BackupOption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupOption As StoreBackupOption" />
      <MemberSignature Language="F#" Value="member this.BackupOption : System.Fabric.StoreBackupOption" Usage="System.Fabric.StoreBackupInfo.BackupOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.StoreBackupOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Sicherungsoption verwendet</para>
        </summary>
        <value>
          <para>Die Sicherungsoption verwendet</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.StoreBackupInfo.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="storeBackupInfo.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Gibt eine <see cref="T:System.String" /> , das diese Instanz darstellt.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.String" /> , das diese Instanz darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>