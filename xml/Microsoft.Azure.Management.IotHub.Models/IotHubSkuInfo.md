<Type Name="IotHubSkuInfo" FullName="Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo">
  <TypeSignature Language="C#" Value="public class IotHubSkuInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IotHubSkuInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class IotHubSkuInfo" />
  <TypeSignature Language="F#" Value="type IotHubSkuInfo = class" />
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
            <span data-ttu-id="dd05b-101">Informationen über die SKU von IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="dd05b-101">Information about the SKU of the IoT hub.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubSkuInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dd05b-102">Initialisiert eine neue Instanz der IotHubSkuInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dd05b-102">Initializes a new instance of the IotHubSkuInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubSkuInfo (string name, long capacity, Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuTier&gt; tier = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, int64 capacity, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.IotHub.Models.IotHubSkuTier&gt; tier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo.#ctor(System.String,System.Int64,System.Nullable{Microsoft.Azure.Management.IotHub.Models.IotHubSkuTier})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, capacity As Long, Optional tier As Nullable(Of IotHubSkuTier) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo : string * int64 * Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuTier&gt; -&gt; Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo" Usage="new Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo (name, capacity, tier)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="capacity" Type="System.Int64" />
        <Parameter Name="tier" Type="System.Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuTier&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="dd05b-103">Der Name der SKU.</span><span class="sxs-lookup"><span data-stu-id="dd05b-103">The name of the SKU.</span></span> <span data-ttu-id="dd05b-104">Folgende Werte sind möglich: "F1", "S1", "S2", "S3"</span><span class="sxs-lookup"><span data-stu-id="dd05b-104">Possible values include: 'F1', 'S1', 'S2', 'S3'</span></span></param>
        <param name="capacity"><span data-ttu-id="dd05b-105">Die Anzahl der bereitgestellten IoT Hub-Einheiten.</span><span class="sxs-lookup"><span data-stu-id="dd05b-105">The number of provisioned IoT Hub units.</span></span>
            <span data-ttu-id="dd05b-106">Finden Sie unter: https://docs.microsoft.com/azure/azure-subscription-service-limits#iot-hub-limits.</span><span class="sxs-lookup"><span data-stu-id="dd05b-106">See: https://docs.microsoft.com/azure/azure-subscription-service-limits#iot-hub-limits.</span></span></param>
        <param name="tier"><span data-ttu-id="dd05b-107">Die abrechnungsebene für den IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="dd05b-107">The billing tier for the IoT hub.</span></span> <span data-ttu-id="dd05b-108">Folgende Werte sind möglich: "Free", "Standard"</span><span class="sxs-lookup"><span data-stu-id="dd05b-108">Possible values include: 'Free', 'Standard'</span></span></param>
        <summary>
            <span data-ttu-id="dd05b-109">Initialisiert eine neue Instanz der IotHubSkuInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dd05b-109">Initializes a new instance of the IotHubSkuInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public long Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As Long" />
      <MemberSignature Language="F#" Value="member this.Capacity : int64 with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo.Capacity" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd05b-110">Ruft ab oder legt die Anzahl der bereitgestellten IoT Hub-Einheiten.</span><span class="sxs-lookup"><span data-stu-id="dd05b-110">Gets or sets the number of provisioned IoT Hub units.</span></span> <span data-ttu-id="dd05b-111">Finden Sie unter: https://docs.microsoft.com/azure/azure-subscription-service-limits#iot-hub-limits.</span><span class="sxs-lookup"><span data-stu-id="dd05b-111">See: https://docs.microsoft.com/azure/azure-subscription-service-limits#iot-hub-limits.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="dd05b-112">Ruft ab oder legt den Namen der SKU.</span><span class="sxs-lookup"><span data-stu-id="dd05b-112">Gets or sets the name of the SKU.</span></span> <span data-ttu-id="dd05b-113">Folgende Werte sind möglich: "F1", "S1", "S2", "S3"</span><span class="sxs-lookup"><span data-stu-id="dd05b-113">Possible values include: 'F1', 'S1', 'S2', 'S3'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuTier&gt; Tier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.IotHub.Models.IotHubSkuTier&gt; Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo.Tier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tier As Nullable(Of IotHubSkuTier)" />
      <MemberSignature Language="F#" Value="member this.Tier : Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuTier&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd05b-114">Ruft die abrechnungsebene für IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="dd05b-114">Gets the billing tier for the IoT hub.</span></span> <span data-ttu-id="dd05b-115">Folgende Werte sind möglich: "Free", "Standard"</span><span class="sxs-lookup"><span data-stu-id="dd05b-115">Possible values include: 'Free', 'Standard'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubSkuInfo.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="iotHubSkuInfo.Validate " />
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
            <span data-ttu-id="dd05b-116">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="dd05b-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dd05b-117">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="dd05b-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>