<Type Name="VirtualMachineScaleSetExtensionProfile" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtensionProfile">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetExtensionProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetExtensionProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtensionProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetExtensionProfile" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetExtensionProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f9d78-101">Beschreibt eine virtuelle Maschine Skalierung festgelegte Erweiterung Profil an.</span><span class="sxs-lookup"><span data-stu-id="f9d78-101">Describes a virtual machine scale set extension profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetExtensionProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtensionProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f9d78-102">Initialisiert eine neue Instanz der VirtualMachineScaleSetExtensionProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f9d78-102">Initializes a new instance of the VirtualMachineScaleSetExtensionProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetExtensionProfile (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension&gt; extensions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension&gt; extensions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtensionProfile.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional extensions As IList(Of VirtualMachineScaleSetExtension) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtensionProfile : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtensionProfile" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtensionProfile extensions" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="extensions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension&gt;" />
      </Parameters>
      <Docs>
        <param name="extensions"><span data-ttu-id="f9d78-103">Die VM-Skalierungsgruppe untergeordneten Erweiterung Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="f9d78-103">The virtual machine scale set child extension resources.</span></span></param>
        <summary>
            <span data-ttu-id="f9d78-104">Initialisiert eine neue Instanz der VirtualMachineScaleSetExtensionProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f9d78-104">Initializes a new instance of the VirtualMachineScaleSetExtensionProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Extensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension&gt; Extensions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension&gt; Extensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtensionProfile.Extensions" />
      <MemberSignature Language="VB.NET" Value="Public Property Extensions As IList(Of VirtualMachineScaleSetExtension)" />
      <MemberSignature Language="F#" Value="member this.Extensions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtensionProfile.Extensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extensions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9d78-105">Abrufen oder Festlegen der VM-Skalierungsgruppe Satz untergeordneten Erweiterung Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="f9d78-105">Gets or sets the virtual machine scale set child extension resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>