<Type Name="IWithMaxSizeBytes" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IWithMaxSizeBytes">
  <TypeSignature Language="C#" Value="public interface IWithMaxSizeBytes" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMaxSizeBytes" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IWithMaxSizeBytes" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMaxSizeBytes" />
  <TypeSignature Language="F#" Value="type IWithMaxSizeBytes = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Definition der SQL-Datenbank mit der Max Size in Bytes für die Datenbank festlegen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMaxSizeBytes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate WithMaxSizeBytes (long maxSizeBytes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate WithMaxSizeBytes(int64 maxSizeBytes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IWithMaxSizeBytes.WithMaxSizeBytes(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMaxSizeBytes (maxSizeBytes As Long) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithMaxSizeBytes : int64 -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate" Usage="iWithMaxSizeBytes.WithMaxSizeBytes maxSizeBytes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxSizeBytes" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="maxSizeBytes">
            Max. Größe der Azure SQL-Datenbank, die in Bytes ausgedrückt werden. Hinweis: Nur die folgenden Größen werden unterstützt (zusätzlich zu den Einschränkungen, die auf den einzelnen Editionen platziert wird): {100 MB | 500 MB | 1 GB | 5 GB | 10 GB | 20 GB | 30 GB... 150 GB | 200 GB... 500 GB}.
            </param>
        <summary>
            Legt die maximale Größe in Bytes für SQL-Datenbank fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>