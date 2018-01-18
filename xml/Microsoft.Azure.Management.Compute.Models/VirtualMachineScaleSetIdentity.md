<Type Name="VirtualMachineScaleSetIdentity" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetIdentity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetIdentity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetIdentity" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetIdentity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8324b-101">Die Identität für die VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="8324b-101">Identity for the virtual machine scale set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetIdentity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8324b-102">Initialisiert eine neue Instanz der VirtualMachineScaleSetIdentity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8324b-102">Initializes a new instance of the VirtualMachineScaleSetIdentity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetIdentity (string principalId = null, string tenantId = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string principalId, string tenantId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Models.ResourceIdentityType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional principalId As String = null, Optional tenantId As String = null, Optional type As Nullable(Of ResourceIdentityType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity : string * string * Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity (principalId, tenantId, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="principalId" Type="System.String" />
        <Parameter Name="tenantId" Type="System.String" />
        <Parameter Name="type" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt;" />
      </Parameters>
      <Docs>
        <param name="principalId"><span data-ttu-id="8324b-103">Der Datenbankprinzipal-Id des VM-Skalierungsgruppe festlegen Identität.</span><span class="sxs-lookup"><span data-stu-id="8324b-103">The principal id of virtual machine scale set identity.</span></span></param>
        <param name="tenantId"><span data-ttu-id="8324b-104">Legen Sie die Mandanten-Id, die der VM-Skalierungsgruppe zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="8324b-104">The tenant id associated with the virtual machine scale set.</span></span></param>
        <param name="type"><span data-ttu-id="8324b-105">Der Typ der Identität, die für die VM-Skalierungsgruppe verwendet gesetzt.</span><span class="sxs-lookup"><span data-stu-id="8324b-105">The type of identity used for the virtual machine scale set.</span></span> <span data-ttu-id="8324b-106">Derzeit ist der einzige unterstützte Typ "SystemAssigned", die eine Identität implizit erstellt.</span><span class="sxs-lookup"><span data-stu-id="8324b-106">Currently, the only supported type is 'SystemAssigned', which implicitly creates an identity.</span></span> <span data-ttu-id="8324b-107">Folgende Werte sind möglich: "SystemAssigned"</span><span class="sxs-lookup"><span data-stu-id="8324b-107">Possible values include: 'SystemAssigned'</span></span></param>
        <summary>
            <span data-ttu-id="8324b-108">Initialisiert eine neue Instanz der VirtualMachineScaleSetIdentity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8324b-108">Initializes a new instance of the VirtualMachineScaleSetIdentity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrincipalId">
      <MemberSignature Language="C#" Value="public string PrincipalId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity.PrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrincipalId As String" />
      <MemberSignature Language="F#" Value="member this.PrincipalId : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity.PrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="principalId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8324b-109">Ruft die Prinzipal-Id der VM-Skalierungsgruppe festgelegten Identität.</span><span class="sxs-lookup"><span data-stu-id="8324b-109">Gets the principal id of virtual machine scale set identity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8324b-110">Ruft die Mandanten-Id, die der VM-Skalierungsgruppe zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="8324b-110">Gets the tenant id associated with the virtual machine scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As Nullable(Of ResourceIdentityType)" />
      <MemberSignature Language="F#" Value="member this.Type : Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8324b-111">Ruft ab oder legt den Typ der Identität, die für die VM-Skalierungsgruppe verwendet.</span><span class="sxs-lookup"><span data-stu-id="8324b-111">Gets or sets the type of identity used for the virtual machine scale set.</span></span> <span data-ttu-id="8324b-112">Derzeit ist der einzige unterstützte Typ "SystemAssigned", die eine Identität implizit erstellt.</span><span class="sxs-lookup"><span data-stu-id="8324b-112">Currently, the only supported type is 'SystemAssigned', which implicitly creates an identity.</span></span> <span data-ttu-id="8324b-113">Folgende Werte sind möglich: "SystemAssigned"</span><span class="sxs-lookup"><span data-stu-id="8324b-113">Possible values include: 'SystemAssigned'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>