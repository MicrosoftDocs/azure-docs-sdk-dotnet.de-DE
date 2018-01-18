<Type Name="BlockListingFilter" FullName="Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter">
  <TypeSignature Language="C#" Value="public enum BlockListingFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed BlockListingFilter extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />
  <TypeSignature Language="VB.NET" Value="Public Enum BlockListingFilter" />
  <TypeSignature Language="F#" Value="type BlockListingFilter = " />
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
            <span data-ttu-id="5f2d0-101">Gibt an, ob nur Blöcke mit ausgeführtem Commit, nur die Blöcke ohne ausgeführten Commit oder alle Blöcke aufgelistet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5f2d0-101">Indicates whether to list only committed blocks, only uncommitted blocks, or all blocks.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="All">
      <MemberSignature Language="C#" Value="All" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter All = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter.All" />
      <MemberSignature Language="VB.NET" Value="All" />
      <MemberSignature Language="F#" Value="All = 2" Usage="Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter.All" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="5f2d0-102">Sowohl und ohne Commit blockiert.</span><span class="sxs-lookup"><span data-stu-id="5f2d0-102">Both committed and uncommitted blocks.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Committed">
      <MemberSignature Language="C#" Value="Committed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter Committed = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter.Committed" />
      <MemberSignature Language="VB.NET" Value="Committed" />
      <MemberSignature Language="F#" Value="Committed = 0" Usage="Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter.Committed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="5f2d0-103">Blöcke mit ausgeführtem Commit.</span><span class="sxs-lookup"><span data-stu-id="5f2d0-103">Committed blocks.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Uncommitted">
      <MemberSignature Language="C#" Value="Uncommitted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter Uncommitted = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter.Uncommitted" />
      <MemberSignature Language="VB.NET" Value="Uncommitted" />
      <MemberSignature Language="F#" Value="Uncommitted = 1" Usage="Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter.Uncommitted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="5f2d0-104">Blöcke.</span><span class="sxs-lookup"><span data-stu-id="5f2d0-104">Uncommitted blocks.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>