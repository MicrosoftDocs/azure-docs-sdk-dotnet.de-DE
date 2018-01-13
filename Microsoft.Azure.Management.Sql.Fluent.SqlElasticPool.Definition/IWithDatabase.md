<Type Name="IWithDatabase" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDatabase">
  <TypeSignature Language="C#" Value="public interface IWithDatabase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDatabase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDatabase" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDatabase" />
  <TypeSignature Language="F#" Value="type IWithDatabase = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dbac9-101">Die elastischen Pool für SQL-Definition, um die Datenbank im elastischen Pool hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="dbac9-101">The SQL Elastic Pool definition to add the Database in the elastic pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingDatabase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithExistingDatabase (Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase database);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithExistingDatabase(class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase database) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDatabase.WithExistingDatabase(Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingDatabase (database As ISqlDatabase) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingDatabase : Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate" Usage="iWithDatabase.WithExistingDatabase database" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="database" Type="Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase" />
      </Parameters>
      <Docs>
        <param name="database"><span data-ttu-id="dbac9-102">Datenbankinstanz, die in SQL elastischen Pool hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="dbac9-102">Database instance to be added in SQL elastic pool.</span></span></param>
        <summary>
            <span data-ttu-id="dbac9-103">Fügt der Datenbank im elastischen Pool für SQL an.</span><span class="sxs-lookup"><span data-stu-id="dbac9-103">Adds the database in the SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="dbac9-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="dbac9-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingDatabase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithExistingDatabase (string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithExistingDatabase(string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDatabase.WithExistingDatabase(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingDatabase (databaseName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingDatabase : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate" Usage="iWithDatabase.WithExistingDatabase databaseName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseName"><span data-ttu-id="dbac9-105">Der Name der vorhandenen Datenbank im elastischen Pool hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="dbac9-105">Name of the existing database to be added in the elastic pool.</span></span></param>
        <summary>
            <span data-ttu-id="dbac9-106">Fügt eine vorhandene Datenbank im elastischen Pool für SQL an.</span><span class="sxs-lookup"><span data-stu-id="dbac9-106">Adds an existing database in the SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="dbac9-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="dbac9-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDatabase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithNewDatabase (string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithNewDatabase(string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDatabase.WithNewDatabase(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDatabase (databaseName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDatabase : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate" Usage="iWithDatabase.WithNewDatabase databaseName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseName"><span data-ttu-id="dbac9-108">Der Name der neuen Datenbank im elastischen Pool hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="dbac9-108">Name of the new database to be added in the elastic pool.</span></span></param>
        <summary>
            <span data-ttu-id="dbac9-109">Erstellt eine neue Datenbank im elastischen Pool für SQL an.</span><span class="sxs-lookup"><span data-stu-id="dbac9-109">Creates a new database in the SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="dbac9-110">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="dbac9-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>