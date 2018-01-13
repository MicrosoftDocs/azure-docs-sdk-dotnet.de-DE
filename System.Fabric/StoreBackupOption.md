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
            <span data-ttu-id="ef331-101">Die Sicherungsoption für die Schlüssel / Wert-Speicher.</span><span class="sxs-lookup"><span data-stu-id="ef331-101">The backup option for the key-value store.</span></span>
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
            <span data-ttu-id="ef331-102">Eine vollständige Sicherung der Schlüssel / Wert-Speicher.</span><span class="sxs-lookup"><span data-stu-id="ef331-102">A full backup of the key-value store.</span></span>
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
            <span data-ttu-id="ef331-103">Inkrementelle Sicherung für den Schlüssel / Wert-Speicher.</span><span class="sxs-lookup"><span data-stu-id="ef331-103">Incremental backup of the key-value store.</span></span> <span data-ttu-id="ef331-104">d. h. nur die Protokolldateien erstellt, da die letzte vollständige oder inkrementelle Sicherung gesichert werden.</span><span class="sxs-lookup"><span data-stu-id="ef331-104">i.e. only the log files created since the last full or incremental backup will be backed up.</span></span>
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
            <span data-ttu-id="ef331-105">Die Option der Transaktionsprotokolle der der Schlüssel / Wert-Speicher abgeschnitten werden, ohne dass alle Sicherungsdateien erstellt.</span><span class="sxs-lookup"><span data-stu-id="ef331-105">Option to truncate the transaction logs of the key-value store without creating any backup files.</span></span>        
            </para>
        </summary>
        <remarks>
            <span data-ttu-id="ef331-106">Dies ist nützlich, in die Erstellung von Sicherungsdateien im sekundären Replikaten zu vermeiden, wenn die inkrementeller Sicherung aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="ef331-106">This is useful in avoiding creation of backup files in secondary replicas when incremental backup is turned on.</span></span>
            <span data-ttu-id="ef331-107">Wenn die inkrementeller Sicherung aktiviert ist, füllt Speicherplatz einrichten mit Transaktionsprotokollen, der die Schlüssel / Wert-Speicher.</span><span class="sxs-lookup"><span data-stu-id="ef331-107">If incremental backup is turned on, then disk space fills up with transaction logs of the key-value store.</span></span>
            <span data-ttu-id="ef331-108">Um dies zu verhindern, müssen über häufige Sicherungen erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="ef331-108">To prevent this, frequent backups have to be created.</span></span> <span data-ttu-id="ef331-109">Allerdings erstellen Sicherungen auf sekundären Replikaten nützlich bei einigen Diensten Schlüssel / Wert-Speicher möglicherweise nicht.</span><span class="sxs-lookup"><span data-stu-id="ef331-109">However, creating backups on secondary replicas may not be useful for some key-value store services.</span></span> <span data-ttu-id="ef331-110">Diese Dienste müssen auch zurecht, verwerfen das Sicherungsverzeichnis.</span><span class="sxs-lookup"><span data-stu-id="ef331-110">These services also have to deal with discarding the backup directory.</span></span> <span data-ttu-id="ef331-111">Wenn diese Option verwendet wird, bereinigt es die Transaktionsprotokolle ohne Sicherungsdateien erstellen.</span><span class="sxs-lookup"><span data-stu-id="ef331-111">If this option is used, it cleans up the transaction logs without creating backup files.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>