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
            Die Netzwerkkonfiguration für einen Pool.
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
            Initialisiert eine neue Instanz der NetworkConfiguration-Klasse.
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
        <param name="subnetId">Die ARM-Ressourcenbezeichner des virtuellen Netzwerks Subnetzes, das Compute-Knoten, der dem Pool hinzugefügt werden. Dies ist der Form/Subscriptions / {Abonnement} / ResourceGroups / {Gruppe} /providers/ {Anbieter} /virtualNetworks/ {Network} /subnets/ {Subnetz}.</param>
        <param name="endpointConfiguration">Die Konfiguration für Endpunkte auf Serverknoten im Batch-Pool an.</param>
        <summary>
            Initialisiert eine neue Instanz der NetworkConfiguration-Klasse.
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
            Ruft ab oder legt die Konfiguration für die Endpunkte auf den Serverknoten im Batch-Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Pool-Endpunktkonfiguration wird nur an den mit der Eigenschaft VirtualMachineConfiguration unterstützt.
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
            Ruft ab oder legt die ARM-Ressourcenbezeichner des virtuellen Netzwerks Subnetzes, das Compute-Knoten, der dem Pool hinzugefügt werden. Dies ist der Form/Subscriptions / {Abonnement} / ResourceGroups / {Gruppe} /providers/ {Anbieter} /virtualNetworks/ {Network} /subnets/ {Subnetz}.
            </summary>
        <value>To be added.</value>
        <remarks>
            Das virtuelle Netzwerk muss sich in derselben Region und demselben Abonnement wie der Azure Batch-Konto. Das angegebene Subnetz sollte genügend freien IP-Adressen verwenden, um die Anzahl der Knoten im Pool zu berücksichtigen haben.
            Wenn das Subnetz nicht über genügend freie IP-Adressen verfügt, der Pool belegt teilweise Serverknoten, und eine größenänderungsfehler zurück, der treten auf.
            Dienstprinzipal "MicrosoftAzureBatch" muss der "klassischen virtuellen Computer Contributor" mit der rollenbasierten Zugriffssteuerung (RBAC)-Rolle für die angegebene VNet verfügen. Das angegebene Subnetz muss die Kommunikation zwischen dem Azure Batch-Dienst, und Planen von Aufgaben auf den Serverknoten können zulassen. Dies kann überprüft werden, indem geprüft wird, ob es sich bei das angegebene VNet alle zugeordneten Netzwerksicherheitsgruppe Gruppen (NSG) hat. Wenn von einer NSG Kommunikation mit den Compute-Knoten im angegebenen Subnetz abgelehnt wird, wird der Batch-Dienst den Zustand der Serverknoten auf unbrauchbar festgelegt. Für mit VirtualMachineConfiguration erstellten Ressourcenpools nur ARM virtuelle Netzwerke ("Microsoft.Network/virtualNetworks") werden unterstützt, aber für mit CloudServiceConfiguration erstellten Ressourcenpools ARM- und klassische virtuelle Netzwerke unterstützt werden. Falls dem angegebenen VNET Netzwerksicherheitsgruppen (NSGs) zugeordnet sind, müssen einige reservierte Systemports für die eingehende Kommunikation aktiviert werden. Aktivieren Sie für Pools, die mit einer VM-Konfiguration erstellt wurden, die Ports 29876 und 29877 sowie den Port 22 für Linux und den Port 3389 für Windows. Aktivieren Sie für Pools, die mit einer Clouddienstkonfiguration erstellt wurden, die Ports 10100, 20100 und 30100. Aktivieren Sie auch ausgehende Verbindungen mit dem Azure-Speicher über Port 443. Weitere Informationen finden Sie unter: https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration
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
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>