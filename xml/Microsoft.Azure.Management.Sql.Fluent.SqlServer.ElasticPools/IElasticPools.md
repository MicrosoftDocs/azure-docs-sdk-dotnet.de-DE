<Type Name="IElasticPools" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlServer.ElasticPools.IElasticPools">
  <TypeSignature Language="C#" Value="public interface IElasticPools" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IElasticPools" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlServer.ElasticPools.IElasticPools" />
  <TypeSignature Language="VB.NET" Value="Public Interface IElasticPools" />
  <TypeSignature Language="F#" Value="type IElasticPools = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="325e9-101">Der Einstiegspunkt für ElasticPools auf dem SQL Server zugreifen.</span><span class="sxs-lookup"><span data-stu-id="325e9-101">Entry point to access ElasticPools from the SQL Server.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Define">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IBlank Define (string elasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IBlank Define(string elasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.ElasticPools.IElasticPools.Define(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Define (elasticPoolName As String) As IBlank" />
      <MemberSignature Language="F#" Value="abstract member Define : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IBlank" Usage="iElasticPools.Define elasticPoolName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IBlank</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="elasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="elasticPoolName"><span data-ttu-id="325e9-102">Der Name des elastischen Pools erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="325e9-102">Name of the elastic pool to be created.</span></span></param>
        <summary>
            <span data-ttu-id="325e9-103">Erstellt einen neuen elastischen Pool in SQL Server.</span><span class="sxs-lookup"><span data-stu-id="325e9-103">Creates a new elastic pool in SQL Server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="325e9-104">Gibt eine Stufe aus, um die Argumente des elastischen Pools angeben.</span><span class="sxs-lookup"><span data-stu-id="325e9-104">Returns a stage to specify arguments of the elastic pool.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (string elasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(string elasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.ElasticPools.IElasticPools.Delete(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (elasticPoolName As String)" />
      <MemberSignature Language="F#" Value="abstract member Delete : string -&gt; unit" Usage="iElasticPools.Delete elasticPoolName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="elasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="elasticPoolName"><span data-ttu-id="325e9-105">Der Name des elastischen Pools gelöscht.</span><span class="sxs-lookup"><span data-stu-id="325e9-105">Name of the elastic pool to delete.</span></span></param>
        <summary>
            <span data-ttu-id="325e9-106">Löschen Sie die angegebenen elastischen Pool auf dem Server.</span><span class="sxs-lookup"><span data-stu-id="325e9-106">Delete specified elastic pool in the server.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.ElasticPools.IElasticPools.DeleteAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iElasticPools.DeleteAsync (elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="elasticPoolName"><span data-ttu-id="325e9-107">Der Name des elastischen Pools gelöscht.</span><span class="sxs-lookup"><span data-stu-id="325e9-107">Name of the elastic pool to delete.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="325e9-108">Löschen Sie die angegebenen elastischen Pool auf dem Server.</span><span class="sxs-lookup"><span data-stu-id="325e9-108">Delete specified elastic pool in the server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="325e9-109">Observable-Objekt für den Löschvorgang.</span><span class="sxs-lookup"><span data-stu-id="325e9-109">Observable for the delete operation.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool Get (string elasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool Get(string elasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.ElasticPools.IElasticPools.Get(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Get (elasticPoolName As String) As ISqlElasticPool" />
      <MemberSignature Language="F#" Value="abstract member Get : string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool" Usage="iElasticPools.Get elasticPoolName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="elasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="elasticPoolName"><span data-ttu-id="325e9-110">Der Name des elastischen Pools abgerufen.</span><span class="sxs-lookup"><span data-stu-id="325e9-110">Name of the elastic pool to get.</span></span></param>
        <summary>
            <span data-ttu-id="325e9-111">Ruft einen bestimmten elastischen Pool ab.</span><span class="sxs-lookup"><span data-stu-id="325e9-111">Gets a particular elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="325e9-112">Gibt den elastischen Pool mit SQL Server zurück.</span><span class="sxs-lookup"><span data-stu-id="325e9-112">Returns the elastic pool with in the SQL Server.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt; List ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt; List() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.ElasticPools.IElasticPools.List" />
      <MemberSignature Language="VB.NET" Value="Public Function List () As IReadOnlyList(Of ISqlElasticPool)" />
      <MemberSignature Language="F#" Value="abstract member List : unit -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt;" Usage="iElasticPools.List " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="325e9-113">Gibt die elastische Pools für den Server zurück.</span><span class="sxs-lookup"><span data-stu-id="325e9-113">Returns all the elastic pools for the server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="325e9-114">Liste der elastische Pools für den Server.</span><span class="sxs-lookup"><span data-stu-id="325e9-114">List of elastic pools for the server.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>