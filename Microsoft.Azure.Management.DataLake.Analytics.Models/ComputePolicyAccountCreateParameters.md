<Type Name="ComputePolicyAccountCreateParameters" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters">
  <TypeSignature Language="C#" Value="public class ComputePolicyAccountCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputePolicyAccountCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputePolicyAccountCreateParameters" />
  <TypeSignature Language="F#" Value="type ComputePolicyAccountCreateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="cbb8f-101">Die Parameter zum Erstellen einer neuen Compute-Richtlinie verwendet.</span><span class="sxs-lookup"><span data-stu-id="cbb8f-101">The parameters used to create a new compute policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputePolicyAccountCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cbb8f-102">Initialisiert eine neue Instanz der ComputePolicyAccountCreateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cbb8f-102">Initializes a new instance of the ComputePolicyAccountCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputePolicyAccountCreateParameters (string name, Guid objectId, string objectType, Nullable&lt;int&gt; maxDegreeOfParallelismPerJob = null, Nullable&lt;int&gt; minPriorityPerJob = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Guid objectId, string objectType, valuetype System.Nullable`1&lt;int32&gt; maxDegreeOfParallelismPerJob, valuetype System.Nullable`1&lt;int32&gt; minPriorityPerJob) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters.#ctor(System.String,System.Guid,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, objectId As Guid, objectType As String, Optional maxDegreeOfParallelismPerJob As Nullable(Of Integer) = null, Optional minPriorityPerJob As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters : string * Guid * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters (name, objectId, objectType, maxDegreeOfParallelismPerJob, minPriorityPerJob)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="objectId" Type="System.Guid" />
        <Parameter Name="objectType" Type="System.String" />
        <Parameter Name="maxDegreeOfParallelismPerJob" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="minPriorityPerJob" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="cbb8f-103">Der eindeutige Name der Richtlinie zu erstellen</span><span class="sxs-lookup"><span data-stu-id="cbb8f-103">The unique name of the policy to create</span></span></param>
        <param name="objectId"><span data-ttu-id="cbb8f-104">Die AAD-Objekt-ID für die Entität, die eine Richtlinie erstellen.</span><span class="sxs-lookup"><span data-stu-id="cbb8f-104">The AAD object identifier for the entity to create a policy for.</span></span></param>
        <param name="objectType"><span data-ttu-id="cbb8f-105">Der Typ des Objekts für AAD bezieht sich die Objekt-ID auf.</span><span class="sxs-lookup"><span data-stu-id="cbb8f-105">The type of AAD object the object identifier refers to.</span></span> <span data-ttu-id="cbb8f-106">Folgende Werte sind möglich: "User", "Group", "ServicePrincipal"</span><span class="sxs-lookup"><span data-stu-id="cbb8f-106">Possible values include: 'User', 'Group', 'ServicePrincipal'</span></span></param>
        <param name="maxDegreeOfParallelismPerJob"><span data-ttu-id="cbb8f-107">Diese Benutzer können den maximalen Grad an Parallelität pro Auftrag Übermitteln von Aufträgen.</span><span class="sxs-lookup"><span data-stu-id="cbb8f-107">The maximum degree of parallelism per job this user can use to submit jobs.</span></span> <span data-ttu-id="cbb8f-108">Diese Eigenschaft muss die Priorität Min. pro Auftrag-Eigenschaft oder sowohl übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="cbb8f-108">This property, the min priority per job property, or both must be passed.</span></span></param>
        <param name="minPriorityPerJob"><span data-ttu-id="cbb8f-109">Der minimalen Priorität pro Auftrag kann dieser Benutzer zum Übermitteln von Aufträgen verwenden.</span><span class="sxs-lookup"><span data-stu-id="cbb8f-109">The minimum priority per job this user can use to submit jobs.</span></span> <span data-ttu-id="cbb8f-110">Diese Eigenschaft muss der Max. Grad an Parallelität pro Auftrag-Eigenschaft oder sowohl übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="cbb8f-110">This property, the max degree of parallelism per job property, or both must be passed.</span></span></param>
        <summary>
            <span data-ttu-id="cbb8f-111">Initialisiert eine neue Instanz der ComputePolicyAccountCreateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cbb8f-111">Initializes a new instance of the ComputePolicyAccountCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDegreeOfParallelismPerJob">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDegreeOfParallelismPerJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDegreeOfParallelismPerJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters.MaxDegreeOfParallelismPerJob" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDegreeOfParallelismPerJob As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDegreeOfParallelismPerJob : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters.MaxDegreeOfParallelismPerJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxDegreeOfParallelismPerJob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cbb8f-112">Ruft ab oder legt den maximalen Grad an Parallelität pro Auftrag, den dieser Benutzer zum Übermitteln von Aufträgen verwenden kann.</span><span class="sxs-lookup"><span data-stu-id="cbb8f-112">Gets or sets the maximum degree of parallelism per job this user can use to submit jobs.</span></span> <span data-ttu-id="cbb8f-113">Diese Eigenschaft muss die Priorität Min. pro Auftrag-Eigenschaft oder sowohl übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="cbb8f-113">This property, the min priority per job property, or both must be passed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinPriorityPerJob">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinPriorityPerJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinPriorityPerJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters.MinPriorityPerJob" />
      <MemberSignature Language="VB.NET" Value="Public Property MinPriorityPerJob As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinPriorityPerJob : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters.MinPriorityPerJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.minPriorityPerJob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cbb8f-114">Abrufen oder festlegen die minimale Priorität pro Auftrag, den dieser Benutzer zum Übermitteln von Aufträgen verwenden kann.</span><span class="sxs-lookup"><span data-stu-id="cbb8f-114">Gets or sets the minimum priority per job this user can use to submit jobs.</span></span> <span data-ttu-id="cbb8f-115">Diese Eigenschaft muss der Max. Grad an Parallelität pro Auftrag-Eigenschaft oder sowohl übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="cbb8f-115">This property, the max degree of parallelism per job property, or both must be passed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="cbb8f-116">Ruft ab oder legt den eindeutigen Namen der Richtlinie zu erstellen</span><span class="sxs-lookup"><span data-stu-id="cbb8f-116">Gets or sets the unique name of the policy to create</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectId">
      <MemberSignature Language="C#" Value="public Guid ObjectId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid ObjectId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters.ObjectId" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectId As Guid" />
      <MemberSignature Language="F#" Value="member this.ObjectId : Guid with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters.ObjectId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.objectId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cbb8f-117">Abrufen oder Festlegen der AAD-Objekt-ID für die Entität, die eine Richtlinie erstellen.</span><span class="sxs-lookup"><span data-stu-id="cbb8f-117">Gets or sets the AAD object identifier for the entity to create a policy for.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectType">
      <MemberSignature Language="C#" Value="public string ObjectType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ObjectType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters.ObjectType" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectType As String" />
      <MemberSignature Language="F#" Value="member this.ObjectType : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters.ObjectType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.objectType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cbb8f-118">Ruft ab oder legt den Typ des AAD-Objekts, auf die die Objekt-ID verweist.</span><span class="sxs-lookup"><span data-stu-id="cbb8f-118">Gets or sets the type of AAD object the object identifier refers to.</span></span> <span data-ttu-id="cbb8f-119">Folgende Werte sind möglich: "User", "Group", "ServicePrincipal"</span><span class="sxs-lookup"><span data-stu-id="cbb8f-119">Possible values include: 'User', 'Group', 'ServicePrincipal'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="computePolicyAccountCreateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cbb8f-120">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="cbb8f-120">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cbb8f-121">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="cbb8f-121">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>