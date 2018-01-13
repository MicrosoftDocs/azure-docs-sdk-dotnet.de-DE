<Type Name="IWithCustomDomain" FullName="Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithCustomDomain">
  <TypeSignature Language="C#" Value="public interface IWithCustomDomain" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCustomDomain" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithCustomDomain" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCustomDomain" />
  <TypeSignature Language="F#" Value="type IWithCustomDomain = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Eine Speicher-Konto Update Stufe ermöglicht die Parameter ändern.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithCustomDomain (Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithCustomDomain(class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithCustomDomain.WithCustomDomain(Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain)" />
      <MemberSignature Language="F#" Value="abstract member WithCustomDomain : Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain -&gt; Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate" Usage="iWithCustomDomain.WithCustomDomain customDomain" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customDomain" Type="Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain" />
      </Parameters>
      <Docs>
        <param name="customDomain">Der Domäne des Benutzers mit dem Speicherkonto zugewiesen.</param>
        <summary>
            Gibt an, der Domäne des Benutzers mit dem Speicherkonto zugewiesen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Aktualisierung des Speicher-Dienstkontos.</return>
      </Docs>
    </Member>
    <Member MemberName="WithCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithCustomDomain (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithCustomDomain(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithCustomDomain.WithCustomDomain(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCustomDomain (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithCustomDomain : string -&gt; Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate" Usage="iWithCustomDomain.WithCustomDomain name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Die benutzerdefinierten Domänennamen, der die Quelle der CNAME ist.</param>
        <summary>
            Gibt an, der Domäne des Benutzers mit dem Speicherkonto zugewiesen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Aktualisierung des Speicher-Dienstkontos.</return>
      </Docs>
    </Member>
    <Member MemberName="WithCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithCustomDomain (string name, bool useSubDomain);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithCustomDomain(string name, bool useSubDomain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithCustomDomain.WithCustomDomain(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCustomDomain (name As String, useSubDomain As Boolean) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithCustomDomain : string * bool -&gt; Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate" Usage="iWithCustomDomain.WithCustomDomain (name, useSubDomain)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="useSubDomain" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name">Die benutzerdefinierten Domänennamen, der die Quelle der CNAME ist.</param>
        <param name="useSubDomain">Gibt an, ob indirekte CName-Überprüfung aktiviert ist.</param>
        <summary>
            Gibt an, der Domäne des Benutzers mit dem Speicherkonto zugewiesen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Aktualisierung des Speicher-Dienstkontos.</return>
      </Docs>
    </Member>
  </Members>
</Type>