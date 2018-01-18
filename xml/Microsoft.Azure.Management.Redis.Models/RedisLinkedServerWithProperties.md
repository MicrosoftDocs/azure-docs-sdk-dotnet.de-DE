<Type Name="RedisLinkedServerWithProperties" FullName="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties">
  <TypeSignature Language="C#" Value="public class RedisLinkedServerWithProperties : Microsoft.Azure.Management.Redis.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedisLinkedServerWithProperties extends Microsoft.Azure.Management.Redis.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class RedisLinkedServerWithProperties&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type RedisLinkedServerWithProperties = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Redis.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="dc0e6-101">Als Antwort auf Put/Verbindungsserver (mit Eigenschaften) für den Redis-Cache abrufen.</span><span class="sxs-lookup"><span data-stu-id="dc0e6-101">Response to put/get linked server (with properties) for Redis cache.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisLinkedServerWithProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc0e6-102">Initialisiert eine neue Instanz der RedisLinkedServerWithProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dc0e6-102">Initializes a new instance of the RedisLinkedServerWithProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisLinkedServerWithProperties (string linkedRedisCacheId, string linkedRedisCacheLocation, Microsoft.Azure.Management.Redis.Models.ReplicationRole serverRole, string id = null, string name = null, string type = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string linkedRedisCacheId, string linkedRedisCacheLocation, valuetype Microsoft.Azure.Management.Redis.Models.ReplicationRole serverRole, string id, string name, string type, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.#ctor(System.String,System.String,Microsoft.Azure.Management.Redis.Models.ReplicationRole,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedRedisCacheId As String, linkedRedisCacheLocation As String, serverRole As ReplicationRole, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties : string * string * Microsoft.Azure.Management.Redis.Models.ReplicationRole * string * string * string * string -&gt; Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties" Usage="new Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties (linkedRedisCacheId, linkedRedisCacheLocation, serverRole, id, name, type, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="linkedRedisCacheId" Type="System.String" />
        <Parameter Name="linkedRedisCacheLocation" Type="System.String" />
        <Parameter Name="serverRole" Type="Microsoft.Azure.Management.Redis.Models.ReplicationRole" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="linkedRedisCacheId"><span data-ttu-id="dc0e6-103">Vollqualifizierte Ressourcen-ID des verknüpften Redis-Cache.</span><span class="sxs-lookup"><span data-stu-id="dc0e6-103">Fully qualified resourceId of the linked redis cache.</span></span></param>
        <param name="linkedRedisCacheLocation"><span data-ttu-id="dc0e6-104">Der Speicherort des verknüpften Redis-Caches.</span><span class="sxs-lookup"><span data-stu-id="dc0e6-104">Location of the linked redis cache.</span></span></param>
        <param name="serverRole"><span data-ttu-id="dc0e6-105">Die Rolle des Verbindungsservers.</span><span class="sxs-lookup"><span data-stu-id="dc0e6-105">Role of the linked server.</span></span> <span data-ttu-id="dc0e6-106">Folgende Werte sind möglich: 'Primary', 'Sekundären'</span><span class="sxs-lookup"><span data-stu-id="dc0e6-106">Possible values include: 'Primary', 'Secondary'</span></span></param>
        <param name="id"><span data-ttu-id="dc0e6-107">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="dc0e6-107">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="dc0e6-108">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="dc0e6-108">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="dc0e6-109">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="dc0e6-109">Resource type.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="dc0e6-110">Endstatus des Links zwischen primären und sekundären redis-Cache.</span><span class="sxs-lookup"><span data-stu-id="dc0e6-110">Terminal state of the link between primary and secondary redis cache.</span></span></param>
        <summary>
            <span data-ttu-id="dc0e6-111">Initialisiert eine neue Instanz der RedisLinkedServerWithProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dc0e6-111">Initializes a new instance of the RedisLinkedServerWithProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedRedisCacheId">
      <MemberSignature Language="C#" Value="public string LinkedRedisCacheId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinkedRedisCacheId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.LinkedRedisCacheId" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedRedisCacheId As String" />
      <MemberSignature Language="F#" Value="member this.LinkedRedisCacheId : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.LinkedRedisCacheId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.linkedRedisCacheId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc0e6-112">Ruft ab, oder legt ihn fest vollqualifizierten ResourceId des verknüpften Redis-Caches.</span><span class="sxs-lookup"><span data-stu-id="dc0e6-112">Gets or sets fully qualified resourceId of the linked redis cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedRedisCacheLocation">
      <MemberSignature Language="C#" Value="public string LinkedRedisCacheLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinkedRedisCacheLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.LinkedRedisCacheLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedRedisCacheLocation As String" />
      <MemberSignature Language="F#" Value="member this.LinkedRedisCacheLocation : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.LinkedRedisCacheLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.linkedRedisCacheLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc0e6-113">Abrufen oder Festlegen der Position des verknüpften Redis-Caches.</span><span class="sxs-lookup"><span data-stu-id="dc0e6-113">Gets or sets location of the linked redis cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="dc0e6-114">Ruft den abgeschlossenen Zustand des Links zwischen primären und sekundären Redis-Cache ab.</span><span class="sxs-lookup"><span data-stu-id="dc0e6-114">Gets terminal state of the link between primary and secondary redis cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerRole">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Models.ReplicationRole ServerRole { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Redis.Models.ReplicationRole ServerRole" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.ServerRole" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerRole As ReplicationRole" />
      <MemberSignature Language="F#" Value="member this.ServerRole : Microsoft.Azure.Management.Redis.Models.ReplicationRole with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.ServerRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverRole")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.ReplicationRole</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc0e6-115">Ruft ab oder legt die Rolle des Verbindungsservers.</span><span class="sxs-lookup"><span data-stu-id="dc0e6-115">Gets or sets role of the linked server.</span></span> <span data-ttu-id="dc0e6-116">Folgende Werte sind möglich: 'Primary', 'Sekundären'</span><span class="sxs-lookup"><span data-stu-id="dc0e6-116">Possible values include: 'Primary', 'Secondary'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="redisLinkedServerWithProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc0e6-117">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="dc0e6-117">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dc0e6-118">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="dc0e6-118">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>