<Type Name="IDatabases" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlServer.Databases.IDatabases">
  <TypeSignature Language="C#" Value="public interface IDatabases" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDatabases" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Databases.IDatabases" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDatabases" />
  <TypeSignature Language="F#" Value="type IDatabases = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9d64b-101">Der Einstiegspunkt für ElasticPools auf dem SQL Server zugreifen.</span><span class="sxs-lookup"><span data-stu-id="9d64b-101">Entry point to access ElasticPools from the SQL Server.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Define">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IBlank Define (string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IBlank Define(string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Databases.IDatabases.Define(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Define (databaseName As String) As IBlank" />
      <MemberSignature Language="F#" Value="abstract member Define : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IBlank" Usage="iDatabases.Define databaseName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IBlank</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseName"><span data-ttu-id="9d64b-102">Der Name der Datenbank erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="9d64b-102">Name of the database to be created.</span></span></param>
        <summary>
            <span data-ttu-id="9d64b-103">Erstellt eine neue Datenbank in SQL Server.</span><span class="sxs-lookup"><span data-stu-id="9d64b-103">Creates a new database in SQL Server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9d64b-104">Gibt eine Stufe aus, um die Argumente der Datenbank angeben.</span><span class="sxs-lookup"><span data-stu-id="9d64b-104">Returns a stage to specify arguments of the database.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Databases.IDatabases.Delete(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (databaseName As String)" />
      <MemberSignature Language="F#" Value="abstract member Delete : string -&gt; unit" Usage="iDatabases.Delete databaseName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseName"><span data-ttu-id="9d64b-105">Name des zu löschenden Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9d64b-105">Name of the database to delete.</span></span></param>
        <summary>
            <span data-ttu-id="9d64b-106">Löschen Sie die angegebene Datenbank auf dem Server.</span><span class="sxs-lookup"><span data-stu-id="9d64b-106">Delete specified database in the server.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Databases.IDatabases.DeleteAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iDatabases.DeleteAsync (databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="databaseName"><span data-ttu-id="9d64b-107">Name des zu löschenden Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9d64b-107">Name of the database to delete.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="9d64b-108">Löschen Sie die angegebene Datenbank auf dem Server.</span><span class="sxs-lookup"><span data-stu-id="9d64b-108">Delete specified database in the server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9d64b-109">Observable-Objekt für den Löschvorgang.</span><span class="sxs-lookup"><span data-stu-id="9d64b-109">Observable for the delete operation.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase Get (string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase Get(string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Databases.IDatabases.Get(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Get (databaseName As String) As ISqlDatabase" />
      <MemberSignature Language="F#" Value="abstract member Get : string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase" Usage="iDatabases.Get databaseName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseName"><span data-ttu-id="9d64b-110">Der Name der Sql-Datenbank abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d64b-110">Name of the sql database to get.</span></span></param>
        <summary>
            <span data-ttu-id="9d64b-111">Ruft eine bestimmte SQL­Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="9d64b-111">Gets a particular sql database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9d64b-112">Gibt die Datenbank mit SQL Server zurück.</span><span class="sxs-lookup"><span data-stu-id="9d64b-112">Returns the database with in the SQL Server.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; List ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; List() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Databases.IDatabases.List" />
      <MemberSignature Language="VB.NET" Value="Public Function List () As IReadOnlyList(Of ISqlDatabase)" />
      <MemberSignature Language="F#" Value="abstract member List : unit -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;" Usage="iDatabases.List " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9d64b-113">Es werden alle Datenbanken für den Server zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="9d64b-113">Returns all the databases for the server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9d64b-114">die Liste der Datenbanken für den Server.</span><span class="sxs-lookup"><span data-stu-id="9d64b-114">List of databases for the server.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>