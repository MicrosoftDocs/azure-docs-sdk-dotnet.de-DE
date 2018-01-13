<Type Name="DynamicsLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService">
  <TypeSignature Language="C#" Value="public class DynamicsLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DynamicsLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class DynamicsLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type DynamicsLinkedService = class&#xA;    inherit LinkedService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.LinkedService</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Dynamics")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="2eb19-101">Dynamics verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="2eb19-101">Dynamics linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DynamicsLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2eb19-102">Initialisiert eine neue Instanz der DynamicsLinkedService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2eb19-102">Initializes a new instance of the DynamicsLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DynamicsLinkedService (object deploymentType, object authenticationType, object username, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object hostName = null, object port = null, object organizationName = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase password = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object deploymentType, object authenticationType, object username, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object hostName, object port, object organizationName, class Microsoft.Azure.Management.DataFactory.Models.SecretBase password, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.#ctor(System.Object,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deploymentType As Object, authenticationType As Object, username As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional hostName As Object = null, Optional port As Object = null, Optional organizationName As Object = null, Optional password As SecretBase = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService : obj * obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService (deploymentType, authenticationType, username, additionalProperties, connectVia, description, hostName, port, organizationName, password, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deploymentType" Type="System.Object" />
        <Parameter Name="authenticationType" Type="System.Object" />
        <Parameter Name="username" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="hostName" Type="System.Object" />
        <Parameter Name="port" Type="System.Object" />
        <Parameter Name="organizationName" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="deploymentType"><span data-ttu-id="2eb19-103">Der Bereitstellungstyp der Dynamics-Instanz.</span><span class="sxs-lookup"><span data-stu-id="2eb19-103">The deployment type of the Dynamics instance.</span></span> <span data-ttu-id="2eb19-104">"Online" für Dynamics Online und "OnPremisesWithIfd" für Dynamics lokal mit Ifd.</span><span class="sxs-lookup"><span data-stu-id="2eb19-104">'Online' for Dynamics Online and 'OnPremisesWithIfd' for Dynamics on-premises with Ifd.</span></span> <span data-ttu-id="2eb19-105">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="2eb19-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="authenticationType"><span data-ttu-id="2eb19-106">Der Authentifizierungstyp für die Verbindungsherstellung mit dem Dynamics-Server.</span><span class="sxs-lookup"><span data-stu-id="2eb19-106">The authentication type to connect to Dynamics server.</span></span> <span data-ttu-id="2eb19-107">"Office 365" für online-Szenario, "Ifd" für on-Premises mit Ifd-Szenario.</span><span class="sxs-lookup"><span data-stu-id="2eb19-107">'Office365' for online scenario, 'Ifd' for on-premises with Ifd scenario.</span></span> <span data-ttu-id="2eb19-108">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="2eb19-108">Type: string (or Expression with resultType string).</span></span></param>
        <param name="username"><span data-ttu-id="2eb19-109">Der Benutzername Zugriff auf die Dynamics-Instanz.</span><span class="sxs-lookup"><span data-stu-id="2eb19-109">User name to access the Dynamics instance.</span></span>
            <span data-ttu-id="2eb19-110">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="2eb19-110">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="2eb19-111">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="2eb19-111">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="2eb19-112">Der Integration Common Language Runtime-Verweis.</span><span class="sxs-lookup"><span data-stu-id="2eb19-112">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="2eb19-113">Beschreibung des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="2eb19-113">Linked service description.</span></span></param>
        <param name="hostName"><span data-ttu-id="2eb19-114">Der Hostname des lokalen Dynamics-Servers.</span><span class="sxs-lookup"><span data-stu-id="2eb19-114">The host name of the on-premises Dynamics server.</span></span> <span data-ttu-id="2eb19-115">Die Eigenschaft ist erforderlich für lokale und nicht zulässig für online.</span><span class="sxs-lookup"><span data-stu-id="2eb19-115">The property is required for on-prem and not allowed for online.</span></span> <span data-ttu-id="2eb19-116">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="2eb19-116">Type: string (or Expression with resultType string).</span></span></param>
        <param name="port"><span data-ttu-id="2eb19-117">Der Port des lokalen Dynamics-Servers.</span><span class="sxs-lookup"><span data-stu-id="2eb19-117">The port of on-premises Dynamics server.</span></span> <span data-ttu-id="2eb19-118">Die Eigenschaft ist erforderlich für lokale und nicht zulässig für online.</span><span class="sxs-lookup"><span data-stu-id="2eb19-118">The property is required for on-prem and not allowed for online.</span></span>
            <span data-ttu-id="2eb19-119">Standard ist 443.</span><span class="sxs-lookup"><span data-stu-id="2eb19-119">Default is 443.</span></span> <span data-ttu-id="2eb19-120">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="2eb19-120">Type: integer (or Expression with resultType integer), minimum: 0.</span></span></param>
        <param name="organizationName"><span data-ttu-id="2eb19-121">Der Organisationsname der Dynamics-Instanz.</span><span class="sxs-lookup"><span data-stu-id="2eb19-121">The organization name of the Dynamics instance.</span></span> <span data-ttu-id="2eb19-122">Die Eigenschaft ist erforderlich für lokale und erforderlich für online auf, wenn es mehr als eine Dynamics-Instanzen, die dem Benutzer zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="2eb19-122">The property is required for on-prem and required for online when there are more than one Dynamics instances associated with the user.</span></span> <span data-ttu-id="2eb19-123">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="2eb19-123">Type: string (or Expression with resultType string).</span></span></param>
        <param name="password"><span data-ttu-id="2eb19-124">Kennwort zum Zugriff auf die Dynamics-Instanz.</span><span class="sxs-lookup"><span data-stu-id="2eb19-124">Password to access the Dynamics instance.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="2eb19-125">Die verschlüsselten Anmeldeinformationen für die Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="2eb19-125">The encrypted credential used for authentication.</span></span> <span data-ttu-id="2eb19-126">Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager.</span><span class="sxs-lookup"><span data-stu-id="2eb19-126">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="2eb19-127">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="2eb19-127">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="2eb19-128">Initialisiert eine neue Instanz der DynamicsLinkedService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2eb19-128">Initializes a new instance of the DynamicsLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public object AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As Object" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.authenticationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2eb19-129">Ruft ab oder legt den Authentifizierungstyp für die Verbindung mit Dynamics-Server.</span><span class="sxs-lookup"><span data-stu-id="2eb19-129">Gets or sets the authentication type to connect to Dynamics server.</span></span>
            <span data-ttu-id="2eb19-130">"Office 365" für online-Szenario, "Ifd" für on-Premises mit Ifd-Szenario.</span><span class="sxs-lookup"><span data-stu-id="2eb19-130">'Office365' for online scenario, 'Ifd' for on-premises with Ifd scenario.</span></span> <span data-ttu-id="2eb19-131">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="2eb19-131">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentType">
      <MemberSignature Language="C#" Value="public object DeploymentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object DeploymentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.DeploymentType" />
      <MemberSignature Language="VB.NET" Value="Public Property DeploymentType As Object" />
      <MemberSignature Language="F#" Value="member this.DeploymentType : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.DeploymentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.deploymentType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2eb19-132">Ruft ab oder legt den Bereitstellungstyp der Dynamics-Instanz.</span><span class="sxs-lookup"><span data-stu-id="2eb19-132">Gets or sets the deployment type of the Dynamics instance.</span></span> <span data-ttu-id="2eb19-133">"Online" für Dynamics Online und "OnPremisesWithIfd" für Dynamics lokal mit Ifd.</span><span class="sxs-lookup"><span data-stu-id="2eb19-133">'Online' for Dynamics Online and 'OnPremisesWithIfd' for Dynamics on-premises with Ifd.</span></span> <span data-ttu-id="2eb19-134">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="2eb19-134">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.encryptedCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2eb19-135">Ruft ab oder legt die verschlüsselte Anmeldeinformationen für die Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="2eb19-135">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="2eb19-136">Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager.</span><span class="sxs-lookup"><span data-stu-id="2eb19-136">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="2eb19-137">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="2eb19-137">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public object HostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.HostName" />
      <MemberSignature Language="VB.NET" Value="Public Property HostName As Object" />
      <MemberSignature Language="F#" Value="member this.HostName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.hostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2eb19-138">Ruft ab oder legt den Hostnamen des Servers, lokaler Dynamics.</span><span class="sxs-lookup"><span data-stu-id="2eb19-138">Gets or sets the host name of the on-premises Dynamics server.</span></span> <span data-ttu-id="2eb19-139">Die Eigenschaft ist erforderlich für lokale und nicht zulässig für online.</span><span class="sxs-lookup"><span data-stu-id="2eb19-139">The property is required for on-prem and not allowed for online.</span></span> <span data-ttu-id="2eb19-140">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="2eb19-140">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrganizationName">
      <MemberSignature Language="C#" Value="public object OrganizationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object OrganizationName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.OrganizationName" />
      <MemberSignature Language="VB.NET" Value="Public Property OrganizationName As Object" />
      <MemberSignature Language="F#" Value="member this.OrganizationName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.OrganizationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.organizationName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2eb19-141">Ruft ab oder legt den Organisationsnamen an, der die Instanz von Dynamics.</span><span class="sxs-lookup"><span data-stu-id="2eb19-141">Gets or sets the organization name of the Dynamics instance.</span></span> <span data-ttu-id="2eb19-142">Die Eigenschaft ist erforderlich für lokale und erforderlich für online auf, wenn es mehr als eine Dynamics-Instanzen, die dem Benutzer zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="2eb19-142">The property is required for on-prem and required for online when there are more than one Dynamics instances associated with the user.</span></span>
            <span data-ttu-id="2eb19-143">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="2eb19-143">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecretBase" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2eb19-144">Ruft ab oder legt das Kennwort zum Zugriff auf die Instanz von Dynamics.</span><span class="sxs-lookup"><span data-stu-id="2eb19-144">Gets or sets password to access the Dynamics instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public object Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Object" />
      <MemberSignature Language="F#" Value="member this.Port : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2eb19-145">Ruft ab oder legt den Port des lokalen Dynamics Server fest.</span><span class="sxs-lookup"><span data-stu-id="2eb19-145">Gets or sets the port of on-premises Dynamics server.</span></span> <span data-ttu-id="2eb19-146">Die Eigenschaft ist erforderlich für lokale und nicht zulässig für online.</span><span class="sxs-lookup"><span data-stu-id="2eb19-146">The property is required for on-prem and not allowed for online.</span></span> <span data-ttu-id="2eb19-147">Standard ist 443.</span><span class="sxs-lookup"><span data-stu-id="2eb19-147">Default is 443.</span></span>
            <span data-ttu-id="2eb19-148">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="2eb19-148">Type: integer (or Expression with resultType integer), minimum: 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.username")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2eb19-149">Ruft ab, oder legt ihn fest Benutzername Zugriff auf die Dynamics-Instanz.</span><span class="sxs-lookup"><span data-stu-id="2eb19-149">Gets or sets user name to access the Dynamics instance.</span></span> <span data-ttu-id="2eb19-150">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="2eb19-150">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="dynamicsLinkedService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2eb19-151">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="2eb19-151">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2eb19-152">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="2eb19-152">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>