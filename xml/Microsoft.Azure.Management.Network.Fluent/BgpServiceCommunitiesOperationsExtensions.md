<Type Name="BgpServiceCommunitiesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.BgpServiceCommunitiesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BgpServiceCommunitiesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BgpServiceCommunitiesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.BgpServiceCommunitiesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BgpServiceCommunitiesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BgpServiceCommunitiesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6b62e-101">Erweiterungsmethoden für BgpServiceCommunitiesOperations.</span><span class="sxs-lookup"><span data-stu-id="6b62e-101">Extension methods for BgpServiceCommunitiesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpServiceCommunityInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.BgpServiceCommunityInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.BgpServiceCommunitiesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpServiceCommunityInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.BgpServiceCommunitiesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.BgpServiceCommunitiesOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpServiceCommunityInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6b62e-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6b62e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b62e-103">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6b62e-103">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b62e-104">Ruft alle verfügbaren Bgp-Service-Communitys ab.</span><span class="sxs-lookup"><span data-stu-id="6b62e-104">Gets all the available bgp service communities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpServiceCommunityInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.BgpServiceCommunityInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.BgpServiceCommunitiesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpServiceCommunityInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.BgpServiceCommunitiesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.BgpServiceCommunitiesOperationsExtensions/&lt;ListNextAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpServiceCommunityInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6b62e-105">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6b62e-105">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6b62e-106">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="6b62e-106">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b62e-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6b62e-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b62e-108">Ruft alle verfügbaren Bgp-Service-Communitys ab.</span><span class="sxs-lookup"><span data-stu-id="6b62e-108">Gets all the available bgp service communities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>