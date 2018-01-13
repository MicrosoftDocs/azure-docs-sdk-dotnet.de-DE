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
            Erweiterungsmethoden für NetworkManagementClient.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="location">
            Der Speicherort des Domänennamens.
            </param>
        <param name="domainNameLabel">
            Der Domänenname überprüft werden. Er muss dem folgenden regulären Ausdruck entsprechen: ^ [a-z][a-z0-9-]{1,61}[a-z0-9]$.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft, ob ein Domänenname in der Zone cloudapp.net für die Verwendung verfügbar ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>