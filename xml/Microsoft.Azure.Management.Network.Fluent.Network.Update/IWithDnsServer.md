<Type Name="IWithDnsServer" FullName="Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithDnsServer">
  <TypeSignature Language="C#" Value="public interface IWithDnsServer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDnsServer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithDnsServer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDnsServer" />
  <TypeSignature Language="F#" Value="type IWithDnsServer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9c5dc-101">Die Stufe der virtuelles Netzwerk aktualisieren ermöglicht die DNS-Server angeben.</span><span class="sxs-lookup"><span data-stu-id="9c5dc-101">The stage of the virtual network update allowing to specify the DNS server.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDnsServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithDnsServer (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithDnsServer(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithDnsServer.WithDnsServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDnsServer (ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDnsServer : string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate" Usage="iWithDnsServer.WithDnsServer ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="9c5dc-102">Die IP-Adresse des DNS-Servers.</span><span class="sxs-lookup"><span data-stu-id="9c5dc-102">The IP address of the DNS server.</span></span></param>
        <summary>
            <span data-ttu-id="9c5dc-103">Gibt die IP-Adresse des DNS-Servers im virtuellen Netzwerk zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="9c5dc-103">Specifies the IP address of the DNS server to associate with the virtual network.</span></span>
            <span data-ttu-id="9c5dc-104">Beachten Sie, diese Methode Effekt ist kumulativ, d. h. jedes Mal, die es verwendet wird, ein neuer DNS-Server ist zum Netzwerk hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="9c5dc-104">Note this method's effect is additive, i.e. each time it is used, a new DNS server is added to the network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9c5dc-105">Die nächste Phase des virtuellen Netzwerks Updates.</span><span class="sxs-lookup"><span data-stu-id="9c5dc-105">The next stage of the virtual network update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>