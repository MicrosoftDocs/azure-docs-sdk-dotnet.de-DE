<Type Name="RampUpRule" FullName="Microsoft.Azure.Management.WebSites.Models.RampUpRule">
  <TypeSignature Language="C#" Value="public class RampUpRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RampUpRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.RampUpRule" />
  <TypeSignature Language="VB.NET" Value="Public Class RampUpRule" />
  <TypeSignature Language="F#" Value="type RampUpRule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cb991-101">Verteilerregeln für Ramp-up testen.</span><span class="sxs-lookup"><span data-stu-id="cb991-101">Routing rules for ramp up testing.</span></span> <span data-ttu-id="cb991-102">Mit dieser Regel können statische Datenverkehr % in einem Einschubfach umleiten oder allmählich routing % basierend auf der Leistung zu ändern.</span><span class="sxs-lookup"><span data-stu-id="cb991-102">This rule allows to redirect static traffic % to a slot or to gradually change routing % based on performance.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RampUpRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RampUpRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cb991-103">Initialisiert eine neue Instanz der RampUpRule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cb991-103">Initializes a new instance of the RampUpRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RampUpRule (string actionHostName = null, Nullable&lt;double&gt; reroutePercentage = null, Nullable&lt;double&gt; changeStep = null, Nullable&lt;int&gt; changeIntervalInMinutes = null, Nullable&lt;double&gt; minReroutePercentage = null, Nullable&lt;double&gt; maxReroutePercentage = null, string changeDecisionCallbackUrl = null, string name = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string actionHostName, valuetype System.Nullable`1&lt;float64&gt; reroutePercentage, valuetype System.Nullable`1&lt;float64&gt; changeStep, valuetype System.Nullable`1&lt;int32&gt; changeIntervalInMinutes, valuetype System.Nullable`1&lt;float64&gt; minReroutePercentage, valuetype System.Nullable`1&lt;float64&gt; maxReroutePercentage, string changeDecisionCallbackUrl, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RampUpRule.#ctor(System.String,System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Int32},System.Nullable{System.Double},System.Nullable{System.Double},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional actionHostName As String = null, Optional reroutePercentage As Nullable(Of Double) = null, Optional changeStep As Nullable(Of Double) = null, Optional changeIntervalInMinutes As Nullable(Of Integer) = null, Optional minReroutePercentage As Nullable(Of Double) = null, Optional maxReroutePercentage As Nullable(Of Double) = null, Optional changeDecisionCallbackUrl As String = null, Optional name As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.RampUpRule : string * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;int&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.RampUpRule" Usage="new Microsoft.Azure.Management.WebSites.Models.RampUpRule (actionHostName, reroutePercentage, changeStep, changeIntervalInMinutes, minReroutePercentage, maxReroutePercentage, changeDecisionCallbackUrl, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actionHostName" Type="System.String" />
        <Parameter Name="reroutePercentage" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="changeStep" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="changeIntervalInMinutes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="minReroutePercentage" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="maxReroutePercentage" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="changeDecisionCallbackUrl" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actionHostName"><span data-ttu-id="cb991-104">Hostname des einen Slot, der Datenverkehr umgeleitet wird, wenn entschieden.</span><span class="sxs-lookup"><span data-stu-id="cb991-104">Hostname of a slot to which the traffic will be redirected if decided to.</span></span> <span data-ttu-id="cb991-105">Beispiel:</span><span class="sxs-lookup"><span data-stu-id="cb991-105">E.g.</span></span>
            <span data-ttu-id="cb991-106">"MyApp"-stage.azurewebsites.net.</span><span class="sxs-lookup"><span data-stu-id="cb991-106">myapp-stage.azurewebsites.net.</span></span></param>
        <param name="reroutePercentage"><span data-ttu-id="cb991-107">Prozentsatz des Datenverkehrs dem umgeleitet wird, &lt;Code&gt;ActionHostName&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="cb991-107">Percentage of the traffic which will be redirected to &lt;code&gt;ActionHostName&lt;/code&gt;.</span></span></param>
        <param name="changeStep"><span data-ttu-id="cb991-108">In Automatisches Ramp-up Szenario ist dies der Schritt zum Hinzufügen/Entfernen von &lt;Code&gt;ReroutePercentage&lt;/code&gt; bis erreicht &lt;Code&gt;MinReroutePercentage &lt; /code &gt; oder &lt;Code&gt;MaxReroutePercentage&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="cb991-108">In auto ramp up scenario this is the step to to add/remove from &lt;code&gt;ReroutePercentage&lt;/code&gt; until it reaches &lt;code&gt;MinReroutePercentage&lt;/code&gt; or &lt;code&gt;MaxReroutePercentage&lt;/code&gt;.</span></span> <span data-ttu-id="cb991-109">Standortmetriken werden überprüft alle N Minuten angegebene in &lt;Code&gt;ChangeIntervalInMinutes&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="cb991-109">Site metrics are checked every N minutes specificed in &lt;code&gt;ChangeIntervalInMinutes&lt;/code&gt;.</span></span>
            <span data-ttu-id="cb991-110">Benutzerdefinierte Decision-Algorithmus kann bereitgestellt werden, in TiPCallback-Website-Erweiterung, die URL angegeben werden kann &lt;Code&gt;ChangeDecisionCallbackUrl&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="cb991-110">Custom decision algorithm can be provided in TiPCallback site extension which URL can be specified in &lt;code&gt;ChangeDecisionCallbackUrl&lt;/code&gt;.</span></span></param>
        <param name="changeIntervalInMinutes"><span data-ttu-id="cb991-111">Gibt Intervall in Mimuntes ReroutePercentage auswertet.</span><span class="sxs-lookup"><span data-stu-id="cb991-111">Specifies interval in mimuntes to reevaluate ReroutePercentage.</span></span></param>
        <param name="minReroutePercentage"><span data-ttu-id="cb991-112">Gibt die untere Grenze höher die ReroutePercentage verbleibt.</span><span class="sxs-lookup"><span data-stu-id="cb991-112">Specifies lower boundary above which ReroutePercentage will stay.</span></span></param>
        <param name="maxReroutePercentage"><span data-ttu-id="cb991-113">Gibt an, obere Grenze unten die ReroutePercentage verbleibt.</span><span class="sxs-lookup"><span data-stu-id="cb991-113">Specifies upper boundary below which ReroutePercentage will stay.</span></span></param>
        <param name="changeDecisionCallbackUrl"><span data-ttu-id="cb991-114">Benutzerdefinierte Decision-Algorithmus kann in TiPCallback websiteerweiterung bereitgestellt werden, der URL angegeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="cb991-114">Custom decision algorithm can be provided in TiPCallback site extension which URL can be specified.</span></span> <span data-ttu-id="cb991-115">Finden Sie unter TiPCallback websiteerweiterung für das Gerüst und Verträge.</span><span class="sxs-lookup"><span data-stu-id="cb991-115">See TiPCallback site extension for the scaffold and contracts.</span></span>
            <span data-ttu-id="cb991-116">https://www.siteextensions.NET/Packages/TiPCallback/</span><span class="sxs-lookup"><span data-stu-id="cb991-116">https://www.siteextensions.net/packages/TiPCallback/</span></span></param>
        <param name="name"><span data-ttu-id="cb991-117">Name der Regel für das routing.</span><span class="sxs-lookup"><span data-stu-id="cb991-117">Name of the routing rule.</span></span> <span data-ttu-id="cb991-118">Der empfohlene Name wäre, in das Einschubfach verweisen, die der Datenverkehr im Experiment empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="cb991-118">The recommended name would be to point to the slot which will receive the traffic in the experiment.</span></span></param>
        <summary>
            <span data-ttu-id="cb991-119">Initialisiert eine neue Instanz der RampUpRule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cb991-119">Initializes a new instance of the RampUpRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionHostName">
      <MemberSignature Language="C#" Value="public string ActionHostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActionHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RampUpRule.ActionHostName" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionHostName As String" />
      <MemberSignature Language="F#" Value="member this.ActionHostName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RampUpRule.ActionHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actionHostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb991-120">Ruft ab, oder legt ihn fest-Hostnamen des einen Slot, der Datenverkehr umgeleitet wird, wenn beschlossen.</span><span class="sxs-lookup"><span data-stu-id="cb991-120">Gets or sets hostname of a slot to which the traffic will be redirected if decided to.</span></span> <span data-ttu-id="cb991-121">Beispiel:</span><span class="sxs-lookup"><span data-stu-id="cb991-121">E.g.</span></span> <span data-ttu-id="cb991-122">"MyApp"-stage.azurewebsites.net.</span><span class="sxs-lookup"><span data-stu-id="cb991-122">myapp-stage.azurewebsites.net.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeDecisionCallbackUrl">
      <MemberSignature Language="C#" Value="public string ChangeDecisionCallbackUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ChangeDecisionCallbackUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RampUpRule.ChangeDecisionCallbackUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property ChangeDecisionCallbackUrl As String" />
      <MemberSignature Language="F#" Value="member this.ChangeDecisionCallbackUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RampUpRule.ChangeDecisionCallbackUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="changeDecisionCallbackUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb991-123">Ruft ab oder legt sie fest benutzerdefinierten Decision-Algorithmus in TiPCallback bereitgestellt werden kann websiteerweiterung der URL angegeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="cb991-123">Gets or sets custom decision algorithm can be provided in TiPCallback site extension which URL can be specified.</span></span> <span data-ttu-id="cb991-124">Finden Sie unter TiPCallback websiteerweiterung für das Gerüst und Verträge.</span><span class="sxs-lookup"><span data-stu-id="cb991-124">See TiPCallback site extension for the scaffold and contracts.</span></span>
            <span data-ttu-id="cb991-125">https://www.siteextensions.NET/Packages/TiPCallback/</span><span class="sxs-lookup"><span data-stu-id="cb991-125">https://www.siteextensions.net/packages/TiPCallback/</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeIntervalInMinutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ChangeIntervalInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ChangeIntervalInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RampUpRule.ChangeIntervalInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property ChangeIntervalInMinutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ChangeIntervalInMinutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RampUpRule.ChangeIntervalInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="changeIntervalInMinutes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb991-126">Ruft ab oder legt gibt Intervall in Mimuntes ReroutePercentage auswertet.</span><span class="sxs-lookup"><span data-stu-id="cb991-126">Gets or sets specifies interval in mimuntes to reevaluate ReroutePercentage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeStep">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; ChangeStep { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; ChangeStep" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RampUpRule.ChangeStep" />
      <MemberSignature Language="VB.NET" Value="Public Property ChangeStep As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.ChangeStep : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RampUpRule.ChangeStep" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="changeStep")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb991-127">Ruft ab oder legt fest, in Automatisches Ramp-up Szenario dies der Schritt zum Hinzufügen ist/Entfernen von &amp;Lt; Code&amp;Gt; ReroutePercentage&amp;Lt; / code&amp;Gt; bis erreicht &amp;Lt; Code&amp;Gt; MinReroutePercentage&amp;Lt; / code&amp;Gt; oder &amp;Lt; Code&amp;Gt; MaxReroutePercentage&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="cb991-127">Gets or sets in auto ramp up scenario this is the step to to add/remove from &amp;lt;code&amp;gt;ReroutePercentage&amp;lt;/code&amp;gt; until it reaches &amp;lt;code&amp;gt;MinReroutePercentage&amp;lt;/code&amp;gt; or &amp;lt;code&amp;gt;MaxReroutePercentage&amp;lt;/code&amp;gt;.</span></span> <span data-ttu-id="cb991-128">Standortmetriken werden überprüft alle N Minuten angegebene in &amp;Lt; Code&amp;Gt; ChangeIntervalInMinutes&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="cb991-128">Site metrics are checked every N minutes specificed in &amp;lt;code&amp;gt;ChangeIntervalInMinutes&amp;lt;/code&amp;gt;.</span></span>
            <span data-ttu-id="cb991-129">Benutzerdefinierte Decision-Algorithmus kann bereitgestellt werden, in TiPCallback-Website-Erweiterung, die URL angegeben werden kann &amp;Lt; Code&amp;Gt; ChangeDecisionCallbackUrl&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="cb991-129">Custom decision algorithm can be provided in TiPCallback site extension which URL can be specified in &amp;lt;code&amp;gt;ChangeDecisionCallbackUrl&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReroutePercentage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MaxReroutePercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MaxReroutePercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RampUpRule.MaxReroutePercentage" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReroutePercentage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MaxReroutePercentage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RampUpRule.MaxReroutePercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxReroutePercentage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb991-130">Ruft ab oder legt gibt Obergrenze unten die ReroutePercentage verbleibt.</span><span class="sxs-lookup"><span data-stu-id="cb991-130">Gets or sets specifies upper boundary below which ReroutePercentage will stay.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinReroutePercentage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MinReroutePercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MinReroutePercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RampUpRule.MinReroutePercentage" />
      <MemberSignature Language="VB.NET" Value="Public Property MinReroutePercentage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MinReroutePercentage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RampUpRule.MinReroutePercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minReroutePercentage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb991-131">Ruft ab oder legt ihn fest gibt die untere Grenze höher die ReroutePercentage verbleibt an.</span><span class="sxs-lookup"><span data-stu-id="cb991-131">Gets or sets specifies lower boundary above which ReroutePercentage will stay.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RampUpRule.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RampUpRule.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb991-132">Ruft ab oder legt den Namen der Regel routing fest.</span><span class="sxs-lookup"><span data-stu-id="cb991-132">Gets or sets name of the routing rule.</span></span> <span data-ttu-id="cb991-133">Der empfohlene Name wäre, in das Einschubfach verweisen, die der Datenverkehr im Experiment empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="cb991-133">The recommended name would be to point to the slot which will receive the traffic in the experiment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReroutePercentage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; ReroutePercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; ReroutePercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RampUpRule.ReroutePercentage" />
      <MemberSignature Language="VB.NET" Value="Public Property ReroutePercentage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.ReroutePercentage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RampUpRule.ReroutePercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reroutePercentage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb991-134">Ruft ab oder legt ihn fest Prozentsatz des Datenverkehrs dem umgeleitet wird, &amp;Lt; Code&amp;Gt; ActionHostName&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="cb991-134">Gets or sets percentage of the traffic which will be redirected to &amp;lt;code&amp;gt;ActionHostName&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>