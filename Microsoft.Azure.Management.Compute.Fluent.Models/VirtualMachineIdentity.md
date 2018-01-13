<Type Name="VirtualMachineIdentity" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineIdentity">
  <TypeSignature Language="C#" Value="public class VirtualMachineIdentity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineIdentity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineIdentity" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineIdentity" />
  <TypeSignature Language="F#" Value="type VirtualMachineIdentity = class" />
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
            <span data-ttu-id="be438-101">Die Identität für den virtuellen Computer.</span><span class="sxs-lookup"><span data-stu-id="be438-101">Identity for the virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineIdentity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineIdentity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="be438-102">Initialisiert eine neue Instanz der VirtualMachineIdentity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="be438-102">Initializes a new instance of the VirtualMachineIdentity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineIdentity (string principalId = null, string tenantId = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType&gt; type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string principalId, string tenantId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType&gt; type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineIdentity.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional principalId As String = null, Optional tenantId As String = null, Optional type As Nullable(Of ResourceIdentityType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineIdentity : string * string * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineIdentity" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineIdentity (principalId, tenantId, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="principalId" Type="System.String" />
        <Parameter Name="tenantId" Type="System.String" />
        <Parameter Name="type" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType&gt;" />
      </Parameters>
      <Docs>
        <param name="principalId"><span data-ttu-id="be438-103">Der Prinzipal-Id der Identität der virtuellen Maschine.</span><span class="sxs-lookup"><span data-stu-id="be438-103">The principal id of virtual machine identity.</span></span></param>
        <param name="tenantId"><span data-ttu-id="be438-104">Die Mandanten-Id der virtuellen Maschine zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="be438-104">The tenant id associated with the virtual machine.</span></span></param>
        <param name="type"><span data-ttu-id="be438-105">Der Typ der Identität für den virtuellen Computer verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="be438-105">The type of identity used for the virtual machine.</span></span> <span data-ttu-id="be438-106">Derzeit ist der einzige unterstützte Typ "SystemAssigned", die eine Identität implizit erstellt.</span><span class="sxs-lookup"><span data-stu-id="be438-106">Currently, the only supported type is 'SystemAssigned', which implicitly creates an identity.</span></span> <span data-ttu-id="be438-107">Folgende Werte sind möglich: "SystemAssigned"</span><span class="sxs-lookup"><span data-stu-id="be438-107">Possible values include: 'SystemAssigned'</span></span></param>
        <summary>
            <span data-ttu-id="be438-108">Initialisiert eine neue Instanz der VirtualMachineIdentity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="be438-108">Initializes a new instance of the VirtualMachineIdentity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrincipalId">
      <MemberSignature Language="C#" Value="public string PrincipalId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineIdentity.PrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrincipalId As String" />
      <MemberSignature Language="F#" Value="member this.PrincipalId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineIdentity.PrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="be438-109">Ruft die Prinzipal-Id der Identität der virtuellen Maschine an.</span><span class="sxs-lookup"><span data-stu-id="be438-109">Gets the principal id of virtual machine identity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineIdentity.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineIdentity.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="be438-110">Ruft die Mandanten-Id der virtuellen Maschine zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="be438-110">Gets the tenant id associated with the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType&gt; Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType&gt; Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineIdentity.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As Nullable(Of ResourceIdentityType)" />
      <MemberSignature Language="F#" Value="member this.Type : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineIdentity.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be438-111">Ruft ab oder legt den Typ der Identität für den virtuellen Computer verwendet.</span><span class="sxs-lookup"><span data-stu-id="be438-111">Gets or sets the type of identity used for the virtual machine.</span></span>
            <span data-ttu-id="be438-112">Derzeit ist der einzige unterstützte Typ "SystemAssigned", die eine Identität implizit erstellt.</span><span class="sxs-lookup"><span data-stu-id="be438-112">Currently, the only supported type is 'SystemAssigned', which implicitly creates an identity.</span></span> <span data-ttu-id="be438-113">Folgende Werte sind möglich: "SystemAssigned"</span><span class="sxs-lookup"><span data-stu-id="be438-113">Possible values include: 'SystemAssigned'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>