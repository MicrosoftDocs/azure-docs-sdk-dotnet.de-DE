<Type Name="DeploymentOperationProperties" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties">
  <TypeSignature Language="C#" Value="public class DeploymentOperationProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeploymentOperationProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class DeploymentOperationProperties" />
  <TypeSignature Language="F#" Value="type DeploymentOperationProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="308ae-101">Eigenschaften für den Bereitstellungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="308ae-101">Deployment operation properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentOperationProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="308ae-102">Initialisiert eine neue Instanz der DeploymentOperationProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="308ae-102">Initializes a new instance of the DeploymentOperationProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentOperationProperties (string provisioningState = null, Nullable&lt;DateTime&gt; timestamp = null, string serviceRequestId = null, string statusCode = null, object statusMessage = null, Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource targetResource = null, Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage request = null, Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage response = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timestamp, string serviceRequestId, string statusCode, object statusMessage, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource targetResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage request, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.#ctor(System.String,System.Nullable{System.DateTime},System.String,System.String,System.Object,Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource,Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage,Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties : string * Nullable&lt;DateTime&gt; * string * string * obj * Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource * Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage * Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties (provisioningState, timestamp, serviceRequestId, statusCode, statusMessage, targetResource, request, response)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="timestamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="serviceRequestId" Type="System.String" />
        <Parameter Name="statusCode" Type="System.String" />
        <Parameter Name="statusMessage" Type="System.Object" />
        <Parameter Name="targetResource" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource" />
        <Parameter Name="request" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage" />
        <Parameter Name="response" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage" />
      </Parameters>
      <Docs>
        <param name="provisioningState"><span data-ttu-id="308ae-103">Der Status der Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="308ae-103">The state of the provisioning.</span></span></param>
        <param name="timestamp"><span data-ttu-id="308ae-104">Das Datum und die Uhrzeit des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="308ae-104">The date and time of the operation.</span></span></param>
        <param name="serviceRequestId"><span data-ttu-id="308ae-105">Bereitstellungsvorgangs Service Request-Id.</span><span class="sxs-lookup"><span data-stu-id="308ae-105">Deployment operation service request id.</span></span></param>
        <param name="statusCode"><span data-ttu-id="308ae-106">Statuscode des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="308ae-106">Operation status code.</span></span></param>
        <param name="statusMessage"><span data-ttu-id="308ae-107">Statusmeldung des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="308ae-107">Operation status message.</span></span></param>
        <param name="targetResource"><span data-ttu-id="308ae-108">Die Zielressource.</span><span class="sxs-lookup"><span data-stu-id="308ae-108">The target resource.</span></span></param>
        <param name="request"><span data-ttu-id="308ae-109">Die HTTP-Anforderungsnachricht.</span><span class="sxs-lookup"><span data-stu-id="308ae-109">The HTTP request message.</span></span></param>
        <param name="response"><span data-ttu-id="308ae-110">Die HTTP-Antwortnachricht.</span><span class="sxs-lookup"><span data-stu-id="308ae-110">The HTTP response message.</span></span></param>
        <summary>
            <span data-ttu-id="308ae-111">Initialisiert eine neue Instanz der DeploymentOperationProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="308ae-111">Initializes a new instance of the DeploymentOperationProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="308ae-112">Ruft ab oder legt den Status der Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="308ae-112">Gets or sets the state of the provisioning.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Request">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage Request { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage Request" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.Request" />
      <MemberSignature Language="VB.NET" Value="Public Property Request As HttpMessage" />
      <MemberSignature Language="F#" Value="member this.Request : Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.Request" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="request")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="308ae-113">Ruft ab oder legt den HTTP-Anforderungsnachricht.</span><span class="sxs-lookup"><span data-stu-id="308ae-113">Gets or sets the HTTP request message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage Response { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage Response" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.Response" />
      <MemberSignature Language="VB.NET" Value="Public Property Response As HttpMessage" />
      <MemberSignature Language="F#" Value="member this.Response : Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.Response" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="response")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="308ae-114">Ruft ab oder legt den HTTP-Antwortnachricht.</span><span class="sxs-lookup"><span data-stu-id="308ae-114">Gets or sets the HTTP response message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceRequestId">
      <MemberSignature Language="C#" Value="public string ServiceRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.ServiceRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceRequestId As String" />
      <MemberSignature Language="F#" Value="member this.ServiceRequestId : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.ServiceRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="308ae-115">Ruft ab, oder legt die Bereitstellungsvorgangs Service Request-Id fest.</span><span class="sxs-lookup"><span data-stu-id="308ae-115">Gets or sets deployment operation service request id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public string StatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusCode As String" />
      <MemberSignature Language="F#" Value="member this.StatusCode : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="308ae-116">Ruft ab, oder legt ihn fest Statuscode des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="308ae-116">Gets or sets operation status code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusMessage">
      <MemberSignature Language="C#" Value="public object StatusMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object StatusMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.StatusMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusMessage As Object" />
      <MemberSignature Language="F#" Value="member this.StatusMessage : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.StatusMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="308ae-117">Ruft ab, oder legt die Statusmeldung des Vorgangs fest.</span><span class="sxs-lookup"><span data-stu-id="308ae-117">Gets or sets operation status message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource TargetResource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource TargetResource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.TargetResource" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResource As TargetResource" />
      <MemberSignature Language="F#" Value="member this.TargetResource : Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.TargetResource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="308ae-118">Ruft ab oder legt die Zielressource.</span><span class="sxs-lookup"><span data-stu-id="308ae-118">Gets or sets the target resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Timestamp : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="308ae-119">Ruft ab oder legt das Datum und Uhrzeit des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="308ae-119">Gets or sets the date and time of the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>