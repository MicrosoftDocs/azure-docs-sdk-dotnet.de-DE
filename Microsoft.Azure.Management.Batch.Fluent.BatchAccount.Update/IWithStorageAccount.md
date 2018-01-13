<Type Name="IWithStorageAccount" FullName="Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithStorageAccount">
  <TypeSignature Language="C#" Value="public interface IWithStorageAccount" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithStorageAccount" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithStorageAccount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithStorageAccount" />
  <TypeSignature Language="F#" Value="type IWithStorageAccount = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase eines Batch-Konto-Updates zulassen, um ein Speicherkonto anzugeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithExistingStorageAccount (Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithExistingStorageAccount(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithStorageAccount.WithExistingStorageAccount(Microsoft.Azure.Management.Storage.Fluent.IStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingStorageAccount (storageAccount As IStorageAccount) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingStorageAccount : Microsoft.Azure.Management.Storage.Fluent.IStorageAccount -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate" Usage="iWithStorageAccount.WithExistingStorageAccount storageAccount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount" />
      </Parameters>
      <Docs>
        <param name="storageAccount">Ein vorhandenes Speicherkonto.</param>
        <summary>
            Gibt ein vorhandenes Speicherkonto, das Batch-Konto zugeordnet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithNewStorageAccount (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; storageAccountCreatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithNewStorageAccount(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; storageAccountCreatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithStorageAccount.WithNewStorageAccount(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Storage.Fluent.IStorageAccount})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStorageAccount (storageAccountCreatable As ICreatable(Of IStorageAccount)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewStorageAccount : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate" Usage="iWithStorageAccount.WithNewStorageAccount storageAccountCreatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountCreatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt;" />
      </Parameters>
      <Docs>
        <param name="storageAccountCreatable">Die Definition des Speicherkontos.</param>
        <summary>
            Gibt ein neues Speicherkonto zum Erstellen und der Batch-Konto zugeordnet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithNewStorageAccount (string storageAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithNewStorageAccount(string storageAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithStorageAccount.WithNewStorageAccount(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStorageAccount (storageAccountName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewStorageAccount : string -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate" Usage="iWithStorageAccount.WithNewStorageAccount storageAccountName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName">Der Name eines neuen Speicherkontos.</param>
        <summary>
            Gibt ein neues Speicherkonto zum Erstellen und der Batch-Konto zugeordnet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithoutStorageAccount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithoutStorageAccount() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithStorageAccount.WithoutStorageAccount" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutStorageAccount () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutStorageAccount : unit -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate" Usage="iWithStorageAccount.WithoutStorageAccount " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Entfernt das zugehörige Speicherkonto an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>