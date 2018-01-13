<Type Name="PutBlockListItem" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem">
  <TypeSignature Language="C#" Value="public sealed class PutBlockListItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PutBlockListItem extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PutBlockListItem" />
  <TypeSignature Language="F#" Value="type PutBlockListItem = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="60cca-101">Stellt einen Block in einer Blockliste dar.</span><span class="sxs-lookup"><span data-stu-id="60cca-101">Represents a block in a block list.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutBlockListItem (string id, Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode searchMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, valuetype Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode searchMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem.#ctor(System.String,Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, searchMode As BlockSearchMode)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem : string * Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode -&gt; Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem" Usage="new Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem (id, searchMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="searchMode" Type="Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="60cca-102">Die Block-ID.</span><span class="sxs-lookup"><span data-stu-id="60cca-102">The block ID.</span></span></param>
        <param name="searchMode"><span data-ttu-id="60cca-103">Einer der Enumerationswerte, der angibt, in welcher Block aufgelistet, für den Block gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="60cca-103">One of the enumeration values that specifies in which block lists to search for the block.</span></span></param>
        <summary>
            <span data-ttu-id="60cca-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="60cca-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60cca-105">Ruft die Block-ID.</span><span class="sxs-lookup"><span data-stu-id="60cca-105">Gets the block ID.</span></span>
            </summary>
        <value><span data-ttu-id="60cca-106">Die Block-ID.</span><span class="sxs-lookup"><span data-stu-id="60cca-106">The block ID.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchMode">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode SearchMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode SearchMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem.SearchMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SearchMode As BlockSearchMode" />
      <MemberSignature Language="F#" Value="member this.SearchMode : Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem.SearchMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60cca-107">Ruft einen Wert, der angibt, welche Blocklisten nach dem Block durchsucht.</span><span class="sxs-lookup"><span data-stu-id="60cca-107">Gets a value that indicates which block lists to search for the block.</span></span>
            </summary>
        <value><span data-ttu-id="60cca-108">Einer der Enumerationswerte, der angibt, in welcher Block aufgelistet, für den Block gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="60cca-108">One of the enumeration values that specifies in which block lists to search for the block.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>