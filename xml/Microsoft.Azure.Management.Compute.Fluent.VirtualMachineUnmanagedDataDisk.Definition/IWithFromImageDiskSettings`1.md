<Type Name="IWithFromImageDiskSettings&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithFromImageDiskSettings&lt;ParentT&gt; : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithAttach&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFromImageDiskSettings`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithAttach`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFromImageDiskSettings(Of ParentT)&#xA;Implements IInDefinition(Of ParentT), IWithAttach(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithFromImageDiskSettings&lt;'ParentT&gt; = interface&#xA;    interface IWithAttach&lt;'ParentT&gt;&#xA;    interface IInDefinition&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithAttach&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="0c794-101">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="0c794-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="0c794-102">Die Stufe, die ermöglicht das Konfigurieren der Datenträger, die basierend auf einem Bild.</span><span class="sxs-lookup"><span data-stu-id="0c794-102">The stage that allows configure the disk based on an image.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="StoreAt">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings&lt;ParentT&gt; StoreAt (string storageAccountName, string containerName, string vhdName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings`1&lt;!ParentT&gt; StoreAt(string storageAccountName, string containerName, string vhdName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings`1.StoreAt(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function StoreAt (storageAccountName As String, containerName As String, vhdName As String) As IWithFromImageDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member StoreAt : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings&lt;'ParentT&gt;" Usage="iWithFromImageDiskSettings.StoreAt (storageAccountName, containerName, vhdName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="vhdName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName"><span data-ttu-id="0c794-103">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="0c794-103">The storage account name.</span></span></param>
        <param name="containerName"><span data-ttu-id="0c794-104">Der Name des Containers zum Speichern der neuen VHD-Datei.</span><span class="sxs-lookup"><span data-stu-id="0c794-104">The name of the container to hold the new VHD file.</span></span></param>
        <param name="vhdName"><span data-ttu-id="0c794-105">Der Name für die neue VHD-Datei.</span><span class="sxs-lookup"><span data-stu-id="0c794-105">The name for the new VHD file.</span></span></param>
        <summary>
            <span data-ttu-id="0c794-106">Gibt an, in denen die neuer leerer Datenträger zugeordnete VHD-Datei gespeichert werden muss.</span><span class="sxs-lookup"><span data-stu-id="0c794-106">Specifies where the VHD associated with the new blank data disk needs to be stored.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0c794-107">Die nächste Phase der Datendefinition der Datenträger.</span><span class="sxs-lookup"><span data-stu-id="0c794-107">The next stage of data disk definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithCaching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings&lt;ParentT&gt; WithCaching (Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings`1&lt;!ParentT&gt; WithCaching(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings`1.WithCaching(Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCaching (cachingType As CachingTypes) As IWithFromImageDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithCaching : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings&lt;'ParentT&gt;" Usage="iWithFromImageDiskSettings.WithCaching cachingType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="cachingType"><span data-ttu-id="0c794-108">der Datenträger, die caching-Typ.</span><span class="sxs-lookup"><span data-stu-id="0c794-108">The disk caching type.</span></span> <span data-ttu-id="0c794-109">Folgende Werte sind möglich: "None", "ReadOnly", "ReadWrite".</span><span class="sxs-lookup"><span data-stu-id="0c794-109">Possible values include: 'None', 'ReadOnly', 'ReadWrite'.</span></span></param>
        <summary>
            <span data-ttu-id="0c794-110">Gibt an, welche Zwischenspeichern für den Datenträger.</span><span class="sxs-lookup"><span data-stu-id="0c794-110">Specifies the caching type for the data disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0c794-111">Die nächste Phase der Datendefinition der Datenträger.</span><span class="sxs-lookup"><span data-stu-id="0c794-111">The next stage of data disk definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSizeInGB">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings&lt;ParentT&gt; WithSizeInGB (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings`1&lt;!ParentT&gt; WithSizeInGB(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings`1.WithSizeInGB(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSizeInGB (sizeInGB As Integer) As IWithFromImageDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithSizeInGB : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings&lt;'ParentT&gt;" Usage="iWithFromImageDiskSettings.WithSizeInGB sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithFromImageDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB"><span data-ttu-id="0c794-112">Die Größe des Datenträgers in GB.</span><span class="sxs-lookup"><span data-stu-id="0c794-112">The disk size in GB.</span></span></param>
        <summary>
            <span data-ttu-id="0c794-113">Gibt die Größe in GB für den Datenträger muss geändert werden soll.</span><span class="sxs-lookup"><span data-stu-id="0c794-113">Specifies the size in GB the disk needs to be resized.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0c794-114">Die nächste Phase der Datendefinition der Datenträger.</span><span class="sxs-lookup"><span data-stu-id="0c794-114">The next stage of data disk definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>