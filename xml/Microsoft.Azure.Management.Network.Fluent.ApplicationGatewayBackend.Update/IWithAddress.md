<Type Name="IWithAddress" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress">
  <TypeSignature Language="C#" Value="public interface IWithAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAddress" />
  <TypeSignature Language="F#" Value="type IWithAddress = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a7eb5-101">Die Phase eines Application Gateway Back-End-Updates zulassen an das Back-End eine Adresse hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="a7eb5-101">The stage of an application gateway backend update allowing to add an address to the backend.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithFqdn (string fqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithFqdn(string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress.WithFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFqdn (fqdn As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithFqdn : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate" Usage="iWithAddress.WithFqdn fqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fqdn"><span data-ttu-id="a7eb5-102">Einen vollständig qualifizierten Domänennamen (FQDN).</span><span class="sxs-lookup"><span data-stu-id="a7eb5-102">A fully qualified domain name (FQDN).</span></span></param>
        <summary>
            <span data-ttu-id="a7eb5-103">Fügt der angegebenen vorhandenen vollständig qualifizierten Domänennamen (FQDN) an den Back-End.</span><span class="sxs-lookup"><span data-stu-id="a7eb5-103">Adds the specified existing fully qualified domain name (FQDN) to the backend.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a7eb5-104">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="a7eb5-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithIPAddress (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithIPAddress(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress.WithIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIPAddress (ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate" Usage="iWithAddress.WithIPAddress ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="a7eb5-105">Eine IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="a7eb5-105">An IP address.</span></span></param>
        <summary>
            <span data-ttu-id="a7eb5-106">Fügt die angegebene vorhandene IP-Adresse an den Back-End.</span><span class="sxs-lookup"><span data-stu-id="a7eb5-106">Adds the specified existing IP address to the backend.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a7eb5-107">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="a7eb5-107">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutAddress (Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutAddress(class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress.WithoutAddress(Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAddress (address As ApplicationGatewayBackendAddress) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutAddress : Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate" Usage="iWithAddress.WithoutAddress address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="a7eb5-108">Eine vorhandene Adresse, die mit dem Back-End derzeit zugewiesen ist.</span><span class="sxs-lookup"><span data-stu-id="a7eb5-108">An existing address currently associated with the backend.</span></span></param>
        <summary>
            <span data-ttu-id="a7eb5-109">Stellen Sie sicher, dass die angegebene Adresse nicht mit diesem Back-End-verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="a7eb5-109">Ensure the specified address is not associated with this backend.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a7eb5-110">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="a7eb5-110">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutFqdn (string fqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutFqdn(string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress.WithoutFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutFqdn (fqdn As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutFqdn : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate" Usage="iWithAddress.WithoutFqdn fqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fqdn"><span data-ttu-id="a7eb5-111">Einen vollständig qualifizierten Domänennamen ein.</span><span class="sxs-lookup"><span data-stu-id="a7eb5-111">A fully qualified domain name.</span></span></param>
        <summary>
            <span data-ttu-id="a7eb5-112">Stellt sicher, dass der angegebene vollqualifizierte Domänenname (FQDN) nicht mit diesem Back-End-verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="a7eb5-112">Ensures the specified fully qualified domain name (FQDN) is not associated with this backend.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a7eb5-113">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="a7eb5-113">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutIPAddress (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutIPAddress(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress.WithoutIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutIPAddress (ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate" Usage="iWithAddress.WithoutIPAddress ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="a7eb5-114">Eine IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="a7eb5-114">An IP address.</span></span></param>
        <summary>
            <span data-ttu-id="a7eb5-115">Stellt sicher, dass die angegebene IP-Adresse nicht mit diesem Back-End-verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="a7eb5-115">Ensures the specified IP address is not associated with this backend.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a7eb5-116">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="a7eb5-116">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>