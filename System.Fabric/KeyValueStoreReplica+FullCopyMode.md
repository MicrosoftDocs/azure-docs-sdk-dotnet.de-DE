<Type Name="KeyValueStoreReplica+FullCopyMode" FullName="System.Fabric.KeyValueStoreReplica+FullCopyMode">
  <TypeSignature Language="C#" Value="public enum KeyValueStoreReplica.FullCopyMode" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed KeyValueStoreReplica/FullCopyMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreReplica.FullCopyMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum KeyValueStoreReplica.FullCopyMode" />
  <TypeSignature Language="F#" Value="type KeyValueStoreReplica.FullCopyMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Gibt das Verhalten beim Erstellen der neuen sekundären Replikate (vollständige Kopie) verwendet.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.KeyValueStoreReplica/FullCopyMode Default = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.FullCopyMode.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="System.Fabric.KeyValueStoreReplica.FullCopyMode.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+FullCopyMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Die vollständige Kopiermodus im clustermanifest angegeben wird verwendet.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Logical">
      <MemberSignature Language="C#" Value="Logical" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.KeyValueStoreReplica/FullCopyMode Logical = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.FullCopyMode.Logical" />
      <MemberSignature Language="VB.NET" Value="Logical" />
      <MemberSignature Language="F#" Value="Logical = 2" Usage="System.Fabric.KeyValueStoreReplica.FullCopyMode.Logical" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+FullCopyMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Vollständige Kopien werden durch das Lesen von Inhalt für alle Datenbank ab und sendet sie an die sekundären Replikate für die Wiedergabe anhand ihrer eigenen Datenbanken ausgeführt werden. Da dieser Modus eine lang andauernde Transaktion auf dem primären Replikat für die Dauer des Builds öffnen erfordert, wird nur für kleine Datenbanken oder Dienste mit niedrigen Schreibaktivitäten empfohlen. In diesem Modus können veränderten Datenbankparameter, die normalerweise nach der Initialisierung behoben wird, wie z. B. wurden <see cref="P:System.Fabric.LocalEseStoreSettings.DatabasePageSizeInKB" /> und <see cref="P:System.Fabric.LocalEseStoreSettings.LogFileSizeInKB" />.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Physical">
      <MemberSignature Language="C#" Value="Physical" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.KeyValueStoreReplica/FullCopyMode Physical = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.FullCopyMode.Physical" />
      <MemberSignature Language="VB.NET" Value="Physical" />
      <MemberSignature Language="F#" Value="Physical = 1" Usage="System.Fabric.KeyValueStoreReplica.FullCopyMode.Physical" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+FullCopyMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Vollständige Kopien erfolgt durch eine Sicherung der Datenbank des primären Replikats und der physischen Datenbankdateien an sekundäre Replikate für die Wiederherstellung zu senden. Dies ist die empfohlene und Standardmodus.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Rebuild">
      <MemberSignature Language="C#" Value="Rebuild" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.KeyValueStoreReplica/FullCopyMode Rebuild = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.FullCopyMode.Rebuild" />
      <MemberSignature Language="VB.NET" Value="Rebuild" />
      <MemberSignature Language="F#" Value="Rebuild = 3" Usage="System.Fabric.KeyValueStoreReplica.FullCopyMode.Rebuild" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+FullCopyMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>Vollständige Kopien werden als physische Kopie, jedoch mit der Wiedergabe von Inhalt für alle Datenbank im primären Indexreihenfolge in eine neue Datenbank auf dem sekundären ein zusätzlicher Schritt ausgeführt werden. In diesem Modus können auch veränderten Datenbankparameter, die normalerweise nach der Initialisierung behoben werden, aber dauert länger als entweder physische oder logische Builds aufgrund der zusätzlichen Replay Schritt. Das endgültige Datenlayout ist nach der Wiedergabe optimal, seit einfügen Primärindex nacheinander. Derzeit wird unter Linux nicht unterstützt.</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>