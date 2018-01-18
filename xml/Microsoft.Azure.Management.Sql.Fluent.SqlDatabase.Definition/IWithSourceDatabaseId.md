<Type Name="IWithSourceDatabaseId" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithSourceDatabaseId">
  <TypeSignature Language="C#" Value="public interface IWithSourceDatabaseId" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSourceDatabaseId" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithSourceDatabaseId" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSourceDatabaseId" />
  <TypeSignature Language="F#" Value="type IWithSourceDatabaseId = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a1ac2-101">Die Definition der SQL-Datenbank die Quelle Datenbank-Id für die Datenbank festlegen.</span><span class="sxs-lookup"><span data-stu-id="a1ac2-101">The SQL Database definition to set the source database id for database.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSourceDatabase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateMode WithSourceDatabase (Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase sourceDatabase);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateMode WithSourceDatabase(class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase sourceDatabase) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithSourceDatabaseId.WithSourceDatabase(Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSourceDatabase (sourceDatabase As ISqlDatabase) As IWithCreateMode" />
      <MemberSignature Language="F#" Value="abstract member WithSourceDatabase : Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateMode" Usage="iWithSourceDatabaseId.WithSourceDatabase sourceDatabase" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateMode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceDatabase" Type="Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase" />
      </Parameters>
      <Docs>
        <param name="sourceDatabase"><span data-ttu-id="a1ac2-102">Die Instanz von der Quelldatenbank.</span><span class="sxs-lookup"><span data-stu-id="a1ac2-102">Instance of the source database.</span></span></param>
        <summary>
            <span data-ttu-id="a1ac2-103">Legt die Ressource Wenn von der Quelldatenbank für die SQL-Datenbank fest.</span><span class="sxs-lookup"><span data-stu-id="a1ac2-103">Sets the resource if of source database for the SQL Database.</span></span>
            <span data-ttu-id="a1ac2-104">Sortierung, Edition und MaxSizeBytes müssen identisch sein, während die Verbindung aktiv ist.</span><span class="sxs-lookup"><span data-stu-id="a1ac2-104">Collation, Edition, and MaxSizeBytes must remain the same while the link is active.</span></span> <span data-ttu-id="a1ac2-105">Für diese Parameter angegebenen Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="a1ac2-105">Values specified for these parameters will be ignored.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a1ac2-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="a1ac2-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSourceDatabase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateMode WithSourceDatabase (string sourceDatabaseId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateMode WithSourceDatabase(string sourceDatabaseId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithSourceDatabaseId.WithSourceDatabase(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSourceDatabase (sourceDatabaseId As String) As IWithCreateMode" />
      <MemberSignature Language="F#" Value="abstract member WithSourceDatabase : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateMode" Usage="iWithSourceDatabaseId.WithSourceDatabase sourceDatabaseId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateMode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceDatabaseId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceDatabaseId"><span data-ttu-id="a1ac2-107">Die ID der Quelldatenbank.</span><span class="sxs-lookup"><span data-stu-id="a1ac2-107">Id of the source database.</span></span></param>
        <summary>
            <span data-ttu-id="a1ac2-108">Legt die Ressource Wenn von der Quelldatenbank für die SQL-Datenbank fest.</span><span class="sxs-lookup"><span data-stu-id="a1ac2-108">Sets the resource if of source database for the SQL Database.</span></span>
            <span data-ttu-id="a1ac2-109">Sortierung, Edition und MaxSizeBytes müssen identisch sein, während die Verbindung aktiv ist.</span><span class="sxs-lookup"><span data-stu-id="a1ac2-109">Collation, Edition, and MaxSizeBytes must remain the same while the link is active.</span></span> <span data-ttu-id="a1ac2-110">Für diese Parameter angegebenen Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="a1ac2-110">Values specified for these parameters will be ignored.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a1ac2-111">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="a1ac2-111">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>