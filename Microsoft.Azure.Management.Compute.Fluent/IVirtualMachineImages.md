<Type Name="IVirtualMachineImages" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImages">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineImages : Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByRegion&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineImages implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByRegion`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImages" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineImages&#xA;Implements ISupportsListingByRegion(Of IVirtualMachineImage)" />
  <TypeSignature Language="F#" Value="type IVirtualMachineImages = interface&#xA;    interface ISupportsListingByRegion&lt;IVirtualMachineImage&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByRegion&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="8cd80-101">Einstiegspunkt für einen VM-Image-Verwaltungs-API.</span><span class="sxs-lookup"><span data-stu-id="8cd80-101">Entry point to virtual machine image management API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage GetImage (Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region, string publisherName, string offerName, string skuName, string version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage GetImage(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region, string publisherName, string offerName, string skuName, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImages.GetImage(Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="abstract member GetImage : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region * string * string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage" Usage="iVirtualMachineImages.GetImage (region, publisherName, offerName, skuName, version)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="region" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="offerName" Type="System.String" />
        <Parameter Name="skuName" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="region"><span data-ttu-id="8cd80-102">Die Region.</span><span class="sxs-lookup"><span data-stu-id="8cd80-102">The region.</span></span></param>
        <param name="publisherName"><span data-ttu-id="8cd80-103">Name des Verlegers.</span><span class="sxs-lookup"><span data-stu-id="8cd80-103">Publisher name.</span></span></param>
        <param name="offerName"><span data-ttu-id="8cd80-104">Angebotsname.</span><span class="sxs-lookup"><span data-stu-id="8cd80-104">Offer name.</span></span></param>
        <param name="skuName"><span data-ttu-id="8cd80-105">SKU-Name.</span><span class="sxs-lookup"><span data-stu-id="8cd80-105">SKU name.</span></span></param>
        <param name="version"><span data-ttu-id="8cd80-106">Der Name.</span><span class="sxs-lookup"><span data-stu-id="8cd80-106">Version name.</span></span></param>
        <summary>
            <span data-ttu-id="8cd80-107">Ruft ein Image eines virtuellen Computers ab.</span><span class="sxs-lookup"><span data-stu-id="8cd80-107">Gets a virtual machine image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8cd80-108">Image des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="8cd80-108">The virtual machine image.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage GetImage (string region, string publisherName, string offerName, string skuName, string version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage GetImage(string region, string publisherName, string offerName, string skuName, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImages.GetImage(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetImage (region As String, publisherName As String, offerName As String, skuName As String, version As String) As IVirtualMachineImage" />
      <MemberSignature Language="F#" Value="abstract member GetImage : string * string * string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage" Usage="iVirtualMachineImages.GetImage (region, publisherName, offerName, skuName, version)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="region" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="offerName" Type="System.String" />
        <Parameter Name="skuName" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="region">To be added.</param>
        <param name="publisherName">To be added.</param>
        <param name="offerName">To be added.</param>
        <param name="skuName">To be added.</param>
        <param name="version">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Publishers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinePublishers Publishers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinePublishers Publishers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImages.Publishers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Publishers As IVirtualMachinePublishers" />
      <MemberSignature Language="F#" Value="member this.Publishers : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinePublishers" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImages.Publishers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinePublishers</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8cd80-109">Ruft den Einstiegspunkt für VM-Image Verleger ab.</span><span class="sxs-lookup"><span data-stu-id="8cd80-109">Gets entry point to virtual machine image publishers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>