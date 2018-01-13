<Type Name="IWithDatabaseDtuMin" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDatabaseDtuMin">
  <TypeSignature Language="C#" Value="public interface IWithDatabaseDtuMin" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDatabaseDtuMin" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDatabaseDtuMin" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDatabaseDtuMin" />
  <TypeSignature Language="F#" Value="type IWithDatabaseDtuMin = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Definition der elastischen Pool für SQL die minimale DTU für die Datenbank festlegen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDatabaseDtuMin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithDatabaseDtuMin (int databaseDtuMin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithDatabaseDtuMin(int32 databaseDtuMin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDatabaseDtuMin.WithDatabaseDtuMin(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDatabaseDtuMin (databaseDtuMin As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDatabaseDtuMin : int -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate" Usage="iWithDatabaseDtuMin.WithDatabaseDtuMin databaseDtuMin" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseDtuMin" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="databaseDtuMin">Minimale DTU für alle SQL Azure-Datenbanken.</param>
        <summary>
            Legt die minimale DTU, die alle SQL Azure-Datenbanken garantiert werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>