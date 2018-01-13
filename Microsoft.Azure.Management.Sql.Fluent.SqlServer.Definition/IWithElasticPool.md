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
            Eine SQL Server-Definition für den elastischen Pool angeben.
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
        <param name="elasticPoolName">Der Name des elastischen Pools erstellt werden soll.</param>
        <param name="elasticPoolEdition">Die Edition des elastischen Pools.</param>
        <summary>
            Erstellt neue elastischen Pool in SQL Server.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Nächste Phase der SQL Server-Definition.</return>
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
        <param name="elasticPoolName">Der Name des elastischen Pools erstellt werden soll.</param>
        <param name="elasticPoolEdition">Die Edition des elastischen Pools.</param>
        <param name="databaseNames">Die Namen der Datenbank im elastischen Pool aufgenommen werden.</param>
        <summary>
            Erstellt neue elastischen Pool in SQL Server.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Nächste Phase der SQL Server-Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>