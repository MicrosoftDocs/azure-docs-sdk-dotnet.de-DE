<Type Name="IWithNetwork&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithNetwork&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNetwork&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNetwork`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithNetwork`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNetwork(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithNetwork&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="2f9ce-101">Der Rückgabetyp des endgültigen Attachable.attach().</span><span class="sxs-lookup"><span data-stu-id="2f9ce-101">The return type of the final  Attachable.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="2f9ce-102">Die Stufe der Netzwerk-IP-Konfiguration Schnittstellendefinition an das virtuelle Netzwerk ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="2f9ce-102">The stage of the network interface IP configuration definition allowing to specify the virtual network.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithSubnet&lt;ParentT&gt; WithExistingNetwork (Microsoft.Azure.Management.Network.Fluent.INetwork network);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithSubnet`1&lt;!ParentT&gt; WithExistingNetwork(class Microsoft.Azure.Management.Network.Fluent.INetwork network) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithNetwork`1.WithExistingNetwork(Microsoft.Azure.Management.Network.Fluent.INetwork)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingNetwork (network As INetwork) As IWithSubnet(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingNetwork : Microsoft.Azure.Management.Network.Fluent.INetwork -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithSubnet&lt;'ParentT&gt;" Usage="iWithNetwork.WithExistingNetwork network" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithSubnet&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
      </Parameters>
      <Docs>
        <param name="network"><span data-ttu-id="2f9ce-103">Ein vorhandenes virtuelles Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="2f9ce-103">An existing virtual network.</span></span></param>
        <summary>
            <span data-ttu-id="2f9ce-104">Ordnen Sie ein vorhandenes virtuelles Netzwerk-IP-Konfiguration der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="2f9ce-104">Associate an existing virtual network with the network interface IP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2f9ce-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="2f9ce-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;ParentT&gt; WithNewNetwork (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP`1&lt;!ParentT&gt; WithNewNetwork(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetwork&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithNetwork`1.WithNewNetwork(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetwork})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewNetwork (creatable As ICreatable(Of INetwork)) As IWithPrivateIP(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNewNetwork : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;'ParentT&gt;" Usage="iWithNetwork.WithNewNetwork creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable"><span data-ttu-id="2f9ce-106">Eine erstellbare Definition für ein neues virtuelles Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="2f9ce-106">A creatable definition for a new virtual network.</span></span></param>
        <summary>
            <span data-ttu-id="2f9ce-107">Erstellen Sie ein neues virtuelles Netzwerk, IP-die Konfiguration der Netzwerkschnittstelle, basierend auf der bereitgestellten Definition zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="2f9ce-107">Create a new virtual network to associate with the  network interface IP configuration, based on the provided definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2f9ce-108">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="2f9ce-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;ParentT&gt; WithNewNetwork (string addressSpace);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP`1&lt;!ParentT&gt; WithNewNetwork(string addressSpace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithNetwork`1.WithNewNetwork(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewNetwork (addressSpace As String) As IWithPrivateIP(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNewNetwork : string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;'ParentT&gt;" Usage="iWithNetwork.WithNewNetwork addressSpace" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addressSpace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="addressSpace"><span data-ttu-id="2f9ce-109">Der Adressraum für das virtuelle Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="2f9ce-109">The address space for the virtual network.</span></span></param>
        <summary>
            <span data-ttu-id="2f9ce-110">Erstellt ein neues virtuelles Netzwerk, IP-Konfiguration der Netzwerkschnittstelle zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="2f9ce-110">Creates a new virtual network to associate with the network interface IP configuration.</span></span>
            <span data-ttu-id="2f9ce-111">das virtuelle Netzwerk wird in derselben Ressourcengruppe und Region ab übergeordneten Netzwerkschnittstelle erstellt werden, wird mit der angegebenen Adressraum und eine standardsubnetz abdecken der Netzwerk-IP-Adressbereich vollständig erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="2f9ce-111">the virtual network will be created in the same resource group and region as of parent network interface, it will be created with the specified address space and a default subnet covering the entirety of the network IP address space.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2f9ce-112">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="2f9ce-112">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;ParentT&gt; WithNewNetwork (string name, string addressSpace);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP`1&lt;!ParentT&gt; WithNewNetwork(string name, string addressSpace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithNetwork`1.WithNewNetwork(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewNetwork (name As String, addressSpace As String) As IWithPrivateIP(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNewNetwork : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;'ParentT&gt;" Usage="iWithNetwork.WithNewNetwork (name, addressSpace)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="addressSpace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="2f9ce-113">Der Name des neuen virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="2f9ce-113">The name of the new virtual network.</span></span></param>
        <param name="addressSpace"><span data-ttu-id="2f9ce-114">Der Adressraum für das virtuelle Netzwerk Rhe.</span><span class="sxs-lookup"><span data-stu-id="2f9ce-114">The address space for rhe virtual network.</span></span></param>
        <summary>
            <span data-ttu-id="2f9ce-115">Erstellt ein neues virtuelles Netzwerk, IP-Konfiguration der Netzwerkschnittstelle zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="2f9ce-115">Creates a new virtual network to associate with the network interface IP configuration.</span></span>
            <span data-ttu-id="2f9ce-116">das virtuelle Netzwerk wird in derselben Ressourcengruppe und Region ab übergeordneten Netzwerkschnittstelle erstellt werden, wird mit der angegebenen Adressraum und eine standardsubnetz abdecken der Netzwerk-IP-Adressbereich vollständig erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="2f9ce-116">the virtual network will be created in the same resource group and region as of parent network interface, it will be created with the specified address space and a default subnet covering the entirety of the network IP address space.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2f9ce-117">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="2f9ce-117">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>