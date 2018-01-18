<Type Name="StorageProgress" FullName="Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress">
  <TypeSignature Language="C#" Value="public sealed class StorageProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StorageProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StorageProgress" />
  <TypeSignature Language="F#" Value="type StorageProgress = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d6977-101">Enthält Informationen über die Statusdaten für Anforderung und Antwort-Datenströme in einem einzigen Vorgang übertragen.</span><span class="sxs-lookup"><span data-stu-id="d6977-101">Holds information about the progress data transfers for both request and response streams in a single operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageProgress (long bytesTransferred);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 bytesTransferred) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress.#ctor(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (bytesTransferred As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress : int64 -&gt; Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" Usage="new Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress bytesTransferred" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="bytesTransferred" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="bytesTransferred"><span data-ttu-id="d6977-102">Der Statuswert, der gemeldet wird.</span><span class="sxs-lookup"><span data-stu-id="d6977-102">The progress value being reported.</span></span></param>
        <summary>
            <span data-ttu-id="d6977-103">Erstellt ein <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="d6977-103">Creates a <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BytesTransferred">
      <MemberSignature Language="C#" Value="public long BytesTransferred { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 BytesTransferred" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress.BytesTransferred" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BytesTransferred As Long" />
      <MemberSignature Language="F#" Value="member this.BytesTransferred : int64" Usage="Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress.BytesTransferred" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6977-104">Status der Anforderung Datenübertragung in Bytes.</span><span class="sxs-lookup"><span data-stu-id="d6977-104">Progress in bytes of the request data transfer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>