<Type Name="LogSettings" FullName="Microsoft.Azure.Management.Monitor.Management.Models.LogSettings">
  <TypeSignature Language="C#" Value="public class LogSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LogSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.LogSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class LogSettings" />
  <TypeSignature Language="F#" Value="type LogSettings = class" />
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
            <span data-ttu-id="83c09-101">Teil des MultiTenantDiagnosticSettings.</span><span class="sxs-lookup"><span data-stu-id="83c09-101">Part of MultiTenantDiagnosticSettings.</span></span> <span data-ttu-id="83c09-102">Gibt die Einstellungen für ein bestimmtes Protokoll.</span><span class="sxs-lookup"><span data-stu-id="83c09-102">Specifies the settings for a particular log.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LogSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LogSettings.#ctor" />
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
            <span data-ttu-id="83c09-103">Initialisiert eine neue Instanz der LogSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="83c09-103">Initializes a new instance of the LogSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LogSettings (bool enabled, string category = null, Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy retentionPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool enabled, string category, class Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy retentionPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LogSettings.#ctor(System.Boolean,System.String,Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.LogSettings : bool * string * Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy -&gt; Microsoft.Azure.Management.Monitor.Management.Models.LogSettings" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.LogSettings (enabled, category, retentionPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
        <Parameter Name="category" Type="System.String" />
        <Parameter Name="retentionPolicy" Type="Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy" />
      </Parameters>
      <Docs>
        <param name="enabled"><span data-ttu-id="83c09-104">ein Wert, der angibt, ob dieses Protokoll aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="83c09-104">a value indicating whether this log is enabled.</span></span></param>
        <param name="category"><span data-ttu-id="83c09-105">Namen einer Kategorie Diagnoseprotokolls wird für eine Ressource geben Sie diese Einstellung auf angewendet.</span><span class="sxs-lookup"><span data-stu-id="83c09-105">Name of a Diagnostic Log category for a resource type this setting is applied to.</span></span> <span data-ttu-id="83c09-106">Um die Liste der Diagnoseprotokollkategorien für eine Ressource zu erhalten, führen Sie zuerst einen GET-Vorgang zum Abrufen von Diagnoseeinstellungen aus.</span><span class="sxs-lookup"><span data-stu-id="83c09-106">To obtain the list of Diagnostic Log categories for a resource, first perform a GET diagnostic settings operation.</span></span></param>
        <param name="retentionPolicy"><span data-ttu-id="83c09-107">die Aufbewahrungsrichtlinie für dieses Protokoll.</span><span class="sxs-lookup"><span data-stu-id="83c09-107">the retention policy for this log.</span></span></param>
        <summary>
            <span data-ttu-id="83c09-108">Initialisiert eine neue Instanz der LogSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="83c09-108">Initializes a new instance of the LogSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Category">
      <MemberSignature Language="C#" Value="public string Category { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Category" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogSettings.Category" />
      <MemberSignature Language="VB.NET" Value="Public Property Category As String" />
      <MemberSignature Language="F#" Value="member this.Category : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogSettings.Category" />
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
            <span data-ttu-id="83c09-109">Ruft ab oder legt Namen einer Kategorie Diagnoseprotokolls für einen Ressourcentyp, dem diese Einstellung angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="83c09-109">Gets or sets name of a Diagnostic Log category for a resource type this setting is applied to.</span></span> <span data-ttu-id="83c09-110">Um die Liste der Diagnoseprotokollkategorien für eine Ressource zu erhalten, führen Sie zuerst einen GET-Vorgang zum Abrufen von Diagnoseeinstellungen aus.</span><span class="sxs-lookup"><span data-stu-id="83c09-110">To obtain the list of Diagnostic Log categories for a resource, first perform a GET diagnostic settings operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public bool Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogSettings.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.Enabled : bool with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogSettings.Enabled" />
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
            <span data-ttu-id="83c09-111">Ruft ab oder legt einen Wert, der angibt, ob dieses Protokoll aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="83c09-111">Gets or sets a value indicating whether this log is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy RetentionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy RetentionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogSettings.RetentionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionPolicy As RetentionPolicy" />
      <MemberSignature Language="F#" Value="member this.RetentionPolicy : Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogSettings.RetentionPolicy" />
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
            <span data-ttu-id="83c09-112">Ruft ab oder legt die Aufbewahrungsrichtlinie für dieses Protokoll.</span><span class="sxs-lookup"><span data-stu-id="83c09-112">Gets or sets the retention policy for this log.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LogSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="logSettings.Validate " />
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
            <span data-ttu-id="83c09-113">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="83c09-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="83c09-114">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="83c09-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>