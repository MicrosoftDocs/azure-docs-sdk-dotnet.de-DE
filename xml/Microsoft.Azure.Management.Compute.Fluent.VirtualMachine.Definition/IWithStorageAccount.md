<Type Name="IWithStorageAccount" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount">
  <TypeSignature Language="C#" Value="public interface IWithStorageAccount" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithStorageAccount" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithStorageAccount" />
  <TypeSignature Language="F#" Value="type IWithStorageAccount = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5c7ed-101">Die Phase der Definition eines virtuellen Computers zulassen an ein Speicherkonto angeben.</span><span class="sxs-lookup"><span data-stu-id="5c7ed-101">The stage of a virtual machine definition allowing to specify a storage account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithExistingStorageAccount (Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithExistingStorageAccount(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount.WithExistingStorageAccount(Microsoft.Azure.Management.Storage.Fluent.IStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingStorageAccount (storageAccount As IStorageAccount) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingStorageAccount : Microsoft.Azure.Management.Storage.Fluent.IStorageAccount -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithStorageAccount.WithExistingStorageAccount storageAccount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount" />
      </Parameters>
      <Docs>
        <param name="storageAccount"><span data-ttu-id="5c7ed-102">Ein vorhandenes Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="5c7ed-102">An existing storage account.</span></span></param>
        <summary>
            <span data-ttu-id="5c7ed-103">Gibt ein vorhandenes Speicherkonto zum Einfügen einer VM Betriebssystem und die Datenträger in VHD.</span><span class="sxs-lookup"><span data-stu-id="5c7ed-103">Specifies an existing storage account to put the VM's OS and data disk VHD in.</span></span>
            <span data-ttu-id="5c7ed-104">In diesem Speicherkonto wird ein Betriebssystem-Datenträger, die basierend auf einem Markt oder einem benutzerimage (generalisierten Image) gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="5c7ed-104">An OS disk based on a marketplace or a user image (generalized image) will be stored in this storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5c7ed-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="5c7ed-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewStorageAccount (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewStorageAccount(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount.WithNewStorageAccount(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Storage.Fluent.IStorageAccount})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStorageAccount (creatable As ICreatable(Of IStorageAccount)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewStorageAccount : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithStorageAccount.WithNewStorageAccount creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable"><span data-ttu-id="5c7ed-106">Die Definition einer erstellbaren Storage-Konto.</span><span class="sxs-lookup"><span data-stu-id="5c7ed-106">A creatable storage account definition.</span></span></param>
        <summary>
            <span data-ttu-id="5c7ed-107">Gibt die Definition der noch nicht erstellt Speicherkontos zum Einfügen von Betriebssystem und die Daten des virtuellen Computers auf den Datenträger VHDs in.</span><span class="sxs-lookup"><span data-stu-id="5c7ed-107">Specifies the definition of a not-yet-created storage account to put the VM's OS and data disk VHDs into.</span></span>
            <span data-ttu-id="5c7ed-108">Nur die Betriebssystem-Datenträger, die auf Grundlage eines Marketplace-Images werden in das neue Speicherkonto gespeichert.</span><span class="sxs-lookup"><span data-stu-id="5c7ed-108">Only the OS disk based on a marketplace image will be stored in the new storage account.</span></span>
            <span data-ttu-id="5c7ed-109">Ein Betriebssystem-Datenträger, die basierend auf einem benutzerimage wird in dasselbe Speicherkonto wie das Bild Benutzer gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="5c7ed-109">An OS disk based on a user image will be stored in the same storage account as the user image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5c7ed-110">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="5c7ed-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewStorageAccount (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewStorageAccount(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount.WithNewStorageAccount(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStorageAccount (name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewStorageAccount : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithStorageAccount.WithNewStorageAccount name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5c7ed-111">Der Name für ein neues Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="5c7ed-111">The name for a new storage account.</span></span></param>
        <summary>
            <span data-ttu-id="5c7ed-112">Gibt den Namen eines neuen Speicherkontos Ablegen von Betriebssystem und die Daten des virtuellen Computers auf den Datenträger in VHD.</span><span class="sxs-lookup"><span data-stu-id="5c7ed-112">Specifies the name of a new storage account to put the VM's OS and data disk VHD into.</span></span>
            <span data-ttu-id="5c7ed-113">Nur ein Betriebssystemdatenträger, basierend auf einem Marketplace-Image wird in das neue Speicherkonto gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="5c7ed-113">Only an OS disk based on a marketplace image will be stored in the new storage account.</span></span>
            <span data-ttu-id="5c7ed-114">Ein Betriebssystem-Datenträger, die basierend auf einem benutzerimage wird in dasselbe Speicherkonto wie das Bild Benutzer gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="5c7ed-114">An OS disk based on a user image will be stored in the same storage account as the user image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5c7ed-115">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="5c7ed-115">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>