<Type Name="IotHubSkuDescription" FullName="Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription">
  <TypeSignature Language="C#" Value="public class IotHubSkuDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IotHubSkuDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class IotHubSkuDescription" />
  <TypeSignature Language="F#" Value="type IotHubSkuDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dd6e0-101">SKU-Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="dd6e0-101">SKU properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubSkuDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dd6e0-102">Initialisiert eine neue Instanz der IotHubSkuDescription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dd6e0-102">Initializes a new instance of the IotHubSkuDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubSkuDescription (Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo sku, Microsoft.Azure.Management.IotHub.Models.IotHubCapacity capacity, string resourceType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo sku, class Microsoft.Azure.Management.IotHub.Models.IotHubCapacity capacity, string resourceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription.#ctor(Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo,Microsoft.Azure.Management.IotHub.Models.IotHubCapacity,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sku As IotHubSkuInfo, capacity As IotHubCapacity, Optional resourceType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription : Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo * Microsoft.Azure.Management.IotHub.Models.IotHubCapacity * string -&gt; Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription" Usage="new Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription (sku, capacity, resourceType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sku" Type="Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo" />
        <Parameter Name="capacity" Type="Microsoft.Azure.Management.IotHub.Models.IotHubCapacity" />
        <Parameter Name="resourceType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sku">To be added.</param>
        <param name="capacity">To be added.</param>
        <param name="resourceType"><span data-ttu-id="dd6e0-103">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="dd6e0-103">The type of the resource.</span></span></param>
        <summary>
            <span data-ttu-id="dd6e0-104">Initialisiert eine neue Instanz der IotHubSkuDescription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dd6e0-104">Initializes a new instance of the IotHubSkuDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.IotHub.Models.IotHubCapacity Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.IotHub.Models.IotHubCapacity Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As IotHubCapacity" />
      <MemberSignature Language="F#" Value="member this.Capacity : Microsoft.Azure.Management.IotHub.Models.IotHubCapacity with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.IotHubCapacity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd6e0-105">Ruft den Typ der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="dd6e0-105">Gets the type of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As IotHubSkuInfo" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="iotHubSkuDescription.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dd6e0-106">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="dd6e0-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dd6e0-107">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="dd6e0-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>