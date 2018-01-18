<Type Name="IWithStorage" FullName="Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithStorage">
  <TypeSignature Language="C#" Value="public interface IWithStorage" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithStorage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithStorage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithStorage" />
  <TypeSignature Language="F#" Value="type IWithStorage = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5659d-101">Die Phase der Definition eines Batch-Konto zulassen, Speicherkonten das Batch-Konto zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5659d-101">The stage of a Batch account definition allowing to associate storage accounts with the Batch account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate WithExistingStorageAccount (Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate WithExistingStorageAccount(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithStorage.WithExistingStorageAccount(Microsoft.Azure.Management.Storage.Fluent.IStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingStorageAccount (storageAccount As IStorageAccount) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingStorageAccount : Microsoft.Azure.Management.Storage.Fluent.IStorageAccount -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate" Usage="iWithStorage.WithExistingStorageAccount storageAccount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount" />
      </Parameters>
      <Docs>
        <param name="storageAccount"><span data-ttu-id="5659d-102">Ein vorhandenes Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="5659d-102">An existing storage account.</span></span></param>
        <summary>
            <span data-ttu-id="5659d-103">Gibt ein vorhandenes Speicherkonto, das Batch-Konto zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5659d-103">Specifies an existing storage account to associate with the Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5659d-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="5659d-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate WithNewStorageAccount (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; storageAccountCreatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate WithNewStorageAccount(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; storageAccountCreatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithStorage.WithNewStorageAccount(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Storage.Fluent.IStorageAccount})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStorageAccount (storageAccountCreatable As ICreatable(Of IStorageAccount)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewStorageAccount : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate" Usage="iWithStorage.WithNewStorageAccount storageAccountCreatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountCreatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt;" />
      </Parameters>
      <Docs>
        <param name="storageAccountCreatable"><span data-ttu-id="5659d-105">Ein Speicherkonto, zusammen mit erstellt und in das Batch-Konto verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="5659d-105">A storage account to be created along with and used in the Batch account.</span></span></param>
        <summary>
            <span data-ttu-id="5659d-106">Gibt ein neues Speicherkonto, das Batch-Konto zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5659d-106">Specifies a new storage account to associate with the Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5659d-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="5659d-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate WithNewStorageAccount (string storageAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate WithNewStorageAccount(string storageAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithStorage.WithNewStorageAccount(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStorageAccount (storageAccountName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewStorageAccount : string -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate" Usage="iWithStorage.WithNewStorageAccount storageAccountName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName"><span data-ttu-id="5659d-108">Der Name eines neuen Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="5659d-108">The name of a new storage account.</span></span></param>
        <summary>
            <span data-ttu-id="5659d-109">Gibt den Namen eines neuen Speicherkontos erstellt und dieses Batch-Konto zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="5659d-109">Specifies the name of a new storage account to be created and associated with this Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5659d-110">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="5659d-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>