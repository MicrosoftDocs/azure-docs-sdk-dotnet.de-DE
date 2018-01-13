<Type Name="IVirtualMachineExtensionImage" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineExtensionImage : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineExtensionImage implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineExtensionImage&#xA;Implements IHasInner(Of VirtualMachineExtensionImageInner)" />
  <TypeSignature Language="F#" Value="type IVirtualMachineExtensionImage = interface&#xA;    interface IHasInner&lt;VirtualMachineExtensionImageInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="7e3d8-101">Eine unveränderliche clientseitige Darstellung eines Bilds Erweiterung virtuellen Azure-Computer.</span><span class="sxs-lookup"><span data-stu-id="7e3d8-101">An immutable client-side representation of an Azure virtual machine extension image.</span></span>
            <span data-ttu-id="7e3d8-102">Hinweis: Azure VM-Erweiterung-Image wird auch als VM-Erweiterungshandler bezeichnet.</span><span class="sxs-lookup"><span data-stu-id="7e3d8-102">Note: Azure virtual machine extension image is also referred as virtual machine extension handler.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ComputeRole">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.ComputeRoles ComputeRole { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.ComputeRoles ComputeRole" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.ComputeRole" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputeRole As ComputeRoles" />
      <MemberSignature Language="F#" Value="member this.ComputeRole : Microsoft.Azure.Management.Compute.Fluent.ComputeRoles" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.ComputeRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.ComputeRoles</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e3d8-103">Ruft den Typ der Rolle, die diese Erweiterung Abbild eines virtuellen Computers unterstützt.</span><span class="sxs-lookup"><span data-stu-id="7e3d8-103">Gets the type of role this virtual machine extension image supports.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HandlerSchema">
      <MemberSignature Language="C#" Value="public string HandlerSchema { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HandlerSchema" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.HandlerSchema" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HandlerSchema As String" />
      <MemberSignature Language="F#" Value="member this.HandlerSchema : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.HandlerSchema" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e3d8-104">Ruft das Schema ab vom Herausgeber, definiert, in denen sollten Consumer Erweiterung Einstellungen in ein übereinstimmendes Schema bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="7e3d8-104">Gets the schema defined by publisher, where extension consumers should provide settings in a matching schema.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e3d8-105">Ruft die Ressourcen-ID des Bilds Erweiterung ab.</span><span class="sxs-lookup"><span data-stu-id="7e3d8-105">Gets the resource ID of the extension image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OSType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OSType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.OSType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSType As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="member this.OSType : Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.OSType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e3d8-106">Ruft das Betriebssystem, das diese Erweiterung Abbild eines virtuellen Computers unterstützt.</span><span class="sxs-lookup"><span data-stu-id="7e3d8-106">Gets the operating system this virtual machine extension image supports.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublisherName">
      <MemberSignature Language="C#" Value="public string PublisherName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublisherName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.PublisherName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublisherName As String" />
      <MemberSignature Language="F#" Value="member this.PublisherName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.PublisherName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e3d8-107">Ruft den Namen des Herausgebers der Erweiterung-Image des virtuellen Computers ab.</span><span class="sxs-lookup"><span data-stu-id="7e3d8-107">Gets the name of the publisher of the virtual machine extension image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegionName">
      <MemberSignature Language="C#" Value="public string RegionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.RegionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegionName As String" />
      <MemberSignature Language="F#" Value="member this.RegionName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.RegionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e3d8-108">Ruft die Region, in die Virtual, die Machine Erweiterung Image verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="7e3d8-108">Gets the region in which virtual machine extension image is available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportsMultipleExtensions">
      <MemberSignature Language="C#" Value="public bool SupportsMultipleExtensions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportsMultipleExtensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.SupportsMultipleExtensions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportsMultipleExtensions As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportsMultipleExtensions : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.SupportsMultipleExtensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e3d8-109">Ruft "true", wenn der Ereignishandler mehrere Erweiterungen unterstützen kann.</span><span class="sxs-lookup"><span data-stu-id="7e3d8-109">Gets true if the handler can support multiple extensions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportsVirtualMachineScaleSets">
      <MemberSignature Language="C#" Value="public bool SupportsVirtualMachineScaleSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportsVirtualMachineScaleSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.SupportsVirtualMachineScaleSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportsVirtualMachineScaleSets As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportsVirtualMachineScaleSets : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.SupportsVirtualMachineScaleSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e3d8-110">Ruft "true", wenn die Erweiterung mit VM-skalierungsgruppen "false" andernfalls verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="7e3d8-110">Gets true if the extension can be used with virtual machine scale sets, false otherwise.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeName">
      <MemberSignature Language="C#" Value="public string TypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TypeName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.TypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TypeName As String" />
      <MemberSignature Language="F#" Value="member this.TypeName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.TypeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e3d8-111">Ruft den Namen des virtuellen Computers Erweiterung Image-Typs, der dieses Image angehört.</span><span class="sxs-lookup"><span data-stu-id="7e3d8-111">Gets the name of the virtual machine extension image type this image belongs to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As IVirtualMachineExtensionImageVersion" />
      <MemberSignature Language="F#" Value="member this.Version : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e3d8-112">Ruft die Erweiterungsversion Image der virtuellen Maschine, der dieses Image gehört.</span><span class="sxs-lookup"><span data-stu-id="7e3d8-112">Gets the virtual machine extension image version this image belongs to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VersionName">
      <MemberSignature Language="C#" Value="public string VersionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VersionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.VersionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VersionName As String" />
      <MemberSignature Language="F#" Value="member this.VersionName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.VersionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e3d8-113">Ruft den Namen der virtuellen Maschine-imageversion-Erweiterung, den dieses Bild darstellt.</span><span class="sxs-lookup"><span data-stu-id="7e3d8-113">Gets the name of the virtual machine extension image version this image represents.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>