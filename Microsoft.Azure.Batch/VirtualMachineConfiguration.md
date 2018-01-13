<Type Name="VirtualMachineConfiguration" FullName="Microsoft.Azure.Batch.VirtualMachineConfiguration">
  <TypeSignature Language="C#" Value="public class VirtualMachineConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineConfiguration" />
  <TypeSignature Language="F#" Value="type VirtualMachineConfiguration = class&#xA;    interface ITransportObjectProvider&lt;VirtualMachineConfiguration&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Die Konfiguration für die Serverknoten in einem Pool basierend auf den virtuellen Computern in Azure-Infrastruktur.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineConfiguration (Microsoft.Azure.Batch.ImageReference imageReference, string nodeAgentSkuId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.ImageReference imageReference, string nodeAgentSkuId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.VirtualMachineConfiguration.#ctor(Microsoft.Azure.Batch.ImageReference,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.VirtualMachineConfiguration : Microsoft.Azure.Batch.ImageReference * string -&gt; Microsoft.Azure.Batch.VirtualMachineConfiguration" Usage="new Microsoft.Azure.Batch.VirtualMachineConfiguration (imageReference, nodeAgentSkuId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Batch.ImageReference" />
        <Parameter Name="nodeAgentSkuId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageReference">Ein Verweis auf das Marketplace-Image in Azure VMs oder des benutzerdefinierten Images des virtuellen Computers zu verwenden.</param>
        <param name="nodeAgentSkuId">Der SKU der Batch Knoten-Agent auf den Computeknoten bereitgestellt werden.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ContainerConfiguration ContainerConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ContainerConfiguration ContainerConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ContainerConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerConfiguration As ContainerConfiguration" />
      <MemberSignature Language="F#" Value="member this.ContainerConfiguration : Microsoft.Azure.Batch.ContainerConfiguration with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.ContainerConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ContainerConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Konfiguration des Containers für den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn angegeben, erfolgt die Setup auf jedem Knoten im Pool zu Aufgaben in Containern ausgeführt werden können. Alle regulären und Auftrags-Manager Aufgaben für diesen Pool ausführen müssen angeben, <see cref="T:Microsoft.Azure.Batch.TaskContainerSettings" />, und alle anderen Aufgaben können sie angeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.DataDisk&gt; DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.DataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As IList(Of DataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.DataDisk&gt; with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.DataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Konfiguration für Datenträger auf den Comptue-Knoten in den Pool zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft muss angegeben werden, wenn die Serverknoten im Pool leere Datenträger verbunden werden sollen. Dieser Wert kann nicht aktualisiert werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ImageReference ImageReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ImageReference ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageReference As ImageReference" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Batch.ImageReference with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.ImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ImageReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert einen Verweis auf das Marketplace-Image in Azure VMs oder des benutzerdefinierten Images des virtuellen Computers zu verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft und <see cref="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.OSDisk" /> gegenseitig und eine der Eigenschaften muss angegeben werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest lokalen Lizenztyp verwendet werden, wenn Sie das Betriebssystem bereitstellen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies gilt nur für Bilder, die Windows-Betriebssystem enthalten und sollte nur verwendet werden, wenn Sie gültige lokale Lizenzen für die Knoten enthalten. diese bereitgestellt wird. Wenn nicht angegeben ist, werden keine lokalen Lizenzierung Preisnachlass angewendet wird. Werte sind: "Windows_Server" - die lokalen-Lizenz ist für Windows Server. "" Windows_client "-" ist die lokale-Lizenz für Windows-Clients.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeAgentSkuId">
      <MemberSignature Language="C#" Value="public string NodeAgentSkuId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeAgentSkuId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.NodeAgentSkuId" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeAgentSkuId As String" />
      <MemberSignature Language="F#" Value="member this.NodeAgentSkuId : string with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.NodeAgentSkuId" />
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
            Ruft ab, oder legt ihn fest-SKU von Batch Knoten Agent auf den Computeknoten bereitgestellt werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Batch-Knoten-Agent ist ein Programm, das auf jedem Knoten im Pool ausgeführt wird, und stellt eine Schnittstelle Befehl Steuerelement zwischen den Knoten und der Batch-Dienst. Es gibt verschiedene Implementierungen des Knoten-Agents (SKUs) für verschiedene Betriebssysteme.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.OSDisk OSDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.OSDisk OSDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.OSDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property OSDisk As OSDisk" />
      <MemberSignature Language="F#" Value="member this.OSDisk : Microsoft.Azure.Batch.OSDisk with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.OSDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.OSDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Einstellungen für den Betriebssystemdatenträger des virtuellen Computers fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft kann nur angegeben werden, wenn das Batch-Konto, wobei seine PoolAllocationMode-Eigenschaft auf "UserSubscription" festgelegt erstellt wurde. Diese Eigenschaft und <see cref="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ImageReference" /> gegenseitig und eine der Eigenschaften muss angegeben werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.WindowsConfiguration WindowsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.WindowsConfiguration WindowsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsConfiguration As WindowsConfiguration" />
      <MemberSignature Language="F#" Value="member this.WindowsConfiguration : Microsoft.Azure.Batch.WindowsConfiguration with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.WindowsConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Einstellungen des Windows-Betriebssystems auf dem virtuellen Computer. Diese Eigenschaft muss angegeben werden, wenn die Eigenschaft ImageReference ein Linux-Betriebssystem-Image angibt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>