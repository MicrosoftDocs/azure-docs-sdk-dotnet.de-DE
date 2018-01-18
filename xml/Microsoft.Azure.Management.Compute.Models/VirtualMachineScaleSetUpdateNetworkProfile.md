<Type Name="VirtualMachineScaleSetUpdateNetworkProfile" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkProfile">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetUpdateNetworkProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetUpdateNetworkProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetUpdateNetworkProfile" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetUpdateNetworkProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="68289-101">Beschreibt ein Netzwerkprofil zu VM Scale Set an.</span><span class="sxs-lookup"><span data-stu-id="68289-101">Describes a virtual machine scale set network profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetUpdateNetworkProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="68289-102">Initialisiert eine neue Instanz der VirtualMachineScaleSetUpdateNetworkProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="68289-102">Initializes a new instance of the VirtualMachineScaleSetUpdateNetworkProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetUpdateNetworkProfile (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration&gt; networkInterfaceConfigurations = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration&gt; networkInterfaceConfigurations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkProfile.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional networkInterfaceConfigurations As IList(Of VirtualMachineScaleSetUpdateNetworkConfiguration) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkProfile : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkProfile" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkProfile networkInterfaceConfigurations" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="networkInterfaceConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration&gt;" />
      </Parameters>
      <Docs>
        <param name="networkInterfaceConfigurations"><span data-ttu-id="68289-103">Die Liste der Netzwerkkonfigurationen.</span><span class="sxs-lookup"><span data-stu-id="68289-103">The list of network configurations.</span></span></param>
        <summary>
            <span data-ttu-id="68289-104">Initialisiert eine neue Instanz der VirtualMachineScaleSetUpdateNetworkProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="68289-104">Initializes a new instance of the VirtualMachineScaleSetUpdateNetworkProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaceConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration&gt; NetworkInterfaceConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration&gt; NetworkInterfaceConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkProfile.NetworkInterfaceConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkInterfaceConfigurations As IList(Of VirtualMachineScaleSetUpdateNetworkConfiguration)" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkProfile.NetworkInterfaceConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkInterfaceConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68289-105">Ruft ab oder legt die Liste der Netzwerkkonfigurationen.</span><span class="sxs-lookup"><span data-stu-id="68289-105">Gets or sets the list of network configurations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>