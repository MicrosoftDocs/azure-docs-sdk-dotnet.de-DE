<Type Name="VirtualMachineConfiguration" FullName="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration">
  <TypeSignature Language="C#" Value="public class VirtualMachineConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineConfiguration" />
  <TypeSignature Language="F#" Value="type VirtualMachineConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public VirtualMachineConfiguration (Microsoft.Azure.Management.Batch.Models.ImageReference imageReference, string nodeAgentSkuId, Microsoft.Azure.Management.Batch.Models.OSDisk osDisk = null, Microsoft.Azure.Management.Batch.Models.WindowsConfiguration windowsConfiguration = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt; dataDisks = null, string licenseType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Batch.Models.ImageReference imageReference, string nodeAgentSkuId, class Microsoft.Azure.Management.Batch.Models.OSDisk osDisk, class Microsoft.Azure.Management.Batch.Models.WindowsConfiguration windowsConfiguration, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.DataDisk&gt; dataDisks, string licenseType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.#ctor(Microsoft.Azure.Management.Batch.Models.ImageReference,System.String,Microsoft.Azure.Management.Batch.Models.OSDisk,Microsoft.Azure.Management.Batch.Models.WindowsConfiguration,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.DataDisk},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration : Microsoft.Azure.Management.Batch.Models.ImageReference * string * Microsoft.Azure.Management.Batch.Models.OSDisk * Microsoft.Azure.Management.Batch.Models.WindowsConfiguration * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt; * string -&gt; Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration" Usage="new Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration (imageReference, nodeAgentSkuId, osDisk, windowsConfiguration, dataDisks, licenseType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Batch.Models.ImageReference" />
        <Parameter Name="nodeAgentSkuId" Type="System.String" />
        <Parameter Name="osDisk" Type="Microsoft.Azure.Management.Batch.Models.OSDisk" />
        <Parameter Name="windowsConfiguration" Type="Microsoft.Azure.Management.Batch.Models.WindowsConfiguration" />
        <Parameter Name="dataDisks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt;" />
        <Parameter Name="licenseType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageReference">Ein Verweis auf das Marketplace-Image in Azure VMs oder des benutzerdefinierten Images des virtuellen Computers zu verwenden.</param>
        <param name="nodeAgentSkuId">Die SKU des Batch-Knoten-Agent auf bereitzustellenden Serverknoten im Pool.</param>
        <param name="osDisk">Einstellungen für den Betriebssystemdatenträger des virtuellen Computers.</param>
        <param name="windowsConfiguration">Windows-Betriebssystem-Einstellungen auf dem virtuellen Computer.</param>
        <param name="dataDisks">Die Konfiguration für Datenträger auf den Comptue-Knoten in den Pool zugeordnet.</param>
        <param name="licenseType">Der Typ des lokalen-Lizenz, um bei der Bereitstellung von Betriebssystemen verwendet werden.</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt; DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.DataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As IList(Of DataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataDisks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Konfiguration für Datenträger auf den Comptue-Knoten in den Pool zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft muss angegeben werden, wenn die Serverknoten im Pool leere Datenträger verbunden werden sollen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.ImageReference ImageReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.ImageReference ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageReference As ImageReference" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Management.Batch.Models.ImageReference with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.ImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="imageReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.ImageReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert einen Verweis auf das Marketplace-Image in Azure VMs oder des benutzerdefinierten Images des virtuellen Computers zu verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
    <Member MemberName="NodeAgentSkuId">
      <MemberSignature Language="C#" Value="public string NodeAgentSkuId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeAgentSkuId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.NodeAgentSkuId" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeAgentSkuId As String" />
      <MemberSignature Language="F#" Value="member this.NodeAgentSkuId : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.NodeAgentSkuId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeAgentSkuId")</AttributeName>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.OSDisk OsDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.OSDisk OsDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.OsDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property OsDisk As OSDisk" />
      <MemberSignature Language="F#" Value="member this.OsDisk : Microsoft.Azure.Management.Batch.Models.OSDisk with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.OsDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.OSDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Einstellungen für den Betriebssystemdatenträger des virtuellen Computers fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.WindowsConfiguration WindowsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.WindowsConfiguration WindowsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsConfiguration As WindowsConfiguration" />
      <MemberSignature Language="F#" Value="member this.WindowsConfiguration : Microsoft.Azure.Management.Batch.Models.WindowsConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="windowsConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.WindowsConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Einstellungen des Windows-Betriebssystems auf dem virtuellen Computer.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft muss nicht angegeben wird, wenn die ImageReference ein Linux-Betriebssystem-Image angibt.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>