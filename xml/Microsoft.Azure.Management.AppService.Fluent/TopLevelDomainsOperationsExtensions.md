<Type Name="TopLevelDomainsOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TopLevelDomainsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TopLevelDomainsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TopLevelDomainsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TopLevelDomainsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="df4c2-101">Erweiterungsmethoden für TopLevelDomainsOperations.</span><span class="sxs-lookup"><span data-stu-id="df4c2-101">Extension methods for TopLevelDomainsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt; GetAsync (this Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt; GetAsync(class Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.GetAsync(Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.GetAsync (operations, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="df4c2-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="df4c2-102">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="df4c2-103">Name der Domäne der obersten Ebene.</span><span class="sxs-lookup"><span data-stu-id="df4c2-103">Name of the top-level domain.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df4c2-104">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df4c2-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df4c2-105">Ruft Details zu einer Domäne auf oberster Ebene an.</span><span class="sxs-lookup"><span data-stu-id="df4c2-105">Get details of a top-level domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="df4c2-106">Ruft Details zu einer Domäne auf oberster Ebene an.</span><span class="sxs-lookup"><span data-stu-id="df4c2-106">Get details of a top-level domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAgreementsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt; ListAgreementsAsync (this Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string name, Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainAgreementOptionInner agreementOption, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt; ListAgreementsAsync(class Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainAgreementOptionInner agreementOption, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAgreementsAsync(Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainAgreementOptionInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAgreementsAsync : Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations * string * Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainAgreementOptionInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAgreementsAsync (operations, name, agreementOption, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions/&lt;ListAgreementsAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="agreementOption" Type="Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainAgreementOptionInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="name">To be added.</param>
        <param name="agreementOption">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAgreementsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt; ListAgreementsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt; ListAgreementsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAgreementsNextAsync(Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAgreementsNextAsync : Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAgreementsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions/&lt;ListAgreementsNextAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="df4c2-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="df4c2-107">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="df4c2-108">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="df4c2-108">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df4c2-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df4c2-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df4c2-110">Ruft alle Verträge, die Benutzer muss vor dem Kauf von einer Domänenkontos akzeptieren.</span><span class="sxs-lookup"><span data-stu-id="df4c2-110">Gets all legal agreements that user needs to accept before purchasing a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="df4c2-111">Ruft alle Verträge, die Benutzer muss vor dem Kauf von einer Domänenkontos akzeptieren.</span><span class="sxs-lookup"><span data-stu-id="df4c2-111">Gets all legal agreements that user needs to accept before purchasing a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="df4c2-112">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="df4c2-112">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df4c2-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df4c2-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df4c2-114">Rufen Sie alle Domänen auf oberster Ebene für die Registrierung unterstützt.</span><span class="sxs-lookup"><span data-stu-id="df4c2-114">Get all top-level domains supported for registration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="df4c2-115">Rufen Sie alle Domänen auf oberster Ebene für die Registrierung unterstützt.</span><span class="sxs-lookup"><span data-stu-id="df4c2-115">Get all top-level domains supported for registration.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="df4c2-116">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="df4c2-116">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="df4c2-117">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="df4c2-117">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df4c2-118">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df4c2-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df4c2-119">Rufen Sie alle Domänen auf oberster Ebene für die Registrierung unterstützt.</span><span class="sxs-lookup"><span data-stu-id="df4c2-119">Get all top-level domains supported for registration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="df4c2-120">Rufen Sie alle Domänen auf oberster Ebene für die Registrierung unterstützt.</span><span class="sxs-lookup"><span data-stu-id="df4c2-120">Get all top-level domains supported for registration.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>