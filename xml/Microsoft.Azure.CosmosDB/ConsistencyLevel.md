<Type Name="ConsistencyLevel" FullName="Microsoft.Azure.CosmosDB.ConsistencyLevel">
  <TypeSignature Language="C#" Value="public enum ConsistencyLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConsistencyLevel extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.ConsistencyLevel" />
  <TypeSignature Language="VB.NET" Value="Public Enum ConsistencyLevel" />
  <TypeSignature Language="F#" Value="type ConsistencyLevel = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary> 
            <span data-ttu-id="1ae3f-101">Hierbei handelt es sich um die konsistenzebenen von der Azure-Cosmos-DB-Dienst unterstützt.</span><span class="sxs-lookup"><span data-stu-id="1ae3f-101">These are the consistency levels supported by the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="1ae3f-102">Die angeforderte Konsistenzebene muss übereinstimmen oder schwächer als die, die für das Konto der Datenbank bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="1ae3f-102">The requested Consistency Level must match or be weaker than that provisioned for the database account.</span></span>
            <span data-ttu-id="1ae3f-103">Weitere Informationen zu konsistenzebenen, finden Sie unter <see>http://azure.microsoft.com/documentation/articles/documentdb-consistency-levels/ "</see> Konsistenzebenen Artikel.</span><span class="sxs-lookup"><span data-stu-id="1ae3f-103">For more information on consistency levels, please see <see>http://azure.microsoft.com/documentation/articles/documentdb-consistency-levels/"</see> Consistency Levels article.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="BoundedStaleness">
      <MemberSignature Language="C#" Value="BoundedStaleness" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel BoundedStaleness = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.ConsistencyLevel.BoundedStaleness" />
      <MemberSignature Language="VB.NET" Value="BoundedStaleness" />
      <MemberSignature Language="F#" Value="BoundedStaleness = 1" Usage="Microsoft.Azure.CosmosDB.ConsistencyLevel.BoundedStaleness" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ae3f-104">Begrenzter Veraltung garantiert, dass Lesevorgänge nicht zu veraltet sind.</span><span class="sxs-lookup"><span data-stu-id="1ae3f-104">Bounded Staleness guarantees that reads are not too out-of-date.</span></span> <span data-ttu-id="1ae3f-105">Dies kann basierend auf der Anzahl von Vorgängen (MaxStalenessPrefix) oder die Zeit (MaxStalenessIntervalInSeconds) konfiguriert werden.</span><span class="sxs-lookup"><span data-stu-id="1ae3f-105">This can be configured based on number of operations (MaxStalenessPrefix) or time (MaxStalenessIntervalInSeconds).</span></span>  <span data-ttu-id="1ae3f-106">Weitere Informationen zu MaxStalenessPrefix und MaxStalenessIntervalInSeconds, finden Sie unter <see cref="T:Microsoft.Azure.Documents.ConsistencyPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="1ae3f-106">For more information on MaxStalenessPrefix and MaxStalenessIntervalInSeconds, please see <see cref="T:Microsoft.Azure.Documents.ConsistencyPolicy" />.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ConsistentPrefix">
      <MemberSignature Language="C#" Value="ConsistentPrefix" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel ConsistentPrefix = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.ConsistencyLevel.ConsistentPrefix" />
      <MemberSignature Language="VB.NET" Value="ConsistentPrefix" />
      <MemberSignature Language="F#" Value="ConsistentPrefix = 4" Usage="Microsoft.Azure.CosmosDB.ConsistencyLevel.ConsistentPrefix" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ae3f-107">ConsistentPrefix Konsistenz gewährleistet, dass Lesevorgänge einige Präfix alle Schreibvorgänge ohne Lücken zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="1ae3f-107">ConsistentPrefix Consistency guarantees that reads will return some prefix of all writes with no gaps.</span></span>
            <span data-ttu-id="1ae3f-108">Alle Schreibvorgänge werden schließlich stehen für Lesevorgänge.</span><span class="sxs-lookup"><span data-stu-id="1ae3f-108">All writes will be eventually be available for reads.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Eventual">
      <MemberSignature Language="C#" Value="Eventual" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel Eventual = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.ConsistencyLevel.Eventual" />
      <MemberSignature Language="VB.NET" Value="Eventual" />
      <MemberSignature Language="F#" Value="Eventual = 3" Usage="Microsoft.Azure.CosmosDB.ConsistencyLevel.Eventual" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ae3f-109">Eventuelle Konsistenz wird sichergestellt, dass Lesevorgänge eine Teilmenge von Schreibvorgängen zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="1ae3f-109">Eventual Consistency guarantees that reads will return a subset of writes.</span></span> <span data-ttu-id="1ae3f-110">Alle Schreibvorgänge werden schließlich stehen für Lesevorgänge.</span><span class="sxs-lookup"><span data-stu-id="1ae3f-110">All writes will be eventually be available for reads.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Session">
      <MemberSignature Language="C#" Value="Session" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel Session = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.ConsistencyLevel.Session" />
      <MemberSignature Language="VB.NET" Value="Session" />
      <MemberSignature Language="F#" Value="Session = 2" Usage="Microsoft.Azure.CosmosDB.ConsistencyLevel.Session" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ae3f-111">Die Sitzungskonsistenz garantiert monoton Lesevorgänge (Sie nie alte Daten gelesen und dann neue und alte erneut), monoton Schreibvorgänge (Schreibvorgänge sind geordnet) "und" Lesen "die Schreibvorgänge (die Schreibvorgänge sind sofort sichtbar, die Lesevorgänge) in einer Sitzung einzelnen.</span><span class="sxs-lookup"><span data-stu-id="1ae3f-111">Session Consistency guarantees monotonic reads (you never read old data, then new, then old again), monotonic writes (writes are ordered) and read your writes (your writes are immediately visible to your reads) within any single session.</span></span> 
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Strong">
      <MemberSignature Language="C#" Value="Strong" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel Strong = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.ConsistencyLevel.Strong" />
      <MemberSignature Language="VB.NET" Value="Strong" />
      <MemberSignature Language="F#" Value="Strong = 0" Usage="Microsoft.Azure.CosmosDB.ConsistencyLevel.Strong" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ae3f-112">Starke Konsistenz gewährleistet, die Lesevorgänge immer zurück, den Wert, der zuletzt geschrieben wurden.</span><span class="sxs-lookup"><span data-stu-id="1ae3f-112">Strong Consistency guarantees that read operations always return the value that was last written.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>