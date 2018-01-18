<Type Name="ServiceEndpointCollection" FullName="Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection">
  <TypeSignature Language="C#" Value="public sealed class ServiceEndpointCollection" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceEndpointCollection extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceEndpointCollection" />
  <TypeSignature Language="F#" Value="type ServiceEndpointCollection = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e44b7-101">Diese Klasse stellt die Endpunkte eines Diensts zuverlässige dar.</span><span class="sxs-lookup"><span data-stu-id="e44b7-101">This class represents the endpoints of a Reliable service.</span></span> <span data-ttu-id="e44b7-102">Jeder Endpunkt hat einen Listenernamen und die Adresse für diesen Listener.</span><span class="sxs-lookup"><span data-stu-id="e44b7-102">Each endpoint has a listener name and the address of that listener.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceEndpointCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e44b7-103">Instanziiert eine leere ServiceEndpointsCollection an.</span><span class="sxs-lookup"><span data-stu-id="e44b7-103">Instantiates an empty ServiceEndpointsCollection.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceEndpointCollection (string listenerName, string endpointAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string listenerName, string endpointAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (listenerName As String, endpointAddress As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection : string * string -&gt; Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection" Usage="new Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection (listenerName, endpointAddress)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="endpointAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="listenerName"><span data-ttu-id="e44b7-104">Verfügbarkeitsgruppenlistener-Namen des Endpunkts</span><span class="sxs-lookup"><span data-stu-id="e44b7-104">Listener name of the endpoint</span></span></param>
        <param name="endpointAddress"><span data-ttu-id="e44b7-105">Adresse des Endpunkts</span><span class="sxs-lookup"><span data-stu-id="e44b7-105">Address of the endpoint</span></span></param>
        <summary>
            <span data-ttu-id="e44b7-106">Instanziiert die ServiceEndpointsCollection mit einem einzelnen Endpunkt, identifiziert durch den Namen des Listeners an.</span><span class="sxs-lookup"><span data-stu-id="e44b7-106">Instantiates the ServiceEndpointsCollection with a single endpoint, identified by the listener name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddEndpoint">
      <MemberSignature Language="C#" Value="public void AddEndpoint (string listenerName, string endpointAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddEndpoint(string listenerName, string endpointAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.AddEndpoint(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddEndpoint (listenerName As String, endpointAddress As String)" />
      <MemberSignature Language="F#" Value="member this.AddEndpoint : string * string -&gt; unit" Usage="serviceEndpointCollection.AddEndpoint (listenerName, endpointAddress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="endpointAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="listenerName"><span data-ttu-id="e44b7-107">Verfügbarkeitsgruppenlistener-Namen des Endpunkts</span><span class="sxs-lookup"><span data-stu-id="e44b7-107">Listener name of the endpoint</span></span></param>
        <param name="endpointAddress"><span data-ttu-id="e44b7-108">Adresse des Endpunkts</span><span class="sxs-lookup"><span data-stu-id="e44b7-108">Address of the endpoint</span></span></param>
        <summary>
            <span data-ttu-id="e44b7-109">Die EndpointsCollection hinzugefügt einen Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="e44b7-109">Adds an endpoint to the EndpointsCollection.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddEndpoints">
      <MemberSignature Language="C#" Value="public void AddEndpoints (Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection newEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddEndpoints(class Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection newEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.AddEndpoints(Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddEndpoints (newEndpoints As ServiceEndpointCollection)" />
      <MemberSignature Language="F#" Value="member this.AddEndpoints : Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection -&gt; unit" Usage="serviceEndpointCollection.AddEndpoints newEndpoints" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newEndpoints" Type="Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection" />
      </Parameters>
      <Docs>
        <param name="newEndpoints"><span data-ttu-id="e44b7-110">Eingabe EndpointsCollection</span><span class="sxs-lookup"><span data-stu-id="e44b7-110">input EndpointsCollection</span></span></param>
        <summary>
            <span data-ttu-id="e44b7-111">Die EndpointsCollection hinzugefügt die Endpunkte in der Eingabe EndpointsCollection-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e44b7-111">Adds the endpoints in the input EndpointsCollection class to the EndpointsCollection.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToReadOnlyDictionary">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; ToReadOnlyDictionary ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; ToReadOnlyDictionary() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.ToReadOnlyDictionary" />
      <MemberSignature Language="VB.NET" Value="Public Function ToReadOnlyDictionary () As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.ToReadOnlyDictionary : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="serviceEndpointCollection.ToReadOnlyDictionary " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e44b7-112">Gibt eine ReadOnlyDictionary von der EndpointsCollection zurück.</span><span class="sxs-lookup"><span data-stu-id="e44b7-112">Returns a ReadOnlyDictionary of the endpointsCollection.</span></span>
            </summary>
        <returns><span data-ttu-id="e44b7-113">EndpointsCollection als eine ReadOnlyDictionary</span><span class="sxs-lookup"><span data-stu-id="e44b7-113">EndpointsCollection as a ReadOnlyDictionary</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceEndpointCollection.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e44b7-114">Konvertiert die EndpointsCollection in eine JSON-Zeichenfolge des Formulars {"Endpunkte": {"Listener1": "Endpoint1", "Listener2": "Endpoint2"...}}</span><span class="sxs-lookup"><span data-stu-id="e44b7-114">Converts the endpointsCollection to a JSON string of the form {"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</span></span>
            </summary>
        <returns><span data-ttu-id="e44b7-115">Von der EndpointsCollection in Form einer Zeichenfolge</span><span class="sxs-lookup"><span data-stu-id="e44b7-115">String form of the endpointsCollection</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetEndpointAddress">
      <MemberSignature Language="C#" Value="public bool TryGetEndpointAddress (string listenerName, out string endpointAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetEndpointAddress(string listenerName, [out] string&amp; endpointAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.TryGetEndpointAddress(System.String,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetEndpointAddress (listenerName As String, ByRef endpointAddress As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetEndpointAddress : string *  -&gt; bool" Usage="serviceEndpointCollection.TryGetEndpointAddress (listenerName, endpointAddress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="endpointAddress" Type="System.String&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="listenerName"><span data-ttu-id="e44b7-116">Name des Listeners</span><span class="sxs-lookup"><span data-stu-id="e44b7-116">Listener name</span></span></param>
        <param name="endpointAddress"><span data-ttu-id="e44b7-117">Die Adresse des Endpunkts, wenn ein Endpunkt mit diesem Listenernamen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="e44b7-117">Address of the endpoint if an endpoint with that listener name exists.</span></span></param>
        <summary>
            <span data-ttu-id="e44b7-118">Ruft den Endpunkt identifiziert durch den Namen des Listeners an.</span><span class="sxs-lookup"><span data-stu-id="e44b7-118">Gets the endpoint identified by the listener name.</span></span>
            </summary>
        <returns><span data-ttu-id="e44b7-119">True, wenn ein Endpunkt mit dem Namen des Listeners "false" vorhanden, andernfalls ist</span><span class="sxs-lookup"><span data-stu-id="e44b7-119">True if an endpoint with the listener name exists, False otherwise</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetFirstEndpointAddress">
      <MemberSignature Language="C#" Value="public bool TryGetFirstEndpointAddress (out string endpointAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetFirstEndpointAddress([out] string&amp; endpointAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.TryGetFirstEndpointAddress(System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetFirstEndpointAddress (ByRef endpointAddress As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetFirstEndpointAddress :  -&gt; bool" Usage="serviceEndpointCollection.TryGetFirstEndpointAddress endpointAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.String&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="e44b7-120">Erste Endpunkt in der EndpointsCollection</span><span class="sxs-lookup"><span data-stu-id="e44b7-120">First endpoint in the EndpointsCollection</span></span></param>
        <summary>
            <span data-ttu-id="e44b7-121">Ruft die erste Adresse des Endpunkts in der EndpointsCollection ab.</span><span class="sxs-lookup"><span data-stu-id="e44b7-121">Gets the first endpoint address in the EndpointsCollection.</span></span>
            </summary>
        <returns><span data-ttu-id="e44b7-122">True, wenn es mindestens einen Endpunkt in der EndpointsCollection "false" andernfalls</span><span class="sxs-lookup"><span data-stu-id="e44b7-122">True if there is at-least one endpoint in the EndpointsCollection, false otherwise</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryParseEndpointsString">
      <MemberSignature Language="C#" Value="public static bool TryParseEndpointsString (string endpointsString, out Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection serviceEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryParseEndpointsString(string endpointsString, [out] class Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection&amp; serviceEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.TryParseEndpointsString(System.String,Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryParseEndpointsString (endpointsString As String, ByRef serviceEndpoints As ServiceEndpointCollection) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryParseEndpointsString : string *  -&gt; bool" Usage="Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.TryParseEndpointsString (endpointsString, serviceEndpoints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointsString" Type="System.String" />
        <Parameter Name="serviceEndpoints" Type="Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="endpointsString"><span data-ttu-id="e44b7-123">der EndpointsCollection in Form einer Zeichenfolge</span><span class="sxs-lookup"><span data-stu-id="e44b7-123">string form of endpointsCollection</span></span></param>
        <param name="serviceEndpoints"><span data-ttu-id="e44b7-124">ServiceEndpointCollection-Objekt, wenn die Zeichenfolge kann, um ein gültiges ServiceEndpointCollection-Objekt analysiert werden</span><span class="sxs-lookup"><span data-stu-id="e44b7-124">ServiceEndpointCollection object if the string can be parsed to a valid ServiceEndpointCollection object</span></span></param>
        <summary>
            <span data-ttu-id="e44b7-125">Erstellt eine EndpointsCollection aus eine Zeichenfolgenversion der Endpunkte.</span><span class="sxs-lookup"><span data-stu-id="e44b7-125">Constructs an EndpointsCollection from a string version of the endpoints.</span></span> <span data-ttu-id="e44b7-126">Der EndpointsCollection in Form einer Zeichenfolge im Format ist {"Endpunkte": {"Listener1": "Endpoint1", "Listener2": "Endpoint2"...}}</span><span class="sxs-lookup"><span data-stu-id="e44b7-126">String form of EndpointsCollection is of the form {"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</span></span>
            </summary>
        <returns><span data-ttu-id="e44b7-127">"True", wenn die Zeichenfolge andernfalls zu einem gültigen EndpointsCollection, "false" analysiert werden kann</span><span class="sxs-lookup"><span data-stu-id="e44b7-127">True if the string can be parsed to a valid EndpointsCollection, False otherwise</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>