<Type Name="BlobContainerPublicAccessType" FullName="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType">
  <TypeSignature Language="C#" Value="public enum BlobContainerPublicAccessType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed BlobContainerPublicAccessType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
  <TypeSignature Language="VB.NET" Value="Public Enum BlobContainerPublicAccessType" />
  <TypeSignature Language="F#" Value="type BlobContainerPublicAccessType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="6899d-101">Gibt die Ebene des öffentlichen Zugriffs, der für den Container zulässig ist.</span><span class="sxs-lookup"><span data-stu-id="6899d-101">Specifies the level of public access that is allowed on the container.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Blob">
      <MemberSignature Language="C#" Value="Blob" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType Blob = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType.Blob" />
      <MemberSignature Language="VB.NET" Value="Blob" />
      <MemberSignature Language="F#" Value="Blob = 2" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType.Blob" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6899d-102">Auf blobebene öffentlicher Zugriff.</span><span class="sxs-lookup"><span data-stu-id="6899d-102">Blob-level public access.</span></span> <span data-ttu-id="6899d-103">Anonyme Clients können blobdaten innerhalb dieses Containers, aber keine Containerdaten lesen.</span><span class="sxs-lookup"><span data-stu-id="6899d-103">Anonymous clients can read blob data within this container, but not container data.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="Container" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType Container = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType.Container" />
      <MemberSignature Language="VB.NET" Value="Container" />
      <MemberSignature Language="F#" Value="Container = 1" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType.Container" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6899d-104">Auf Containerebene öffentlicher Zugriff.</span><span class="sxs-lookup"><span data-stu-id="6899d-104">Container-level public access.</span></span> <span data-ttu-id="6899d-105">Anonyme Clients können Container-und blobdaten lesen.</span><span class="sxs-lookup"><span data-stu-id="6899d-105">Anonymous clients can read container and blob data.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Off">
      <MemberSignature Language="C#" Value="Off" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType Off = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType.Off" />
      <MemberSignature Language="VB.NET" Value="Off" />
      <MemberSignature Language="F#" Value="Off = 0" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType.Off" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6899d-106">Kein öffentlicher Zugriff.</span><span class="sxs-lookup"><span data-stu-id="6899d-106">No public access.</span></span> <span data-ttu-id="6899d-107">Nur der Kontobesitzer kann Ressourcen in diesem Container lesen.</span><span class="sxs-lookup"><span data-stu-id="6899d-107">Only the account owner can read resources in this container.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="Unknown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType Unknown = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType.Unknown" />
      <MemberSignature Language="VB.NET" Value="Unknown" />
      <MemberSignature Language="F#" Value="Unknown = 3" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6899d-108">Der Zugriffstyp ist unbekannt.</span><span class="sxs-lookup"><span data-stu-id="6899d-108">Unknown access type.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>