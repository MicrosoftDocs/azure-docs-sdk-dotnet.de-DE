<Type Name="LeaseAction" FullName="Microsoft.WindowsAzure.Storage.Blob.LeaseAction">
  <TypeSignature Language="C#" Value="public enum LeaseAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed LeaseAction extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.LeaseAction" />
  <TypeSignature Language="VB.NET" Value="Public Enum LeaseAction" />
  <TypeSignature Language="F#" Value="type LeaseAction = " />
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
            <span data-ttu-id="4c6ca-101">Beschreibt Aktionen, die auf einem Lease ausgeführt werden können.</span><span class="sxs-lookup"><span data-stu-id="4c6ca-101">Describes actions that can be performed on a lease.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Acquire">
      <MemberSignature Language="C#" Value="Acquire" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseAction Acquire = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.LeaseAction.Acquire" />
      <MemberSignature Language="VB.NET" Value="Acquire" />
      <MemberSignature Language="F#" Value="Acquire = 0" Usage="Microsoft.WindowsAzure.Storage.Blob.LeaseAction.Acquire" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseAction</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c6ca-102">Die Lease abrufen.</span><span class="sxs-lookup"><span data-stu-id="4c6ca-102">Acquire the lease.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Break">
      <MemberSignature Language="C#" Value="Break" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseAction Break = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.LeaseAction.Break" />
      <MemberSignature Language="VB.NET" Value="Break" />
      <MemberSignature Language="F#" Value="Break = 3" Usage="Microsoft.WindowsAzure.Storage.Blob.LeaseAction.Break" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseAction</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c6ca-103">Unterbrochen Sie die Lease werden.</span><span class="sxs-lookup"><span data-stu-id="4c6ca-103">Break the lease.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Change">
      <MemberSignature Language="C#" Value="Change" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseAction Change = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.LeaseAction.Change" />
      <MemberSignature Language="VB.NET" Value="Change" />
      <MemberSignature Language="F#" Value="Change = 4" Usage="Microsoft.WindowsAzure.Storage.Blob.LeaseAction.Change" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseAction</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c6ca-104">Ändern der Lease-ID</span><span class="sxs-lookup"><span data-stu-id="4c6ca-104">Change the lease ID.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Release">
      <MemberSignature Language="C#" Value="Release" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseAction Release = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.LeaseAction.Release" />
      <MemberSignature Language="VB.NET" Value="Release" />
      <MemberSignature Language="F#" Value="Release = 2" Usage="Microsoft.WindowsAzure.Storage.Blob.LeaseAction.Release" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseAction</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c6ca-105">Freigeben der Lease an.</span><span class="sxs-lookup"><span data-stu-id="4c6ca-105">Release the lease.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Renew">
      <MemberSignature Language="C#" Value="Renew" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseAction Renew = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.LeaseAction.Renew" />
      <MemberSignature Language="VB.NET" Value="Renew" />
      <MemberSignature Language="F#" Value="Renew = 1" Usage="Microsoft.WindowsAzure.Storage.Blob.LeaseAction.Renew" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseAction</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c6ca-106">Die Lease zu verlängern.</span><span class="sxs-lookup"><span data-stu-id="4c6ca-106">Renew the lease.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>