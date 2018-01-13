<Type Name="IndexKind" FullName="Microsoft.Azure.Documents.IndexKind">
  <TypeSignature Language="C#" Value="public enum IndexKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed IndexKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.IndexKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum IndexKind" />
  <TypeSignature Language="F#" Value="type IndexKind = " />
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
            Dies sind die Volltextindizierung Typen, die für die Indizierung eines Pfads in der Azure-Cosmos-DB-Dienst verfügbar.
            </summary>
    <remarks>
            Weitere Informationen finden Sie unter http://azure.microsoft.com/documentation/articles/documentdb-indexing-policies/#ConfigPolicy.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Hash">
      <MemberSignature Language="C#" Value="Hash" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.IndexKind Hash = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.IndexKind.Hash" />
      <MemberSignature Language="VB.NET" Value="Hash" />
      <MemberSignature Language="F#" Value="Hash = 0" Usage="Microsoft.Azure.Documents.IndexKind.Hash" />
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
        <ReturnType>Microsoft.Azure.Documents.IndexKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Die Indexeinträge werden hinzugefügt, um Punkt Nachschlagen Abfragen zu fungieren.
            </summary>
        <remarks>
            Kann verwendet werden, um Abfragen wie dienen: Wählen Sie * aus Docs d WHERE d.prop = 5
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Range">
      <MemberSignature Language="C#" Value="Range" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.IndexKind Range = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.IndexKind.Range" />
      <MemberSignature Language="VB.NET" Value="Range" />
      <MemberSignature Language="F#" Value="Range = 1" Usage="Microsoft.Azure.Documents.IndexKind.Range" />
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
        <ReturnType>Microsoft.Azure.Documents.IndexKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Die Indexeinträge werden sortiert. Bereichsindizes sind für Ungleichheit Prädikat Abfragen mit effiziente Bereichsscans optimiert.
            </summary>
        <remarks>
            Kann verwendet werden, um Abfragen wie dienen: Wählen Sie * aus Docs d WHERE d.prop &gt; 5
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Spatial">
      <MemberSignature Language="C#" Value="Spatial" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.IndexKind Spatial = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.IndexKind.Spatial" />
      <MemberSignature Language="VB.NET" Value="Spatial" />
      <MemberSignature Language="F#" Value="Spatial = 2" Usage="Microsoft.Azure.Documents.IndexKind.Spatial" />
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
        <ReturnType>Microsoft.Azure.Documents.IndexKind</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Die Indexeinträge werden indiziert, um Abfragen nach räumlichen Daten dienen.
            </summary>
        <remarks>
            Kann verwendet werden, um Abfragen wie dienen: Wählen Sie * FROM Root R, in denen ST_DISTANCE({"type":"Point","coordinates":[71.0589,42.3601]}, r.location) $LE 10000
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>