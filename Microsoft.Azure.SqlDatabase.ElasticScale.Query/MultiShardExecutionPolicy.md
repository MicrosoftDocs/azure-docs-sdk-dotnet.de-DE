<Type Name="MultiShardExecutionPolicy" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy">
  <TypeSignature Language="C#" Value="public enum MultiShardExecutionPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed MultiShardExecutionPolicy extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Enum MultiShardExecutionPolicy" />
  <TypeSignature Language="F#" Value="type MultiShardExecutionPolicy = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1704:IdentifiersShouldBeSpelledCorrectly", MessageId="Multi")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Definiert die möglichen Abfrage Ausführungsrichtlinien
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CompleteResults">
      <MemberSignature Language="C#" Value="CompleteResults" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy CompleteResults = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy.CompleteResults" />
      <MemberSignature Language="VB.NET" Value="CompleteResults" />
      <MemberSignature Language="F#" Value="CompleteResults = 0" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy.CompleteResults" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Mit der vollständigen Ergebnisse Ausführungsrichtlinie führt eine nicht erfolgreiche Ausführung anhand jeder Shard zu alle Ergebnisse, die verworfen wird und eine Ausnahme ausgelöst wird, indem Sie entweder die ExecuteReader-Methode für den Befehl oder die Read-Methode für den Reader. 
            </summary>
      </Docs>
    </Member>
    <Member MemberName="PartialResults">
      <MemberSignature Language="C#" Value="PartialResults" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy PartialResults = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy.PartialResults" />
      <MemberSignature Language="VB.NET" Value="PartialResults" />
      <MemberSignature Language="F#" Value="PartialResults = 1" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy.PartialResults" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Eine Best-Effort-Ausführungsrichtlinie, die im Gegensatz zu CompleteResults, unvollständige fehlgeschlagenen befehlsausführung auf einige (aber nicht alle) Shards und die Ergebnisse der Befehle erfolgreich zurückgegeben.  
            Alle aufgetretenen werden dem Benutzer zusammen mit den partiellen Ergebnissen zurückgegeben.
            Der Aufrufer kann Ausnahmen, die beim Ausführen des Abfrageprozessors durch Überprüfen der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" /> Eigenschaft <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />. 
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>