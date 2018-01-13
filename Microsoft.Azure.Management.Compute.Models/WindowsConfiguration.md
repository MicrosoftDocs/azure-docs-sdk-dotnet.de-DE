<Type Name="WindowsConfiguration" FullName="Microsoft.Azure.Management.Compute.Models.WindowsConfiguration">
  <TypeSignature Language="C#" Value="public class WindowsConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WindowsConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.WindowsConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class WindowsConfiguration" />
  <TypeSignature Language="F#" Value="type WindowsConfiguration = class" />
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
            <span data-ttu-id="44c45-101">Gibt die Einstellungen des Windows-Betriebssystems auf dem virtuellen Computer an.</span><span class="sxs-lookup"><span data-stu-id="44c45-101">Specifies Windows operating system settings on the virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.WindowsConfiguration.#ctor" />
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
            <span data-ttu-id="44c45-102">Initialisiert eine neue Instanz der WindowsConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="44c45-102">Initializes a new instance of the WindowsConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsConfiguration (Nullable&lt;bool&gt; provisionVMAgent = null, Nullable&lt;bool&gt; enableAutomaticUpdates = null, string timeZone = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent&gt; additionalUnattendContent = null, Microsoft.Azure.Management.Compute.Models.WinRMConfiguration winRM = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; provisionVMAgent, valuetype System.Nullable`1&lt;bool&gt; enableAutomaticUpdates, string timeZone, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent&gt; additionalUnattendContent, class Microsoft.Azure.Management.Compute.Models.WinRMConfiguration winRM) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.WindowsConfiguration.#ctor(System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent},Microsoft.Azure.Management.Compute.Models.WinRMConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional provisionVMAgent As Nullable(Of Boolean) = null, Optional enableAutomaticUpdates As Nullable(Of Boolean) = null, Optional timeZone As String = null, Optional additionalUnattendContent As IList(Of AdditionalUnattendContent) = null, Optional winRM As WinRMConfiguration = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.WindowsConfiguration : Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent&gt; * Microsoft.Azure.Management.Compute.Models.WinRMConfiguration -&gt; Microsoft.Azure.Management.Compute.Models.WindowsConfiguration" Usage="new Microsoft.Azure.Management.Compute.Models.WindowsConfiguration (provisionVMAgent, enableAutomaticUpdates, timeZone, additionalUnattendContent, winRM)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provisionVMAgent" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableAutomaticUpdates" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="timeZone" Type="System.String" />
        <Parameter Name="additionalUnattendContent" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent&gt;" />
        <Parameter Name="winRM" Type="Microsoft.Azure.Management.Compute.Models.WinRMConfiguration" />
      </Parameters>
      <Docs>
        <param name="provisionVMAgent"><span data-ttu-id="44c45-103">Gibt an, ob die VM-Agent auf dem virtuellen Computer bereitgestellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="44c45-103">Indicates whether virtual machine agent should be provisioned on the virtual machine.</span></span>
            <span data-ttu-id="44c45-104">&lt;Brasilien&gt;&lt;Br&gt; Wenn diese Eigenschaft nicht im Anforderungstext angegeben wird, wird standardmäßig auf "true" festlegen.</span><span class="sxs-lookup"><span data-stu-id="44c45-104">&lt;br&gt;&lt;br&gt; When this property is not specified in the request body, default behavior is to set it to true.</span></span>  <span data-ttu-id="44c45-105">Dadurch wird sichergestellt, dass VM-Agent auf dem virtuellen Computer installiert ist, sodass Erweiterungen können später mit dem virtuellen Computer hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="44c45-105">This will ensure that VM Agent is installed on the VM so that extensions can be added to the VM later.</span></span></param>
        <param name="enableAutomaticUpdates"><span data-ttu-id="44c45-106">Gibt an, ob die virtuelle Maschine für automatische Updates aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="44c45-106">Indicates whether virtual machine is enabled for automatic updates.</span></span></param>
        <param name="timeZone"><span data-ttu-id="44c45-107">Gibt die Zeitzone des virtuellen Computers an.</span><span class="sxs-lookup"><span data-stu-id="44c45-107">Specifies the time zone of the virtual machine.</span></span> <span data-ttu-id="44c45-108">Z. B. "Pacific Standard Time"</span><span class="sxs-lookup"><span data-stu-id="44c45-108">e.g. "Pacific Standard Time"</span></span></param>
        <param name="additionalUnattendContent"><span data-ttu-id="44c45-109">Base64-codierte XML-Format gibt zusätzliche Informationen an, die in der Datei "Unattend.xml" aufgenommen werden kann, die von Windows Setup verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="44c45-109">Specifies additional base-64 encoded XML formatted information that can be included in the Unattend.xml file, which is used by Windows Setup.</span></span></param>
        <param name="winRM"><span data-ttu-id="44c45-110">Gibt die Windows-Remoteverwaltung-Listener an.</span><span class="sxs-lookup"><span data-stu-id="44c45-110">Specifies the Windows Remote Management listeners.</span></span> <span data-ttu-id="44c45-111">Dadurch können remote-Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="44c45-111">This enables remote Windows PowerShell.</span></span></param>
        <summary>
            <span data-ttu-id="44c45-112">Initialisiert eine neue Instanz der WindowsConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="44c45-112">Initializes a new instance of the WindowsConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalUnattendContent">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent&gt; AdditionalUnattendContent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent&gt; AdditionalUnattendContent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.WindowsConfiguration.AdditionalUnattendContent" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalUnattendContent As IList(Of AdditionalUnattendContent)" />
      <MemberSignature Language="F#" Value="member this.AdditionalUnattendContent : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.WindowsConfiguration.AdditionalUnattendContent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="additionalUnattendContent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44c45-113">Ruft ab oder legt gibt zusätzliche Base-64-codierte XML-Format Informationen, die in der Datei "Unattend.xml" aufgenommen werden kann, die von Windows Setup verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="44c45-113">Gets or sets specifies additional base-64 encoded XML formatted information that can be included in the Unattend.xml file, which is used by Windows Setup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutomaticUpdates">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableAutomaticUpdates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableAutomaticUpdates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.WindowsConfiguration.EnableAutomaticUpdates" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableAutomaticUpdates As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableAutomaticUpdates : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.WindowsConfiguration.EnableAutomaticUpdates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableAutomaticUpdates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44c45-114">Gibt an, ob die virtuelle Maschine für automatische Updates aktiviert ist, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="44c45-114">Gets or sets indicates whether virtual machine is enabled for automatic updates.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisionVMAgent">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ProvisionVMAgent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ProvisionVMAgent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.WindowsConfiguration.ProvisionVMAgent" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisionVMAgent As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ProvisionVMAgent : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.WindowsConfiguration.ProvisionVMAgent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provisionVMAgent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44c45-115">Ruft ab oder legt ihn fest gibt an, ob die VM-Agent auf dem virtuellen Computer bereitgestellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="44c45-115">Gets or sets indicates whether virtual machine agent should be provisioned on the virtual machine.</span></span>
            <span data-ttu-id="44c45-116">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Wenn diese Eigenschaft nicht im Anforderungstext angegeben wird, ist standardmäßig auf "true" festlegen.</span><span class="sxs-lookup"><span data-stu-id="44c45-116">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; When this property is not specified in the request body, default behavior is to set it to true.</span></span>  <span data-ttu-id="44c45-117">Dadurch wird sichergestellt, dass VM-Agent auf dem virtuellen Computer installiert ist, sodass Erweiterungen können später mit dem virtuellen Computer hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="44c45-117">This will ensure that VM Agent is installed on the VM so that extensions can be added to the VM later.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeZone">
      <MemberSignature Language="C#" Value="public string TimeZone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.WindowsConfiguration.TimeZone" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeZone As String" />
      <MemberSignature Language="F#" Value="member this.TimeZone : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.WindowsConfiguration.TimeZone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeZone")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44c45-118">Ruft ab oder legt gibt die Zeitzone des virtuellen Computers an.</span><span class="sxs-lookup"><span data-stu-id="44c45-118">Gets or sets specifies the time zone of the virtual machine.</span></span> <span data-ttu-id="44c45-119">Z. B. "Pacific Standard Time"</span><span class="sxs-lookup"><span data-stu-id="44c45-119">e.g. "Pacific Standard Time"</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WinRM">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.WinRMConfiguration WinRM { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.WinRMConfiguration WinRM" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.WindowsConfiguration.WinRM" />
      <MemberSignature Language="VB.NET" Value="Public Property WinRM As WinRMConfiguration" />
      <MemberSignature Language="F#" Value="member this.WinRM : Microsoft.Azure.Management.Compute.Models.WinRMConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Models.WindowsConfiguration.WinRM" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="winRM")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.WinRMConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44c45-120">Gibt an die Windows-Remoteverwaltung-Listener, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="44c45-120">Gets or sets specifies the Windows Remote Management listeners.</span></span>
            <span data-ttu-id="44c45-121">Dadurch können remote-Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="44c45-121">This enables remote Windows PowerShell.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>