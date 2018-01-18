<Type Name="IWithAddress&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAddress&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAddress&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAddress`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAddress`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAddress(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAddress&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="b9369-101">Die Phase der Definition des übergeordneten Anwendung Gateway wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="b9369-101">The stage of the parent application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="b9369-102">Die Stufe der Gateway Back-End-Anwendungsdefinition hinzufügen eine Adresse auf dem Back-End ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="b9369-102">The stage of an application gateway backend definition allowing to add an address to the backend.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAttach&lt;ParentT&gt; WithFqdn (string fqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAttach`1&lt;!ParentT&gt; WithFqdn(string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAddress`1.WithFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFqdn (fqdn As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithFqdn : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAddress.WithFqdn fqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fqdn"><span data-ttu-id="b9369-103">Einen vollständig qualifizierten Domänennamen (FQDN).</span><span class="sxs-lookup"><span data-stu-id="b9369-103">A fully qualified domain name (FQDN).</span></span></param>
        <summary>
            <span data-ttu-id="b9369-104">Fügt der angegebenen vorhandenen vollständig qualifizierten Domänennamen (FQDN) an den Back-End.</span><span class="sxs-lookup"><span data-stu-id="b9369-104">Adds the specified existing fully qualified domain name (FQDN) to the backend.</span></span>
            <span data-ttu-id="b9369-105">Dieser Aufruf kann in einer Sequenz vorgenommen werden, um mehrere FQDNs hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="b9369-105">This call can be made in a sequence to add multiple FQDNs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b9369-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="b9369-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAttach&lt;ParentT&gt; WithIPAddress (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAttach`1&lt;!ParentT&gt; WithIPAddress(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAddress`1.WithIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIPAddress (ipAddress As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAddress.WithIPAddress ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="b9369-107">Eine IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="b9369-107">An IP address.</span></span></param>
        <summary>
            <span data-ttu-id="b9369-108">Fügt die angegebene vorhandene IP-Adresse an den Back-End.</span><span class="sxs-lookup"><span data-stu-id="b9369-108">Adds the specified existing IP address to the backend.</span></span>
            <span data-ttu-id="b9369-109">Dieser Aufruf kann in einer Sequenz erfolgen mehrere IP-Adressen hinzu.</span><span class="sxs-lookup"><span data-stu-id="b9369-109">This call can be made in a sequence to add multiple IP addresses.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b9369-110">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="b9369-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>