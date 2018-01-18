<Type Name="VirtualMachineSize" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize">
  <TypeSignature Language="C#" Value="public class VirtualMachineSize" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineSize extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineSize" />
  <TypeSignature Language="F#" Value="type VirtualMachineSize = class" />
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
            <span data-ttu-id="e2c87-101">Beschreibt die Eigenschaften des VM-Größe.</span><span class="sxs-lookup"><span data-stu-id="e2c87-101">Describes the properties of a VM size.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineSize ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e2c87-102">Initialisiert eine neue Instanz der VirtualMachineSize-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e2c87-102">Initializes a new instance of the VirtualMachineSize class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineSize (string name = null, Nullable&lt;int&gt; numberOfCores = null, Nullable&lt;int&gt; osDiskSizeInMB = null, Nullable&lt;int&gt; resourceDiskSizeInMB = null, Nullable&lt;int&gt; memoryInMB = null, Nullable&lt;int&gt; maxDataDiskCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; numberOfCores, valuetype System.Nullable`1&lt;int32&gt; osDiskSizeInMB, valuetype System.Nullable`1&lt;int32&gt; resourceDiskSizeInMB, valuetype System.Nullable`1&lt;int32&gt; memoryInMB, valuetype System.Nullable`1&lt;int32&gt; maxDataDiskCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional numberOfCores As Nullable(Of Integer) = null, Optional osDiskSizeInMB As Nullable(Of Integer) = null, Optional resourceDiskSizeInMB As Nullable(Of Integer) = null, Optional memoryInMB As Nullable(Of Integer) = null, Optional maxDataDiskCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize (name, numberOfCores, osDiskSizeInMB, resourceDiskSizeInMB, memoryInMB, maxDataDiskCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="numberOfCores" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="osDiskSizeInMB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resourceDiskSizeInMB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="memoryInMB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxDataDiskCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="e2c87-103">Der Name der Größe des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="e2c87-103">The name of the virtual machine size.</span></span></param>
        <param name="numberOfCores"><span data-ttu-id="e2c87-104">Die Anzahl der Kerne, die von der Größe des virtuellen Computers unterstützt.</span><span class="sxs-lookup"><span data-stu-id="e2c87-104">The number of cores supported by the virtual machine size.</span></span></param>
        <param name="osDiskSizeInMB"><span data-ttu-id="e2c87-105">Das Betriebssystem auf den Datenträger Größe in MB, von der Größe des virtuellen Computers zulässig.</span><span class="sxs-lookup"><span data-stu-id="e2c87-105">The OS disk size, in MB, allowed by the virtual machine size.</span></span></param>
        <param name="resourceDiskSizeInMB"><span data-ttu-id="e2c87-106">Die Ressource Datenträgergröße in MB, von der Größe des virtuellen Computers zulässig.</span><span class="sxs-lookup"><span data-stu-id="e2c87-106">The resource disk size, in MB, allowed by the virtual machine size.</span></span></param>
        <param name="memoryInMB"><span data-ttu-id="e2c87-107">Die Menge des Arbeitsspeichers in MB, von der Größe des virtuellen Computers unterstützt wird.</span><span class="sxs-lookup"><span data-stu-id="e2c87-107">The amount of memory, in MB, supported by the virtual machine size.</span></span></param>
        <param name="maxDataDiskCount"><span data-ttu-id="e2c87-108">Die maximale Anzahl von Datenträgern, die Größe des virtuellen Computers angefügt werden können.</span><span class="sxs-lookup"><span data-stu-id="e2c87-108">The maximum number of data disks that can be attached to the virtual machine size.</span></span></param>
        <summary>
            <span data-ttu-id="e2c87-109">Initialisiert eine neue Instanz der VirtualMachineSize-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e2c87-109">Initializes a new instance of the VirtualMachineSize class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDataDiskCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDataDiskCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDataDiskCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize.MaxDataDiskCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDataDiskCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDataDiskCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize.MaxDataDiskCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxDataDiskCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2c87-110">Ruft ab oder legt die maximale Anzahl von Datenträgern, die Größe des virtuellen Computers angefügt werden können.</span><span class="sxs-lookup"><span data-stu-id="e2c87-110">Gets or sets the maximum number of data disks that can be attached to the virtual machine size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MemoryInMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MemoryInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MemoryInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize.MemoryInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property MemoryInMB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MemoryInMB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize.MemoryInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="memoryInMB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2c87-111">Ruft ab oder legt die Größe des Speichers in MB, von der Größe des virtuellen Computers unterstützt.</span><span class="sxs-lookup"><span data-stu-id="e2c87-111">Gets or sets the amount of memory, in MB, supported by the virtual machine size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2c87-112">Ruft ab oder legt den Namen der Größe des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="e2c87-112">Gets or sets the name of the virtual machine size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfCores">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfCores { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfCores" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize.NumberOfCores" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfCores As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfCores : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize.NumberOfCores" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numberOfCores")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2c87-113">Ruft ab oder legt die Anzahl der Kerne, die von der Größe des virtuellen Computers unterstützt.</span><span class="sxs-lookup"><span data-stu-id="e2c87-113">Gets or sets the number of cores supported by the virtual machine size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsDiskSizeInMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; OsDiskSizeInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; OsDiskSizeInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize.OsDiskSizeInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property OsDiskSizeInMB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.OsDiskSizeInMB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize.OsDiskSizeInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osDiskSizeInMB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2c87-114">Ruft ab oder legt die Datenträgergröße des Betriebssystems in MB, von der Größe des virtuellen Computers zulässig.</span><span class="sxs-lookup"><span data-stu-id="e2c87-114">Gets or sets the OS disk size, in MB, allowed by the virtual machine size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceDiskSizeInMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ResourceDiskSizeInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ResourceDiskSizeInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize.ResourceDiskSizeInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceDiskSizeInMB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ResourceDiskSizeInMB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize.ResourceDiskSizeInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceDiskSizeInMB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2c87-115">Ruft ab oder legt die Datenträgergröße Ressource in MB, von der Größe des virtuellen Computers zulässig.</span><span class="sxs-lookup"><span data-stu-id="e2c87-115">Gets or sets the resource disk size, in MB, allowed by the virtual machine size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>