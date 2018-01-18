<Type Name="TransactionIsolationLevel" FullName="System.Fabric.TransactionIsolationLevel">
  <TypeSignature Language="C#" Value="public enum TransactionIsolationLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TransactionIsolationLevel extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.TransactionIsolationLevel" />
  <TypeSignature Language="VB.NET" Value="Public Enum TransactionIsolationLevel" />
  <TypeSignature Language="F#" Value="type TransactionIsolationLevel = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="38aae-101">Listet den Satz von möglichen Isolationsstufen für eine <see cref="T:System.Fabric.Transaction" />.</span><span class="sxs-lookup"><span data-stu-id="38aae-101">Enumerates the set of possible isolation levels for a <see cref="T:System.Fabric.Transaction" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TransactionIsolationLevel Default = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TransactionIsolationLevel.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="System.Fabric.TransactionIsolationLevel.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TransactionIsolationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="38aae-102">Gibt die Standardisolationsstufe des Speichers an.</span><span class="sxs-lookup"><span data-stu-id="38aae-102">Indicates the default isolation level of the store.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ReadCommitted">
      <MemberSignature Language="C#" Value="ReadCommitted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TransactionIsolationLevel ReadCommitted = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TransactionIsolationLevel.ReadCommitted" />
      <MemberSignature Language="VB.NET" Value="ReadCommitted" />
      <MemberSignature Language="F#" Value="ReadCommitted = 2" Usage="System.Fabric.TransactionIsolationLevel.ReadCommitted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TransactionIsolationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="38aae-103">Gibt an, dass flüchtige Daten können nicht während der Transaktion gelesen werden, jedoch geändert werden können.</span><span class="sxs-lookup"><span data-stu-id="38aae-103">Indicates that volatile data cannot be read during the transaction, but can be modified.</span></span> <span data-ttu-id="38aae-104">Freigegebene Sperren werden aufrechterhalten, während Daten gelesen wird, werden um dirty Reads zu vermeiden, jedoch Daten können vor dem Ende der Transaktion, die zu nicht wiederholbaren Lesevorgängen oder Phantomdaten führt geändert werden.</span><span class="sxs-lookup"><span data-stu-id="38aae-104">Shared locks are held while data is being read to avoid dirty reads, but data can be changed before the end of the transaction that results in non-repeatable reads or phantom data.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ReadUncommitted">
      <MemberSignature Language="C#" Value="ReadUncommitted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TransactionIsolationLevel ReadUncommitted = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TransactionIsolationLevel.ReadUncommitted" />
      <MemberSignature Language="VB.NET" Value="ReadUncommitted" />
      <MemberSignature Language="F#" Value="ReadUncommitted = 1" Usage="System.Fabric.TransactionIsolationLevel.ReadUncommitted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TransactionIsolationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="38aae-105">Gibt an, dass die flüchtige Daten während der Transaktion gelesen werden können.</span><span class="sxs-lookup"><span data-stu-id="38aae-105">Indicates that volatile data can be read during the transaction.</span></span> 
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RepeatableRead">
      <MemberSignature Language="C#" Value="RepeatableRead" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TransactionIsolationLevel RepeatableRead = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TransactionIsolationLevel.RepeatableRead" />
      <MemberSignature Language="VB.NET" Value="RepeatableRead" />
      <MemberSignature Language="F#" Value="RepeatableRead = 3" Usage="System.Fabric.TransactionIsolationLevel.RepeatableRead" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TransactionIsolationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="38aae-106">Gibt an, dass die flüchtige Daten gelesen, jedoch nicht während der Transaktion geändert werden können.</span><span class="sxs-lookup"><span data-stu-id="38aae-106">Indicates that volatile data can be read but not modified during the transaction.</span></span> <span data-ttu-id="38aae-107">Sperren werden auf alle Daten platziert, die in einer Abfrage verwendet wird, um zu verhindern, dass andere Benutzer aktualisieren von Daten.</span><span class="sxs-lookup"><span data-stu-id="38aae-107">Locks are placed on all data that is used in a query to prevent other users from updating data.</span></span> <span data-ttu-id="38aae-108">Neue Zeilen in Datasets eingefügt werden können und in höheren Lesevorgänge in der aktuellen Transaktion enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="38aae-108">New rows can be inserted into data sets and are included in later reads in the current transaction.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Serializable">
      <MemberSignature Language="C#" Value="Serializable" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TransactionIsolationLevel Serializable = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TransactionIsolationLevel.Serializable" />
      <MemberSignature Language="VB.NET" Value="Serializable" />
      <MemberSignature Language="F#" Value="Serializable = 5" Usage="System.Fabric.TransactionIsolationLevel.Serializable" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TransactionIsolationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="38aae-109">Gibt an, dass flüchtige Daten serialisierbar sind.</span><span class="sxs-lookup"><span data-stu-id="38aae-109">Indicates that volatile data are serializable.</span></span> <span data-ttu-id="38aae-110">Flüchtige Daten können gelesen, aber nicht geändert, und während der Transaktions können keine neuen Daten hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="38aae-110">Volatile data can be read but not modified, and no new data can be added during the transaction.</span></span> <span data-ttu-id="38aae-111">Gibt dieses Bereichs liegt, die Sperren auf Datasets gelegt werden.</span><span class="sxs-lookup"><span data-stu-id="38aae-111">Indicates that range locks will be put on data sets.</span></span> <span data-ttu-id="38aae-112">Die Sperren verhindern Updates oder einfügungen in Datasets, bis die Transaktion abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="38aae-112">The locks prevent updates or inserts in data sets until the transaction finishes.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Snapshot">
      <MemberSignature Language="C#" Value="Snapshot" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TransactionIsolationLevel Snapshot = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TransactionIsolationLevel.Snapshot" />
      <MemberSignature Language="VB.NET" Value="Snapshot" />
      <MemberSignature Language="F#" Value="Snapshot = 4" Usage="System.Fabric.TransactionIsolationLevel.Snapshot" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TransactionIsolationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="38aae-113">Gibt die Momentaufnahme, in denen flüchtige Daten gelesen werden kann.</span><span class="sxs-lookup"><span data-stu-id="38aae-113">Indicates the snapshot level where volatile data can be read.</span></span> <span data-ttu-id="38aae-114">Alle Daten, die gelesen werden, werden eine Transaktion konsistente Version der Daten, die zu Beginn der Transaktion vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="38aae-114">Any data that is read will be a transaction-consistent version of the data that existed at start of the transaction.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>