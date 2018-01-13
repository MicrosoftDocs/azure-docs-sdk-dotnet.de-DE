<Type Name="IWithDatabase" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IWithDatabase">
  <TypeSignature Language="C#" Value="public interface IWithDatabase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDatabase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IWithDatabase" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDatabase" />
  <TypeSignature Language="F#" Value="type IWithDatabase = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Eine SQL Server-Definition für die Datenbanken angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewDatabase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate WithNewDatabase (string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate WithNewDatabase(string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IWithDatabase.WithNewDatabase(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDatabase (databaseName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDatabase : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate" Usage="iWithDatabase.WithNewDatabase databaseName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseName">Der Name der Datenbank erstellt werden soll.</param>
        <summary>
            Erstellen Sie neue Datenbank in SQL Server.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Nächste Phase der SQL Server-Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutDatabase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate WithoutDatabase (string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate WithoutDatabase(string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IWithDatabase.WithoutDatabase(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutDatabase (databaseName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutDatabase : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate" Usage="iWithDatabase.WithoutDatabase databaseName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseName">Der Name der Datenbank entfernt werden soll.</param>
        <summary>
            Entfernen Sie Datenbank vom SQL Server.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Nächste Phase der SQL Server-Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>