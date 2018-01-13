<Type Name="DeploymentOperationProperties" FullName="Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties">
  <TypeSignature Language="C#" Value="public class DeploymentOperationProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeploymentOperationProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class DeploymentOperationProperties" />
  <TypeSignature Language="F#" Value="type DeploymentOperationProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c222f-101">Eigenschaften für den Bereitstellungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="c222f-101">Deployment operation properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentOperationProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c222f-102">Initialisiert eine neue Instanz der DeploymentOperationProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c222f-102">Initializes a new instance of the DeploymentOperationProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentOperationProperties (string provisioningState = null, Nullable&lt;DateTime&gt; timestamp = null, string serviceRequestId = null, string statusCode = null, object statusMessage = null, Microsoft.Azure.Management.ResourceManager.Models.TargetResource targetResource = null, Microsoft.Azure.Management.ResourceManager.Models.HttpMessage request = null, Microsoft.Azure.Management.ResourceManager.Models.HttpMessage response = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timestamp, string serviceRequestId, string statusCode, object statusMessage, class Microsoft.Azure.Management.ResourceManager.Models.TargetResource targetResource, class Microsoft.Azure.Management.ResourceManager.Models.HttpMessage request, class Microsoft.Azure.Management.ResourceManager.Models.HttpMessage response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.#ctor(System.String,System.Nullable{System.DateTime},System.String,System.String,System.Object,Microsoft.Azure.Management.ResourceManager.Models.TargetResource,Microsoft.Azure.Management.ResourceManager.Models.HttpMessage,Microsoft.Azure.Management.ResourceManager.Models.HttpMessage)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties : string * Nullable&lt;DateTime&gt; * string * string * obj * Microsoft.Azure.Management.ResourceManager.Models.TargetResource * Microsoft.Azure.Management.ResourceManager.Models.HttpMessage * Microsoft.Azure.Management.ResourceManager.Models.HttpMessage -&gt; Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties" Usage="new Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties (provisioningState, timestamp, serviceRequestId, statusCode, statusMessage, targetResource, request, response)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="timestamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="serviceRequestId" Type="System.String" />
        <Parameter Name="statusCode" Type="System.String" />
        <Parameter Name="statusMessage" Type="System.Object" />
        <Parameter Name="targetResource" Type="Microsoft.Azure.Management.ResourceManager.Models.TargetResource" />
        <Parameter Name="request" Type="Microsoft.Azure.Management.ResourceManager.Models.HttpMessage" />
        <Parameter Name="response" Type="Microsoft.Azure.Management.ResourceManager.Models.HttpMessage" />
      </Parameters>
      <Docs>
        <param name="provisioningState"><span data-ttu-id="c222f-103">Der Status der Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="c222f-103">The state of the provisioning.</span></span></param>
        <param name="timestamp"><span data-ttu-id="c222f-104">Das Datum und die Uhrzeit des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c222f-104">The date and time of the operation.</span></span></param>
        <param name="serviceRequestId"><span data-ttu-id="c222f-105">Bereitstellungsvorgangs Service Request-Id.</span><span class="sxs-lookup"><span data-stu-id="c222f-105">Deployment operation service request id.</span></span></param>
        <param name="statusCode"><span data-ttu-id="c222f-106">Statuscode des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c222f-106">Operation status code.</span></span></param>
        <param name="statusMessage"><span data-ttu-id="c222f-107">Statusmeldung des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c222f-107">Operation status message.</span></span></param>
        <param name="targetResource"><span data-ttu-id="c222f-108">Die Zielressource.</span><span class="sxs-lookup"><span data-stu-id="c222f-108">The target resource.</span></span></param>
        <param name="request"><span data-ttu-id="c222f-109">Die HTTP-Anforderungsnachricht.</span><span class="sxs-lookup"><span data-stu-id="c222f-109">The HTTP request message.</span></span></param>
        <param name="response"><span data-ttu-id="c222f-110">Die HTTP-Antwortnachricht.</span><span class="sxs-lookup"><span data-stu-id="c222f-110">The HTTP response message.</span></span></param>
        <summary>
            <span data-ttu-id="c222f-111">Initialisiert eine neue Instanz der DeploymentOperationProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c222f-111">Initializes a new instance of the DeploymentOperationProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c222f-112">Ruft den Status der Bereitstellung ab.</span><span class="sxs-lookup"><span data-stu-id="c222f-112">Gets the state of the provisioning.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Request">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.HttpMessage Request { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.HttpMessage Request" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.Request" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Request As HttpMessage" />
      <MemberSignature Language="F#" Value="member this.Request : Microsoft.Azure.Management.ResourceManager.Models.HttpMessage" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.Request" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="request")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.HttpMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c222f-113">Ruft die HTTP-Anforderungsnachricht ab.</span><span class="sxs-lookup"><span data-stu-id="c222f-113">Gets the HTTP request message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.HttpMessage Response { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.HttpMessage Response" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.Response" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Response As HttpMessage" />
      <MemberSignature Language="F#" Value="member this.Response : Microsoft.Azure.Management.ResourceManager.Models.HttpMessage" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.Response" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="response")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.HttpMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c222f-114">Ruft die HTTP-Antwortnachricht ab.</span><span class="sxs-lookup"><span data-stu-id="c222f-114">Gets the HTTP response message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceRequestId">
      <MemberSignature Language="C#" Value="public string ServiceRequestId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.ServiceRequestId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceRequestId As String" />
      <MemberSignature Language="F#" Value="member this.ServiceRequestId : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.ServiceRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceRequestId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c222f-115">Ruft die Bereitstellungsvorgangs Service Request-Id ab.</span><span class="sxs-lookup"><span data-stu-id="c222f-115">Gets deployment operation service request id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public string StatusCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusCode As String" />
      <MemberSignature Language="F#" Value="member this.StatusCode : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statusCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c222f-116">Ruft die Statuscode des Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="c222f-116">Gets operation status code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusMessage">
      <MemberSignature Language="C#" Value="public object StatusMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object StatusMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.StatusMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusMessage As Object" />
      <MemberSignature Language="F#" Value="member this.StatusMessage : obj" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.StatusMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statusMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c222f-117">Ruft die Statusmeldung des Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="c222f-117">Gets operation status message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.TargetResource TargetResource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.TargetResource TargetResource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.TargetResource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetResource As TargetResource" />
      <MemberSignature Language="F#" Value="member this.TargetResource : Microsoft.Azure.Management.ResourceManager.Models.TargetResource" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.TargetResource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.TargetResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c222f-118">Ruft die Zielressource ab.</span><span class="sxs-lookup"><span data-stu-id="c222f-118">Gets the target resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Timestamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c222f-119">Ruft das Datum und die Uhrzeit des Vorgangs an.</span><span class="sxs-lookup"><span data-stu-id="c222f-119">Gets the date and time of the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>