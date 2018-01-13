<Type Name="RestoreDescription" FullName="Microsoft.ServiceFabric.Data.RestoreDescription">
  <TypeSignature Language="C#" Value="public struct RestoreDescription" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi sealed beforefieldinit RestoreDescription extends System.ValueType" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.RestoreDescription" />
  <TypeSignature Language="VB.NET" Value="Public Structure RestoreDescription" />
  <TypeSignature Language="F#" Value="type RestoreDescription = struct" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine RestoreDescription enthält alle Informationen, die zum Wiederherstellen eines zustandsbehafteten dienstreplikats erforderlich. 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreDescription (string backupFolderPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupFolderPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (backupFolderPath As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.RestoreDescription : string -&gt; Microsoft.ServiceFabric.Data.RestoreDescription" Usage="new Microsoft.ServiceFabric.Data.RestoreDescription backupFolderPath" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.
            Dieser Parameter kann nicht null, leer oder nur aus Leerzeichen bestehen. UNC-Pfade können auch angegeben werden.
            </param>
        <summary>
            Initialisiert eine neue Instanz der dem <cref name="RestoreDescription" /> Struktur
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreDescription (string backupFolderPath, Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupFolderPath, valuetype Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreDescription.#ctor(System.String,Microsoft.ServiceFabric.Data.RestorePolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.RestoreDescription : string * Microsoft.ServiceFabric.Data.RestorePolicy -&gt; Microsoft.ServiceFabric.Data.RestoreDescription" Usage="new Microsoft.ServiceFabric.Data.RestoreDescription (backupFolderPath, restorePolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
        <Parameter Name="restorePolicy" Type="Microsoft.ServiceFabric.Data.RestorePolicy" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.
            Dieser Parameter kann nicht null, leer oder nur aus Leerzeichen bestehen. UNC-Pfade können auch angegeben werden.
            </param>
        <param name="restorePolicy">Die Richtlinie für die Wiederherstellung.</param>
        <summary>
            Initialisiert eine neue Instanz der RestoreDescription-Struktur.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupFolderPath">
      <MemberSignature Language="C#" Value="public string BackupFolderPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupFolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupFolderPath As String" />
      <MemberSignature Language="F#" Value="member this.BackupFolderPath : string" Usage="Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" />
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
            Ruft das Verzeichnis, das wiederherzustellenden Zustand des Replikats verwendet wird.
            Dieser Parameter kann nicht null, leer oder nur aus Leerzeichen bestehen. UNC-Pfade können auch angegeben werden.
            </summary>
        <value>
            Das Verzeichnis der verwendet wird, um den Status für das Replikat wiederherzustellen.
            </value>
        <remarks>
            Ordner muss über mindestens eine vollständige Sicherung enthalten.
            Darüber hinaus kann es eine oder mehrere inkrementelle Sicherungen enthalten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Policy">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.RestorePolicy Policy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.RestorePolicy Policy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.RestoreDescription.Policy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Policy As RestorePolicy" />
      <MemberSignature Language="F#" Value="member this.Policy : Microsoft.ServiceFabric.Data.RestorePolicy" Usage="Microsoft.ServiceFabric.Data.RestoreDescription.Policy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.RestorePolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Richtlinie für die Wiederherstellung an.
            </summary>
        <value>
            Richtlinie für die Wiederherstellung verwendet werden soll.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>