<Type Name="SharedAccessSignatureAuthorizationRule" FullName="Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule">
  <TypeSignature Language="C#" Value="public class SharedAccessSignatureAuthorizationRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedAccessSignatureAuthorizationRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedAccessSignatureAuthorizationRule" />
  <TypeSignature Language="F#" Value="type SharedAccessSignatureAuthorizationRule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e0a67-101">Die Eigenschaften des IoT Hub freigegebenen Zugriffsrichtlinien.</span><span class="sxs-lookup"><span data-stu-id="e0a67-101">The properties of an IoT hub shared access policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessSignatureAuthorizationRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e0a67-102">Initialisiert eine neue Instanz der SharedAccessSignatureAuthorizationRule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e0a67-102">Initializes a new instance of the SharedAccessSignatureAuthorizationRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessSignatureAuthorizationRule (string keyName, Microsoft.Azure.Management.IotHub.Models.AccessRights rights, string primaryKey = null, string secondaryKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyName, valuetype Microsoft.Azure.Management.IotHub.Models.AccessRights rights, string primaryKey, string secondaryKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.#ctor(System.String,Microsoft.Azure.Management.IotHub.Models.AccessRights,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyName As String, rights As AccessRights, Optional primaryKey As String = null, Optional secondaryKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule : string * Microsoft.Azure.Management.IotHub.Models.AccessRights * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule" Usage="new Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule (keyName, rights, primaryKey, secondaryKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="rights" Type="Microsoft.Azure.Management.IotHub.Models.AccessRights" />
        <Parameter Name="primaryKey" Type="System.String" />
        <Parameter Name="secondaryKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="e0a67-103">Der Name der Richtlinie für freigegebenen Zugriff.</span><span class="sxs-lookup"><span data-stu-id="e0a67-103">The name of the shared access policy.</span></span></param>
        <param name="rights"><span data-ttu-id="e0a67-104">Die Berechtigungen, die die SAS-Richtlinie zugewiesen ist.</span><span class="sxs-lookup"><span data-stu-id="e0a67-104">The permissions assigned to the shared access policy.</span></span> <span data-ttu-id="e0a67-105">Mögliche Werte sind: "RegistryRead", "RegistryWrite", "ServiceConnect", "DeviceConnect", 'RegistryRead RegistryWrite', 'RegistryRead, ServiceConnect', 'RegistryRead, DeviceConnect', 'RegistryWrite, ServiceConnect', ' RegistryWrite, DeviceConnect', 'ServiceConnect, DeviceConnect', "RegistryRead RegistryWrite, ServiceConnect", "RegistryRead RegistryWrite, DeviceConnect", "RegistryRead ServiceConnect, DeviceConnect", "RegistryWrite ServiceConnect, DeviceConnect", " RegistryRead, RegistryWrite, ServiceConnect, DeviceConnect "</span><span class="sxs-lookup"><span data-stu-id="e0a67-105">Possible values include: 'RegistryRead', 'RegistryWrite', 'ServiceConnect', 'DeviceConnect', 'RegistryRead, RegistryWrite', 'RegistryRead, ServiceConnect', 'RegistryRead, DeviceConnect', 'RegistryWrite, ServiceConnect', 'RegistryWrite, DeviceConnect', 'ServiceConnect, DeviceConnect', 'RegistryRead, RegistryWrite, ServiceConnect', 'RegistryRead, RegistryWrite, DeviceConnect', 'RegistryRead, ServiceConnect, DeviceConnect', 'RegistryWrite, ServiceConnect, DeviceConnect', 'RegistryRead, RegistryWrite, ServiceConnect, DeviceConnect'</span></span></param>
        <param name="primaryKey"><span data-ttu-id="e0a67-106">Der primäre Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="e0a67-106">The primary key.</span></span></param>
        <param name="secondaryKey"><span data-ttu-id="e0a67-107">Der sekundäre Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="e0a67-107">The secondary key.</span></span></param>
        <summary>
            <span data-ttu-id="e0a67-108">Initialisiert eine neue Instanz der SharedAccessSignatureAuthorizationRule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e0a67-108">Initializes a new instance of the SharedAccessSignatureAuthorizationRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0a67-109">Ruft ab oder legt den Namen der Richtlinie für freigegebenen Zugriff.</span><span class="sxs-lookup"><span data-stu-id="e0a67-109">Gets or sets the name of the shared access policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryKey">
      <MemberSignature Language="C#" Value="public string PrimaryKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.PrimaryKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryKey As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryKey : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.PrimaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0a67-110">Ruft ab oder legt den primären Schlüssel fest.</span><span class="sxs-lookup"><span data-stu-id="e0a67-110">Gets or sets the primary key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rights">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.IotHub.Models.AccessRights Rights { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.IotHub.Models.AccessRights Rights" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.Rights" />
      <MemberSignature Language="VB.NET" Value="Public Property Rights As AccessRights" />
      <MemberSignature Language="F#" Value="member this.Rights : Microsoft.Azure.Management.IotHub.Models.AccessRights with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.Rights" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rights")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.AccessRights</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0a67-111">Ruft ab oder legt die Berechtigungen, die die SAS-Richtlinie zugewiesen ist.</span><span class="sxs-lookup"><span data-stu-id="e0a67-111">Gets or sets the permissions assigned to the shared access policy.</span></span>
            <span data-ttu-id="e0a67-112">Mögliche Werte sind: "RegistryRead", "RegistryWrite", "ServiceConnect", "DeviceConnect", 'RegistryRead RegistryWrite', 'RegistryRead, ServiceConnect', 'RegistryRead, DeviceConnect', 'RegistryWrite, ServiceConnect', ' RegistryWrite, DeviceConnect', 'ServiceConnect, DeviceConnect', "RegistryRead RegistryWrite, ServiceConnect", "RegistryRead RegistryWrite, DeviceConnect", "RegistryRead ServiceConnect, DeviceConnect", "RegistryWrite ServiceConnect, DeviceConnect", " RegistryRead, RegistryWrite, ServiceConnect, DeviceConnect "</span><span class="sxs-lookup"><span data-stu-id="e0a67-112">Possible values include: 'RegistryRead', 'RegistryWrite', 'ServiceConnect', 'DeviceConnect', 'RegistryRead, RegistryWrite', 'RegistryRead, ServiceConnect', 'RegistryRead, DeviceConnect', 'RegistryWrite, ServiceConnect', 'RegistryWrite, DeviceConnect', 'ServiceConnect, DeviceConnect', 'RegistryRead, RegistryWrite, ServiceConnect', 'RegistryRead, RegistryWrite, DeviceConnect', 'RegistryRead, ServiceConnect, DeviceConnect', 'RegistryWrite, ServiceConnect, DeviceConnect', 'RegistryRead, RegistryWrite, ServiceConnect, DeviceConnect'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryKey">
      <MemberSignature Language="C#" Value="public string SecondaryKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.SecondaryKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryKey As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryKey : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.SecondaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0a67-113">Ruft ab oder legt den sekundären Schlüssel fest.</span><span class="sxs-lookup"><span data-stu-id="e0a67-113">Gets or sets the secondary key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sharedAccessSignatureAuthorizationRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e0a67-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="e0a67-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e0a67-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="e0a67-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>