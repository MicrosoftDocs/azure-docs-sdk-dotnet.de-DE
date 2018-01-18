<Type Name="CertificateOrderAction" FullName="Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction">
  <TypeSignature Language="C#" Value="public class CertificateOrderAction : Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateOrderAction extends Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateOrderAction&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type CertificateOrderAction = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f8865-101">Zertifikat-Order-Aktion.</span><span class="sxs-lookup"><span data-stu-id="f8865-101">Certificate order action.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateOrderAction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f8865-102">Initialisiert eine neue Instanz der CertificateOrderAction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f8865-102">Initializes a new instance of the CertificateOrderAction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateOrderAction (string location, string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderActionType&gt; certificateOrderActionType = null, Nullable&lt;DateTime&gt; createdAt = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string kind, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.CertificateOrderActionType&gt; certificateOrderActionType, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{Microsoft.Azure.Management.WebSites.Models.CertificateOrderActionType},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional certificateOrderActionType As Nullable(Of CertificateOrderActionType) = null, Optional createdAt As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction : string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderActionType&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction" Usage="new Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction (location, id, name, kind, type, tags, certificateOrderActionType, createdAt)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="certificateOrderActionType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderActionType&gt;" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="f8865-103">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="f8865-103">Resource Location.</span></span></param>
        <param name="id"><span data-ttu-id="f8865-104">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="f8865-104">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="f8865-105">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="f8865-105">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="f8865-106">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="f8865-106">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="f8865-107">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="f8865-107">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="f8865-108">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="f8865-108">Resource tags.</span></span></param>
        <param name="certificateOrderActionType"><span data-ttu-id="f8865-109">Aktionstyp.</span><span class="sxs-lookup"><span data-stu-id="f8865-109">Action type.</span></span> <span data-ttu-id="f8865-110">Folgende Werte sind möglich: "CertificateIssued", "CertificateOrderCanceled", "CertificateOrderCreated", "CertificateRevoked", "DomainValidationComplete", "FraudDetected", "OrgNameChange", "OrgValidationComplete", "SanDrop", "FraudCleared", " CertificateExpired', 'CertificateExpirationWarning', 'FraudDocumentationRequired', 'Unbekannt'</span><span class="sxs-lookup"><span data-stu-id="f8865-110">Possible values include: 'CertificateIssued', 'CertificateOrderCanceled', 'CertificateOrderCreated', 'CertificateRevoked', 'DomainValidationComplete', 'FraudDetected', 'OrgNameChange', 'OrgValidationComplete', 'SanDrop', 'FraudCleared', 'CertificateExpired', 'CertificateExpirationWarning', 'FraudDocumentationRequired', 'Unknown'</span></span></param>
        <param name="createdAt"><span data-ttu-id="f8865-111">Der Zeitpunkt, an dem die Aktion Zertifikat durchgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="f8865-111">Time at which the certificate action was performed.</span></span></param>
        <summary>
            <span data-ttu-id="f8865-112">Initialisiert eine neue Instanz der CertificateOrderAction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f8865-112">Initializes a new instance of the CertificateOrderAction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateOrderActionType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderActionType&gt; CertificateOrderActionType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.CertificateOrderActionType&gt; CertificateOrderActionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction.CertificateOrderActionType" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateOrderActionType As Nullable(Of CertificateOrderActionType)" />
      <MemberSignature Language="F#" Value="member this.CertificateOrderActionType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderActionType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction.CertificateOrderActionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderActionType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8865-113">Ruft ab, oder legt ihn fest-Aktionstyp.</span><span class="sxs-lookup"><span data-stu-id="f8865-113">Gets or sets action type.</span></span> <span data-ttu-id="f8865-114">Folgende Werte sind möglich: "CertificateIssued", "CertificateOrderCanceled", "CertificateOrderCreated", "CertificateRevoked", "DomainValidationComplete", "FraudDetected", "OrgNameChange", "OrgValidationComplete", "SanDrop", "FraudCleared", " CertificateExpired', 'CertificateExpirationWarning', 'FraudDocumentationRequired', 'Unbekannt'</span><span class="sxs-lookup"><span data-stu-id="f8865-114">Possible values include: 'CertificateIssued', 'CertificateOrderCanceled', 'CertificateOrderCreated', 'CertificateRevoked', 'DomainValidationComplete', 'FraudDetected', 'OrgNameChange', 'OrgValidationComplete', 'SanDrop', 'FraudCleared', 'CertificateExpired', 'CertificateExpirationWarning', 'FraudDocumentationRequired', 'Unknown'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8865-115">Abrufen oder Festlegen der Zeit an, die Zertifikat-Aktion ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="f8865-115">Gets or sets time at which the certificate action was performed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="certificateOrderAction.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f8865-116">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="f8865-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f8865-117">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="f8865-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>