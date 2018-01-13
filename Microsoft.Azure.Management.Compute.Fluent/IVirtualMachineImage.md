<Type Name="IVirtualMachineImage" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineImage : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageInner&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineImage implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageInner&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineImage&#xA;Implements IHasInner(Of VirtualMachineImageInner)" />
  <TypeSignature Language="F#" Value="type IVirtualMachineImage = interface&#xA;    interface IHasInner&lt;VirtualMachineImageInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageInner&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Eine unveränderliche clientseitige Darstellung eines Bilds virtuellen Azure-Computer.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DataDiskImages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;int,Microsoft.Azure.Management.Compute.Fluent.Models.DataDiskImage&gt; DataDiskImages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;int32, class Microsoft.Azure.Management.Compute.Fluent.Models.DataDiskImage&gt; DataDiskImages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.DataDiskImages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataDiskImages As IReadOnlyDictionary(Of Integer, DataDiskImage)" />
      <MemberSignature Language="F#" Value="member this.DataDiskImages : System.Collections.Generic.IReadOnlyDictionary&lt;int, Microsoft.Azure.Management.Compute.Fluent.Models.DataDiskImage&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.DataDiskImages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.DataDiskImage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Daten Datenträgerabbilder in Image des virtuellen Computers, von dem Datenträger LUN indiziert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.Id" />
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
            Ruft die Ressourcen-ID dieses Bilds ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference ImageReference { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ImageReference As ImageReference" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.ImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Bildverweis darstellen von Verleger, Angebot, SKU und Version des Image des virtuellen Computers ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As Region" />
      <MemberSignature Language="F#" Value="member this.Location : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Region, in die Virtual, die Machine-Image verfügbar ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offer">
      <MemberSignature Language="C#" Value="public string Offer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.Offer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Offer As String" />
      <MemberSignature Language="F#" Value="member this.Offer : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.Offer" />
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
            Ruft den Namen des virtuellen Computers Image Angebots, die in dieser Abbildung ist Teil des ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.OSDiskImage OSDiskImage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.OSDiskImage OSDiskImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.OSDiskImage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskImage As OSDiskImage" />
      <MemberSignature Language="F#" Value="member this.OSDiskImage : Microsoft.Azure.Management.Compute.Fluent.Models.OSDiskImage" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.OSDiskImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.OSDiskImage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Betriebssystem-Datenträger-Imagedatei in Image des virtuellen Computers ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Plan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.PurchasePlan Plan { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.PurchasePlan Plan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.Plan" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Plan As PurchasePlan" />
      <MemberSignature Language="F#" Value="member this.Plan : Microsoft.Azure.Management.Compute.Fluent.Models.PurchasePlan" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.Plan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.PurchasePlan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft des erwerbsplans für das Image des virtuellen Computers ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublisherName">
      <MemberSignature Language="C#" Value="public string PublisherName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublisherName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.PublisherName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublisherName As String" />
      <MemberSignature Language="F#" Value="member this.PublisherName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.PublisherName" />
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
            Ruft den Verlegernamen Image des virtuellen Computers ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public string Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As String" />
      <MemberSignature Language="F#" Value="member this.Sku : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.Sku" />
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
            Ruft den kommerziellen Namen Image des virtuellen Computers (SKU) ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage.Version" />
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
            Ruft die Version des Image des virtuellen Computers ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>