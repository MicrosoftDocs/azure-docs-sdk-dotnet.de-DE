<Type Name="RestorePointsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.RestorePointsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RestorePointsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RestorePointsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.RestorePointsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RestorePointsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RestorePointsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="49bcf-101">Erweiterungsmethoden für RestorePointsOperations.</span><span class="sxs-lookup"><span data-stu-id="49bcf-101">Extension methods for RestorePointsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByDatabase">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RestorePoint&gt; ListByDatabase (this Microsoft.Azure.Management.Sql.IRestorePointsOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.RestorePoint&gt; ListByDatabase(class Microsoft.Azure.Management.Sql.IRestorePointsOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RestorePointsOperationsExtensions.ListByDatabase(Microsoft.Azure.Management.Sql.IRestorePointsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatabase (operations As IRestorePointsOperations, resourceGroupName As String, serverName As String, databaseName As String) As IEnumerable(Of RestorePoint)" />
      <MemberSignature Language="F#" Value="static member ListByDatabase : Microsoft.Azure.Management.Sql.IRestorePointsOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.RestorePoint&gt;" Usage="Microsoft.Azure.Management.Sql.RestorePointsOperationsExtensions.ListByDatabase (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RestorePoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRestorePointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="49bcf-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="49bcf-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="49bcf-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="49bcf-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="49bcf-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="49bcf-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="49bcf-105">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="49bcf-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="49bcf-106">Der Name der Datenbank verfügbaren abzurufenden Wiederherstellungspunkte.</span><span class="sxs-lookup"><span data-stu-id="49bcf-106">The name of the database to get available restore points.</span></span>
            </param>
        <summary>
            <span data-ttu-id="49bcf-107">Ruft eine Liste der Wiederherstellungspunkte an.</span><span class="sxs-lookup"><span data-stu-id="49bcf-107">Gets a list of database restore points.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RestorePoint&gt;&gt; ListByDatabaseAsync (this Microsoft.Azure.Management.Sql.IRestorePointsOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.RestorePoint&gt;&gt; ListByDatabaseAsync(class Microsoft.Azure.Management.Sql.IRestorePointsOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RestorePointsOperationsExtensions.ListByDatabaseAsync(Microsoft.Azure.Management.Sql.IRestorePointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseAsync : Microsoft.Azure.Management.Sql.IRestorePointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.RestorePoint&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.RestorePointsOperationsExtensions.ListByDatabaseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.RestorePointsOperationsExtensions/&lt;ListByDatabaseAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RestorePoint&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRestorePointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="49bcf-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="49bcf-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="49bcf-109">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="49bcf-109">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="49bcf-110">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="49bcf-110">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="49bcf-111">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="49bcf-111">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="49bcf-112">Der Name der Datenbank verfügbaren abzurufenden Wiederherstellungspunkte.</span><span class="sxs-lookup"><span data-stu-id="49bcf-112">The name of the database to get available restore points.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="49bcf-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="49bcf-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="49bcf-114">Ruft eine Liste der Wiederherstellungspunkte an.</span><span class="sxs-lookup"><span data-stu-id="49bcf-114">Gets a list of database restore points.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>