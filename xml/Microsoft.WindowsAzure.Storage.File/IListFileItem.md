<Type Name="IListFileItem" FullName="Microsoft.WindowsAzure.Storage.File.IListFileItem">
  <TypeSignature Language="C#" Value="public interface IListFileItem" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IListFileItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.IListFileItem" />
  <TypeSignature Language="VB.NET" Value="Public Interface IListFileItem" />
  <TypeSignature Language="F#" Value="type IListFileItem = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ecee4-101">Stellt ein Element, das durch einen dateiauflistungsvorgang zurückgegeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="ecee4-101">Represents an item that may be returned by a file listing operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Parent">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.CloudFileDirectory Parent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory Parent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.IListFileItem.Parent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parent As CloudFileDirectory" />
      <MemberSignature Language="F#" Value="member this.Parent : Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" Usage="Microsoft.WindowsAzure.Storage.File.IListFileItem.Parent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.CloudFileDirectory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecee4-102">Ruft die übergeordnete Verzeichnis des Dateielements ab.</span><span class="sxs-lookup"><span data-stu-id="ecee4-102">Gets the file item's parent directory.</span></span>
            </summary>
        <value><span data-ttu-id="ecee4-103">Übergeordnete-Verzeichnis des Dateielements.</span><span class="sxs-lookup"><span data-stu-id="ecee4-103">The file item's parent directory.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Share">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.CloudFileShare Share { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.CloudFileShare Share" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.IListFileItem.Share" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Share As CloudFileShare" />
      <MemberSignature Language="F#" Value="member this.Share : Microsoft.WindowsAzure.Storage.File.CloudFileShare" Usage="Microsoft.WindowsAzure.Storage.File.IListFileItem.Share" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.CloudFileShare</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecee4-104">Ruft die Freigabe des Dateielements ab.</span><span class="sxs-lookup"><span data-stu-id="ecee4-104">Gets the file item's share.</span></span>
            </summary>
        <value><span data-ttu-id="ecee4-105">Freigabe des Dateielements.</span><span class="sxs-lookup"><span data-stu-id="ecee4-105">The file item's share.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.IListFileItem.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.File.IListFileItem.StorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecee4-106">Ruft den URI des Dateielements ab.</span><span class="sxs-lookup"><span data-stu-id="ecee4-106">Gets the URI to the file item.</span></span>
            </summary>
        <value><span data-ttu-id="ecee4-107">Der URI des Dateielements.</span><span class="sxs-lookup"><span data-stu-id="ecee4-107">The file item's URI.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.IListFileItem.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.WindowsAzure.Storage.File.IListFileItem.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecee4-108">Ruft den URI des Dateielements ab.</span><span class="sxs-lookup"><span data-stu-id="ecee4-108">Gets the URI to the file item.</span></span>
            </summary>
        <value><span data-ttu-id="ecee4-109">Der URI des Dateielements.</span><span class="sxs-lookup"><span data-stu-id="ecee4-109">The file item's URI.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>