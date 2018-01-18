<Type Name="EncryptionSettings" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings">
  <TypeSignature Language="C#" Value="public class EncryptionSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EncryptionSettings extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class EncryptionSettings&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type EncryptionSettings = class&#xA;    inherit BaseModel" />
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
            <span data-ttu-id="2ad17-101">die verschlüsselungseinstellungen.</span><span class="sxs-lookup"><span data-stu-id="2ad17-101">The encryption settings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2ad17-102">Initialisiert eine neue Instanz der EncryptionSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2ad17-102">Initializes a new instance of the EncryptionSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionSettings (Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus encryptionStatus, Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus keyRolloverStatus, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus encryptionStatus, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus keyRolloverStatus, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus,Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus * Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings (encryptionStatus, keyRolloverStatus, id, name, type, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="encryptionStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus" />
        <Parameter Name="keyRolloverStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
      </Parameters>
      <Docs>
        <param name="encryptionStatus"><span data-ttu-id="2ad17-103">Der Verschlüsselungsstatus, der angibt, ob Verschlüsselung aktiviert ist oder nicht.</span><span class="sxs-lookup"><span data-stu-id="2ad17-103">The encryption status to indicates if encryption is enabled or not.</span></span> <span data-ttu-id="2ad17-104">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="2ad17-104">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="keyRolloverStatus"><span data-ttu-id="2ad17-105">Der Rollover des Status, der angibt, ob der Rollover des datenverschlüsselungsschlüssels erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="2ad17-105">The key rollover status to indicates if key rollover is required or not.</span></span> <span data-ttu-id="2ad17-106">Wenn die Verschlüsselung des geheimen Schlüssels aktualisiert wurde, erfordert sie schlüsselrollovers.</span><span class="sxs-lookup"><span data-stu-id="2ad17-106">If secret's encryption has been upgraded, then it requires key rollover.</span></span>
            <span data-ttu-id="2ad17-107">Folgende Werte sind möglich: "Erforderlich", "NotRequired"</span><span class="sxs-lookup"><span data-stu-id="2ad17-107">Possible values include: 'Required', 'NotRequired'</span></span></param>
        <param name="id"><span data-ttu-id="2ad17-108">Die Pfad-ID, die das Objekt eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="2ad17-108">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="2ad17-109">Der Name des Objekts.</span><span class="sxs-lookup"><span data-stu-id="2ad17-109">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="2ad17-110">Der hierarchische Typ des Objekts.</span><span class="sxs-lookup"><span data-stu-id="2ad17-110">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="2ad17-111">Die Art des Objekts.</span><span class="sxs-lookup"><span data-stu-id="2ad17-111">The Kind of the object.</span></span> <span data-ttu-id="2ad17-112">Derzeit wird nur Series8000 wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="2ad17-112">Currently only Series8000 is supported.</span></span> <span data-ttu-id="2ad17-113">Folgende Werte sind möglich: "Series8000"</span><span class="sxs-lookup"><span data-stu-id="2ad17-113">Possible values include: 'Series8000'</span></span></param>
        <summary>
            <span data-ttu-id="2ad17-114">Initialisiert eine neue Instanz der EncryptionSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2ad17-114">Initializes a new instance of the EncryptionSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus EncryptionStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus EncryptionStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.EncryptionStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionStatus As EncryptionStatus" />
      <MemberSignature Language="F#" Value="member this.EncryptionStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.EncryptionStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ad17-115">Ruft ab oder legt den Status der Verschlüsselung, der angibt, ob Verschlüsselung aktiviert ist oder nicht.</span><span class="sxs-lookup"><span data-stu-id="2ad17-115">Gets or sets the encryption status to indicates if encryption is enabled or not.</span></span> <span data-ttu-id="2ad17-116">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="2ad17-116">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyRolloverStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus KeyRolloverStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus KeyRolloverStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.KeyRolloverStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyRolloverStatus As KeyRolloverStatus" />
      <MemberSignature Language="F#" Value="member this.KeyRolloverStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.KeyRolloverStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyRolloverStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ad17-117">Abrufen oder festlegen den Rollover des datenverschlüsselungsschlüssels Status gibt an, ob der Rollover des datenverschlüsselungsschlüssels erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="2ad17-117">Gets or sets the key rollover status to indicates if key rollover is required or not.</span></span> <span data-ttu-id="2ad17-118">Wenn die Verschlüsselung des geheimen Schlüssels aktualisiert wurde, erfordert sie schlüsselrollovers.</span><span class="sxs-lookup"><span data-stu-id="2ad17-118">If secret's encryption has been upgraded, then it requires key rollover.</span></span> <span data-ttu-id="2ad17-119">Folgende Werte sind möglich: "Erforderlich", "NotRequired"</span><span class="sxs-lookup"><span data-stu-id="2ad17-119">Possible values include: 'Required', 'NotRequired'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="encryptionSettings.Validate " />
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
            <span data-ttu-id="2ad17-120">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="2ad17-120">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2ad17-121">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="2ad17-121">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>