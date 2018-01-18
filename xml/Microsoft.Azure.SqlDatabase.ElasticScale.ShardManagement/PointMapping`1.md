<Type Name="PointMapping&lt;TKey&gt;" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;">
  <TypeSignature Language="C#" Value="public sealed class PointMapping&lt;TKey&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PointMapping`1&lt;TKey&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PointMapping(Of TKey)" />
  <TypeSignature Language="F#" Value="type PointMapping&lt;'Key&gt; = class&#xA;    interface IShardProvider&lt;'Key&gt;&#xA;    interface IShardProvider&#xA;    interface ICloneable&lt;PointMapping&lt;'Key&gt;&gt;&#xA;    interface IMappingInfoProvider" />
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
    <typeparam name="TKey"><span data-ttu-id="c9f33-101">Der Typ des Schlüssels (Punkt).</span><span class="sxs-lookup"><span data-stu-id="c9f33-101">Type of the key (point).</span></span></typeparam>
    <summary>
            <span data-ttu-id="c9f33-102">Stellt eine Zuordnung zwischen den Singleton-Schlüsselwert eines shardlets (ein Punkt) und einen <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1.Shard" />.</span><span class="sxs-lookup"><span data-stu-id="c9f33-102">Represents a mapping between the singleton key value of a shardlet (a point) and a <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1.Shard" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As PointMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;&#xA;override this.Clone : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;" Usage="pointMapping.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ICloneable`1.Clone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c9f33-103">Klont die Instanz.</span><span class="sxs-lookup"><span data-stu-id="c9f33-103">Clones the instance.</span></span>
            </summary>
        <returns><span data-ttu-id="c9f33-104">Klon der Instanz.</span><span class="sxs-lookup"><span data-stu-id="c9f33-104">Clone of the instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="pointMapping.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="c9f33-105">Das Objekt, das mit dem aktuellen Objekt verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c9f33-105">The object to compare with the current object.</span></span></param>
        <summary>
            <span data-ttu-id="c9f33-106">Bestimmt, ob das angegebene Objekt mit dem aktuellen Objekt identisch ist.</span><span class="sxs-lookup"><span data-stu-id="c9f33-106">Determines whether the specified object is equal to the current object.</span></span>
            </summary>
        <returns><span data-ttu-id="c9f33-107">True, wenn das angegebene Objekt mit dem aktuellen Objekt identisch ist. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="c9f33-107">True if the specified object is equal to the current object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="pointMapping.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c9f33-108">Berechnet den Hashcode für diese Instanz an.</span><span class="sxs-lookup"><span data-stu-id="c9f33-108">Calculates the hash code for this instance.</span></span>
            </summary>
        <returns><span data-ttu-id="c9f33-109">Der Hashcode für das Objekt.</span><span class="sxs-lookup"><span data-stu-id="c9f33-109">Hash code for the object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Shard">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard Shard { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard Shard" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1.Shard" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Shard As Shard" />
      <MemberSignature Language="F#" Value="member this.Shard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;.Shard" />
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
            <span data-ttu-id="c9f33-110">Ruft die Shard, der den Schlüsselwert enthält.</span><span class="sxs-lookup"><span data-stu-id="c9f33-110">Gets Shard that contains the key value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As MappingStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;.Status" />
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
            <span data-ttu-id="c9f33-111">Ruft die Status der Zuordnung ab.</span><span class="sxs-lookup"><span data-stu-id="c9f33-111">Gets Status of the mapping.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="pointMapping.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c9f33-112">Konvertiert das Objekt in seine Zeichenfolgendarstellung.</span><span class="sxs-lookup"><span data-stu-id="c9f33-112">Converts the object to its string representation.</span></span>
            </summary>
        <returns><span data-ttu-id="c9f33-113">Entspricht der Zeichenfolgendarstellung des Objekts.</span><span class="sxs-lookup"><span data-stu-id="c9f33-113">String representation of the object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public TKey Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TKey Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As TKey" />
      <MemberSignature Language="F#" Value="member this.Value : 'Key" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;.Value" />
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
            <span data-ttu-id="c9f33-114">Ruft den Schlüsselwert ab.</span><span class="sxs-lookup"><span data-stu-id="c9f33-114">Gets key value.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>