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
            Die Definition der SQL-Datenbank die Quelle Datenbank-Id für die Datenbank festlegen.
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
        <param name="sourceDatabase">Die Instanz von der Quelldatenbank.</param>
        <summary>
            Legt die Ressource Wenn von der Quelldatenbank für die SQL-Datenbank fest.
            Sortierung, Edition und MaxSizeBytes müssen identisch sein, während die Verbindung aktiv ist. Für diese Parameter angegebenen Werte werden ignoriert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
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
        <param name="sourceDatabaseId">Die ID der Quelldatenbank.</param>
        <summary>
            Legt die Ressource Wenn von der Quelldatenbank für die SQL-Datenbank fest.
            Sortierung, Edition und MaxSizeBytes müssen identisch sein, während die Verbindung aktiv ist. Für diese Parameter angegebenen Werte werden ignoriert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>