<Type Name="ConsistencyLevel" FullName="Microsoft.Azure.Documents.ConsistencyLevel">
  <TypeSignature Language="C#" Value="public enum ConsistencyLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConsistencyLevel extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.ConsistencyLevel" />
  <TypeSignature Language="VB.NET" Value="Public Enum ConsistencyLevel" />
  <TypeSignature Language="F#" Value="type ConsistencyLevel = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary> 
            Hierbei handelt es sich um die konsistenzebenen von der Azure-Cosmos-DB-Dienst unterstützt.
            </summary>
    <remarks>
            Die angeforderte Konsistenzebene muss übereinstimmen oder schwächer als die, die für das Konto der Datenbank bereitgestellt werden.
            Weitere Informationen zu konsistenzebenen, finden Sie unter <see>http://azure.microsoft.com/documentation/articles/documentdb-consistency-levels/ "</see> Konsistenzebenen Artikel.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="BoundedStaleness">
      <MemberSignature Language="C#" Value="BoundedStaleness" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.ConsistencyLevel BoundedStaleness = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.ConsistencyLevel.BoundedStaleness" />
      <MemberSignature Language="VB.NET" Value="BoundedStaleness" />
      <MemberSignature Language="F#" Value="BoundedStaleness = 1" Usage="Microsoft.Azure.Documents.ConsistencyLevel.BoundedStaleness" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Begrenzter Veraltung garantiert, dass Lesevorgänge nicht zu veraltet sind. Dies kann basierend auf der Anzahl von Vorgängen (MaxStalenessPrefix) oder die Zeit (MaxStalenessIntervalInSeconds) konfiguriert werden.  Weitere Informationen zu MaxStalenessPrefix und MaxStalenessIntervalInSeconds, finden Sie unter <see cref="T:Microsoft.Azure.Documents.ConsistencyPolicy" />.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ConsistentPrefix">
      <MemberSignature Language="C#" Value="ConsistentPrefix" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.ConsistencyLevel ConsistentPrefix = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.ConsistencyLevel.ConsistentPrefix" />
      <MemberSignature Language="VB.NET" Value="ConsistentPrefix" />
      <MemberSignature Language="F#" Value="ConsistentPrefix = 4" Usage="Microsoft.Azure.Documents.ConsistencyLevel.ConsistentPrefix" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            ConsistentPrefix Konsistenz gewährleistet, dass Lesevorgänge einige Präfix alle Schreibvorgänge ohne Lücken zurückgegeben werden.
            Alle Schreibvorgänge werden schließlich stehen für Lesevorgänge.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Eventual">
      <MemberSignature Language="C#" Value="Eventual" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.ConsistencyLevel Eventual = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.ConsistencyLevel.Eventual" />
      <MemberSignature Language="VB.NET" Value="Eventual" />
      <MemberSignature Language="F#" Value="Eventual = 3" Usage="Microsoft.Azure.Documents.ConsistencyLevel.Eventual" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            Eventuelle Konsistenz wird sichergestellt, dass Lesevorgänge eine Teilmenge von Schreibvorgängen zurückgeben. Alle Schreibvorgänge werden schließlich stehen für Lesevorgänge.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Session">
      <MemberSignature Language="C#" Value="Session" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.ConsistencyLevel Session = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.ConsistencyLevel.Session" />
      <MemberSignature Language="VB.NET" Value="Session" />
      <MemberSignature Language="F#" Value="Session = 2" Usage="Microsoft.Azure.Documents.ConsistencyLevel.Session" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Die Sitzungskonsistenz garantiert monoton Lesevorgänge (Sie nie alte Daten gelesen und dann neue und alte erneut), monoton Schreibvorgänge (Schreibvorgänge sind geordnet) "und" Lesen "die Schreibvorgänge (die Schreibvorgänge sind sofort sichtbar, die Lesevorgänge) in einer Sitzung einzelnen. 
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Strong">
      <MemberSignature Language="C#" Value="Strong" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.ConsistencyLevel Strong = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.ConsistencyLevel.Strong" />
      <MemberSignature Language="VB.NET" Value="Strong" />
      <MemberSignature Language="F#" Value="Strong = 0" Usage="Microsoft.Azure.Documents.ConsistencyLevel.Strong" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Starke Konsistenz gewährleistet, die Lesevorgänge immer zurück, den Wert, der zuletzt geschrieben wurden.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>