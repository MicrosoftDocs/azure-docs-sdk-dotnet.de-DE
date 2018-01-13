<Type Name="IWithElasticPool" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithElasticPool">
  <TypeSignature Language="C#" Value="public interface IWithElasticPool" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithElasticPool" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithElasticPool" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithElasticPool" />
  <TypeSignature Language="F#" Value="type IWithElasticPool = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dc01a-101">Eine SQL Server-Definition für den elastischen Pool angeben.</span><span class="sxs-lookup"><span data-stu-id="dc01a-101">A SQL Server definition for specifying elastic pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewElasticPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate WithNewElasticPool (string elasticPoolName, string elasticPoolEdition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate WithNewElasticPool(string elasticPoolName, string elasticPoolEdition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithElasticPool.WithNewElasticPool(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewElasticPool (elasticPoolName As String, elasticPoolEdition As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewElasticPool : string * string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate" Usage="iWithElasticPool.WithNewElasticPool (elasticPoolName, elasticPoolEdition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="elasticPoolEdition" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="elasticPoolName"><span data-ttu-id="dc01a-102">Der Name des elastischen Pools erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="dc01a-102">Name of the elastic pool to be created.</span></span></param>
        <param name="elasticPoolEdition"><span data-ttu-id="dc01a-103">Die Edition des elastischen Pools.</span><span class="sxs-lookup"><span data-stu-id="dc01a-103">Edition of the elastic pool.</span></span></param>
        <summary>
            <span data-ttu-id="dc01a-104">Erstellt neue elastischen Pool in SQL Server.</span><span class="sxs-lookup"><span data-stu-id="dc01a-104">Creates new elastic pool in the SQL Server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="dc01a-105">Nächste Phase der SQL Server-Definition.</span><span class="sxs-lookup"><span data-stu-id="dc01a-105">Next stage of the SQL Server definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewElasticPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate WithNewElasticPool (string elasticPoolName, string elasticPoolEdition, params string[] databaseNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate WithNewElasticPool(string elasticPoolName, string elasticPoolEdition, string[] databaseNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithElasticPool.WithNewElasticPool(System.String,System.String,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewElasticPool (elasticPoolName As String, elasticPoolEdition As String, ParamArray databaseNames As String()) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewElasticPool : string * string * string[] -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate" Usage="iWithElasticPool.WithNewElasticPool (elasticPoolName, elasticPoolEdition, databaseNames)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="elasticPoolEdition" Type="System.String" />
        <Parameter Name="databaseNames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="elasticPoolName"><span data-ttu-id="dc01a-106">Der Name des elastischen Pools erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="dc01a-106">Name of the elastic pool to be created.</span></span></param>
        <param name="elasticPoolEdition"><span data-ttu-id="dc01a-107">Die Edition des elastischen Pools.</span><span class="sxs-lookup"><span data-stu-id="dc01a-107">Edition of the elastic pool.</span></span></param>
        <param name="databaseNames"><span data-ttu-id="dc01a-108">Die Namen der Datenbank im elastischen Pool aufgenommen werden.</span><span class="sxs-lookup"><span data-stu-id="dc01a-108">Names of the database to be included in the elastic pool.</span></span></param>
        <summary>
            <span data-ttu-id="dc01a-109">Erstellt neue elastischen Pool in SQL Server.</span><span class="sxs-lookup"><span data-stu-id="dc01a-109">Creates new elastic pool in the SQL Server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="dc01a-110">Nächste Phase der SQL Server-Definition.</span><span class="sxs-lookup"><span data-stu-id="dc01a-110">Next stage of the SQL Server definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>