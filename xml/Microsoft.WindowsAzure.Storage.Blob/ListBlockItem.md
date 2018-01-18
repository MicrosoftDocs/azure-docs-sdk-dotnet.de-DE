<Type Name="ListBlockItem" FullName="Microsoft.WindowsAzure.Storage.Blob.ListBlockItem">
  <TypeSignature Language="C#" Value="public sealed class ListBlockItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListBlockItem extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListBlockItem" />
  <TypeSignature Language="F#" Value="type ListBlockItem = class" />
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
            <span data-ttu-id="334f4-101">Stellt einen Block aus der blobsperrliste abgerufen.</span><span class="sxs-lookup"><span data-stu-id="334f4-101">Represents a block retrieved from the blob's block list.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListBlockItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Committed">
      <MemberSignature Language="C#" Value="public bool Committed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Committed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem.Committed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Committed As Boolean" />
      <MemberSignature Language="F#" Value="member this.Committed : bool" Usage="Microsoft.WindowsAzure.Storage.Blob.ListBlockItem.Committed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="334f4-102">Ruft einen Wert, der angibt, ab, unabhängig davon, ob der Block ein Commit ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="334f4-102">Gets a value indicating whether or not the block has been committed.</span></span>
            </summary>
        <value>
          <span data-ttu-id="334f4-103"><c>"true"</c> , wenn der Block ein Commit ausgeführt wurde; andernfalls wurde <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="334f4-103"><c>true</c> if the block has been committed; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public long Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem.Length" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64" Usage="Microsoft.WindowsAzure.Storage.Blob.ListBlockItem.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="334f4-104">Ruft die Größe des Blocks in Bytes ab.</span><span class="sxs-lookup"><span data-stu-id="334f4-104">Gets the size of block in bytes.</span></span>
            </summary>
        <value><span data-ttu-id="334f4-105">Die Blockgröße.</span><span class="sxs-lookup"><span data-stu-id="334f4-105">The block size.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.WindowsAzure.Storage.Blob.ListBlockItem.Name" />
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
            <span data-ttu-id="334f4-106">Ruft den Namen des Blocks ab.</span><span class="sxs-lookup"><span data-stu-id="334f4-106">Gets the name of the block.</span></span>
            </summary>
        <value><span data-ttu-id="334f4-107">Der Blockname.</span><span class="sxs-lookup"><span data-stu-id="334f4-107">The block name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>