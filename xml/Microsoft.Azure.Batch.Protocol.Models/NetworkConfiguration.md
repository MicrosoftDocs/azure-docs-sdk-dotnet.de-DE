<Type Name="NetworkConfiguration" FullName="Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration">
  <TypeSignature Language="C#" Value="public class NetworkConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkConfiguration" />
  <TypeSignature Language="F#" Value="type NetworkConfiguration = class" />
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
            <span data-ttu-id="0d06a-101">Die Netzwerkkonfiguration für einen Pool.</span><span class="sxs-lookup"><span data-stu-id="0d06a-101">The network configuration for a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration.#ctor" />
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
            <span data-ttu-id="0d06a-102">Initialisiert eine neue Instanz der NetworkConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0d06a-102">Initializes a new instance of the NetworkConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkConfiguration (string subnetId = null, Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration endpointConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string subnetId, class Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration endpointConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional subnetId As String = null, Optional endpointConfiguration As PoolEndpointConfiguration = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration : string * Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration -&gt; Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration" Usage="new Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration (subnetId, endpointConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="subnetId" Type="System.String" />
        <Parameter Name="endpointConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration" />
      </Parameters>
      <Docs>
        <param name="subnetId"><span data-ttu-id="0d06a-103">Die ARM-Ressourcenbezeichner des virtuellen Netzwerks Subnetzes, das Compute-Knoten, der dem Pool hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="0d06a-103">The ARM resource identifier of the virtual network subnet which the compute nodes of the pool will join.</span></span> <span data-ttu-id="0d06a-104">Dies ist der Form/Subscriptions / {Abonnement} / ResourceGroups / {Gruppe} /providers/ {Anbieter} /virtualNetworks/ {Network} /subnets/ {Subnetz}.</span><span class="sxs-lookup"><span data-stu-id="0d06a-104">This is of the form /subscriptions/{subscription}/resourceGroups/{group}/providers/{provider}/virtualNetworks/{network}/subnets/{subnet}.</span></span></param>
        <param name="endpointConfiguration"><span data-ttu-id="0d06a-105">Die Konfiguration für Endpunkte auf Serverknoten im Batch-Pool an.</span><span class="sxs-lookup"><span data-stu-id="0d06a-105">The configuration for endpoints on compute nodes in the Batch pool.</span></span></param>
        <summary>
            <span data-ttu-id="0d06a-106">Initialisiert eine neue Instanz der NetworkConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0d06a-106">Initializes a new instance of the NetworkConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration EndpointConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration EndpointConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration.EndpointConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointConfiguration As PoolEndpointConfiguration" />
      <MemberSignature Language="F#" Value="member this.EndpointConfiguration : Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration.EndpointConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endpointConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d06a-107">Ruft ab oder legt die Konfiguration für die Endpunkte auf den Serverknoten im Batch-Pool.</span><span class="sxs-lookup"><span data-stu-id="0d06a-107">Gets or sets the configuration for endpoints on compute nodes in the Batch pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0d06a-108">Pool-Endpunktkonfiguration wird nur an den mit der Eigenschaft VirtualMachineConfiguration unterstützt.</span><span class="sxs-lookup"><span data-stu-id="0d06a-108">Pool endpoint configuration is only supported on pools with the virtualMachineConfiguration property.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetId">
      <MemberSignature Language="C#" Value="public string SubnetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubnetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration.SubnetId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubnetId As String" />
      <MemberSignature Language="F#" Value="member this.SubnetId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration.SubnetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subnetId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d06a-109">Ruft ab oder legt die ARM-Ressourcenbezeichner des virtuellen Netzwerks Subnetzes, das Compute-Knoten, der dem Pool hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="0d06a-109">Gets or sets the ARM resource identifier of the virtual network subnet which the compute nodes of the pool will join.</span></span> <span data-ttu-id="0d06a-110">Dies ist der Form/Subscriptions / {Abonnement} / ResourceGroups / {Gruppe} /providers/ {Anbieter} /virtualNetworks/ {Network} /subnets/ {Subnetz}.</span><span class="sxs-lookup"><span data-stu-id="0d06a-110">This is of the form /subscriptions/{subscription}/resourceGroups/{group}/providers/{provider}/virtualNetworks/{network}/subnets/{subnet}.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0d06a-111">Das virtuelle Netzwerk muss sich in derselben Region und demselben Abonnement wie der Azure Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="0d06a-111">The virtual network must be in the same region and subscription as the Azure Batch account.</span></span> <span data-ttu-id="0d06a-112">Das angegebene Subnetz sollte genügend freien IP-Adressen verwenden, um die Anzahl der Knoten im Pool zu berücksichtigen haben.</span><span class="sxs-lookup"><span data-stu-id="0d06a-112">The specified subnet should have enough free IP addresses to accommodate the number of nodes in the pool.</span></span>
            <span data-ttu-id="0d06a-113">Wenn das Subnetz nicht über genügend freie IP-Adressen verfügt, der Pool belegt teilweise Serverknoten, und eine größenänderungsfehler zurück, der treten auf.</span><span class="sxs-lookup"><span data-stu-id="0d06a-113">If the subnet doesn't have enough free IP addresses, the pool will partially allocate compute nodes, and a resize error will occur.</span></span>
            <span data-ttu-id="0d06a-114">Dienstprinzipal "MicrosoftAzureBatch" muss der "klassischen virtuellen Computer Contributor" mit der rollenbasierten Zugriffssteuerung (RBAC)-Rolle für die angegebene VNet verfügen.</span><span class="sxs-lookup"><span data-stu-id="0d06a-114">The 'MicrosoftAzureBatch' service principal must have the 'Classic Virtual Machine Contributor' Role-Based Access Control (RBAC) role for the specified VNet.</span></span> <span data-ttu-id="0d06a-115">Das angegebene Subnetz muss die Kommunikation zwischen dem Azure Batch-Dienst, und Planen von Aufgaben auf den Serverknoten können zulassen.</span><span class="sxs-lookup"><span data-stu-id="0d06a-115">The specified subnet must allow communication from the Azure Batch service to be able to schedule tasks on the compute nodes.</span></span> <span data-ttu-id="0d06a-116">Dies kann überprüft werden, indem geprüft wird, ob es sich bei das angegebene VNet alle zugeordneten Netzwerksicherheitsgruppe Gruppen (NSG) hat.</span><span class="sxs-lookup"><span data-stu-id="0d06a-116">This can be verified by checking if the specified VNet has any associated Network Security Groups (NSG).</span></span> <span data-ttu-id="0d06a-117">Wenn von einer NSG Kommunikation mit den Compute-Knoten im angegebenen Subnetz abgelehnt wird, wird der Batch-Dienst den Zustand der Serverknoten auf unbrauchbar festgelegt.</span><span class="sxs-lookup"><span data-stu-id="0d06a-117">If communication to the compute nodes in the specified subnet is denied by an NSG, then the Batch service will set the state of the compute nodes to unusable.</span></span> <span data-ttu-id="0d06a-118">Für mit VirtualMachineConfiguration erstellten Ressourcenpools nur ARM virtuelle Netzwerke ("Microsoft.Network/virtualNetworks") werden unterstützt, aber für mit CloudServiceConfiguration erstellten Ressourcenpools ARM- und klassische virtuelle Netzwerke unterstützt werden.</span><span class="sxs-lookup"><span data-stu-id="0d06a-118">For pools created with virtualMachineConfiguration only ARM virtual networks ('Microsoft.Network/virtualNetworks') are supported, but for pools created with cloudServiceConfiguration both ARM and classic virtual networks are supported.</span></span> <span data-ttu-id="0d06a-119">Falls dem angegebenen VNET Netzwerksicherheitsgruppen (NSGs) zugeordnet sind, müssen einige reservierte Systemports für die eingehende Kommunikation aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="0d06a-119">If the specified VNet has any associated Network Security Groups (NSG), then a few reserved system ports must be enabled for inbound communication.</span></span> <span data-ttu-id="0d06a-120">Aktivieren Sie für Pools, die mit einer VM-Konfiguration erstellt wurden, die Ports 29876 und 29877 sowie den Port 22 für Linux und den Port 3389 für Windows.</span><span class="sxs-lookup"><span data-stu-id="0d06a-120">For pools created with a virtual machine configuration, enable ports 29876 and 29877, as well as port 22 for Linux and port 3389 for Windows.</span></span> <span data-ttu-id="0d06a-121">Aktivieren Sie für Pools, die mit einer Clouddienstkonfiguration erstellt wurden, die Ports 10100, 20100 und 30100.</span><span class="sxs-lookup"><span data-stu-id="0d06a-121">For pools created with a cloud service configuration, enable ports 10100, 20100, and 30100.</span></span> <span data-ttu-id="0d06a-122">Aktivieren Sie auch ausgehende Verbindungen mit dem Azure-Speicher über Port 443.</span><span class="sxs-lookup"><span data-stu-id="0d06a-122">Also enable outbound connections to Azure Storage on port 443.</span></span> <span data-ttu-id="0d06a-123">Weitere Informationen finden Sie unter: https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration</span><span class="sxs-lookup"><span data-stu-id="0d06a-123">For more details see: https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="networkConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0d06a-124">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d06a-124">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0d06a-125">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="0d06a-125">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>