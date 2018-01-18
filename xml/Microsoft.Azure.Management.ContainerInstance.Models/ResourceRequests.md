<Type Name="ResourceRequests" FullName="Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests">
  <TypeSignature Language="C#" Value="public class ResourceRequests" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceRequests extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceRequests" />
  <TypeSignature Language="F#" Value="type ResourceRequests = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="12bc1-101">Die Ressource-Anforderungen.</span><span class="sxs-lookup"><span data-stu-id="12bc1-101">The resource requests.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceRequests ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="12bc1-102">Initialisiert eine neue Instanz der ResourceRequests-Klasse.</span><span class="sxs-lookup"><span data-stu-id="12bc1-102">Initializes a new instance of the ResourceRequests class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceRequests (double memoryInGB, double cpu);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(float64 memoryInGB, float64 cpu) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests.#ctor(System.Double,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (memoryInGB As Double, cpu As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests : double * double -&gt; Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests" Usage="new Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests (memoryInGB, cpu)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="memoryInGB" Type="System.Double" />
        <Parameter Name="cpu" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="memoryInGB"><span data-ttu-id="12bc1-103">Die arbeitsspeicheranforderung der dieser Containerinstanz.</span><span class="sxs-lookup"><span data-stu-id="12bc1-103">The memory request in GB of this container instance.</span></span></param>
        <param name="cpu"><span data-ttu-id="12bc1-104">Die CPU-Anforderung dieser Container-Instanz.</span><span class="sxs-lookup"><span data-stu-id="12bc1-104">The CPU request of this container instance.</span></span></param>
        <summary>
            <span data-ttu-id="12bc1-105">Initialisiert eine neue Instanz der ResourceRequests-Klasse.</span><span class="sxs-lookup"><span data-stu-id="12bc1-105">Initializes a new instance of the ResourceRequests class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cpu">
      <MemberSignature Language="C#" Value="public double Cpu { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Cpu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests.Cpu" />
      <MemberSignature Language="VB.NET" Value="Public Property Cpu As Double" />
      <MemberSignature Language="F#" Value="member this.Cpu : double with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests.Cpu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cpu")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="12bc1-106">Ruft ab oder legt die CPU-Anforderung dieser Container-Instanz.</span><span class="sxs-lookup"><span data-stu-id="12bc1-106">Gets or sets the CPU request of this container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MemoryInGB">
      <MemberSignature Language="C#" Value="public double MemoryInGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 MemoryInGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests.MemoryInGB" />
      <MemberSignature Language="VB.NET" Value="Public Property MemoryInGB As Double" />
      <MemberSignature Language="F#" Value="member this.MemoryInGB : double with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests.MemoryInGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="memoryInGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="12bc1-107">Ruft ab oder legt die arbeitsspeicheranforderung der dieser Containerinstanz.</span><span class="sxs-lookup"><span data-stu-id="12bc1-107">Gets or sets the memory request in GB of this container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceRequests.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="12bc1-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="12bc1-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="12bc1-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="12bc1-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>