<Type Name="VirtualMachineScaleSetVMProfile" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetVMProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetVMProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetVMProfile" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetVMProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Beschreibt eine virtuelle Maschine Skalierung Satz virtuelle Maschine-Profil an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVMProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineScaleSetVMProfile-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVMProfile (Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile osProfile = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile storageProfile = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile networkProfile = null, Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile diagnosticsProfile = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile extensionProfile = null, string licenseType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile osProfile, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile storageProfile, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile networkProfile, class Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile diagnosticsProfile, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile extensionProfile, string licenseType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.#ctor(Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile,Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile * Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile (osProfile, storageProfile, networkProfile, diagnosticsProfile, extensionProfile, licenseType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="osProfile" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile" />
        <Parameter Name="storageProfile" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile" />
        <Parameter Name="networkProfile" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile" />
        <Parameter Name="diagnosticsProfile" Type="Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile" />
        <Parameter Name="extensionProfile" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile" />
        <Parameter Name="licenseType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="osProfile">Gibt die betriebssystemeinstellungen für die virtuellen Computer in der Menge der Skala an.</param>
        <param name="storageProfile">Gibt die speichereinstellungen für den Datenträger des virtuellen Computers an.</param>
        <param name="networkProfile">Gibt Eigenschaften der Netzwerkschnittstellen der virtuellen Computer in der Menge der Skala an.</param>
        <param name="diagnosticsProfile">Gibt den Status der Boot-diagnoseeinstellungen. &lt;Brasilien&gt;&lt;Br&gt;-api-Mindestversion: 2015-06-15.</param>
        <param name="extensionProfile">Gibt eine Auflistung von Einstellungen für Erweiterungen auf virtuellen Computern in der Skalierungsgruppe installiert.</param>
        <param name="licenseType">Gibt an, dass das Image oder Datenträger, der verwendet wird lizenzierte lokalen war. Dieses Element wird nur für Bilder verwendet, die das Betriebssystem Windows Server enthalten.
            &lt;Brasilien&gt;&lt;Br&gt; folgende Werte sind möglich: &lt;Br&gt;&lt;Br&gt; "windows_client" &lt;Br&gt;&lt;Br&gt; Windows_Server &lt;Br&gt;&lt;Br&gt; Wenn dieses Element in einer Anforderung für ein Update enthalten ist, muss der Wert den ursprünglichen Wert übereinstimmen. Dieser Wert kann nicht aktualisiert werden. &lt;Brasilien&gt;&lt;Br&gt; Weitere Informationen finden Sie unter [Azure Hybrid verwenden Vorteil für Windows Server](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;Br&gt;&lt;Br&gt; Minimum API-Version: 2015-06-15</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineScaleSetVMProfile-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile DiagnosticsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile DiagnosticsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.DiagnosticsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property DiagnosticsProfile As DiagnosticsProfile" />
      <MemberSignature Language="F#" Value="member this.DiagnosticsProfile : Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.DiagnosticsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diagnosticsProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an die diagnoseeinstellungen Startzustands, ruft ab oder legt ihn fest.
            &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Api-Mindestversion: 2015-06-15.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtensionProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile ExtensionProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile ExtensionProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.ExtensionProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtensionProfile As VirtualMachineScaleSetExtensionProfile" />
      <MemberSignature Language="F#" Value="member this.ExtensionProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.ExtensionProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extensionProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt eine Auflistung von Einstellungen für Erweiterungen auf virtuellen Computern in der Skalierungsgruppe installiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt ihn fest gibt an, dass das Image oder Datenträger, der verwendet wird lizenzierte lokalen war. Dieses Element wird nur für Bilder verwendet, die das Betriebssystem Windows Server enthalten.
            &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Mögliche Werte sind: &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; "Windows_client" &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Windows_Server &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Wenn dieses Element in einer Anforderung für ein Update enthalten ist, muss der Wert den ursprünglichen Wert übereinstimmen.
            Dieser Wert kann nicht aktualisiert werden. &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Weitere Informationen finden Sie unter [Azure Hybrid verwenden Vorteil für Windows Server](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Api-Mindestversion: 2015-06-15
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile NetworkProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile NetworkProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.NetworkProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkProfile As VirtualMachineScaleSetNetworkProfile" />
      <MemberSignature Language="F#" Value="member this.NetworkProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.NetworkProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt Eigenschaften der Netzwerkschnittstellen der virtuellen Computer in der Menge der Skala an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile OsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile OsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.OsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property OsProfile As VirtualMachineScaleSetOSProfile" />
      <MemberSignature Language="F#" Value="member this.OsProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.OsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die betriebssystemeinstellungen für die virtuellen Computer in der Menge der Skala an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile StorageProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile StorageProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.StorageProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageProfile As VirtualMachineScaleSetStorageProfile" />
      <MemberSignature Language="F#" Value="member this.StorageProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.StorageProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die speichereinstellungen für den Datenträger des virtuellen Computers an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetVMProfile.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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