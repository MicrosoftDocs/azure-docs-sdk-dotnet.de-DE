<Type Name="MetricSettings" FullName="Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings">
  <TypeSignature Language="C#" Value="public class MetricSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricSettings" />
  <TypeSignature Language="F#" Value="type MetricSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="67ffe-101">Teil des MultiTenantDiagnosticSettings.</span><span class="sxs-lookup"><span data-stu-id="67ffe-101">Part of MultiTenantDiagnosticSettings.</span></span> <span data-ttu-id="67ffe-102">Gibt die Einstellungen für eine bestimmte Metrik.</span><span class="sxs-lookup"><span data-stu-id="67ffe-102">Specifies the settings for a particular metric.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings.#ctor" />
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
            <span data-ttu-id="67ffe-103">Initialisiert eine neue Instanz der MetricSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="67ffe-103">Initializes a new instance of the MetricSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricSettings (bool enabled, Nullable&lt;TimeSpan&gt; timeGrain = null, string category = null, Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy retentionPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool enabled, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeGrain, string category, class Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy retentionPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings.#ctor(System.Boolean,System.Nullable{System.TimeSpan},System.String,Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings : bool * Nullable&lt;TimeSpan&gt; * string * Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy -&gt; Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings (enabled, timeGrain, category, retentionPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
        <Parameter Name="timeGrain" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="category" Type="System.String" />
        <Parameter Name="retentionPolicy" Type="Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy" />
      </Parameters>
      <Docs>
        <param name="enabled"><span data-ttu-id="67ffe-104">ein Wert, der angibt, ob diese Kategorie aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="67ffe-104">a value indicating whether this category is enabled.</span></span></param>
        <param name="timeGrain"><span data-ttu-id="67ffe-105">der timegrain-Wert der Metrik im ISO8601-Format.</span><span class="sxs-lookup"><span data-stu-id="67ffe-105">the timegrain of the metric in ISO8601 format.</span></span></param>
        <param name="category"><span data-ttu-id="67ffe-106">Namen einer Kategorie diagnostische Metrik wird für eine Ressource geben Sie diese Einstellung auf angewendet.</span><span class="sxs-lookup"><span data-stu-id="67ffe-106">Name of a Diagnostic Metric category for a resource type this setting is applied to.</span></span> <span data-ttu-id="67ffe-107">Um die Liste der Metrik-Diagnosekategorien für eine Ressource zu erhalten, führen Sie zuerst einen Abrufvorgang-diagnoseeinstellungen.</span><span class="sxs-lookup"><span data-stu-id="67ffe-107">To obtain the list of Diagnostic metric categories for a resource, first perform a GET diagnostic settings operation.</span></span></param>
        <param name="retentionPolicy"><span data-ttu-id="67ffe-108">die Aufbewahrungsrichtlinie für diese Kategorie.</span><span class="sxs-lookup"><span data-stu-id="67ffe-108">the retention policy for this category.</span></span></param>
        <summary>
            <span data-ttu-id="67ffe-109">Initialisiert eine neue Instanz der MetricSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="67ffe-109">Initializes a new instance of the MetricSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Category">
      <MemberSignature Language="C#" Value="public string Category { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Category" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings.Category" />
      <MemberSignature Language="VB.NET" Value="Public Property Category As String" />
      <MemberSignature Language="F#" Value="member this.Category : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings.Category" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="category")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ffe-110">Ruft ab oder legt Namen einer Kategorie diagnostische Metrik für einen Ressourcentyp, dem diese Einstellung angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="67ffe-110">Gets or sets name of a Diagnostic Metric category for a resource type this setting is applied to.</span></span> <span data-ttu-id="67ffe-111">Um die Liste der Metrik-Diagnosekategorien für eine Ressource zu erhalten, führen Sie zuerst einen Abrufvorgang-diagnoseeinstellungen.</span><span class="sxs-lookup"><span data-stu-id="67ffe-111">To obtain the list of Diagnostic metric categories for a resource, first perform a GET diagnostic settings operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public bool Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.Enabled : bool with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ffe-112">Ruft ab oder legt einen Wert, der angibt, ob diese Kategorie aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="67ffe-112">Gets or sets a value indicating whether this category is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy RetentionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy RetentionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings.RetentionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionPolicy As RetentionPolicy" />
      <MemberSignature Language="F#" Value="member this.RetentionPolicy : Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings.RetentionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ffe-113">Ruft ab oder legt die Aufbewahrungsrichtlinie für diese Kategorie.</span><span class="sxs-lookup"><span data-stu-id="67ffe-113">Gets or sets the retention policy for this category.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; TimeGrain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeGrain As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeGrain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ffe-114">Ruft ab oder legt der timegrain-Wert der Metrik im ISO8601-Format.</span><span class="sxs-lookup"><span data-stu-id="67ffe-114">Gets or sets the timegrain of the metric in ISO8601 format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="metricSettings.Validate " />
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
            <span data-ttu-id="67ffe-115">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="67ffe-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="67ffe-116">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="67ffe-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>