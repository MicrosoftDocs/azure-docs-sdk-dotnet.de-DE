<Type Name="LinkedServicesOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LinkedServicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LinkedServicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LinkedServicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LinkedServicesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5f076-101">Erweiterungsmethoden für LinkedServicesOperations.</span><span class="sxs-lookup"><span data-stu-id="5f076-101">Extension methods for LinkedServicesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource CreateOrUpdate (this Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string resourceGroupName, string factoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource linkedService, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource CreateOrUpdate(class Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string resourceGroupName, string factoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource linkedService, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ILinkedServicesOperations, resourceGroupName As String, factoryName As String, linkedServiceName As String, linkedService As LinkedServiceResource, Optional ifMatch As String = null) As LinkedServiceResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource * string -&gt; Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource" Usage="Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, factoryName, linkedServiceName, linkedService, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="linkedService" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5f076-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5f076-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5f076-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5f076-103">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="5f076-104">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="5f076-104">The factory name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="5f076-105">Der Name des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="5f076-105">The linked service name.</span></span>
            </param>
        <param name="linkedService">
            <span data-ttu-id="5f076-106">Verknüpften Dienst der Ressourcendefinition.</span><span class="sxs-lookup"><span data-stu-id="5f076-106">Linked service resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="5f076-107">ETag der Entität LinkedService.</span><span class="sxs-lookup"><span data-stu-id="5f076-107">ETag of the linkedService entity.</span></span>  <span data-ttu-id="5f076-108">Sollte nur angegeben werden, für das Update, für die vorhandene Entität übereinstimmen oder können werden \* für unbedingtes Update.</span><span class="sxs-lookup"><span data-stu-id="5f076-108">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5f076-109">Erstellt oder aktualisiert einen verknüpften Dienst.</span><span class="sxs-lookup"><span data-stu-id="5f076-109">Creates or updates a linked service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string resourceGroupName, string factoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource linkedService, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string resourceGroupName, string factoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource linkedService, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, factoryName, linkedServiceName, linkedService, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="linkedService" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5f076-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5f076-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5f076-111">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5f076-111">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="5f076-112">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="5f076-112">The factory name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="5f076-113">Der Name des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="5f076-113">The linked service name.</span></span>
            </param>
        <param name="linkedService">
            <span data-ttu-id="5f076-114">Verknüpften Dienst der Ressourcendefinition.</span><span class="sxs-lookup"><span data-stu-id="5f076-114">Linked service resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="5f076-115">ETag der Entität LinkedService.</span><span class="sxs-lookup"><span data-stu-id="5f076-115">ETag of the linkedService entity.</span></span>  <span data-ttu-id="5f076-116">Sollte nur angegeben werden, für das Update, für die vorhandene Entität übereinstimmen oder können werden \* für unbedingtes Update.</span><span class="sxs-lookup"><span data-stu-id="5f076-116">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5f076-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5f076-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5f076-118">Erstellt oder aktualisiert einen verknüpften Dienst.</span><span class="sxs-lookup"><span data-stu-id="5f076-118">Creates or updates a linked service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string resourceGroupName, string factoryName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string resourceGroupName, string factoryName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ILinkedServicesOperations, resourceGroupName As String, factoryName As String, linkedServiceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.Delete (operations, resourceGroupName, factoryName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5f076-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5f076-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5f076-120">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5f076-120">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="5f076-121">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="5f076-121">The factory name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="5f076-122">Der Name des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="5f076-122">The linked service name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5f076-123">Löscht einen verknüpften Dienst an.</span><span class="sxs-lookup"><span data-stu-id="5f076-123">Deletes a linked service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string resourceGroupName, string factoryName, string linkedServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string resourceGroupName, string factoryName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.DeleteAsync (operations, resourceGroupName, factoryName, linkedServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5f076-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5f076-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5f076-125">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5f076-125">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="5f076-126">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="5f076-126">The factory name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="5f076-127">Der Name des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="5f076-127">The linked service name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5f076-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5f076-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5f076-129">Löscht einen verknüpften Dienst an.</span><span class="sxs-lookup"><span data-stu-id="5f076-129">Deletes a linked service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource Get (this Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string resourceGroupName, string factoryName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource Get(class Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string resourceGroupName, string factoryName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.Get(Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ILinkedServicesOperations, resourceGroupName As String, factoryName As String, linkedServiceName As String) As LinkedServiceResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource" Usage="Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.Get (operations, resourceGroupName, factoryName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5f076-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5f076-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5f076-131">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5f076-131">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="5f076-132">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="5f076-132">The factory name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="5f076-133">Der Name des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="5f076-133">The linked service name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5f076-134">Ruft einen verknüpften Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="5f076-134">Gets a linked service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt; GetAsync (this Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string resourceGroupName, string factoryName, string linkedServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt; GetAsync(class Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string resourceGroupName, string factoryName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.GetAsync (operations, resourceGroupName, factoryName, linkedServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5f076-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5f076-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5f076-136">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5f076-136">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="5f076-137">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="5f076-137">The factory name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="5f076-138">Der Name des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="5f076-138">The linked service name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5f076-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5f076-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5f076-140">Ruft einen verknüpften Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="5f076-140">Gets a linked service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactory">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt; ListByFactory (this Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string resourceGroupName, string factoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt; ListByFactory(class Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string resourceGroupName, string factoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.ListByFactory(Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactory (operations As ILinkedServicesOperations, resourceGroupName As String, factoryName As String) As IPage(Of LinkedServiceResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactory : Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.ListByFactory (operations, resourceGroupName, factoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5f076-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5f076-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5f076-142">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5f076-142">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="5f076-143">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="5f076-143">The factory name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5f076-144">Listen verknüpften Dienste.</span><span class="sxs-lookup"><span data-stu-id="5f076-144">Lists linked services.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt; ListByFactoryAsync (this Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string resourceGroupName, string factoryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt; ListByFactoryAsync(class Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string resourceGroupName, string factoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.ListByFactoryAsync(Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryAsync : Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.ListByFactoryAsync (operations, resourceGroupName, factoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions/&lt;ListByFactoryAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5f076-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5f076-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5f076-146">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5f076-146">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="5f076-147">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="5f076-147">The factory name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5f076-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5f076-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5f076-149">Listen verknüpften Dienste.</span><span class="sxs-lookup"><span data-stu-id="5f076-149">Lists linked services.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt; ListByFactoryNext (this Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt; ListByFactoryNext(class Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.ListByFactoryNext(Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactoryNext (operations As ILinkedServicesOperations, nextPageLink As String) As IPage(Of LinkedServiceResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNext : Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.ListByFactoryNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5f076-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5f076-150">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="5f076-151">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="5f076-151">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5f076-152">Listen verknüpften Dienste.</span><span class="sxs-lookup"><span data-stu-id="5f076-152">Lists linked services.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt; ListByFactoryNextAsync (this Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt; ListByFactoryNextAsync(class Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.ListByFactoryNextAsync(Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNextAsync : Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions.ListByFactoryNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.LinkedServicesOperationsExtensions/&lt;ListByFactoryNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5f076-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5f076-153">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="5f076-154">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="5f076-154">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5f076-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5f076-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5f076-156">Listen verknüpften Dienste.</span><span class="sxs-lookup"><span data-stu-id="5f076-156">Lists linked services.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>