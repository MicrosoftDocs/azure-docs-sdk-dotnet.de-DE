<Type Name="ResourceEncryptionKeyOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.ResourceEncryptionKeyOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ResourceEncryptionKeyOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ResourceEncryptionKeyOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.ResourceEncryptionKeyOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ResourceEncryptionKeyOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ResourceEncryptionKeyOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e5ebd-101">Dies ist eine RESTFul-API, um Sie StorSimple-Objekte zu verwalten</span><span class="sxs-lookup"><span data-stu-id="e5ebd-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ResourceEncryptionKeyOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.ResourceEncryptionKeyOperationsExtensions.Get (operations, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations" RefType="this" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e5ebd-102">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations.</span><span class="sxs-lookup"><span data-stu-id="e5ebd-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="e5ebd-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e5ebd-103">Required.</span></span> <span data-ttu-id="e5ebd-104">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="e5ebd-104">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="e5ebd-105">Das Antwort-Modell für den Verschlüsselungsschlüssel für die Ressource.</span><span class="sxs-lookup"><span data-stu-id="e5ebd-105">The response model for Resource Encryption Key.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ResourceEncryptionKeyOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.ResourceEncryptionKeyOperationsExtensions.GetAsync (operations, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations" RefType="this" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e5ebd-106">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations.</span><span class="sxs-lookup"><span data-stu-id="e5ebd-106">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="e5ebd-107">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e5ebd-107">Required.</span></span> <span data-ttu-id="e5ebd-108">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="e5ebd-108">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="e5ebd-109">Das Antwort-Modell für den Verschlüsselungsschlüssel für die Ressource.</span><span class="sxs-lookup"><span data-stu-id="e5ebd-109">The response model for Resource Encryption Key.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>