<Type Name="VirtualMachineExtension" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension">
  <TypeSignature Language="C#" Value="public class VirtualMachineExtension : Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineExtension extends Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineExtension&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualMachineExtension = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="59c7f-101">Beschreibt eine Erweiterung des virtuellen Computers an.</span><span class="sxs-lookup"><span data-stu-id="59c7f-101">Describes a Virtual Machine Extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineExtension ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.#ctor" />
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
            <span data-ttu-id="59c7f-102">Initialisiert eine neue Instanz der VirtualMachineExtension-Klasse.</span><span class="sxs-lookup"><span data-stu-id="59c7f-102">Initializes a new instance of the VirtualMachineExtension class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineExtension (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string forceUpdateTag = null, string publisher = null, string virtualMachineExtensionType = null, string typeHandlerVersion = null, Nullable&lt;bool&gt; autoUpgradeMinorVersion = null, object settings = null, object protectedSettings = null, string provisioningState = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView instanceView = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string forceUpdateTag, string publisher, string virtualMachineExtensionType, string typeHandlerVersion, valuetype System.Nullable`1&lt;bool&gt; autoUpgradeMinorVersion, object settings, object protectedSettings, string provisioningState, class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView instanceView) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Object,System.Object,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional forceUpdateTag As String = null, Optional publisher As String = null, Optional virtualMachineExtensionType As String = null, Optional typeHandlerVersion As String = null, Optional autoUpgradeMinorVersion As Nullable(Of Boolean) = null, Optional settings As Object = null, Optional protectedSettings As Object = null, Optional provisioningState As String = null, Optional instanceView As VirtualMachineExtensionInstanceView = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * string * string * Nullable&lt;bool&gt; * obj * obj * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension (location, id, name, type, tags, forceUpdateTag, publisher, virtualMachineExtensionType, typeHandlerVersion, autoUpgradeMinorVersion, settings, protectedSettings, provisioningState, instanceView)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="forceUpdateTag" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="virtualMachineExtensionType" Type="System.String" />
        <Parameter Name="typeHandlerVersion" Type="System.String" />
        <Parameter Name="autoUpgradeMinorVersion" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="settings" Type="System.Object" />
        <Parameter Name="protectedSettings" Type="System.Object" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="instanceView" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="59c7f-103">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="59c7f-103">Resource location</span></span></param>
        <param name="id"><span data-ttu-id="59c7f-104">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="59c7f-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="59c7f-105">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="59c7f-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="59c7f-106">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="59c7f-106">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="59c7f-107">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="59c7f-107">Resource tags</span></span></param>
        <param name="forceUpdateTag"><span data-ttu-id="59c7f-108">Wie der Erweiterungshandler erzwungen werden soll, zu aktualisieren, auch wenn die Konfiguration der Erweiterung nicht geändert hat.</span><span class="sxs-lookup"><span data-stu-id="59c7f-108">How the extension handler should be forced to update even if the extension configuration has not changed.</span></span></param>
        <param name="publisher"><span data-ttu-id="59c7f-109">Der Name des Verlegers der Handler.</span><span class="sxs-lookup"><span data-stu-id="59c7f-109">The name of the extension handler publisher.</span></span></param>
        <param name="virtualMachineExtensionType"><span data-ttu-id="59c7f-110">Gibt den Typ der Erweiterung an. Ein Beispiel ist "CustomScriptExtension".</span><span class="sxs-lookup"><span data-stu-id="59c7f-110">Specifies the type of the extension; an example is "CustomScriptExtension".</span></span></param>
        <param name="typeHandlerVersion"><span data-ttu-id="59c7f-111">Gibt die Version des Skript-Handlers.</span><span class="sxs-lookup"><span data-stu-id="59c7f-111">Specifies the version of the script handler.</span></span></param>
        <param name="autoUpgradeMinorVersion"><span data-ttu-id="59c7f-112">Gibt an, ob die Erweiterung auf eine neuere Nebenversion verwenden soll, wenn eine zum Zeitpunkt der Bereitstellung verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="59c7f-112">Indicates whether the extension should use a newer minor version if one is available at deployment time.</span></span> <span data-ttu-id="59c7f-113">Nach der Bereitstellung wird jedoch die Erweiterung nicht Nebenversionen aktualisiert, sofern bereitgestellt, selbst bei dieser Eigenschaft auf True festgelegt.</span><span class="sxs-lookup"><span data-stu-id="59c7f-113">Once deployed, however, the extension will not upgrade minor versions unless redeployed, even with this property set to true.</span></span></param>
        <param name="settings"><span data-ttu-id="59c7f-114">Public-Einstellungen für die Erweiterung im JSON-Format.</span><span class="sxs-lookup"><span data-stu-id="59c7f-114">Json formatted public settings for the extension.</span></span></param>
        <param name="protectedSettings"><span data-ttu-id="59c7f-115">Die Erweiterung kann ProtectedSettings oder ProtectedSettingsFromKeyVault oder gar keine geschützten Einstellungen enthalten.</span><span class="sxs-lookup"><span data-stu-id="59c7f-115">The extension can contain either protectedSettings or protectedSettingsFromKeyVault or no protected settings at all.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="59c7f-116">Der Bereitstellungsstatus, die nur in der Antwort angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="59c7f-116">The provisioning state, which only appears in the response.</span></span></param>
        <param name="instanceView"><span data-ttu-id="59c7f-117">Die virtuelle Maschine Erweiterung Instanzansicht.</span><span class="sxs-lookup"><span data-stu-id="59c7f-117">The virtual machine extension instance view.</span></span></param>
        <summary>
            <span data-ttu-id="59c7f-118">Initialisiert eine neue Instanz der VirtualMachineExtension-Klasse.</span><span class="sxs-lookup"><span data-stu-id="59c7f-118">Initializes a new instance of the VirtualMachineExtension class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoUpgradeMinorVersion">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoUpgradeMinorVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoUpgradeMinorVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.AutoUpgradeMinorVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoUpgradeMinorVersion As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoUpgradeMinorVersion : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.AutoUpgradeMinorVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoUpgradeMinorVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59c7f-119">Gibt an, ob die Erweiterung auf eine neuere Nebenversion verwenden soll, wenn eine zum Zeitpunkt der Bereitstellung verfügbar ist, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="59c7f-119">Gets or sets indicates whether the extension should use a newer minor version if one is available at deployment time.</span></span> <span data-ttu-id="59c7f-120">Nach der Bereitstellung wird jedoch die Erweiterung nicht Nebenversionen aktualisiert, sofern bereitgestellt, selbst bei dieser Eigenschaft auf True festgelegt.</span><span class="sxs-lookup"><span data-stu-id="59c7f-120">Once deployed, however, the extension will not upgrade minor versions unless redeployed, even with this property set to true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceUpdateTag">
      <MemberSignature Language="C#" Value="public string ForceUpdateTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForceUpdateTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.ForceUpdateTag" />
      <MemberSignature Language="VB.NET" Value="Public Property ForceUpdateTag As String" />
      <MemberSignature Language="F#" Value="member this.ForceUpdateTag : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.ForceUpdateTag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.forceUpdateTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59c7f-121">Ruft ab oder legt sie fest, wie der Erweiterungshandler erzwungen werden soll, zu aktualisieren, auch wenn die Konfiguration der Erweiterung nicht geändert hat.</span><span class="sxs-lookup"><span data-stu-id="59c7f-121">Gets or sets how the extension handler should be forced to update even if the extension configuration has not changed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceView">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView InstanceView { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView InstanceView" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.InstanceView" />
      <MemberSignature Language="VB.NET" Value="Public Property InstanceView As VirtualMachineExtensionInstanceView" />
      <MemberSignature Language="F#" Value="member this.InstanceView : Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.InstanceView" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.instanceView")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59c7f-122">Ruft ab oder legt die Instanzansicht für VM-Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="59c7f-122">Gets or sets the virtual machine extension instance view.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedSettings">
      <MemberSignature Language="C#" Value="public object ProtectedSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ProtectedSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.ProtectedSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedSettings As Object" />
      <MemberSignature Language="F#" Value="member this.ProtectedSettings : obj with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.ProtectedSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.protectedSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59c7f-123">Ruft ab oder legt die Erweiterung ProtectedSettings oder ProtectedSettingsFromKeyVault oder gar keine geschützten Einstellungen enthalten können.</span><span class="sxs-lookup"><span data-stu-id="59c7f-123">Gets or sets the extension can contain either protectedSettings or protectedSettingsFromKeyVault or no protected settings at all.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59c7f-124">Ruft den Status der Bereitstellung, die nur in der Antwort angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="59c7f-124">Gets the provisioning state, which only appears in the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.Publisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publisher")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59c7f-125">Ruft ab oder legt den Namen des Verlegers der Handler fest.</span><span class="sxs-lookup"><span data-stu-id="59c7f-125">Gets or sets the name of the extension handler publisher.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public object Settings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.Settings" />
      <MemberSignature Language="VB.NET" Value="Public Property Settings As Object" />
      <MemberSignature Language="F#" Value="member this.Settings : obj with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.settings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59c7f-126">Abrufen oder Festlegen der Json-formatierte public-Einstellungen für die Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="59c7f-126">Gets or sets json formatted public settings for the extension.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeHandlerVersion">
      <MemberSignature Language="C#" Value="public string TypeHandlerVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TypeHandlerVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.TypeHandlerVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property TypeHandlerVersion As String" />
      <MemberSignature Language="F#" Value="member this.TypeHandlerVersion : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.TypeHandlerVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.typeHandlerVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59c7f-127">Ruft ab oder legt gibt die Version des Handlers Skript an.</span><span class="sxs-lookup"><span data-stu-id="59c7f-127">Gets or sets specifies the version of the script handler.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="virtualMachineExtension.Validate " />
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
            <span data-ttu-id="59c7f-128">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="59c7f-128">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="59c7f-129">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="59c7f-129">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineExtensionType">
      <MemberSignature Language="C#" Value="public string VirtualMachineExtensionType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineExtensionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.VirtualMachineExtensionType" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineExtensionType As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineExtensionType : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension.VirtualMachineExtensionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59c7f-130">Ruft ab oder legt gibt den Typ der Erweiterung an. Ein Beispiel ist "CustomScriptExtension".</span><span class="sxs-lookup"><span data-stu-id="59c7f-130">Gets or sets specifies the type of the extension; an example is "CustomScriptExtension".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>