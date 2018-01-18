<Type Name="PointMappingUpdate" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate">
  <TypeSignature Language="C#" Value="public sealed class PointMappingUpdate : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.BaseMappingUpdate&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PointMappingUpdate extends Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.BaseMappingUpdate`1&lt;valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PointMappingUpdate&#xA;Inherits BaseMappingUpdate(Of MappingStatus)" />
  <TypeSignature Language="F#" Value="type PointMappingUpdate = class&#xA;    inherit BaseMappingUpdate&lt;MappingStatus&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.BaseMappingUpdate&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TStatus">Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0f4a5-101">Stellt Updates auf eine Zuordnung zwischen den Singleton-Schlüsselwert eines shardlets (ein Punkt) und den Shard, der die Daten enthält.</span><span class="sxs-lookup"><span data-stu-id="0f4a5-101">Represents updates to a mapping between the singleton key value of a shardlet (a point) and the shard that holds its data.</span></span> <span data-ttu-id="0f4a5-102">Siehe auch <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1" />.</span><span class="sxs-lookup"><span data-stu-id="0f4a5-102">Also see <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PointMappingUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0f4a5-103">Instanziiert ein neue Punkt Zuordnung Update-Objekt.</span><span class="sxs-lookup"><span data-stu-id="0f4a5-103">Instantiates a new point mapping update object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBeingTakenOffline">
      <MemberSignature Language="C#" Value="protected override bool IsBeingTakenOffline (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus originalStatus, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus updatedStatus);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool IsBeingTakenOffline(valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus originalStatus, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus updatedStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate.IsBeingTakenOffline(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function IsBeingTakenOffline (originalStatus As MappingStatus, updatedStatus As MappingStatus) As Boolean" />
      <MemberSignature Language="F#" Value="override this.IsBeingTakenOffline : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus -&gt; bool" Usage="pointMappingUpdate.IsBeingTakenOffline (originalStatus, updatedStatus)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="originalStatus" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus" />
        <Parameter Name="updatedStatus" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus" />
      </Parameters>
      <Docs>
        <param name="originalStatus"><span data-ttu-id="0f4a5-104">Ursprünglicher Status.</span><span class="sxs-lookup"><span data-stu-id="0f4a5-104">Original status.</span></span></param>
        <param name="updatedStatus"><span data-ttu-id="0f4a5-105">Status aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="0f4a5-105">Updated status.</span></span></param>
        <summary>
            <span data-ttu-id="0f4a5-106">Erkennt, ob die aktuelle Zuordnung offline geschaltet wird.</span><span class="sxs-lookup"><span data-stu-id="0f4a5-106">Detects if the current mapping is being taken offline.</span></span>
            </summary>
        <returns><span data-ttu-id="0f4a5-107">In den abgeleiteten Typen erkennt, wenn die Zuordnung offline geschaltet wird.</span><span class="sxs-lookup"><span data-stu-id="0f4a5-107">Detects in the derived types if the mapping is being taken offline.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>