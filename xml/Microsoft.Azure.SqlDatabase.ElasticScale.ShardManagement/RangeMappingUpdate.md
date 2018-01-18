<Type Name="RangeMappingUpdate" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate">
  <TypeSignature Language="C#" Value="public sealed class RangeMappingUpdate : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.BaseMappingUpdate&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RangeMappingUpdate extends Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.BaseMappingUpdate`1&lt;valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RangeMappingUpdate&#xA;Inherits BaseMappingUpdate(Of MappingStatus)" />
  <TypeSignature Language="F#" Value="type RangeMappingUpdate = class&#xA;    inherit BaseMappingUpdate&lt;MappingStatus&gt;" />
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
            <span data-ttu-id="ee73b-101">Stellt Updates auf eine Zuordnung zwischen einer <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1" /> von Werten und die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" /> zur Speicherung der zugehörigen Daten.</span><span class="sxs-lookup"><span data-stu-id="ee73b-101">Represents updates to a mapping between a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1" /> of values and the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" /> that stores its data.</span></span> <span data-ttu-id="ee73b-102">Siehe auch <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1" />.</span><span class="sxs-lookup"><span data-stu-id="ee73b-102">Also see <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RangeMappingUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ee73b-103">Instanziiert ein neuen Bereich Zuordnung Update-Objekt.</span><span class="sxs-lookup"><span data-stu-id="ee73b-103">Instantiates a new range mapping update object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBeingTakenOffline">
      <MemberSignature Language="C#" Value="protected override bool IsBeingTakenOffline (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus originalStatus, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus updatedStatus);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool IsBeingTakenOffline(valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus originalStatus, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus updatedStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate.IsBeingTakenOffline(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function IsBeingTakenOffline (originalStatus As MappingStatus, updatedStatus As MappingStatus) As Boolean" />
      <MemberSignature Language="F#" Value="override this.IsBeingTakenOffline : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus -&gt; bool" Usage="rangeMappingUpdate.IsBeingTakenOffline (originalStatus, updatedStatus)" />
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
        <param name="originalStatus"><span data-ttu-id="ee73b-104">Ursprünglicher Status.</span><span class="sxs-lookup"><span data-stu-id="ee73b-104">Original status.</span></span></param>
        <param name="updatedStatus"><span data-ttu-id="ee73b-105">Status aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="ee73b-105">Updated status.</span></span></param>
        <summary>
            <span data-ttu-id="ee73b-106">Erkennt, ob die aktuelle Zuordnung offline geschaltet wird.</span><span class="sxs-lookup"><span data-stu-id="ee73b-106">Detects if the current mapping is being taken offline.</span></span>
            </summary>
        <returns><span data-ttu-id="ee73b-107">In den abgeleiteten Typen erkennt, wenn die Zuordnung offline geschaltet wird.</span><span class="sxs-lookup"><span data-stu-id="ee73b-107">Detects in the derived types if the mapping is being taken offline.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>