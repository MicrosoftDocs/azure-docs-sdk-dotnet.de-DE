<Type Name="AutoscaleSettingResourcePatch" FullName="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch">
  <TypeSignature Language="C#" Value="public class AutoscaleSettingResourcePatch" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoscaleSettingResourcePatch extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoscaleSettingResourcePatch" />
  <TypeSignature Language="F#" Value="type AutoscaleSettingResourcePatch = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="4990c-101">Die automatische Skalierung-Einstellungsobjekt für Patch-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="4990c-101">The autoscale setting object for patch operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoscaleSettingResourcePatch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4990c-102">Initialisiert eine neue Instanz der AutoscaleSettingResourcePatch-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4990c-102">Initializes a new instance of the AutoscaleSettingResourcePatch class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoscaleSettingResourcePatch (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; profiles, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; notifications = null, Nullable&lt;bool&gt; enabled = null, string name = null, string targetResourceUri = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; profiles, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; notifications, valuetype System.Nullable`1&lt;bool&gt; enabled, string name, string targetResourceUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile},System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification},System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (profiles As IList(Of AutoscaleProfile), Optional tags As IDictionary(Of String, String) = null, Optional notifications As IList(Of AutoscaleNotification) = null, Optional enabled As Nullable(Of Boolean) = null, Optional name As String = null, Optional targetResourceUri As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; * Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch (profiles, tags, notifications, enabled, name, targetResourceUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="profiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt;" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="notifications" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="targetResourceUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="profiles"><span data-ttu-id="4990c-103">die Auflistung der automatischen skalierungsprofile, die verschiedene Skalierungsparameter für unterschiedliche Zeiträume angeben.</span><span class="sxs-lookup"><span data-stu-id="4990c-103">the collection of automatic scaling profiles that specify different scaling parameters for different time periods.</span></span> <span data-ttu-id="4990c-104">Es kann maximal 20 Profile angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="4990c-104">A maximum of 20 profiles can be specified.</span></span></param>
        <param name="tags"><span data-ttu-id="4990c-105">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="4990c-105">Resource tags</span></span></param>
        <param name="notifications"><span data-ttu-id="4990c-106">die Auflistung von Benachrichtigungen.</span><span class="sxs-lookup"><span data-stu-id="4990c-106">the collection of notifications.</span></span></param>
        <param name="enabled"><span data-ttu-id="4990c-107">das Kennzeichen "enabled".</span><span class="sxs-lookup"><span data-stu-id="4990c-107">the enabled flag.</span></span> <span data-ttu-id="4990c-108">Gibt an, ob die automatische Skalierung für die Ressource aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="4990c-108">Specifies whether automatic scaling is enabled for the resource.</span></span> <span data-ttu-id="4990c-109">Der Standardwert ist 'true'.</span><span class="sxs-lookup"><span data-stu-id="4990c-109">The default value is 'true'.</span></span></param>
        <param name="name"><span data-ttu-id="4990c-110">der Name der automatischen skalierungseinstellung.</span><span class="sxs-lookup"><span data-stu-id="4990c-110">the name of the autoscale setting.</span></span></param>
        <param name="targetResourceUri"><span data-ttu-id="4990c-111">Der Ressourcenbezeichner der Ressource, der die skalierungseinstellung zur automatischen hinzugefügt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="4990c-111">the resource identifier of the resource that the autoscale setting should be added to.</span></span></param>
        <summary>
            <span data-ttu-id="4990c-112">Initialisiert eine neue Instanz der AutoscaleSettingResourcePatch-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4990c-112">Initializes a new instance of the AutoscaleSettingResourcePatch class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4990c-113">Ruft ab oder legt das Kennzeichen "enabled".</span><span class="sxs-lookup"><span data-stu-id="4990c-113">Gets or sets the enabled flag.</span></span> <span data-ttu-id="4990c-114">Gibt an, ob die automatische Skalierung für die Ressource aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="4990c-114">Specifies whether automatic scaling is enabled for the resource.</span></span> <span data-ttu-id="4990c-115">Der Standardwert ist 'true'.</span><span class="sxs-lookup"><span data-stu-id="4990c-115">The default value is 'true'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4990c-116">Ruft ab oder legt den Namen für die automatische Skalierung.</span><span class="sxs-lookup"><span data-stu-id="4990c-116">Gets or sets the name of the autoscale setting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Notifications">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; Notifications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; Notifications" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Notifications" />
      <MemberSignature Language="VB.NET" Value="Public Property Notifications As IList(Of AutoscaleNotification)" />
      <MemberSignature Language="F#" Value="member this.Notifications : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Notifications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.notifications")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4990c-117">Ruft ab oder legt die Auflistung von Benachrichtigungen.</span><span class="sxs-lookup"><span data-stu-id="4990c-117">Gets or sets the collection of notifications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Profiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; Profiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; Profiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Profiles" />
      <MemberSignature Language="VB.NET" Value="Public Property Profiles As IList(Of AutoscaleProfile)" />
      <MemberSignature Language="F#" Value="member this.Profiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Profiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.profiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4990c-118">Ruft ab oder legt die Auflistung der automatischen skalierungsprofile, die verschiedene Skalierungsparameter für unterschiedliche Zeiträume angeben.</span><span class="sxs-lookup"><span data-stu-id="4990c-118">Gets or sets the collection of automatic scaling profiles that specify different scaling parameters for different time periods.</span></span> <span data-ttu-id="4990c-119">Es kann maximal 20 Profile angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="4990c-119">A maximum of 20 profiles can be specified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4990c-120">Ruft ab oder legt ihn fest Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="4990c-120">Gets or sets resource tags</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceUri">
      <MemberSignature Language="C#" Value="public string TargetResourceUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.TargetResourceUri" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceUri As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceUri : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.TargetResourceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetResourceUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4990c-121">Ruft ab oder legt den Ressourcenbezeichner der Ressource, der die skalierungseinstellung zur automatischen hinzugefügt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="4990c-121">Gets or sets the resource identifier of the resource that the autoscale setting should be added to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="autoscaleSettingResourcePatch.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4990c-122">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="4990c-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4990c-123">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="4990c-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>