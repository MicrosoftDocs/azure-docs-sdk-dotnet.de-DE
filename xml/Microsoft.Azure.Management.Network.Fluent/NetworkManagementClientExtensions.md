<Type Name="NetworkManagementClientExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClientExtensions">
  <TypeSignature Language="C#" Value="public static class NetworkManagementClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NetworkManagementClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NetworkManagementClientExtensions" />
  <TypeSignature Language="F#" Value="type NetworkManagementClientExtensions = class" />
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
            <span data-ttu-id="28c4a-101">Erweiterungsmethoden für NetworkManagementClient.</span><span class="sxs-lookup"><span data-stu-id="28c4a-101">Extension methods for NetworkManagementClient.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckDnsNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.DnsNameAvailabilityResultInner&gt; CheckDnsNameAvailabilityAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient operations, string location, string domainNameLabel = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.DnsNameAvailabilityResultInner&gt; CheckDnsNameAvailabilityAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient operations, string location, string domainNameLabel, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkManagementClientExtensions.CheckDnsNameAvailabilityAsync(Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckDnsNameAvailabilityAsync : Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.DnsNameAvailabilityResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManagementClientExtensions.CheckDnsNameAvailabilityAsync (operations, location, domainNameLabel, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkManagementClientExtensions/&lt;CheckDnsNameAvailabilityAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.DnsNameAvailabilityResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="domainNameLabel" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="28c4a-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="28c4a-102">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="28c4a-103">Der Speicherort des Domänennamens.</span><span class="sxs-lookup"><span data-stu-id="28c4a-103">The location of the domain name.</span></span>
            </param>
        <param name="domainNameLabel">
            <span data-ttu-id="28c4a-104">Der Domänenname überprüft werden.</span><span class="sxs-lookup"><span data-stu-id="28c4a-104">The domain name to be verified.</span></span> <span data-ttu-id="28c4a-105">Er muss dem folgenden regulären Ausdruck entsprechen: ^ [a-z][a-z0-9-]{1,61}[a-z0-9]$.</span><span class="sxs-lookup"><span data-stu-id="28c4a-105">It must conform to the following regular expression: ^[a-z][a-z0-9-]{1,61}[a-z0-9]$.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28c4a-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="28c4a-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28c4a-107">Überprüft, ob ein Domänenname in der Zone cloudapp.net für die Verwendung verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="28c4a-107">Checks whether a domain name in the cloudapp.net zone is available for use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>