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
            Die Netzwerkkonfiguration für einen Pool.
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
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.NetworkConfiguration" />-Klasse.
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
            Ruft ab oder legt die Konfiguration für die Endpunkte auf den Serverknoten im Batch-Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft kann nur angegeben werden, für Pools mit erstellt eine <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" />.
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
            Ruft ab oder legt die ARM-Ressourcenbezeichner des virtuellen Netzwerks Subnetzes, das Compute-Knoten, der dem Pool hinzugefügt werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Das virtuelle Netzwerk muss sich in derselben Region und demselben Abonnement wie der Azure Batch-Konto. Das angegebene Subnetz sollte genügend freien IP-Adressen verwenden, um die Anzahl der Knoten im Pool zu berücksichtigen haben. Wenn das Subnetz nicht über genügend freie IP-Adressen verfügt, der Pool belegt teilweise Serverknoten, und eine größenänderungsfehler zurück, der treten auf. Dienstprinzipal "MicrosoftAzureBatch" muss der "klassischen virtuellen Computer Contributor" mit der rollenbasierten Zugriffssteuerung (RBAC)-Rolle für die angegebene VNet verfügen. Das angegebene Subnetz muss die Kommunikation zwischen dem Azure Batch-Dienst, und Planen von Aufgaben auf den Serverknoten können zulassen. Dies kann überprüft werden, indem geprüft wird, ob es sich bei das angegebene VNet alle zugeordneten Netzwerksicherheitsgruppe Gruppen (NSG) hat. Wenn von einer NSG Kommunikation mit den Compute-Knoten im angegebenen Subnetz abgelehnt wird, wird der Batch-Dienst den Zustand der Serverknoten auf unbrauchbar festgelegt. Für Anwendungspools-Computer erstellte Clientkonfigurationsanforderungen <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" /> nur ARM virtuelle Netzwerke ("Microsoft.Network/virtualNetworks") unterstützt werden, aber für Pools erstellt, mit <see cref="P:Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" /> ARM und klassische virtuelle Netzwerke werden unterstützt. Falls dem angegebenen VNET Netzwerksicherheitsgruppen (NSGs) zugeordnet sind, müssen einige reservierte Systemports für die eingehende Kommunikation aktiviert werden. Für Anwendungspools mit erstellt eine <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" />, aktivieren Sie Ports 29876 und 29877 als auch port 22 für Linux und Port 3389 für Windows. Für Anwendungspools mit erstellt eine <see cref="P:Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" />, aktivieren Sie Ports 10100 20100 und 30100. Aktivieren Sie auch ausgehende Verbindungen mit dem Azure-Speicher über Port 443. Weitere Informationen finden Sie unter: https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>