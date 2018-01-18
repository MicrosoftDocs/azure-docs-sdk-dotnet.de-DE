<Type Name="AccessCondition" FullName="Microsoft.Azure.Search.Models.AccessCondition">
  <TypeSignature Language="C#" Value="public class AccessCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AccessCondition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.AccessCondition" />
  <TypeSignature Language="VB.NET" Value="Public Class AccessCondition" />
  <TypeSignature Language="F#" Value="type AccessCondition = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="68517-101">Zusätzliche Parameter für eine Reihe von Vorgängen.</span><span class="sxs-lookup"><span data-stu-id="68517-101">Additional parameters for a set of operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="68517-102">Initialisiert eine neue Instanz der Klasse AccessCondition an.</span><span class="sxs-lookup"><span data-stu-id="68517-102">Initializes a new instance of the AccessCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessCondition (string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional ifMatch As String = null, Optional ifNoneMatch As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.AccessCondition : string * string -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="new Microsoft.Azure.Search.Models.AccessCondition (ifMatch, ifNoneMatch)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ifMatch"><span data-ttu-id="68517-103">Definiert die If-Match-Bedingung an.</span><span class="sxs-lookup"><span data-stu-id="68517-103">Defines the If-Match condition.</span></span> <span data-ttu-id="68517-104">Der Vorgang wird ausgeführt werden, nur dann, wenn das ETag auf dem Server mit diesem Wert übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="68517-104">The operation will be performed only if the ETag on the server matches this value.</span></span></param>
        <param name="ifNoneMatch"><span data-ttu-id="68517-105">Definiert die If-None-Match-Bedingung an.</span><span class="sxs-lookup"><span data-stu-id="68517-105">Defines the If-None-Match condition.</span></span> <span data-ttu-id="68517-106">Der Vorgang wird ausgeführt werden, nur dann, wenn das ETag auf dem Server nicht mit diesem Wert übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="68517-106">The operation will be performed only if the ETag on the server does not match this value.</span></span></param>
        <summary>
            <span data-ttu-id="68517-107">Initialisiert eine neue Instanz der Klasse AccessCondition an.</span><span class="sxs-lookup"><span data-stu-id="68517-107">Initializes a new instance of the AccessCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateEmptyCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition GenerateEmptyCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition GenerateEmptyCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.GenerateEmptyCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateEmptyCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateEmptyCondition : unit -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.GenerateEmptyCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="68517-108">Erstellt eine leere zugriffsbedingung.</span><span class="sxs-lookup"><span data-stu-id="68517-108">Constructs an empty access condition.</span></span>
            </summary>
        <returns><span data-ttu-id="68517-109">Ein leeres <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="68517-109">An empty <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfExistsCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition GenerateIfExistsCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition GenerateIfExistsCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.GenerateIfExistsCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfExistsCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfExistsCondition : unit -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.GenerateIfExistsCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="68517-110">Erstellt eine zugriffsbedingung, sodass ein Vorgang ausgeführt wird, nur, wenn die Ressource vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="68517-110">Constructs an access condition such that an operation will be performed only if the resource exists.</span></span>
            </summary>
        <returns><span data-ttu-id="68517-111">Ein <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> Objekt, das eine Bedingung darstellt, in dem eine Ressource vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="68517-111">An <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> object that represents a condition where a resource exists.</span></span></returns>
        <remarks><span data-ttu-id="68517-112">Festlegen von dieser Bedingung für den Zugriff ändert die Anforderung der HTTP einschließen <i>If-Match</i> bedingten Header festgelegt <c>"\*"</c>.</span><span class="sxs-lookup"><span data-stu-id="68517-112">Setting this access condition modifies the request to include the HTTP <i>If-Match</i> conditional header set to <c>"\*"</c>.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfMatchCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition GenerateIfMatchCondition (string eTag);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition GenerateIfMatchCondition(string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.GenerateIfMatchCondition(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfMatchCondition (eTag As String) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfMatchCondition : string -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.GenerateIfMatchCondition eTag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eTag"><span data-ttu-id="68517-113">Der ETag-Wert, auf das ETag der Ressource geprüft werden soll.</span><span class="sxs-lookup"><span data-stu-id="68517-113">The ETag value to check against the resource's ETag.</span></span></param>
        <summary>
            <span data-ttu-id="68517-114">Erstellt eine zugriffsbedingung, sodass ein Vorgang ausgeführt wird, nur, wenn die Ressource aktuelle ETag-Wert den angegebenen ETag-Wert entspricht.</span><span class="sxs-lookup"><span data-stu-id="68517-114">Constructs an access condition such that an operation will be performed only if the resource's current ETag value matches the specified ETag value.</span></span>
            </summary>
        <returns><span data-ttu-id="68517-115">Ein <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> Objekt, das die If-Match-Bedingung darstellt.</span><span class="sxs-lookup"><span data-stu-id="68517-115">An <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> object that represents the If-Match condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfNoneMatchCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition GenerateIfNoneMatchCondition (string eTag);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition GenerateIfNoneMatchCondition(string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.GenerateIfNoneMatchCondition(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfNoneMatchCondition (eTag As String) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfNoneMatchCondition : string -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.GenerateIfNoneMatchCondition eTag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eTag"><span data-ttu-id="68517-116">Der ETag-Wert, auf das ETag der Ressource geprüft werden soll.</span><span class="sxs-lookup"><span data-stu-id="68517-116">The ETag value to check against the resource's ETag.</span></span></param>
        <summary>
            <span data-ttu-id="68517-117">Erstellt eine zugriffsbedingung, sodass ein Vorgang ausgeführt wird, nur wenn der aktuelle ETag-Wert der Ressource nicht mit den angegebenen ETag-Wert übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="68517-117">Constructs an access condition such that an operation will be performed only if the resource's current ETag value does not match the specified ETag value.</span></span>
            </summary>
        <returns><span data-ttu-id="68517-118">Ein <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> Objekt, das die If-None-Match-Bedingung darstellt.</span><span class="sxs-lookup"><span data-stu-id="68517-118">An <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> object that represents the If-None-Match condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfNotExistsCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition GenerateIfNotExistsCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition GenerateIfNotExistsCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.GenerateIfNotExistsCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfNotExistsCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfNotExistsCondition : unit -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.GenerateIfNotExistsCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="68517-119">Erstellt eine zugriffsbedingung, sodass ein Vorgang ausgeführt wird, nur, wenn die Ressource nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="68517-119">Constructs an access condition such that an operation will be performed only if the resource does not exist.</span></span>
            </summary>
        <returns><span data-ttu-id="68517-120">Ein <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> Objekt, das eine Bedingung darstellt, in dem eine Ressource ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="68517-120">An <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> object that represents a condition where a resource does not exist.</span></span></returns>
        <remarks><span data-ttu-id="68517-121">Festlegen von dieser Bedingung für den Zugriff ändert die Anforderung der HTTP einschließen <i>If-None-Match</i> bedingten Header festgelegt <c>"\*"</c>.</span><span class="sxs-lookup"><span data-stu-id="68517-121">Setting this access condition modifies the request to include the HTTP <i>If-None-Match</i> conditional header set to <c>"\*"</c>.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="IfMatch">
      <MemberSignature Language="C#" Value="public string IfMatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IfMatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AccessCondition.IfMatch" />
      <MemberSignature Language="VB.NET" Value="Public Property IfMatch As String" />
      <MemberSignature Language="F#" Value="member this.IfMatch : string with get, set" Usage="Microsoft.Azure.Search.Models.AccessCondition.IfMatch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68517-122">If-Match-Bedingung definiert, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="68517-122">Gets or sets defines the If-Match condition.</span></span> <span data-ttu-id="68517-123">Der Vorgang wird ausgeführt werden, nur dann, wenn das ETag auf dem Server mit diesem Wert übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="68517-123">The operation will be performed only if the ETag on the server matches this value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfNoneMatch">
      <MemberSignature Language="C#" Value="public string IfNoneMatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IfNoneMatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AccessCondition.IfNoneMatch" />
      <MemberSignature Language="VB.NET" Value="Public Property IfNoneMatch As String" />
      <MemberSignature Language="F#" Value="member this.IfNoneMatch : string with get, set" Usage="Microsoft.Azure.Search.Models.AccessCondition.IfNoneMatch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68517-124">If-None-Match-Bedingung definiert, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="68517-124">Gets or sets defines the If-None-Match condition.</span></span> <span data-ttu-id="68517-125">Der Vorgang wird ausgeführt werden, nur dann, wenn das ETag auf dem Server nicht mit diesem Wert übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="68517-125">The operation will be performed only if the ETag on the server does not match this value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfNotChanged">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition IfNotChanged (Microsoft.Azure.Search.Models.IResourceWithETag resource);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition IfNotChanged(class Microsoft.Azure.Search.Models.IResourceWithETag resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.IfNotChanged(Microsoft.Azure.Search.Models.IResourceWithETag)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IfNotChanged (resource As IResourceWithETag) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member IfNotChanged : Microsoft.Azure.Search.Models.IResourceWithETag -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.IfNotChanged resource" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="Microsoft.Azure.Search.Models.IResourceWithETag" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="68517-126">Eine Ressource mit einem ETag-Wert, auf das ETag der Ressource geprüft werden soll.</span><span class="sxs-lookup"><span data-stu-id="68517-126">A resource with an ETag value to check against the resource's ETag.</span></span></param>
        <summary>
            <span data-ttu-id="68517-127">Erstellt eine zugriffsbedingung, sodass ein Vorgang ausgeführt wird, nur, wenn die Ressource aktuelle ETag-Wert der angegebenen Ressource ETag-Wert übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="68517-127">Constructs an access condition such that an operation will be performed only if the resource's current ETag value matches the specified resource's ETag value.</span></span>
            </summary>
        <returns><span data-ttu-id="68517-128">Ein <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> Objekt, das die If-Match-Bedingung darstellt.</span><span class="sxs-lookup"><span data-stu-id="68517-128">An <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> object that represents the If-Match condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>