<Type Name="ResourceRequirements" FullName="Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements">
  <TypeSignature Language="C#" Value="public class ResourceRequirements" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceRequirements extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceRequirements" />
  <TypeSignature Language="F#" Value="type ResourceRequirements = class" />
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
            <span data-ttu-id="1b16d-101">Die ressourcenanforderungen.</span><span class="sxs-lookup"><span data-stu-id="1b16d-101">The resource requirements.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceRequirements ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1b16d-102">Initialisiert eine neue Instanz der ResourceRequirements-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1b16d-102">Initializes a new instance of the ResourceRequirements class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceRequirements (Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests requests, Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits limits = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests requests, class Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits limits) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements.#ctor(Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests,Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (requests As ResourceRequests, Optional limits As ResourceLimits = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements : Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests * Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits -&gt; Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements" Usage="new Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements (requests, limits)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="requests" Type="Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests" />
        <Parameter Name="limits" Type="Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits" />
      </Parameters>
      <Docs>
        <param name="requests"><span data-ttu-id="1b16d-103">Die Ressource Anforderungen dieser Container-Instanz.</span><span class="sxs-lookup"><span data-stu-id="1b16d-103">The resource requests of this container instance.</span></span></param>
        <param name="limits"><span data-ttu-id="1b16d-104">Die Ressourcengrenzwerte dieser Container-Instanz.</span><span class="sxs-lookup"><span data-stu-id="1b16d-104">The resource limits of this container instance.</span></span></param>
        <summary>
            <span data-ttu-id="1b16d-105">Initialisiert eine neue Instanz der ResourceRequirements-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1b16d-105">Initializes a new instance of the ResourceRequirements class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limits">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits Limits { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits Limits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements.Limits" />
      <MemberSignature Language="VB.NET" Value="Public Property Limits As ResourceLimits" />
      <MemberSignature Language="F#" Value="member this.Limits : Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements.Limits" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="limits")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b16d-106">Ruft ab oder legt die Ressourcengrenzwerte dieser Container-Instanz.</span><span class="sxs-lookup"><span data-stu-id="1b16d-106">Gets or sets the resource limits of this container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Requests">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests Requests { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests Requests" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements.Requests" />
      <MemberSignature Language="VB.NET" Value="Public Property Requests As ResourceRequests" />
      <MemberSignature Language="F#" Value="member this.Requests : Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements.Requests" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="requests")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequests</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b16d-107">Abrufen oder Festlegen der Ressource Anforderungen dieser Container-Instanz.</span><span class="sxs-lookup"><span data-stu-id="1b16d-107">Gets or sets the resource requests of this container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceRequirements.Validate " />
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
            <span data-ttu-id="1b16d-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="1b16d-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1b16d-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="1b16d-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>