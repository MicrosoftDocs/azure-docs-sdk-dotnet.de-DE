<Type Name="ImageReference" FullName="Microsoft.Azure.Batch.Protocol.Models.ImageReference">
  <TypeSignature Language="C#" Value="public class ImageReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ImageReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageReference" />
  <TypeSignature Language="F#" Value="type ImageReference = class" />
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
            Ein Verweis auf ein Azure-virtuelle Computer-Marketplace-Image oder ein benutzerdefiniertes Image des virtuellen Azure-Computer. Zum Abrufen aller Azure Marketplace-Image-Verweise, die vom Azure Batch überprüft wurden, finden Sie unter "Liste Knoten Agent-SKUs" Vorgang.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ImageReference.#ctor" />
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
            Initialisiert eine neue Instanz der Klasse ImageReference.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference (string publisher = null, string offer = null, string sku = null, string version = null, string virtualMachineImageId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string publisher, string offer, string sku, string version, string virtualMachineImageId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ImageReference.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional publisher As String = null, Optional offer As String = null, Optional sku As String = null, Optional version As String = null, Optional virtualMachineImageId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ImageReference : string * string * string * string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.ImageReference" Usage="new Microsoft.Azure.Batch.Protocol.Models.ImageReference (publisher, offer, sku, version, virtualMachineImageId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="virtualMachineImageId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher">Der Herausgeber des Images Marketplace für Azure-virtuellen Computern.</param>
        <param name="offer">Der Angebotstyp von der Azure-virtuelle Computer-Marketplace-Image.</param>
        <param name="sku">Die SKU des Images Marketplace für Azure-virtuellen Computern.</param>
        <param name="version">Die Version des Azure VMs Marketplace-Images.</param>
        <param name="virtualMachineImageId">Die ARM-Ressourcenbezeichner des Image des virtuellen Computers. Berechnet, dass die Knoten des Pools mit diesem benutzerdefinierten Abbild erstellt werden. Dies ist von der Form /subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName}</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse ImageReference.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offer">
      <MemberSignature Language="C#" Value="public string Offer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ImageReference.Offer" />
      <MemberSignature Language="VB.NET" Value="Public Property Offer As String" />
      <MemberSignature Language="F#" Value="member this.Offer : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ImageReference.Offer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="offer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest die Angebot der Azure-virtuelle Computer-Marketplace-Image.
            </summary>
        <value>To be added.</value>
        <remarks>
            Z. B. UbuntuServer oder Windows Server.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ImageReference.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ImageReference.Publisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="publisher")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Herausgeber des Images Marketplace für Azure-virtuellen Computern.
            </summary>
        <value>To be added.</value>
        <remarks>
            Canonical oder MicrosoftWindowsServer.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public string Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ImageReference.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As String" />
      <MemberSignature Language="F#" Value="member this.Sku : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ImageReference.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen die SKU der Azure-virtuelle Computer-Marketplace-Image.
            </summary>
        <value>To be added.</value>
        <remarks>
            Beispielsweise 14.04.0-LTS oder 2012 R2 Datencenter.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ImageReference.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ImageReference.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Version von der Azure-virtuelle Computer-Marketplace-Image.
            </summary>
        <value>To be added.</value>
        <remarks>
            Ein Wert "latest" kann angegeben werden, um die neueste Version eines Bilds auszuwählen. Wenn nicht angegeben, ist die Standardeinstellung 'letzte'.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineImageId">
      <MemberSignature Language="C#" Value="public string VirtualMachineImageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineImageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ImageReference.VirtualMachineImageId" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineImageId As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineImageId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ImageReference.VirtualMachineImageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineImageId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den ARM-Ressourcenbezeichner des Image des virtuellen Computers. Berechnet, dass die Knoten des Pools mit diesem benutzerdefinierten Abbild erstellt werden. Dies ist von der Form /subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName}
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft ist mit anderen Eigenschaften ImageReference gegenseitig. Image des virtuellen Computers muss sich in derselben Region und demselben Abonnement wie der Azure Batch-Konto. Informationen über die Firewall-Einstellungen für den Batch-Knoten-Agent für die Kommunikation mit der Batch-Dienst finden Sie unter https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>