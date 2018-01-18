<Type Name="MSDeployStatus" FullName="Microsoft.Azure.Management.WebSites.Models.MSDeployStatus">
  <TypeSignature Language="C#" Value="public class MSDeployStatus : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MSDeployStatus extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.MSDeployStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class MSDeployStatus&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type MSDeployStatus = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="7a530-101">MSDeploy-ARM-Antwort</span><span class="sxs-lookup"><span data-stu-id="7a530-101">MSDeploy ARM response</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MSDeployStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7a530-102">Initialisiert eine neue Instanz der MSDeployStatus-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7a530-102">Initializes a new instance of the MSDeployStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MSDeployStatus (string id = null, string name = null, string kind = null, string type = null, string deployer = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState&gt; provisioningState = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Nullable&lt;bool&gt; complete = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string deployer, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, valuetype System.Nullable`1&lt;bool&gt; complete) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional deployer As String = null, Optional provisioningState As Nullable(Of MSDeployProvisioningState) = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional complete As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.MSDeployStatus : string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.MSDeployStatus" Usage="new Microsoft.Azure.Management.WebSites.Models.MSDeployStatus (id, name, kind, type, deployer, provisioningState, startTime, endTime, complete)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="deployer" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="complete" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="7a530-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="7a530-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="7a530-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="7a530-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="7a530-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="7a530-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="7a530-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="7a530-106">Resource type.</span></span></param>
        <param name="deployer"><span data-ttu-id="7a530-107">Der Benutzername des Bereitsteller</span><span class="sxs-lookup"><span data-stu-id="7a530-107">Username of deployer</span></span></param>
        <param name="provisioningState"><span data-ttu-id="7a530-108">Der Bereitstellungsstatus.</span><span class="sxs-lookup"><span data-stu-id="7a530-108">Provisioning state.</span></span> <span data-ttu-id="7a530-109">Folgende Werte sind möglich: "akzeptiert", "wird ausgeführt", "erfolgreich abgeschlossen", "fehlgeschlagen", "abgebrochen"</span><span class="sxs-lookup"><span data-stu-id="7a530-109">Possible values include: 'accepted', 'running', 'succeeded', 'failed', 'canceled'</span></span></param>
        <param name="startTime"><span data-ttu-id="7a530-110">Vorgang zur Startzeit der Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="7a530-110">Start time of deploy operation</span></span></param>
        <param name="endTime"><span data-ttu-id="7a530-111">Endzeit der Vorgang zur Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="7a530-111">End time of deploy operation</span></span></param>
        <param name="complete"><span data-ttu-id="7a530-112">Gibt an, ob der Bereitstellungsvorgang abgeschlossen ist</span><span class="sxs-lookup"><span data-stu-id="7a530-112">Whether the deployment operation has completed</span></span></param>
        <summary>
            <span data-ttu-id="7a530-113">Initialisiert eine neue Instanz der MSDeployStatus-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7a530-113">Initializes a new instance of the MSDeployStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Complete">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Complete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Complete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.Complete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Complete As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Complete : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.Complete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.complete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a530-114">Ruft ab, ob der Bereitstellungsvorgang abgeschlossen ist</span><span class="sxs-lookup"><span data-stu-id="7a530-114">Gets whether the deployment operation has completed</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deployer">
      <MemberSignature Language="C#" Value="public string Deployer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Deployer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.Deployer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Deployer As String" />
      <MemberSignature Language="F#" Value="member this.Deployer : string" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.Deployer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deployer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a530-115">Ruft ab, der Benutzername des Bereitsteller</span><span class="sxs-lookup"><span data-stu-id="7a530-115">Gets username of deployer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a530-116">Ruft Uhrzeit des Endes des Vorgang zur Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="7a530-116">Gets end time of deploy operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of MSDeployProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a530-117">Ruft die Status Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="7a530-117">Gets provisioning state.</span></span> <span data-ttu-id="7a530-118">Folgende Werte sind möglich: "akzeptiert", "wird ausgeführt", "erfolgreich abgeschlossen", "fehlgeschlagen", "abgebrochen"</span><span class="sxs-lookup"><span data-stu-id="7a530-118">Possible values include: 'accepted', 'running', 'succeeded', 'failed', 'canceled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a530-119">Ruft Startzeit des Vorgang zur Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="7a530-119">Gets start time of deploy operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>