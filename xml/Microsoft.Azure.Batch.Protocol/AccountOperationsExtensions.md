<Type Name="AccountOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.AccountOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AccountOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AccountOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.AccountOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AccountOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AccountOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fa3cd-101">Erweiterungsmethoden für AccountOperations.</span><span class="sxs-lookup"><span data-stu-id="fa3cd-101">Extension methods for AccountOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListNodeAgentSkus">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt; ListNodeAgentSkus (this Microsoft.Azure.Batch.Protocol.IAccountOperations operations, Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions accountListNodeAgentSkusOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt; ListNodeAgentSkus(class Microsoft.Azure.Batch.Protocol.IAccountOperations operations, class Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions accountListNodeAgentSkusOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.AccountOperationsExtensions.ListNodeAgentSkus(Microsoft.Azure.Batch.Protocol.IAccountOperations,Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions)" />
      <MemberSignature Language="F#" Value="static member ListNodeAgentSkus : Microsoft.Azure.Batch.Protocol.IAccountOperations * Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;" Usage="Microsoft.Azure.Batch.Protocol.AccountOperationsExtensions.ListNodeAgentSkus (operations, accountListNodeAgentSkusOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IAccountOperations" RefType="this" />
        <Parameter Name="accountListNodeAgentSkusOptions" Type="Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa3cd-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fa3cd-102">The operations group for this extension method.</span></span>
            </param>
        <param name="accountListNodeAgentSkusOptions">
            <span data-ttu-id="fa3cd-103">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="fa3cd-103">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa3cd-104">Listet alle Knoten-Agent-SKUs von der Azure Batch-Dienst unterstützt.</span><span class="sxs-lookup"><span data-stu-id="fa3cd-104">Lists all node agent SKUs supported by the Azure Batch service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeAgentSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;&gt; ListNodeAgentSkusAsync (this Microsoft.Azure.Batch.Protocol.IAccountOperations operations, Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions accountListNodeAgentSkusOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;&gt; ListNodeAgentSkusAsync(class Microsoft.Azure.Batch.Protocol.IAccountOperations operations, class Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions accountListNodeAgentSkusOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.AccountOperationsExtensions.ListNodeAgentSkusAsync(Microsoft.Azure.Batch.Protocol.IAccountOperations,Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNodeAgentSkusAsync : Microsoft.Azure.Batch.Protocol.IAccountOperations * Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.AccountOperationsExtensions.ListNodeAgentSkusAsync (operations, accountListNodeAgentSkusOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.AccountOperationsExtensions/&lt;ListNodeAgentSkusAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IAccountOperations" RefType="this" />
        <Parameter Name="accountListNodeAgentSkusOptions" Type="Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa3cd-105">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fa3cd-105">The operations group for this extension method.</span></span>
            </param>
        <param name="accountListNodeAgentSkusOptions">
            <span data-ttu-id="fa3cd-106">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="fa3cd-106">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fa3cd-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fa3cd-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa3cd-108">Listet alle Knoten-Agent-SKUs von der Azure Batch-Dienst unterstützt.</span><span class="sxs-lookup"><span data-stu-id="fa3cd-108">Lists all node agent SKUs supported by the Azure Batch service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeAgentSkusNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt; ListNodeAgentSkusNext (this Microsoft.Azure.Batch.Protocol.IAccountOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions accountListNodeAgentSkusNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt; ListNodeAgentSkusNext(class Microsoft.Azure.Batch.Protocol.IAccountOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions accountListNodeAgentSkusNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.AccountOperationsExtensions.ListNodeAgentSkusNext(Microsoft.Azure.Batch.Protocol.IAccountOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNodeAgentSkusNext : Microsoft.Azure.Batch.Protocol.IAccountOperations * string * Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;" Usage="Microsoft.Azure.Batch.Protocol.AccountOperationsExtensions.ListNodeAgentSkusNext (operations, nextPageLink, accountListNodeAgentSkusNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="accountListNodeAgentSkusNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa3cd-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fa3cd-109">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="fa3cd-110">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fa3cd-110">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="accountListNodeAgentSkusNextOptions">
            <span data-ttu-id="fa3cd-111">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="fa3cd-111">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa3cd-112">Listet alle Knoten-Agent-SKUs von der Azure Batch-Dienst unterstützt.</span><span class="sxs-lookup"><span data-stu-id="fa3cd-112">Lists all node agent SKUs supported by the Azure Batch service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeAgentSkusNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;&gt; ListNodeAgentSkusNextAsync (this Microsoft.Azure.Batch.Protocol.IAccountOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions accountListNodeAgentSkusNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;&gt; ListNodeAgentSkusNextAsync(class Microsoft.Azure.Batch.Protocol.IAccountOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions accountListNodeAgentSkusNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.AccountOperationsExtensions.ListNodeAgentSkusNextAsync(Microsoft.Azure.Batch.Protocol.IAccountOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNodeAgentSkusNextAsync : Microsoft.Azure.Batch.Protocol.IAccountOperations * string * Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.AccountOperationsExtensions.ListNodeAgentSkusNextAsync (operations, nextPageLink, accountListNodeAgentSkusNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.AccountOperationsExtensions/&lt;ListNodeAgentSkusNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="accountListNodeAgentSkusNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa3cd-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fa3cd-113">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="fa3cd-114">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fa3cd-114">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="accountListNodeAgentSkusNextOptions">
            <span data-ttu-id="fa3cd-115">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="fa3cd-115">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fa3cd-116">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fa3cd-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa3cd-117">Listet alle Knoten-Agent-SKUs von der Azure Batch-Dienst unterstützt.</span><span class="sxs-lookup"><span data-stu-id="fa3cd-117">Lists all node agent SKUs supported by the Azure Batch service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>