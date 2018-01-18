<Type Name="CustomHostnameAnalysisResult" FullName="Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult">
  <TypeSignature Language="C#" Value="public class CustomHostnameAnalysisResult : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CustomHostnameAnalysisResult extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult" />
  <TypeSignature Language="VB.NET" Value="Public Class CustomHostnameAnalysisResult&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type CustomHostnameAnalysisResult = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5fac9-101">Analyse der benutzerdefinierten Domäne.</span><span class="sxs-lookup"><span data-stu-id="5fac9-101">Custom domain analysis.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomHostnameAnalysisResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5fac9-102">Initialisiert eine neue Instanz der CustomHostnameAnalysisResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5fac9-102">Initializes a new instance of the CustomHostnameAnalysisResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomHostnameAnalysisResult (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;bool&gt; isHostnameAlreadyVerified = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsVerificationTestResult&gt; customDomainVerificationTest = null, Microsoft.Azure.Management.WebSites.Models.ErrorEntity customDomainVerificationFailureInfo = null, Nullable&lt;bool&gt; hasConflictOnScaleUnit = null, Nullable&lt;bool&gt; hasConflictAcrossSubscription = null, string conflictingAppResourceId = null, System.Collections.Generic.IList&lt;string&gt; cNameRecords = null, System.Collections.Generic.IList&lt;string&gt; txtRecords = null, System.Collections.Generic.IList&lt;string&gt; aRecords = null, System.Collections.Generic.IList&lt;string&gt; alternateCNameRecords = null, System.Collections.Generic.IList&lt;string&gt; alternateTxtRecords = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;bool&gt; isHostnameAlreadyVerified, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.DnsVerificationTestResult&gt; customDomainVerificationTest, class Microsoft.Azure.Management.WebSites.Models.ErrorEntity customDomainVerificationFailureInfo, valuetype System.Nullable`1&lt;bool&gt; hasConflictOnScaleUnit, valuetype System.Nullable`1&lt;bool&gt; hasConflictAcrossSubscription, string conflictingAppResourceId, class System.Collections.Generic.IList`1&lt;string&gt; cNameRecords, class System.Collections.Generic.IList`1&lt;string&gt; txtRecords, class System.Collections.Generic.IList`1&lt;string&gt; aRecords, class System.Collections.Generic.IList`1&lt;string&gt; alternateCNameRecords, class System.Collections.Generic.IList`1&lt;string&gt; alternateTxtRecords) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.WebSites.Models.DnsVerificationTestResult},Microsoft.Azure.Management.WebSites.Models.ErrorEntity,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional isHostnameAlreadyVerified As Nullable(Of Boolean) = null, Optional customDomainVerificationTest As Nullable(Of DnsVerificationTestResult) = null, Optional customDomainVerificationFailureInfo As ErrorEntity = null, Optional hasConflictOnScaleUnit As Nullable(Of Boolean) = null, Optional hasConflictAcrossSubscription As Nullable(Of Boolean) = null, Optional conflictingAppResourceId As String = null, Optional cNameRecords As IList(Of String) = null, Optional txtRecords As IList(Of String) = null, Optional aRecords As IList(Of String) = null, Optional alternateCNameRecords As IList(Of String) = null, Optional alternateTxtRecords As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult : string * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsVerificationTestResult&gt; * Microsoft.Azure.Management.WebSites.Models.ErrorEntity * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult" Usage="new Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult (id, name, kind, type, isHostnameAlreadyVerified, customDomainVerificationTest, customDomainVerificationFailureInfo, hasConflictOnScaleUnit, hasConflictAcrossSubscription, conflictingAppResourceId, cNameRecords, txtRecords, aRecords, alternateCNameRecords, alternateTxtRecords)" />
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
        <Parameter Name="isHostnameAlreadyVerified" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customDomainVerificationTest" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsVerificationTestResult&gt;" />
        <Parameter Name="customDomainVerificationFailureInfo" Type="Microsoft.Azure.Management.WebSites.Models.ErrorEntity" />
        <Parameter Name="hasConflictOnScaleUnit" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="hasConflictAcrossSubscription" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="conflictingAppResourceId" Type="System.String" />
        <Parameter Name="cNameRecords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="txtRecords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="aRecords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="alternateCNameRecords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="alternateTxtRecords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="5fac9-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="5fac9-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="5fac9-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="5fac9-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="5fac9-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="5fac9-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="5fac9-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="5fac9-106">Resource type.</span></span></param>
        <param name="isHostnameAlreadyVerified"><span data-ttu-id="5fac9-107">&lt;Code&gt;"true"&lt;/code&gt; Wenn Hostname bereits überprüft; andernfalls wird &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="5fac9-107">&lt;code&gt;true&lt;/code&gt; if hostname is already verified; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="customDomainVerificationTest"><span data-ttu-id="5fac9-108">Testergebnis für DNS-Überprüfung.</span><span class="sxs-lookup"><span data-stu-id="5fac9-108">DNS verification test result.</span></span> <span data-ttu-id="5fac9-109">Folgende Werte sind möglich: "Abgelaufen", "Fehlgeschlagen", "übersprungen"</span><span class="sxs-lookup"><span data-stu-id="5fac9-109">Possible values include: 'Passed', 'Failed', 'Skipped'</span></span></param>
        <param name="customDomainVerificationFailureInfo"><span data-ttu-id="5fac9-110">Unformatierte Fehlerinformationen, wenn der DNS-Überprüfung ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="5fac9-110">Raw failure information if DNS verification fails.</span></span></param>
        <param name="hasConflictOnScaleUnit"><span data-ttu-id="5fac9-111">&lt;Code&gt;"true"&lt;/code&gt; Wenn ein Konflikt auf einer Skalierungseinheit; vorhanden ist, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="5fac9-111">&lt;code&gt;true&lt;/code&gt; if there is a conflict on a scale unit; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="hasConflictAcrossSubscription"><span data-ttu-id="5fac9-112">&lt;Code&gt;"true"&lt;/code&gt; , wenn ein Konflikt zwischen Abonnements; vorhanden ist, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="5fac9-112">&lt;code&gt;true&lt;/code&gt; if htere is a conflict across subscriptions; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="conflictingAppResourceId"><span data-ttu-id="5fac9-113">Name der in Konflikt stehenden app auf Skalierungseinheit, wenn es innerhalb des gleichen Abonnements ist.</span><span class="sxs-lookup"><span data-stu-id="5fac9-113">Name of the conflicting app on scale unit if it's within the same subscription.</span></span></param>
        <param name="cNameRecords"><span data-ttu-id="5fac9-114">CName-Datensätze Controller kann für diesen Hostnamen finden Sie unter.</span><span class="sxs-lookup"><span data-stu-id="5fac9-114">CName records controller can see for this hostname.</span></span></param>
        <param name="txtRecords"><span data-ttu-id="5fac9-115">TXT Records Controller kann für diesen Hostnamen finden Sie unter.</span><span class="sxs-lookup"><span data-stu-id="5fac9-115">TXT records controller can see for this hostname.</span></span></param>
        <param name="aRecords"><span data-ttu-id="5fac9-116">Ein Controller Datensätze kann für diesen Hostnamen finden Sie unter.</span><span class="sxs-lookup"><span data-stu-id="5fac9-116">A records controller can see for this hostname.</span></span></param>
        <param name="alternateCNameRecords"><span data-ttu-id="5fac9-117">Alternative CName-Datensätze Controller kann für diesen Hostnamen finden Sie unter.</span><span class="sxs-lookup"><span data-stu-id="5fac9-117">Alternate CName records controller can see for this hostname.</span></span></param>
        <param name="alternateTxtRecords"><span data-ttu-id="5fac9-118">Alternative TXT Records Controller kann für diesen Hostnamen finden Sie unter.</span><span class="sxs-lookup"><span data-stu-id="5fac9-118">Alternate TXT records controller can see for this hostname.</span></span></param>
        <summary>
            <span data-ttu-id="5fac9-119">Initialisiert eine neue Instanz der CustomHostnameAnalysisResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5fac9-119">Initializes a new instance of the CustomHostnameAnalysisResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlternateCNameRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AlternateCNameRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AlternateCNameRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.AlternateCNameRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property AlternateCNameRecords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AlternateCNameRecords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.AlternateCNameRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.alternateCNameRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fac9-120">Ruft ab, oder legt ihn fest alternativen CName-Datensätze Controller für diesen Hostnamen sehen kann.</span><span class="sxs-lookup"><span data-stu-id="5fac9-120">Gets or sets alternate CName records controller can see for this hostname.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlternateTxtRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AlternateTxtRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AlternateTxtRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.AlternateTxtRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property AlternateTxtRecords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AlternateTxtRecords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.AlternateTxtRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.alternateTxtRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fac9-121">Ruft ab, oder legt ihn fest alternativen TXT-Datensätze, die Controller für diesen Hostnamen sehen kann.</span><span class="sxs-lookup"><span data-stu-id="5fac9-121">Gets or sets alternate TXT records controller can see for this hostname.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ARecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ARecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ARecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.ARecords" />
      <MemberSignature Language="VB.NET" Value="Public Property ARecords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ARecords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.ARecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.aRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fac9-122">Ermittelt oder definiert einen Datensätze, die Controller für diesen Hostnamen sehen kann.</span><span class="sxs-lookup"><span data-stu-id="5fac9-122">Gets or sets a records controller can see for this hostname.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CNameRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; CNameRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; CNameRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.CNameRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property CNameRecords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.CNameRecords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.CNameRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cNameRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fac9-123">Ruft ab, oder legt ihn fest cName-Einträge, die Controller für diesen Hostnamen sehen kann.</span><span class="sxs-lookup"><span data-stu-id="5fac9-123">Gets or sets cName records controller can see for this hostname.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConflictingAppResourceId">
      <MemberSignature Language="C#" Value="public string ConflictingAppResourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConflictingAppResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.ConflictingAppResourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConflictingAppResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ConflictingAppResourceId : string" Usage="Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.ConflictingAppResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.conflictingAppResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fac9-124">Ruft Sie Namen in Konflikt stehende app auf Skalierungseinheit ab, wenn es innerhalb des gleichen Abonnements ist.</span><span class="sxs-lookup"><span data-stu-id="5fac9-124">Gets name of the conflicting app on scale unit if it's within the same subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomainVerificationFailureInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.ErrorEntity CustomDomainVerificationFailureInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.ErrorEntity CustomDomainVerificationFailureInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.CustomDomainVerificationFailureInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomDomainVerificationFailureInfo As ErrorEntity" />
      <MemberSignature Language="F#" Value="member this.CustomDomainVerificationFailureInfo : Microsoft.Azure.Management.WebSites.Models.ErrorEntity" Usage="Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.CustomDomainVerificationFailureInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customDomainVerificationFailureInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.ErrorEntity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fac9-125">Ruft unformatierten Fehlerinformationen ab, wenn der DNS-Überprüfung ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="5fac9-125">Gets raw failure information if DNS verification fails.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomainVerificationTest">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsVerificationTestResult&gt; CustomDomainVerificationTest { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.DnsVerificationTestResult&gt; CustomDomainVerificationTest" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.CustomDomainVerificationTest" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomDomainVerificationTest As Nullable(Of DnsVerificationTestResult)" />
      <MemberSignature Language="F#" Value="member this.CustomDomainVerificationTest : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsVerificationTestResult&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.CustomDomainVerificationTest" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customDomainVerificationTest")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DnsVerificationTestResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fac9-126">Ruft die DNS-Überprüfung Testergebnis ab.</span><span class="sxs-lookup"><span data-stu-id="5fac9-126">Gets DNS verification test result.</span></span> <span data-ttu-id="5fac9-127">Folgende Werte sind möglich: "Abgelaufen", "Fehlgeschlagen", "übersprungen"</span><span class="sxs-lookup"><span data-stu-id="5fac9-127">Possible values include: 'Passed', 'Failed', 'Skipped'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasConflictAcrossSubscription">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HasConflictAcrossSubscription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HasConflictAcrossSubscription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.HasConflictAcrossSubscription" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasConflictAcrossSubscription As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HasConflictAcrossSubscription : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.HasConflictAcrossSubscription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hasConflictAcrossSubscription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fac9-128">Ruft &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn ein Konflikt zwischen Abonnements; vorhanden ist, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="5fac9-128">Gets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if htere is a conflict across subscriptions; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasConflictOnScaleUnit">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HasConflictOnScaleUnit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HasConflictOnScaleUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.HasConflictOnScaleUnit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasConflictOnScaleUnit As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HasConflictOnScaleUnit : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.HasConflictOnScaleUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hasConflictOnScaleUnit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fac9-129">Ruft &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn ein Konflikt auf einer Skalierungseinheit; vorhanden ist, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="5fac9-129">Gets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if there is a conflict on a scale unit; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsHostnameAlreadyVerified">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsHostnameAlreadyVerified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsHostnameAlreadyVerified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.IsHostnameAlreadyVerified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsHostnameAlreadyVerified As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsHostnameAlreadyVerified : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.IsHostnameAlreadyVerified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isHostnameAlreadyVerified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fac9-130">Ruft &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn Hostname bereits überprüft; andernfalls wird &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="5fac9-130">Gets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if hostname is already verified; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TxtRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; TxtRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; TxtRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.TxtRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property TxtRecords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.TxtRecords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CustomHostnameAnalysisResult.TxtRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.txtRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fac9-131">Ruft ab, oder legt ihn fest TXT-Datensätze, die Controller für diesen Hostnamen sehen kann.</span><span class="sxs-lookup"><span data-stu-id="5fac9-131">Gets or sets TXT records controller can see for this hostname.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>