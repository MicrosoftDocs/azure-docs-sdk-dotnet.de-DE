<Type Name="OriginsOperationsExtensions" FullName="Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class OriginsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit OriginsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module OriginsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type OriginsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2be5a-101">Erweiterungsmethoden für OriginsOperations.</span><span class="sxs-lookup"><span data-stu-id="2be5a-101">Extension methods for OriginsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string resourceGroupName, string profileName, string endpointName, string originName, Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner originUpdateProperties, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string resourceGroupName, string profileName, string endpointName, string originName, class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner originUpdateProperties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations * string * string * string * string * Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, profileName, endpointName, originName, originUpdateProperties, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="originName" Type="System.String" />
        <Parameter Name="originUpdateProperties" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2be5a-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2be5a-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2be5a-103">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2be5a-103">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="2be5a-104">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="2be5a-104">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="2be5a-105">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="2be5a-105">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="originName">
            <span data-ttu-id="2be5a-106">Der Name des Ursprungs der innerhalb der Endpunkt eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="2be5a-106">Name of the origin which is unique within the endpoint.</span></span>
            </param>
        <param name="originUpdateProperties">
            <span data-ttu-id="2be5a-107">Ursprungseigenschaften</span><span class="sxs-lookup"><span data-stu-id="2be5a-107">Origin properties</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2be5a-108">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2be5a-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2be5a-109">Aktualisiert einen vorhandenen Ursprung innerhalb eines Endpunkts an.</span><span class="sxs-lookup"><span data-stu-id="2be5a-109">Updates an existing origin within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt; GetAsync (this Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string resourceGroupName, string profileName, string endpointName, string originName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt; GetAsync(class Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string resourceGroupName, string profileName, string endpointName, string originName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, endpointName, originName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="originName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2be5a-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2be5a-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2be5a-111">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2be5a-111">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="2be5a-112">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="2be5a-112">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="2be5a-113">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="2be5a-113">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="originName">
            <span data-ttu-id="2be5a-114">Der Name des Ursprungs der innerhalb der Endpunkt eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="2be5a-114">Name of the origin which is unique within the endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2be5a-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2be5a-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2be5a-116">Ruft einen vorhandenen Ursprung innerhalb eines Endpunkts ab.</span><span class="sxs-lookup"><span data-stu-id="2be5a-116">Gets an existing origin within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt; ListByEndpointAsync (this Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt; ListByEndpointAsync(class Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.ListByEndpointAsync(Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByEndpointAsync : Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.ListByEndpointAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions/&lt;ListByEndpointAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2be5a-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2be5a-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2be5a-118">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2be5a-118">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="2be5a-119">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="2be5a-119">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="2be5a-120">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="2be5a-120">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2be5a-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2be5a-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2be5a-122">Zeigt eine Liste aller die vorhandenen Ursprünge in einem Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="2be5a-122">Lists all of the existing origins within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt; ListByEndpointNextAsync (this Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt; ListByEndpointNextAsync(class Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.ListByEndpointNextAsync(Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByEndpointNextAsync : Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.ListByEndpointNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions/&lt;ListByEndpointNextAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2be5a-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2be5a-123">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2be5a-124">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2be5a-124">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2be5a-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2be5a-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2be5a-126">Zeigt eine Liste aller die vorhandenen Ursprünge in einem Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="2be5a-126">Lists all of the existing origins within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt; UpdateAsync (this Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string resourceGroupName, string profileName, string endpointName, string originName, Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner originUpdateProperties, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt; UpdateAsync(class Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string resourceGroupName, string profileName, string endpointName, string originName, class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner originUpdateProperties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations * string * string * string * string * Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.UpdateAsync (operations, resourceGroupName, profileName, endpointName, originName, originUpdateProperties, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions/&lt;UpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="originName" Type="System.String" />
        <Parameter Name="originUpdateProperties" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2be5a-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2be5a-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2be5a-128">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2be5a-128">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="2be5a-129">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="2be5a-129">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="2be5a-130">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="2be5a-130">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="originName">
            <span data-ttu-id="2be5a-131">Der Name des Ursprungs der innerhalb der Endpunkt eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="2be5a-131">Name of the origin which is unique within the endpoint.</span></span>
            </param>
        <param name="originUpdateProperties">
            <span data-ttu-id="2be5a-132">Ursprungseigenschaften</span><span class="sxs-lookup"><span data-stu-id="2be5a-132">Origin properties</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2be5a-133">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2be5a-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2be5a-134">Aktualisiert einen vorhandenen Ursprung innerhalb eines Endpunkts an.</span><span class="sxs-lookup"><span data-stu-id="2be5a-134">Updates an existing origin within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>