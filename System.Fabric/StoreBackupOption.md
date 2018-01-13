<Type Name="StoreBackupOption" FullName="System.Fabric.StoreBackupOption">
  <TypeSignature Language="C#" Value="public enum StoreBackupOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed StoreBackupOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.StoreBackupOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum StoreBackupOption" />
  <TypeSignature Language="F#" Value="type StoreBackupOption = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>
            Die Sicherungsoption für die Schlüssel / Wert-Speicher.
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Full">
      <MemberSignature Language="C#" Value="Full" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.StoreBackupOption Full = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.StoreBackupOption.Full" />
      <MemberSignature Language="VB.NET" Value="Full" />
      <MemberSignature Language="F#" Value="Full = 1" Usage="System.Fabric.StoreBackupOption.Full" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.StoreBackupOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>
            Eine vollständige Sicherung der Schlüssel / Wert-Speicher.
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Incremental">
      <MemberSignature Language="C#" Value="Incremental" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.StoreBackupOption Incremental = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.StoreBackupOption.Incremental" />
      <MemberSignature Language="VB.NET" Value="Incremental" />
      <MemberSignature Language="F#" Value="Incremental = 2" Usage="System.Fabric.StoreBackupOption.Incremental" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.StoreBackupOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>
            Inkrementelle Sicherung für den Schlüssel / Wert-Speicher. d. h. nur die Protokolldateien erstellt, da die letzte vollständige oder inkrementelle Sicherung gesichert werden.
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="TruncateLogsOnly">
      <MemberSignature Language="C#" Value="TruncateLogsOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.StoreBackupOption TruncateLogsOnly = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />
      <MemberSignature Language="VB.NET" Value="TruncateLogsOnly" />
      <MemberSignature Language="F#" Value="TruncateLogsOnly = 3" Usage="System.Fabric.StoreBackupOption.TruncateLogsOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.StoreBackupOption</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>
            Die Option der Transaktionsprotokolle der der Schlüssel / Wert-Speicher abgeschnitten werden, ohne dass alle Sicherungsdateien erstellt.        
            </para>
        </summary>
        <remarks>
            Dies ist nützlich, in die Erstellung von Sicherungsdateien im sekundären Replikaten zu vermeiden, wenn die inkrementeller Sicherung aktiviert ist.
            Wenn die inkrementeller Sicherung aktiviert ist, füllt Speicherplatz einrichten mit Transaktionsprotokollen, der die Schlüssel / Wert-Speicher.
            Um dies zu verhindern, müssen über häufige Sicherungen erstellt werden. Allerdings erstellen Sicherungen auf sekundären Replikaten nützlich bei einigen Diensten Schlüssel / Wert-Speicher möglicherweise nicht. Diese Dienste müssen auch zurecht, verwerfen das Sicherungsverzeichnis. Wenn diese Option verwendet wird, bereinigt es die Transaktionsprotokolle ohne Sicherungsdateien erstellen.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>