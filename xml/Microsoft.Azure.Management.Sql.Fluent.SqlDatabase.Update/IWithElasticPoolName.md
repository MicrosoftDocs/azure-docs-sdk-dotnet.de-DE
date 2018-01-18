<Type Name="IWithElasticPoolName" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IWithElasticPoolName">
  <TypeSignature Language="C#" Value="public interface IWithElasticPoolName" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithElasticPoolName" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IWithElasticPoolName" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithElasticPoolName" />
  <TypeSignature Language="F#" Value="type IWithElasticPoolName = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="389db-101">Die Definition der SQL-Datenbank den elastischen Pool für die Datenbank festlegen.</span><span class="sxs-lookup"><span data-stu-id="389db-101">The SQL Database definition to set the elastic pool for database.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingElasticPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate WithExistingElasticPool (Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool sqlElasticPool);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate WithExistingElasticPool(class Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool sqlElasticPool) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IWithElasticPoolName.WithExistingElasticPool(Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingElasticPool (sqlElasticPool As ISqlElasticPool) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingElasticPool : Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate" Usage="iWithElasticPoolName.WithExistingElasticPool sqlElasticPool" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlElasticPool" Type="Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool" />
      </Parameters>
      <Docs>
        <param name="sqlElasticPool"><span data-ttu-id="389db-102">Für die SQL­Datenbank.</span><span class="sxs-lookup"><span data-stu-id="389db-102">For the SQL Database.</span></span></param>
        <summary>
            <span data-ttu-id="389db-103">Legt den vorhandenen elastischen Pool für SQL-Datenbank fest.</span><span class="sxs-lookup"><span data-stu-id="389db-103">Sets the existing elastic pool for the SQLDatabase.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="389db-104">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="389db-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingElasticPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate WithExistingElasticPool (string elasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate WithExistingElasticPool(string elasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IWithElasticPoolName.WithExistingElasticPool(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingElasticPool (elasticPoolName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingElasticPool : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate" Usage="iWithElasticPoolName.WithExistingElasticPool elasticPoolName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="elasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="elasticPoolName"><span data-ttu-id="389db-105">Für die SQL­Datenbank.</span><span class="sxs-lookup"><span data-stu-id="389db-105">For the SQL Database.</span></span></param>
        <summary>
            <span data-ttu-id="389db-106">Legt den vorhandenen elastischen Pool für SQL-Datenbank fest.</span><span class="sxs-lookup"><span data-stu-id="389db-106">Sets the existing elastic pool for the SQLDatabase.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="389db-107">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="389db-107">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewElasticPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate WithNewElasticPool (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt; sqlElasticPool);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate WithNewElasticPool(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt; sqlElasticPool) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IWithElasticPoolName.WithNewElasticPool(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewElasticPool (sqlElasticPool As ICreatable(Of ISqlElasticPool)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewElasticPool : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate" Usage="iWithElasticPoolName.WithNewElasticPool sqlElasticPool" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlElasticPool" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt;" />
      </Parameters>
      <Docs>
        <param name="sqlElasticPool"><span data-ttu-id="389db-108">Erstellbar Definition für neue elastischen Pool für die SQL-Datenbank erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="389db-108">Creatable definition for new elastic pool to be created for the SQL Database.</span></span></param>
        <summary>
            <span data-ttu-id="389db-109">Legt den neuen elastischen pool für SQL-Datenbank, wird dies einen neuen elastischen Pool erstellt, beim Erstellen der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="389db-109">Sets the new elastic pool for the SQLDatabase, this will create a new elastic pool while creating database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="389db-110">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="389db-110">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutElasticPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IWithEdition WithoutElasticPool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IWithEdition WithoutElasticPool() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IWithElasticPoolName.WithoutElasticPool" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutElasticPool () As IWithEdition" />
      <MemberSignature Language="F#" Value="abstract member WithoutElasticPool : unit -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IWithEdition" Usage="iWithElasticPoolName.WithoutElasticPool " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IWithEdition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="389db-111">Wird die Datenbank aus der elastischen Pool entfernt.</span><span class="sxs-lookup"><span data-stu-id="389db-111">Removes database from it's elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="389db-112">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="389db-112">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>