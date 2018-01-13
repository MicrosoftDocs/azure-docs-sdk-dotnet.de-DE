<Type Name="AccessConditionType" FullName="Microsoft.Azure.Documents.Client.AccessConditionType">
  <TypeSignature Language="C#" Value="public enum AccessConditionType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed AccessConditionType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.AccessConditionType" />
  <TypeSignature Language="VB.NET" Value="Public Enum AccessConditionType" />
  <TypeSignature Language="F#" Value="type AccessConditionType = " />
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
            Gibt den Satz der <see cref="T:Microsoft.Azure.Documents.Client.AccessCondition" /> Typen, die für Vorgänge in der Azure-Cosmos-DB-Dienst verwendet werden können. 
            </summary>
    <remarks>To be added.</remarks>
    <altmember cref="T:Microsoft.Azure.Documents.Client.AccessCondition" />
    <altmember cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />
  </Docs>
  <Members>
    <Member MemberName="IfMatch">
      <MemberSignature Language="C#" Value="IfMatch" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.Client.AccessConditionType IfMatch = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.Client.AccessConditionType.IfMatch" />
      <MemberSignature Language="VB.NET" Value="IfMatch" />
      <MemberSignature Language="F#" Value="IfMatch = 0" Usage="Microsoft.Azure.Documents.Client.AccessConditionType.IfMatch" />
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
        <ReturnType>Microsoft.Azure.Documents.Client.AccessConditionType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Überprüfen Sie, ob der ETag-Wert der Ressource entspricht, den ETag-Wert ausgeführt.
            </summary>
        <remarks>
            Das Dokument für die Steuerung durch vollständige Parallelität verwendet, z. B. ersetzt werden, nur verwendet werden, wenn das ETag identisch mit dem Kennwort in der Anforderung zur Vermeidung von verlorenen Updates enthalten ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IfNoneMatch">
      <MemberSignature Language="C#" Value="IfNoneMatch" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.Client.AccessConditionType IfNoneMatch = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.Client.AccessConditionType.IfNoneMatch" />
      <MemberSignature Language="VB.NET" Value="IfNoneMatch" />
      <MemberSignature Language="F#" Value="IfNoneMatch = 1" Usage="Microsoft.Azure.Documents.Client.AccessConditionType.IfNoneMatch" />
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
        <ReturnType>Microsoft.Azure.Documents.Client.AccessConditionType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Überprüfen Sie, ob der ETag-Wert der Ressource nicht ausgeführt ETag-Wert übereinstimmt.
            </summary>
        <remarks>
            Zurück zum Zwischenspeichern von Szenarien verwendet, um den Netzwerkverkehr zu reduzieren, z. B. das Dokument in der Nutzlast, nur dann, wenn das ETag, von dem die Anforderung geändert hat.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>