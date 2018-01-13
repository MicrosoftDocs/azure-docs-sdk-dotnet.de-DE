<Type Name="ShardMapManagerLoadPolicy" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy">
  <TypeSignature Language="C#" Value="public enum ShardMapManagerLoadPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ShardMapManagerLoadPolicy extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Enum ShardMapManagerLoadPolicy" />
  <TypeSignature Language="F#" Value="type ShardMapManagerLoadPolicy = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="40d64-101">Beschreibt die Richtlinien, die zum Initialisieren des <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> aus dem Speicher.</span><span class="sxs-lookup"><span data-stu-id="40d64-101">Describes the policy used for initialization of <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> from the store.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Eager">
      <MemberSignature Language="C#" Value="Eager" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy Eager = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy.Eager" />
      <MemberSignature Language="VB.NET" Value="Eager" />
      <MemberSignature Language="F#" Value="Eager = 0" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy.Eager" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="40d64-102">Laden Sie alle shardzuordnungen und ihre entsprechenden Zuordnungen in den Cache für den schnellen Abruf.</span><span class="sxs-lookup"><span data-stu-id="40d64-102">Load all shard maps and their corresponding mappings into the cache for fast retrieval.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Lazy">
      <MemberSignature Language="C#" Value="Lazy" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy Lazy = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy.Lazy" />
      <MemberSignature Language="VB.NET" Value="Lazy" />
      <MemberSignature Language="F#" Value="Lazy = 1" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy.Lazy" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="40d64-103">Laden Sie alle shardzuordnungen und ihre entsprechenden Zuordnungen auf als Basis erforderlich.</span><span class="sxs-lookup"><span data-stu-id="40d64-103">Load all shard maps and their corresponding mappings on as needed basis.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>