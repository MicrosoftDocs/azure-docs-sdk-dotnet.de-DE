<Type Name="VirtualMachineConfiguration" FullName="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration">
  <TypeSignature Language="C#" Value="public class VirtualMachineConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineConfiguration" />
  <TypeSignature Language="F#" Value="type VirtualMachineConfiguration = class" />
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
      <MemberSignature Language="C#" Value="public VirtualMachineConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.#ctor" />
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
            Initialisiert eine neue Instanz der VirtualMachineConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineConfiguration (Microsoft.Azure.Batch.Protocol.Models.ImageReference imageReference, string nodeAgentSKUId, Microsoft.Azure.Batch.Protocol.Models.OSDisk osDisk = null, Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration windowsConfiguration = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; dataDisks = null, string licenseType = null, Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration containerConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.Models.ImageReference imageReference, string nodeAgentSKUId, class Microsoft.Azure.Batch.Protocol.Models.OSDisk osDisk, class Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration windowsConfiguration, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; dataDisks, string licenseType, class Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration containerConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.#ctor(Microsoft.Azure.Batch.Protocol.Models.ImageReference,System.String,Microsoft.Azure.Batch.Protocol.Models.OSDisk,Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.DataDisk},System.String,Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration : Microsoft.Azure.Batch.Protocol.Models.ImageReference * string * Microsoft.Azure.Batch.Protocol.Models.OSDisk * Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; * string * Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration -&gt; Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration" Usage="new Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration (imageReference, nodeAgentSKUId, osDisk, windowsConfiguration, dataDisks, licenseType, containerConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Batch.Protocol.Models.ImageReference" />
        <Parameter Name="nodeAgentSKUId" Type="System.String" />
        <Parameter Name="osDisk" Type="Microsoft.Azure.Batch.Protocol.Models.OSDisk" />
        <Parameter Name="windowsConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration" />
        <Parameter Name="dataDisks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt;" />
        <Parameter Name="licenseType" Type="System.String" />
        <Parameter Name="containerConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration" />
      </Parameters>
      <Docs>
        <param name="imageReference">Ein Verweis auf den Azure-virtuelle Computer-Marketplace-Image oder die benutzerdefinierte VM-Image zu verwenden.</param>
        <param name="nodeAgentSKUId">Die SKU des Batch-Knoten-Agent auf bereitzustellenden Serverknoten im Pool.</param>
        <param name="osDisk">Einstellungen für den Betriebssystemdatenträger des virtuellen Computers.</param>
        <param name="windowsConfiguration">Windows-Betriebssystem-Einstellungen auf dem virtuellen Computer.</param>
        <param name="dataDisks">Die Konfiguration für Datenträger auf den Comptue-Knoten in den Pool zugeordnet.</param>
        <param name="licenseType">Der Typ des lokalen-Lizenz, um bei der Bereitstellung von Betriebssystemen verwendet werden.</param>
        <param name="containerConfiguration">Die Konfiguration des Containers für den Pool.</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration ContainerConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration ContainerConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.ContainerConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerConfiguration As ContainerConfiguration" />
      <MemberSignature Language="F#" Value="member this.ContainerConfiguration : Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.ContainerConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Konfiguration des Containers für den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn angegeben, erfolgt die Setup auf jedem Knoten im Pool zu Aufgaben in Containern ausgeführt werden können. Alle regulären und Auftrags-Manager Aufgaben für diesen Pool ausgeführt, müssen die ContainerSettings-Eigenschaft angeben, und alle anderen Aufgaben können sie angeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As IList(Of DataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataDisks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Konfiguration für Datenträger auf den Comptue-Knoten in den Pool zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft muss angegeben werden, wenn die Serverknoten im Pool leere Datenträger verbunden werden sollen. Dieser Wert kann nicht aktualisiert werden. Jeder Knoten Ruft einen eigenen Datenträger (der Datenträger ist nicht auf eine Dateifreigabe) ab. Vorhandene Datenträger können nicht angefügt werden, jede angefügte Datenträger ist leer. Wenn der Knoten aus dem Pool entfernt wird, wird der Datenträger und alle zugeordneten Daten ebenfalls gelöscht. Der Datenträger nicht nach dem Anfügen formatiert wird, müssen Sie vor der Verwendung - Weitere Informationen finden Sie unter https://docs.microsoft.com/en-us/azure/virtual-machines/linux/classic/attach-disk#initialize-a-new-data-disk-in-linux und https:// formatiert werden docs.Microsoft.com/en-US/Azure/Virtual-Machines/Windows/Attach-Disk-PS#Add-an-Empty-Data-Disk-to-a-Virtual-Machine.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ImageReference ImageReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ImageReference ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageReference As ImageReference" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Batch.Protocol.Models.ImageReference with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.ImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="imageReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ImageReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Verweis auf das Azure-virtuelle Computer-Marketplace-Image oder benutzerdefinierten virtuellen Computers zu verwendenden Images.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft und der Betriebssystemdatenträger schließen sich gegenseitig aus, und eine der Eigenschaften muss angegeben werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="licenseType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             Ruft ab, oder legt ihn fest lokalen Lizenztyp verwendet werden, wenn Sie das Betriebssystem bereitstellen.
             </summary>
        <value>To be added.</value>
        <remarks>
             Dies gilt nur für Bilder, die Windows-Betriebssystem enthalten und sollte nur verwendet werden, wenn Sie gültige lokale Lizenzen für die Knoten enthalten. diese bereitgestellt wird. Wenn nicht angegeben ist, werden keine lokalen Lizenzierung Preisnachlass angewendet wird. Gültige Werte:
             
             Windows_Server - ist der lokale für Windows Server.
             "Windows_client" - ist der lokale für Windows-Clients.
            
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeAgentSKUId">
      <MemberSignature Language="C#" Value="public string NodeAgentSKUId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeAgentSKUId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.NodeAgentSKUId" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeAgentSKUId As String" />
      <MemberSignature Language="F#" Value="member this.NodeAgentSKUId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.NodeAgentSKUId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeAgentSKUId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die SKU des Batch-Knoten-Agent auf den Serverknoten im Pool bereitgestellt werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Batch-Knoten-Agent ist ein Programm, das auf jedem Knoten im Pool ausgeführt wird, und stellt eine Schnittstelle Befehl Steuerelement zwischen den Knoten und der Batch-Dienst. Es gibt verschiedene Implementierungen des Knoten-Agents (SKUs) für verschiedene Betriebssysteme. Sie müssen einen Knoten-Agent-SKU angeben, die den ausgewählten Bildverweis entspricht. Um die Liste der unterstützten Knoten Agent SKUs sowie eine Liste von überprüften bildreferenzen zu erhalten, finden Sie unter dem Vorgang "Liste unterstützter Knoten Agent SKUs".
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OsDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.OSDisk OsDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.OSDisk OsDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.OsDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property OsDisk As OSDisk" />
      <MemberSignature Language="F#" Value="member this.OsDisk : Microsoft.Azure.Batch.Protocol.Models.OSDisk with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.OsDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.OSDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Einstellungen für den Betriebssystemdatenträger des virtuellen Computers fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft kann nur angegeben werden, wenn das Batch-Konto, wobei seine PoolAllocationMode-Eigenschaft auf "UserSubscription" festgelegt erstellt wurde. Diese Eigenschaft und die ImageReference schließen sich gegenseitig aus, und eine der Eigenschaften muss angegeben werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineConfiguration.Validate " />
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
    <Member MemberName="WindowsConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration WindowsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration WindowsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsConfiguration As WindowsConfiguration" />
      <MemberSignature Language="F#" Value="member this.WindowsConfiguration : Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="windowsConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Einstellungen des Windows-Betriebssystems auf dem virtuellen Computer.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft muss angegeben werden, wenn die Eigenschaft ImageReference oder Betriebssystemdatenträger ein Linux-Betriebssystem-Image angibt.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>