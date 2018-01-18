<Type Name="VirtualMachineScaleSetManagedDiskParameters" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetManagedDiskParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetManagedDiskParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetManagedDiskParameters" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetManagedDiskParameters = class" />
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
            <span data-ttu-id="a97d8-101">Beschreibt die Parameter eines verwalteten ScaleSet-Datenträgers.</span><span class="sxs-lookup"><span data-stu-id="a97d8-101">Describes the parameters of a ScaleSet managed disk.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetManagedDiskParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters.#ctor" />
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
            <span data-ttu-id="a97d8-102">Initialisiert eine neue Instanz der VirtualMachineScaleSetManagedDiskParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a97d8-102">Initializes a new instance of the VirtualMachineScaleSetManagedDiskParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetManagedDiskParameters (Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; storageAccountType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Models.StorageAccountTypes})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional storageAccountType As Nullable(Of StorageAccountTypes) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters : Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters storageAccountType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccountType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt;" />
      </Parameters>
      <Docs>
        <param name="storageAccountType"><span data-ttu-id="a97d8-103">Gibt den Typ des Speicher-Konto für den verwalteten Datenträger.</span><span class="sxs-lookup"><span data-stu-id="a97d8-103">Specifies the storage account type for the managed disk.</span></span> <span data-ttu-id="a97d8-104">Mögliche Werte sind: Standard_LRS oder "premium_lrs".</span><span class="sxs-lookup"><span data-stu-id="a97d8-104">Possible values are: Standard_LRS or Premium_LRS.</span></span> <span data-ttu-id="a97d8-105">Folgende Werte sind möglich: "Standard_LRS", "premium_lrs" ""</span><span class="sxs-lookup"><span data-stu-id="a97d8-105">Possible values include: 'Standard_LRS', 'Premium_LRS'</span></span></param>
        <summary>
            <span data-ttu-id="a97d8-106">Initialisiert eine neue Instanz der VirtualMachineScaleSetManagedDiskParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a97d8-106">Initializes a new instance of the VirtualMachineScaleSetManagedDiskParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; StorageAccountType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountType As Nullable(Of StorageAccountTypes)" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a97d8-107">Ruft ab oder legt gibt der speicherkontotyp für den verwalteten Datenträger an.</span><span class="sxs-lookup"><span data-stu-id="a97d8-107">Gets or sets specifies the storage account type for the managed disk.</span></span> <span data-ttu-id="a97d8-108">Mögliche Werte sind: Standard_LRS oder "premium_lrs".</span><span class="sxs-lookup"><span data-stu-id="a97d8-108">Possible values are: Standard_LRS or Premium_LRS.</span></span> <span data-ttu-id="a97d8-109">Folgende Werte sind möglich: "Standard_LRS", "premium_lrs" ""</span><span class="sxs-lookup"><span data-stu-id="a97d8-109">Possible values include: 'Standard_LRS', 'Premium_LRS'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>