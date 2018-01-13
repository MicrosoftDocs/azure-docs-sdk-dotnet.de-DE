<Type Name="MultiShardExecutionOptions" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions">
  <TypeSignature Language="C#" Value="public enum MultiShardExecutionOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed MultiShardExecutionOptions extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions" />
  <TypeSignature Language="VB.NET" Value="Public Enum MultiShardExecutionOptions" />
  <TypeSignature Language="F#" Value="type MultiShardExecutionOptions = " />
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
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="d91d0-101">Definiert die verfügbaren Optionen beim Ausführen von Befehlen für mehrere shards</span><span class="sxs-lookup"><span data-stu-id="d91d0-101">Defines the available options when executing commands against multiple shards</span></span>
            </summary>
    <remarks><span data-ttu-id="d91d0-102">Diese Enumeration verfügt über eine Flags-Attribut</span><span class="sxs-lookup"><span data-stu-id="d91d0-102">This enumeration has a flags attribute</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="IncludeShardNameColumn">
      <MemberSignature Language="C#" Value="IncludeShardNameColumn" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions IncludeShardNameColumn = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions.IncludeShardNameColumn" />
      <MemberSignature Language="VB.NET" Value="IncludeShardNameColumn" />
      <MemberSignature Language="F#" Value="IncludeShardNameColumn = 1" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions.IncludeShardNameColumn" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="d91d0-103">Gibt an, ob die $ShardName Pseudo-Spalte in den Resultsets aufgenommen wird.</span><span class="sxs-lookup"><span data-stu-id="d91d0-103">Whether the $ShardName pseudo column should be included in the result-sets.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="d91d0-104">, Ohne Optionen aktiviert ausführen</span><span class="sxs-lookup"><span data-stu-id="d91d0-104">, Execute without any options enabled</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>