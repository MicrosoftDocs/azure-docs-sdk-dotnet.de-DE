<Type Name="PolicyDefinitionsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PolicyDefinitionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PolicyDefinitionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PolicyDefinitionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PolicyDefinitionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b78cc-101">Erweiterungsmethoden für PolicyDefinitionsOperations.</span><span class="sxs-lookup"><span data-stu-id="b78cc-101">Extension methods for PolicyDefinitionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition CreateOrUpdate (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition CreateOrUpdate(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IPolicyDefinitionsOperations, policyDefinitionName As String, parameters As PolicyDefinition) As PolicyDefinition" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.CreateOrUpdate (operations, policyDefinitionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="policyDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b78cc-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b78cc-102">The operations group for this extension method.</span></span>
            </param>
        <param name="policyDefinitionName">
            <span data-ttu-id="b78cc-103">Der Name der Richtliniendefinition zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="b78cc-103">The name of the policy definition to create.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b78cc-104">Die Eigenschaften der Richtliniendefinition.</span><span class="sxs-lookup"><span data-stu-id="b78cc-104">The policy definition properties.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b78cc-105">Erstellt oder aktualisiert eine Richtliniendefinition.</span><span class="sxs-lookup"><span data-stu-id="b78cc-105">Creates or updates a policy definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.CreateOrUpdateAsync (operations, policyDefinitionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="policyDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b78cc-106">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b78cc-106">The operations group for this extension method.</span></span>
            </param>
        <param name="policyDefinitionName">
            <span data-ttu-id="b78cc-107">Der Name der Richtliniendefinition zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="b78cc-107">The name of the policy definition to create.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b78cc-108">Die Eigenschaften der Richtliniendefinition.</span><span class="sxs-lookup"><span data-stu-id="b78cc-108">The policy definition properties.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b78cc-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b78cc-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b78cc-110">Erstellt oder aktualisiert eine Richtliniendefinition.</span><span class="sxs-lookup"><span data-stu-id="b78cc-110">Creates or updates a policy definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.Delete(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IPolicyDefinitionsOperations, policyDefinitionName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.Delete (operations, policyDefinitionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="policyDefinitionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b78cc-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b78cc-111">The operations group for this extension method.</span></span>
            </param>
        <param name="policyDefinitionName">
            <span data-ttu-id="b78cc-112">Der Name der Richtliniendefinition zu löschen.</span><span class="sxs-lookup"><span data-stu-id="b78cc-112">The name of the policy definition to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b78cc-113">Löscht eine Richtliniendefinition an.</span><span class="sxs-lookup"><span data-stu-id="b78cc-113">Deletes a policy definition.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.DeleteAsync (operations, policyDefinitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="policyDefinitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b78cc-114">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b78cc-114">The operations group for this extension method.</span></span>
            </param>
        <param name="policyDefinitionName">
            <span data-ttu-id="b78cc-115">Der Name der Richtliniendefinition zu löschen.</span><span class="sxs-lookup"><span data-stu-id="b78cc-115">The name of the policy definition to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b78cc-116">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b78cc-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b78cc-117">Löscht eine Richtliniendefinition an.</span><span class="sxs-lookup"><span data-stu-id="b78cc-117">Deletes a policy definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition Get (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition Get(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPolicyDefinitionsOperations, policyDefinitionName As String) As PolicyDefinition" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.Get (operations, policyDefinitionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="policyDefinitionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b78cc-118">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b78cc-118">The operations group for this extension method.</span></span>
            </param>
        <param name="policyDefinitionName">
            <span data-ttu-id="b78cc-119">Der Name der Richtliniendefinition abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="b78cc-119">The name of the policy definition to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b78cc-120">Ruft die Richtliniendefinition ab.</span><span class="sxs-lookup"><span data-stu-id="b78cc-120">Gets the policy definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.GetAsync (operations, policyDefinitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="policyDefinitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b78cc-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b78cc-121">The operations group for this extension method.</span></span>
            </param>
        <param name="policyDefinitionName">
            <span data-ttu-id="b78cc-122">Der Name der Richtliniendefinition abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="b78cc-122">The name of the policy definition to get.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b78cc-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b78cc-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b78cc-124">Ruft die Richtliniendefinition ab.</span><span class="sxs-lookup"><span data-stu-id="b78cc-124">Gets the policy definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; List (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; List(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IPolicyDefinitionsOperations, Optional odataQuery As ODataQuery(Of PolicyDefinition) = null) As IPage(Of PolicyDefinition)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.List (operations, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b78cc-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b78cc-125">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="b78cc-126">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="b78cc-126">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b78cc-127">Ruft den Richtliniendefinitionen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="b78cc-127">Gets all the policy definitions for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b78cc-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b78cc-128">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="b78cc-129">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="b78cc-129">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b78cc-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b78cc-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b78cc-131">Ruft den Richtliniendefinitionen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="b78cc-131">Gets all the policy definitions for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IPolicyDefinitionsOperations, nextPageLink As String) As IPage(Of PolicyDefinition)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b78cc-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b78cc-132">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b78cc-133">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b78cc-133">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b78cc-134">Ruft den Richtliniendefinitionen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="b78cc-134">Gets all the policy definitions for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions/&lt;ListNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b78cc-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b78cc-135">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b78cc-136">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b78cc-136">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b78cc-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b78cc-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b78cc-138">Ruft den Richtliniendefinitionen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="b78cc-138">Gets all the policy definitions for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>