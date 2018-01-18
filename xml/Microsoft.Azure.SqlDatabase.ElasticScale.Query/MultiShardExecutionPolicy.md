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
            <span data-ttu-id="6f967-101">Definiert die möglichen Abfrage Ausführungsrichtlinien</span><span class="sxs-lookup"><span data-stu-id="6f967-101">Defines the possible query execution policies</span></span>
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
            <span data-ttu-id="6f967-102">Mit der vollständigen Ergebnisse Ausführungsrichtlinie führt eine nicht erfolgreiche Ausführung anhand jeder Shard zu alle Ergebnisse, die verworfen wird und eine Ausnahme ausgelöst wird, indem Sie entweder die ExecuteReader-Methode für den Befehl oder die Read-Methode für den Reader.</span><span class="sxs-lookup"><span data-stu-id="6f967-102">With the complete results execution policy an unsuccessful execution against any shard leads to all results being discarded and an exception being thrown either by the ExecuteReader method on the command or the Read method on the reader.</span></span> 
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
            <span data-ttu-id="6f967-103">Eine Best-Effort-Ausführungsrichtlinie, die im Gegensatz zu CompleteResults, unvollständige fehlgeschlagenen befehlsausführung auf einige (aber nicht alle) Shards und die Ergebnisse der Befehle erfolgreich zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="6f967-103">A best-effort execution policy that, unlike CompleteResults, tolerates unsuccessful command execution on some (but not all) shards and returns the results of the successful commands.</span></span>  
            <span data-ttu-id="6f967-104">Alle aufgetretenen werden dem Benutzer zusammen mit den partiellen Ergebnissen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="6f967-104">Any errors encountered are returned to the user along with the partial results.</span></span>
            <span data-ttu-id="6f967-105">Der Aufrufer kann Ausnahmen, die beim Ausführen des Abfrageprozessors durch Überprüfen der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" /> Eigenschaft <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />.</span><span class="sxs-lookup"><span data-stu-id="6f967-105">The caller can inspect exceptions encountered during execution through the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" /> property of <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />.</span></span> 
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>