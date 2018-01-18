<Type Name="Sku" FullName="Microsoft.Azure.Management.Redis.Fluent.Models.Sku">
  <TypeSignature Language="C#" Value="public class Sku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Sku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.Models.Sku" />
  <TypeSignature Language="VB.NET" Value="Public Class Sku" />
  <TypeSignature Language="F#" Value="type Sku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="eec98-101">So erstellen Sie Redis-Vorgang angegebenen SKU-Parameter.</span><span class="sxs-lookup"><span data-stu-id="eec98-101">SKU parameters supplied to the create Redis operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.Sku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="eec98-102">Initialisiert eine neue Instanz der Sku-Klasse.</span><span class="sxs-lookup"><span data-stu-id="eec98-102">Initializes a new instance of the Sku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku (string name, string family, int capacity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string family, int32 capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.Sku.#ctor(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, family As String, capacity As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Fluent.Models.Sku : string * string * int -&gt; Microsoft.Azure.Management.Redis.Fluent.Models.Sku" Usage="new Microsoft.Azure.Management.Redis.Fluent.Models.Sku (name, family, capacity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="family" Type="System.String" />
        <Parameter Name="capacity" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="eec98-103">Der Typ des Redis-Cache bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="eec98-103">The type of Redis cache to deploy.</span></span> <span data-ttu-id="eec98-104">Gültige Werte: (Basic, Standard, Premium).</span><span class="sxs-lookup"><span data-stu-id="eec98-104">Valid values: (Basic, Standard, Premium).</span></span> <span data-ttu-id="eec98-105">Folgende Werte sind möglich: "Basic", "Standard", "Premium"</span><span class="sxs-lookup"><span data-stu-id="eec98-105">Possible values include: 'Basic', 'Standard', 'Premium'</span></span></param>
        <param name="family"><span data-ttu-id="eec98-106">Die SKU-Familie verwenden.</span><span class="sxs-lookup"><span data-stu-id="eec98-106">The SKU family to use.</span></span> <span data-ttu-id="eec98-107">Gültige Werte: (C, P).</span><span class="sxs-lookup"><span data-stu-id="eec98-107">Valid values: (C, P).</span></span>
            <span data-ttu-id="eec98-108">(C = Basic-/Standard, P = Premium).</span><span class="sxs-lookup"><span data-stu-id="eec98-108">(C = Basic/Standard, P = Premium).</span></span> <span data-ttu-id="eec98-109">Folgende Werte sind möglich: "C", "P"</span><span class="sxs-lookup"><span data-stu-id="eec98-109">Possible values include: 'C', 'P'</span></span></param>
        <param name="capacity"><span data-ttu-id="eec98-110">Die Größe des Redis-Caches bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="eec98-110">The size of the Redis cache to deploy.</span></span> <span data-ttu-id="eec98-111">Gültige Werte: für C (Basic-/Standard) der Produktfamilie (0, 1, 2, 3, 4, 5, 6), P (Premium) Familie (1, 2, 3, 4).</span><span class="sxs-lookup"><span data-stu-id="eec98-111">Valid values: for C (Basic/Standard) family (0, 1, 2, 3, 4, 5, 6), for P (Premium) family (1, 2, 3, 4).</span></span></param>
        <summary>
            <span data-ttu-id="eec98-112">Initialisiert eine neue Instanz der Sku-Klasse.</span><span class="sxs-lookup"><span data-stu-id="eec98-112">Initializes a new instance of the Sku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public int Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.Sku.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As Integer" />
      <MemberSignature Language="F#" Value="member this.Capacity : int with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.Sku.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eec98-113">Ruft ab oder legt die Größe des Redis-Cache bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="eec98-113">Gets or sets the size of the Redis cache to deploy.</span></span> <span data-ttu-id="eec98-114">Gültige Werte: für C (Basic-/Standard) der Produktfamilie (0, 1, 2, 3, 4, 5, 6), P (Premium) Familie (1, 2, 3, 4).</span><span class="sxs-lookup"><span data-stu-id="eec98-114">Valid values: for C (Basic/Standard) family (0, 1, 2, 3, 4, 5, 6), for P (Premium) family (1, 2, 3, 4).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Family">
      <MemberSignature Language="C#" Value="public string Family { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Family" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.Sku.Family" />
      <MemberSignature Language="VB.NET" Value="Public Property Family As String" />
      <MemberSignature Language="F#" Value="member this.Family : string with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.Sku.Family" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="family")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eec98-115">Abrufen oder festlegen die SKU-Familie verwenden.</span><span class="sxs-lookup"><span data-stu-id="eec98-115">Gets or sets the SKU family to use.</span></span> <span data-ttu-id="eec98-116">Gültige Werte: (C, P).</span><span class="sxs-lookup"><span data-stu-id="eec98-116">Valid values: (C, P).</span></span> <span data-ttu-id="eec98-117">(C = Basic-/Standard, P = Premium).</span><span class="sxs-lookup"><span data-stu-id="eec98-117">(C = Basic/Standard, P = Premium).</span></span> <span data-ttu-id="eec98-118">Folgende Werte sind möglich: "C", "P"</span><span class="sxs-lookup"><span data-stu-id="eec98-118">Possible values include: 'C', 'P'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.Sku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.Sku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
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
            <span data-ttu-id="eec98-119">Ruft ab oder legt den Typ des Redis-Caches bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="eec98-119">Gets or sets the type of Redis cache to deploy.</span></span> <span data-ttu-id="eec98-120">Gültige Werte: (Basic, Standard, Premium).</span><span class="sxs-lookup"><span data-stu-id="eec98-120">Valid values: (Basic, Standard, Premium).</span></span> <span data-ttu-id="eec98-121">Folgende Werte sind möglich: "Basic", "Standard", "Premium"</span><span class="sxs-lookup"><span data-stu-id="eec98-121">Possible values include: 'Basic', 'Standard', 'Premium'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.Sku.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sku.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="eec98-122">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="eec98-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="eec98-123">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="eec98-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>