<Type Name="SecuritySettings" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings">
  <TypeSignature Language="C#" Value="public class SecuritySettings : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecuritySettings extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings" />
  <TypeSignature Language="VB.NET" Value="Public Class SecuritySettings&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type SecuritySettings = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="35cf4-101">Die Sicherheitseinstellungen für ein Gerät.</span><span class="sxs-lookup"><span data-stu-id="35cf4-101">The security settings of a device.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecuritySettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="35cf4-102">Initialisiert eine neue Instanz der SecuritySettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="35cf4-102">Initializes a new instance of the SecuritySettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecuritySettings (Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings remoteManagementSettings, Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings chapSettings, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings remoteManagementSettings, class Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings chapSettings, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings,Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings : Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings * Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings (remoteManagementSettings, chapSettings, id, name, type, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="remoteManagementSettings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings" />
        <Parameter Name="chapSettings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
      </Parameters>
      <Docs>
        <param name="remoteManagementSettings"><span data-ttu-id="35cf4-103">Die Einstellungen für die Remoteverwaltung eines Geräts.</span><span class="sxs-lookup"><span data-stu-id="35cf4-103">The settings for remote management of a device.</span></span></param>
        <param name="chapSettings"><span data-ttu-id="35cf4-104">Die Einstellungen des Challenge Handshake Authentication-Protokoll (CHAP).</span><span class="sxs-lookup"><span data-stu-id="35cf4-104">The Challenge-Handshake Authentication Protocol (CHAP) settings.</span></span></param>
        <param name="id"><span data-ttu-id="35cf4-105">Die Pfad-ID, die das Objekt eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="35cf4-105">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="35cf4-106">Der Name des Objekts.</span><span class="sxs-lookup"><span data-stu-id="35cf4-106">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="35cf4-107">Der hierarchische Typ des Objekts.</span><span class="sxs-lookup"><span data-stu-id="35cf4-107">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="35cf4-108">Die Art des Objekts.</span><span class="sxs-lookup"><span data-stu-id="35cf4-108">The Kind of the object.</span></span> <span data-ttu-id="35cf4-109">Derzeit wird nur Series8000 wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="35cf4-109">Currently only Series8000 is supported.</span></span> <span data-ttu-id="35cf4-110">Folgende Werte sind möglich: "Series8000"</span><span class="sxs-lookup"><span data-stu-id="35cf4-110">Possible values include: 'Series8000'</span></span></param>
        <summary>
            <span data-ttu-id="35cf4-111">Initialisiert eine neue Instanz der SecuritySettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="35cf4-111">Initializes a new instance of the SecuritySettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChapSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings ChapSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings ChapSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings.ChapSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ChapSettings As ChapSettings" />
      <MemberSignature Language="F#" Value="member this.ChapSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings.ChapSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.chapSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35cf4-112">Ruft ab oder legt die Einstellungen des Challenge Handshake Authentication-Protokoll (CHAP) fest.</span><span class="sxs-lookup"><span data-stu-id="35cf4-112">Gets or sets the Challenge-Handshake Authentication Protocol (CHAP) settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteManagementSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings RemoteManagementSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings RemoteManagementSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings.RemoteManagementSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteManagementSettings As RemoteManagementSettings" />
      <MemberSignature Language="F#" Value="member this.RemoteManagementSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings.RemoteManagementSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.remoteManagementSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35cf4-113">Ruft ab oder legt die Einstellungen für die Remoteverwaltung eines Geräts fest.</span><span class="sxs-lookup"><span data-stu-id="35cf4-113">Gets or sets the settings for remote management of a device.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="securitySettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="35cf4-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="35cf4-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="35cf4-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="35cf4-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>