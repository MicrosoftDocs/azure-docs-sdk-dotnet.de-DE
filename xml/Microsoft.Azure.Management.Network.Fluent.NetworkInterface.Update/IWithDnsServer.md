<Type Name="IWithDnsServer" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithDnsServer">
  <TypeSignature Language="C#" Value="public interface IWithDnsServer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDnsServer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithDnsServer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDnsServer" />
  <TypeSignature Language="F#" Value="type IWithDnsServer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="aee50-101">Die Phase der Network Interface Update ermöglichen DNS-Server angeben.</span><span class="sxs-lookup"><span data-stu-id="aee50-101">The stage of the network interface update allowing to specify DNS servers.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAzureDnsServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithAzureDnsServer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithAzureDnsServer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithDnsServer.WithAzureDnsServer" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAzureDnsServer () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithAzureDnsServer : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithDnsServer.WithAzureDnsServer " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="aee50-102">Gibt an, dass die Azure-DNS-Standardserver für die Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="aee50-102">Specifies to use the default Azure DNS server for the network interface.</span></span>
            <span data-ttu-id="aee50-103">Mithilfe von Azure-DNS-wird Server diese Netzwerkschnittstelle zugeordneten benutzerdefinierten DNS-Servern entfernt.</span><span class="sxs-lookup"><span data-stu-id="aee50-103">Using azure DNS server will remove any custom DNS server associated with this network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="aee50-104">Die nächste Phase des Netzwerk-Schnittstelle Updates.</span><span class="sxs-lookup"><span data-stu-id="aee50-104">The next stage of the network interface update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithDnsServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithDnsServer (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithDnsServer(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithDnsServer.WithDnsServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDnsServer (ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDnsServer : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithDnsServer.WithDnsServer ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="aee50-105">Die IP-Adresse des DNS-Servers.</span><span class="sxs-lookup"><span data-stu-id="aee50-105">The IP address of the DNS server.</span></span></param>
        <summary>
            <span data-ttu-id="aee50-106">Gibt die IP-Adresse der benutzerdefinierten DNS-Server, die Netzwerkschnittstelle zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="aee50-106">Specifies the IP address of the custom DNS server to associate with the network interface.</span></span>
            <span data-ttu-id="aee50-107">Beachten Sie, diese Methode Effekt ist kumulativ, d. h. jedes Mal, die es verwendet wird, der neuen DNS-Server hinzugefügt an die Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="aee50-107">Note this method's effect is additive, i.e. each time it is used, the new dns server is added to the network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="aee50-108">Die nächste Phase des Netzwerk-Schnittstelle Updates.</span><span class="sxs-lookup"><span data-stu-id="aee50-108">The next stage of the network interface update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutDnsServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithoutDnsServer (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithoutDnsServer(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithDnsServer.WithoutDnsServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutDnsServer (ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutDnsServer : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithDnsServer.WithoutDnsServer ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="aee50-109">Die IP-Adresse des DNS-Servers.</span><span class="sxs-lookup"><span data-stu-id="aee50-109">The IP address of the DNS server.</span></span></param>
        <summary>
            <span data-ttu-id="aee50-110">Entfernt einen DNS-Server der Netzwerkschnittstelle zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="aee50-110">Removes a DNS server associated with the network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="aee50-111">Die nächste Phase des Netzwerk-Schnittstelle Updates.</span><span class="sxs-lookup"><span data-stu-id="aee50-111">The next stage of the network interface update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>