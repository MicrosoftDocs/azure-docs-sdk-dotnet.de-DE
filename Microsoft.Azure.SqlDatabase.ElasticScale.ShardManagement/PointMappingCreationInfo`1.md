<Type Name="PointMappingCreationInfo&lt;TKey&gt;" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo&lt;TKey&gt;">
  <TypeSignature Language="C#" Value="public sealed class PointMappingCreationInfo&lt;TKey&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PointMappingCreationInfo`1&lt;TKey&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo`1" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PointMappingCreationInfo(Of TKey)" />
  <TypeSignature Language="F#" Value="type PointMappingCreationInfo&lt;'Key&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TKey" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TKey"><span data-ttu-id="1e46c-101">Der Typ des Schlüssels (Punkt).</span><span class="sxs-lookup"><span data-stu-id="1e46c-101">Type of the key (point).</span></span></typeparam>
    <summary>
            <span data-ttu-id="1e46c-102">Argumente, die zum Erstellen einer <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1" />.</span><span class="sxs-lookup"><span data-stu-id="1e46c-102">Arguments used to create a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PointMappingCreationInfo (TKey point, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus status);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!TKey point, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo`1.#ctor(`0,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo&lt;'Key&gt; : 'Key * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo&lt;'Key&gt;" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo&lt;'Key&gt; (point, shard, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="point" Type="TKey" />
        <Parameter Name="shard" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
        <Parameter Name="status" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus" />
      </Parameters>
      <Docs>
        <param name="point"><span data-ttu-id="1e46c-103">Der Punktwert zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="1e46c-103">Point value being mapped.</span></span></param>
        <param name="shard"><span data-ttu-id="1e46c-104">Shard als Zuordnungsziel für die verwendet.</span><span class="sxs-lookup"><span data-stu-id="1e46c-104">Shard used as the mapping target.</span></span></param>
        <param name="status"><span data-ttu-id="1e46c-105">Status der Zuordnung.</span><span class="sxs-lookup"><span data-stu-id="1e46c-105">Status of the mapping.</span></span></param>
        <summary>
            <span data-ttu-id="1e46c-106">Die Argumente verwendet, um eine Punkt-Zuordnung zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="1e46c-106">Arguments used to create a point mapping.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Shard">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard Shard { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard Shard" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo`1.Shard" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Shard As Shard" />
      <MemberSignature Language="F#" Value="member this.Shard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo&lt;'Key&gt;.Shard" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e46c-107">Ruft den Shard der Zuordnung ab.</span><span class="sxs-lookup"><span data-stu-id="1e46c-107">Gets the Shard of the mapping.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo`1.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As MappingStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo&lt;'Key&gt;.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e46c-108">Ruft den Status der Zuordnung ab.</span><span class="sxs-lookup"><span data-stu-id="1e46c-108">Gets the Status of the mapping.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public TKey Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TKey Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo`1.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As TKey" />
      <MemberSignature Language="F#" Value="member this.Value : 'Key" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo&lt;'Key&gt;.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e46c-109">Ruft den Punktwert zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="1e46c-109">Gets the point value being mapped.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>