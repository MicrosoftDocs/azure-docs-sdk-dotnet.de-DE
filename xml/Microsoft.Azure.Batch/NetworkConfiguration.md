<Type Name="NetworkConfiguration" FullName="Microsoft.Azure.Batch.NetworkConfiguration">
  <TypeSignature Language="C#" Value="public class NetworkConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.NetworkConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkConfiguration" />
  <TypeSignature Language="F#" Value="type NetworkConfiguration = class&#xA;    interface ITransportObjectProvider&lt;NetworkConfiguration&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="bc690-101">Die Netzwerkkonfiguration für einen Pool.</span><span class="sxs-lookup"><span data-stu-id="bc690-101">The network configuration for a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NetworkConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bc690-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.NetworkConfiguration" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bc690-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.NetworkConfiguration" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolEndpointConfiguration EndpointConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.PoolEndpointConfiguration EndpointConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NetworkConfiguration.EndpointConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointConfiguration As PoolEndpointConfiguration" />
      <MemberSignature Language="F#" Value="member this.EndpointConfiguration : Microsoft.Azure.Batch.PoolEndpointConfiguration with get, set" Usage="Microsoft.Azure.Batch.NetworkConfiguration.EndpointConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolEndpointConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bc690-103">Ruft ab oder legt die Konfiguration für die Endpunkte auf den Serverknoten im Batch-Pool.</span><span class="sxs-lookup"><span data-stu-id="bc690-103">Gets or sets the configuration for endpoints on compute nodes in the Batch pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="bc690-104">Diese Eigenschaft kann nur angegeben werden, für Pools mit erstellt eine <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" />.</span><span class="sxs-lookup"><span data-stu-id="bc690-104">This property can only be specified for pools created with a <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetId">
      <MemberSignature Language="C#" Value="public string SubnetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubnetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NetworkConfiguration.SubnetId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubnetId As String" />
      <MemberSignature Language="F#" Value="member this.SubnetId : string with get, set" Usage="Microsoft.Azure.Batch.NetworkConfiguration.SubnetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bc690-105">Ruft ab oder legt die ARM-Ressourcenbezeichner des virtuellen Netzwerks Subnetzes, das Compute-Knoten, der dem Pool hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="bc690-105">Gets or sets the ARM resource identifier of the virtual network subnet which the compute nodes of the pool will join.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="bc690-106">Das virtuelle Netzwerk muss sich in derselben Region und demselben Abonnement wie der Azure Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="bc690-106">The virtual network must be in the same region and subscription as the Azure Batch account.</span></span> <span data-ttu-id="bc690-107">Das angegebene Subnetz sollte genügend freien IP-Adressen verwenden, um die Anzahl der Knoten im Pool zu berücksichtigen haben.</span><span class="sxs-lookup"><span data-stu-id="bc690-107">The specified subnet should have enough free IP addresses to accommodate the number of nodes in the pool.</span></span> <span data-ttu-id="bc690-108">Wenn das Subnetz nicht über genügend freie IP-Adressen verfügt, der Pool belegt teilweise Serverknoten, und eine größenänderungsfehler zurück, der treten auf.</span><span class="sxs-lookup"><span data-stu-id="bc690-108">If the subnet doesn't have enough free IP addresses, the pool will partially allocate compute nodes, and a resize error will occur.</span></span> <span data-ttu-id="bc690-109">Dienstprinzipal "MicrosoftAzureBatch" muss der "klassischen virtuellen Computer Contributor" mit der rollenbasierten Zugriffssteuerung (RBAC)-Rolle für die angegebene VNet verfügen.</span><span class="sxs-lookup"><span data-stu-id="bc690-109">The 'MicrosoftAzureBatch' service principal must have the 'Classic Virtual Machine Contributor' Role-Based Access Control (RBAC) role for the specified VNet.</span></span> <span data-ttu-id="bc690-110">Das angegebene Subnetz muss die Kommunikation zwischen dem Azure Batch-Dienst, und Planen von Aufgaben auf den Serverknoten können zulassen.</span><span class="sxs-lookup"><span data-stu-id="bc690-110">The specified subnet must allow communication from the Azure Batch service to be able to schedule tasks on the compute nodes.</span></span> <span data-ttu-id="bc690-111">Dies kann überprüft werden, indem geprüft wird, ob es sich bei das angegebene VNet alle zugeordneten Netzwerksicherheitsgruppe Gruppen (NSG) hat.</span><span class="sxs-lookup"><span data-stu-id="bc690-111">This can be verified by checking if the specified VNet has any associated Network Security Groups (NSG).</span></span> <span data-ttu-id="bc690-112">Wenn von einer NSG Kommunikation mit den Compute-Knoten im angegebenen Subnetz abgelehnt wird, wird der Batch-Dienst den Zustand der Serverknoten auf unbrauchbar festgelegt.</span><span class="sxs-lookup"><span data-stu-id="bc690-112">If communication to the compute nodes in the specified subnet is denied by an NSG, then the Batch service will set the state of the compute nodes to unusable.</span></span> <span data-ttu-id="bc690-113">Für Anwendungspools-Computer erstellte Clientkonfigurationsanforderungen <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" /> nur ARM virtuelle Netzwerke ("Microsoft.Network/virtualNetworks") unterstützt werden, aber für Pools erstellt, mit <see cref="P:Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" /> ARM und klassische virtuelle Netzwerke werden unterstützt.</span><span class="sxs-lookup"><span data-stu-id="bc690-113">For pools created via <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" /> only  only ARM virtual networks ('Microsoft.Network/virtualNetworks') are supported, but for pools created with <see cref="P:Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" /> both ARM and classic virtual networks are supported.</span></span> <span data-ttu-id="bc690-114">Falls dem angegebenen VNET Netzwerksicherheitsgruppen (NSGs) zugeordnet sind, müssen einige reservierte Systemports für die eingehende Kommunikation aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="bc690-114">If the specified VNet has any associated Network Security Groups (NSG), then a few reserved system ports must be enabled for inbound communication.</span></span> <span data-ttu-id="bc690-115">Für Anwendungspools mit erstellt eine <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" />, aktivieren Sie Ports 29876 und 29877 als auch port 22 für Linux und Port 3389 für Windows.</span><span class="sxs-lookup"><span data-stu-id="bc690-115">For pools created with a <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" />, enable ports 29876 and 29877, as well as port 22 for Linux and port 3389 for Windows.</span></span> <span data-ttu-id="bc690-116">Für Anwendungspools mit erstellt eine <see cref="P:Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" />, aktivieren Sie Ports 10100 20100 und 30100.</span><span class="sxs-lookup"><span data-stu-id="bc690-116">For pools created with a <see cref="P:Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" />, enable ports 10100, 20100, and 30100.</span></span> <span data-ttu-id="bc690-117">Aktivieren Sie auch ausgehende Verbindungen mit dem Azure-Speicher über Port 443.</span><span class="sxs-lookup"><span data-stu-id="bc690-117">Also enable outbound connections to Azure Storage on port 443.</span></span> <span data-ttu-id="bc690-118">Weitere Informationen finden Sie unter: https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration.</span><span class="sxs-lookup"><span data-stu-id="bc690-118">For more details see: https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>