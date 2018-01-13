<Type Name="CorrelationFilter" FullName="Microsoft.ServiceBus.Messaging.CorrelationFilter">
  <TypeSignature Language="C#" Value="public sealed class CorrelationFilter : Microsoft.ServiceBus.Messaging.Filter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CorrelationFilter extends Microsoft.ServiceBus.Messaging.Filter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.CorrelationFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CorrelationFilter&#xA;Inherits Filter" />
  <TypeSignature Language="F#" Value="type CorrelationFilter = class&#xA;    inherit Filter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.Filter</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="CorrelationFilter", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.DateTimeOffset))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="cc419-101">Stellt den Filterausdruck für die Korrelation dar.</span><span class="sxs-lookup"><span data-stu-id="cc419-101">Represents the correlation filter expression.</span></span></summary>
    <remarks>
            <span data-ttu-id="cc419-102">Die CorrelationFilter verfügt über eine effiziente Tastenkombination für Deklarationen von Filtern, die nur mit Korrelation auf Gleichheit.</span><span class="sxs-lookup"><span data-stu-id="cc419-102">The CorrelationFilter provides an efficient shortcut for declarations of filters that deal only with correlation equality.</span></span> <span data-ttu-id="cc419-103">In diesem Fall kann die Kosten der Lexigraphical Analyse des Ausdrucks vermieden werden.</span><span class="sxs-lookup"><span data-stu-id="cc419-103">In this case the cost of the lexigraphical analysis of the expression can be avoided.</span></span>  
            <span data-ttu-id="cc419-104">Nicht nur werden zum Zeitpunkt der Deklaration korrelationsfilter optimiert werden, sondern wird auch zur Laufzeit optimiert werden.</span><span class="sxs-lookup"><span data-stu-id="cc419-104">Not only will correlation filters be optimized at declaration time, but they will also be optimized at runtime.</span></span> <span data-ttu-id="cc419-105">Korrelationszuordnung Filter kann auf eine Hashtabelle Suche reduziert werden die die Komplexität des Satzes von definierten korrelationsfilter aus, die o(1)-Einfüge-aggregiert.</span><span class="sxs-lookup"><span data-stu-id="cc419-105">Correlation filter matching can be reduced to a hashtable lookup, which aggregates the complexity of the set of defined correlation filters to O(1).</span></span> 
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorrelationFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.CorrelationFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="cc419-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.CorrelationFilter" />-Klasse mit Standardwerten.</span><span class="sxs-lookup"><span data-stu-id="cc419-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.CorrelationFilter" /> class with default values.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorrelationFilter (string correlationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string correlationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.CorrelationFilter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (correlationId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.CorrelationFilter : string -&gt; Microsoft.ServiceBus.Messaging.CorrelationFilter" Usage="new Microsoft.ServiceBus.Messaging.CorrelationFilter correlationId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="correlationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="correlationId"><span data-ttu-id="cc419-107">Der Bezeichner für die Korrelation.</span><span class="sxs-lookup"><span data-stu-id="cc419-107">The identifier for the correlation.</span></span></param>
        <summary><span data-ttu-id="cc419-108">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.CorrelationFilter" /> -Klasse mit der angegebenen Korrelations-ID.</span><span class="sxs-lookup"><span data-stu-id="cc419-108">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.CorrelationFilter" /> class with the specified correlation identifier.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="cc419-109">Wird ausgelöst, wenn die <paramref name="correlationId" /> ist null oder leer.</span><span class="sxs-lookup"><span data-stu-id="cc419-109">Thrown when the <paramref name="correlationId" /> is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.CorrelationFilter.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.ServiceBus.Messaging.CorrelationFilter.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="ContentType", Order=131079)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cc419-110">Ruft den Inhaltstyp der Nachricht ab.</span><span class="sxs-lookup"><span data-stu-id="cc419-110">Gets the content type of the message.</span></span> </summary>
        <value><span data-ttu-id="cc419-111">Der Inhaltstyp der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="cc419-111">The content type of the message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.CorrelationFilter.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.CorrelationFilter.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="CorrelationId", Order=65537)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cc419-112">Ruft den Bezeichner der Korrelation.</span><span class="sxs-lookup"><span data-stu-id="cc419-112">Gets the identifier of the correlation.</span></span></summary>
        <value><span data-ttu-id="cc419-113">Der Bezeichner der Korrelation.</span><span class="sxs-lookup"><span data-stu-id="cc419-113">The identifier of the correlation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.CorrelationFilter.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.ServiceBus.Messaging.CorrelationFilter.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Label", Order=131076)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cc419-114">Ruft die anwendungsspezifische Bezeichnung ab.</span><span class="sxs-lookup"><span data-stu-id="cc419-114">Gets the application specific label.</span></span></summary>
        <value><span data-ttu-id="cc419-115">Die anwendungsspezifische Bezeichnung.</span><span class="sxs-lookup"><span data-stu-id="cc419-115">The application specific label.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Match">
      <MemberSignature Language="C#" Value="public override bool Match (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Match(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.CorrelationFilter.Match(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Match (message As BrokeredMessage) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Match : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; bool" Usage="correlationFilter.Match message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="cc419-116">Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</span><span class="sxs-lookup"><span data-stu-id="cc419-116">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</span></span></param>
        <summary><span data-ttu-id="cc419-117">Gibt an, ob eine Nachricht anhand der aktuellen SQL-Ausdruck übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="cc419-117">Indicates whether a message matches against the current SQL expression.</span></span></summary>
        <returns><span data-ttu-id="cc419-118">"true", wenn eine Nachricht anhand der aktuellen SQL-Ausdruck entspricht; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="cc419-118">true if a message matches against the current SQL expression; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.CorrelationFilter.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.CorrelationFilter.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="MessageId", Order=131073)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cc419-119">Ruft den Bezeichner der Nachricht ab.</span><span class="sxs-lookup"><span data-stu-id="cc419-119">Gets the identifier of the message.</span></span></summary>
        <value><span data-ttu-id="cc419-120">Der Bezeichner der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="cc419-120">The identifier of the message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Preprocess">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceBus.Messaging.Filter Preprocess ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceBus.Messaging.Filter Preprocess() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.CorrelationFilter.Preprocess" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Preprocess () As Filter" />
      <MemberSignature Language="F#" Value="override this.Preprocess : unit -&gt; Microsoft.ServiceBus.Messaging.Filter" Usage="correlationFilter.Preprocess " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.Filter</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="cc419-121">Ruft den vorverarbeiteten Filterausdruck an.</span><span class="sxs-lookup"><span data-stu-id="cc419-121">Gets the preprocessed filter expression.</span></span></summary>
        <returns><span data-ttu-id="cc419-122">Der Filterausdruck vorverarbeitet.</span><span class="sxs-lookup"><span data-stu-id="cc419-122">The preprocessed filter expression.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.CorrelationFilter.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.CorrelationFilter.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cc419-123">Ruft die anwendungsspezifische Eigenschaften der Nachricht ab.</span><span class="sxs-lookup"><span data-stu-id="cc419-123">Gets the application specific properties of the message.</span></span></summary>
        <value><span data-ttu-id="cc419-124">Die Anwendung spezifischen Eigenschaften der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="cc419-124">The application specific properties of the message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.CorrelationFilter.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.CorrelationFilter.ReplyTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="ReplyTo", Order=131075)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cc419-125">Ruft die Adresse der Warteschlange, an die geantwortet.</span><span class="sxs-lookup"><span data-stu-id="cc419-125">Gets the address of the queue to reply to.</span></span></summary>
        <value><span data-ttu-id="cc419-126">Die Adresse der Warteschlange, an die geantwortet werden soll.</span><span class="sxs-lookup"><span data-stu-id="cc419-126">The address of the queue to reply to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.CorrelationFilter.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.CorrelationFilter.ReplyToSessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="ReplyToSessionId", Order=131078)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cc419-127">Ruft die Sitzungs-ID, um zu antworten.</span><span class="sxs-lookup"><span data-stu-id="cc419-127">Gets the session identifier to reply to.</span></span></summary>
        <value><span data-ttu-id="cc419-128">Die Sitzungs-ID, an die geantwortet werden soll.</span><span class="sxs-lookup"><span data-stu-id="cc419-128">The session identifier to reply to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresPreprocessing">
      <MemberSignature Language="C#" Value="public override bool RequiresPreprocessing { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresPreprocessing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.CorrelationFilter.RequiresPreprocessing" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RequiresPreprocessing As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresPreprocessing : bool" Usage="Microsoft.ServiceBus.Messaging.CorrelationFilter.RequiresPreprocessing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cc419-129">Ruft einen Wert, der angibt, ob die <see cref="T:Microsoft.ServiceBus.Messaging.CorrelationFilter" /> Ausdruck eine vorverarbeitung erfordert.</span><span class="sxs-lookup"><span data-stu-id="cc419-129">Gets a value indicating whether the <see cref="T:Microsoft.ServiceBus.Messaging.CorrelationFilter" /> expression requires preprocessing.</span></span></summary>
        <value><span data-ttu-id="cc419-130">True, wenn die <see cref="T:Microsoft.ServiceBus.Messaging.CorrelationFilter" /> Ausdruck erfordert den; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="cc419-130">true if the <see cref="T:Microsoft.ServiceBus.Messaging.CorrelationFilter" /> expression requires preprocessing; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.CorrelationFilter.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.CorrelationFilter.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="SessionId", Order=131077)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cc419-131">Ruft den Sitzungsbezeichner ab.</span><span class="sxs-lookup"><span data-stu-id="cc419-131">Gets the session identifier.</span></span></summary>
        <value><span data-ttu-id="cc419-132">Die Sitzungs-ID.</span><span class="sxs-lookup"><span data-stu-id="cc419-132">The session identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.CorrelationFilter.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.ServiceBus.Messaging.CorrelationFilter.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="To", Order=131074)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cc419-133">Ruft die Adresse an.</span><span class="sxs-lookup"><span data-stu-id="cc419-133">Gets the address to send to.</span></span></summary>
        <value><span data-ttu-id="cc419-134">Die Adresse an.</span><span class="sxs-lookup"><span data-stu-id="cc419-134">The address to send to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.CorrelationFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="correlationFilter.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="cc419-135">Konvertiert den Wert der aktuellen Instanz in die entsprechende Zeichenfolgendarstellung.</span><span class="sxs-lookup"><span data-stu-id="cc419-135">Converts the value of the current instance to its equivalent string representation.</span></span></summary>
        <returns><span data-ttu-id="cc419-136">Eine Zeichenfolgendarstellung der aktuellen Instanz.</span><span class="sxs-lookup"><span data-stu-id="cc419-136">A string representation of the current instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.CorrelationFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="correlationFilter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="cc419-137">Überprüft die <see cref="T:Microsoft.ServiceBus.Messaging.CorrelationFilter" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="cc419-137">Validates the <see cref="T:Microsoft.ServiceBus.Messaging.CorrelationFilter" /> object.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>