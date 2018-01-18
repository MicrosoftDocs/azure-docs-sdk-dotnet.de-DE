<Type Name="PageDiffRange" FullName="Microsoft.WindowsAzure.Storage.Blob.PageDiffRange">
  <TypeSignature Language="C#" Value="public sealed class PageDiffRange : Microsoft.WindowsAzure.Storage.Blob.PageRange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PageDiffRange extends Microsoft.WindowsAzure.Storage.Blob.PageRange" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.PageDiffRange" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PageDiffRange&#xA;Inherits PageRange" />
  <TypeSignature Language="F#" Value="type PageDiffRange = class&#xA;    inherit PageRange" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Blob.PageRange</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="43e23-101">Stellt einen Bereich von Seiten in einem Seitenblob dar.</span><span class="sxs-lookup"><span data-stu-id="43e23-101">Represents a range of pages in a page blob.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PageDiffRange (long start, long end, bool isCleared);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 start, int64 end, bool isCleared) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.PageDiffRange.#ctor(System.Int64,System.Int64,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (start As Long, end As Long, isCleared As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.PageDiffRange : int64 * int64 * bool -&gt; Microsoft.WindowsAzure.Storage.Blob.PageDiffRange" Usage="new Microsoft.WindowsAzure.Storage.Blob.PageDiffRange (start, end, isCleared)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="start" Type="System.Int64" />
        <Parameter Name="end" Type="System.Int64" />
        <Parameter Name="isCleared" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="start"><span data-ttu-id="43e23-102">Der Startoffset.</span><span class="sxs-lookup"><span data-stu-id="43e23-102">The starting offset.</span></span></param>
        <param name="end"><span data-ttu-id="43e23-103">Der Endoffset.</span><span class="sxs-lookup"><span data-stu-id="43e23-103">The ending offset.</span></span></param>
        <param name="isCleared"><span data-ttu-id="43e23-104">"True", wenn der Seitenbereich eines gelöschten Bereichs "false" ist.</span><span class="sxs-lookup"><span data-stu-id="43e23-104">True if the page range is a cleared range, false otherwise.</span></span></param>
        <summary>
            <span data-ttu-id="43e23-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageDiffRange" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="43e23-105">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageDiffRange" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsClearedPageRange">
      <MemberSignature Language="C#" Value="public bool IsClearedPageRange { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsClearedPageRange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.PageDiffRange.IsClearedPageRange" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsClearedPageRange As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsClearedPageRange : bool" Usage="Microsoft.WindowsAzure.Storage.Blob.PageDiffRange.IsClearedPageRange" />
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
            <span data-ttu-id="43e23-106">"True", wenn der Seitenbereich eines gelöschten Bereichs "false" ist.</span><span class="sxs-lookup"><span data-stu-id="43e23-106">True if the page range is a cleared range, false otherwise.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>