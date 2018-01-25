<Type Name="CorrelationFilter" FullName="Microsoft.Azure.ServiceBus.CorrelationFilter">
  <TypeSignature Language="C#" Value="public sealed class CorrelationFilter : Microsoft.Azure.ServiceBus.Filter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CorrelationFilter extends Microsoft.Azure.ServiceBus.Filter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.CorrelationFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CorrelationFilter&#xA;Inherits Filter" />
  <TypeSignature Language="F#" Value="type CorrelationFilter = class&#xA;    inherit Filter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.Filter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dfeb4-101">Stellt den Filterausdruck für die Korrelation dar.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-101">Represents the correlation filter expression.</span></span>
            </summary>
    <remarks>
      <para>
            <span data-ttu-id="dfeb4-102">Eine CorrelationFilter enthält eine Reihe von Bedingungen, die mit einem oder mehreren der Benutzer- und Systemeigenschaften einer eingehenden Nachricht abgeglichen werden.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-102">A CorrelationFilter holds a set of conditions that are matched against one of more of an arriving message's user and system properties.</span></span>
            <span data-ttu-id="dfeb4-103">Eine übliche Verwendung wird eine Übereinstimmung für die <see cref="P:Microsoft.Azure.ServiceBus.Message.CorrelationId" /> -Eigenschaft, die Anwendung jedoch auch die Möglichkeit, für den Vergleich <see cref="P:Microsoft.Azure.ServiceBus.Message.ContentType" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.Label" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.MessageId" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyTo" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyToSessionId" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.To" />, und ein beliebiger Benutzerdefinierte Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-103">A common use is a match against the <see cref="P:Microsoft.Azure.ServiceBus.Message.CorrelationId" /> property, but the application can also choose to match against <see cref="P:Microsoft.Azure.ServiceBus.Message.ContentType" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.Label" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.MessageId" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyTo" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyToSessionId" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.To" />, and any user-defined properties.</span></span>
            <span data-ttu-id="dfeb4-104">Eine Übereinstimmung liegt vor, wenn der Wert einer Eigenschaft einer eingehenden Nachricht gleich dem im Korrelationsfilter angegebenen Wert ist.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-104">A match exists when an arriving message's value for a property is equal to the value specified in the correlation filter.</span></span> <span data-ttu-id="dfeb4-105">Für Zeichenfolgenausdrücke wird beim Vergleich die Groß-/Kleinschreibung beachtet.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-105">For string expressions, the comparison is case-sensitive.</span></span> <span data-ttu-id="dfeb4-106">Wenn Sie mehrere Übereinstimmung Eigenschaften angeben, fasst der Filter als einer logischen AND-Bedingung, was bedeutet, dass alle Bedingungen für den Filter entsprechend übereinstimmen müssen.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-106">When specifying multiple match properties, the filter combines them as a logical AND condition, meaning all conditions must match for the filter to match.</span></span>
            </para>
      <para>
            <span data-ttu-id="dfeb4-107">Die CorrelationFilter verfügt über eine effiziente Tastenkombination für Deklarationen von Filtern, die nur mit Korrelation auf Gleichheit.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-107">The CorrelationFilter provides an efficient shortcut for declarations of filters that deal only with correlation equality.</span></span>
            <span data-ttu-id="dfeb4-108">In diesem Fall kann die Kosten der Lexigraphical Analyse des Ausdrucks vermieden werden.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-108">In this case the cost of the lexigraphical analysis of the expression can be avoided.</span></span>
            <span data-ttu-id="dfeb4-109">Nicht nur werden zum Zeitpunkt der Deklaration korrelationsfilter optimiert werden, sondern wird auch zur Laufzeit optimiert werden.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-109">Not only will correlation filters be optimized at declaration time, but they will also be optimized at runtime.</span></span>
            <span data-ttu-id="dfeb4-110">Korrelationszuordnung Filter kann auf eine Hashtabelle Suche reduziert werden die die Komplexität des Satzes von definierten korrelationsfilter aus, die o(1)-Einfüge-aggregiert.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-110">Correlation filter matching can be reduced to a hashtable lookup, which aggregates the complexity of the set of defined correlation filters to O(1).</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorrelationFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.CorrelationFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dfeb4-111">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.ServiceBus.CorrelationFilter" />-Klasse mit Standardwerten.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-111">Initializes a new instance of the <see cref="T:Microsoft.Azure.ServiceBus.CorrelationFilter" /> class with default values.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorrelationFilter (string correlationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string correlationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.CorrelationFilter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (correlationId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.CorrelationFilter : string -&gt; Microsoft.Azure.ServiceBus.CorrelationFilter" Usage="new Microsoft.Azure.ServiceBus.CorrelationFilter correlationId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="correlationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="correlationId"><span data-ttu-id="dfeb4-112">Der Bezeichner für die Korrelation.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-112">The identifier for the correlation.</span></span></param>
        <summary>
            <span data-ttu-id="dfeb4-113">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.ServiceBus.CorrelationFilter" /> -Klasse mit der angegebenen Korrelations-ID.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-113">Initializes a new instance of the <see cref="T:Microsoft.Azure.ServiceBus.CorrelationFilter" /> class with the specified correlation identifier.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="dfeb4-114">Wird ausgelöst, wenn die <paramref name="correlationId" /> ist null oder leer.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-114">Thrown when the <paramref name="correlationId" /> is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dfeb4-115">Der Inhaltstyp der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-115">Content type of the message.</span></span>
            </summary>
        <value><span data-ttu-id="dfeb4-116">Der Inhaltstyp der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-116">The content type of the message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dfeb4-117">ID der Korrelation</span><span class="sxs-lookup"><span data-stu-id="dfeb4-117">Identifier of the correlation.</span></span>
            </summary>
        <value><span data-ttu-id="dfeb4-118">Der Bezeichner der Korrelation.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-118">The identifier of the correlation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dfeb4-119">Anwendungsspezifische Bezeichnung.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-119">Application specific label.</span></span>
            </summary>
        <value><span data-ttu-id="dfeb4-120">Die anwendungsspezifische Bezeichnung.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-120">The application specific label.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dfeb4-121">Der Bezeichner der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-121">Identifier of the message.</span></span>
            </summary>
        <value><span data-ttu-id="dfeb4-122">Der Bezeichner der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-122">The identifier of the message.</span></span></value>
        <remarks><span data-ttu-id="dfeb4-123">Max. MessageId-Größe beträgt 128 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-123">Max MessageId size is 128 chars.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dfeb4-124">Anwendungsspezifische Eigenschaften der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-124">Application specific properties of the message.</span></span>
            </summary>
        <value><span data-ttu-id="dfeb4-125">Die Anwendung spezifischen Eigenschaften der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-125">The application specific properties of the message.</span></span></value>
        <remarks>
            <span data-ttu-id="dfeb4-126">Nur nach Wert Typen werden unterstützt: Byte, Sbyte, Char, Short, Ushort, Int, "uint", long, Ulong, Float, double, Decimal, Bool, Guid, Zeichenfolge, Uri, "DateTime", "DateTimeOffset", TimeSpan, Stream, Byte [] und IList / IDictionary von unterstützte Typen</span><span class="sxs-lookup"><span data-stu-id="dfeb4-126">Only following value types are supported: byte, sbyte, char, short, ushort, int, uint, long, ulong, float, double, decimal, bool, Guid, string, Uri, DateTime, DateTimeOffset, TimeSpan, Stream, byte[], and IList / IDictionary of supported types</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.ReplyTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dfeb4-127">Warteschlangenadresse für die Antwort.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-127">Address of the queue to reply to.</span></span>
            </summary>
        <value><span data-ttu-id="dfeb4-128">Die Adresse der Warteschlange, an die geantwortet werden soll.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-128">The address of the queue to reply to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.ReplyToSessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dfeb4-129">Sitzungs-ID, um zu antworten.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-129">Session identifier to reply to.</span></span>
            </summary>
        <value><span data-ttu-id="dfeb4-130">Die Sitzungs-ID, an die geantwortet werden soll.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-130">The session identifier to reply to.</span></span></value>
        <remarks><span data-ttu-id="dfeb4-131">Max. Größe der ReplyToSessionId ist 128.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-131">Max size of ReplyToSessionId is 128.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dfeb4-132">Sitzungs-ID.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-132">Session identifier.</span></span>
            </summary>
        <value><span data-ttu-id="dfeb4-133">Die Sitzungs-ID.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-133">The session identifier.</span></span></value>
        <remarks><span data-ttu-id="dfeb4-134">Max. Größe der SessionId beträgt 128 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-134">Max size of sessionId is 128 chars.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dfeb4-135">Zieladresse.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-135">Address to send to.</span></span>
            </summary>
        <value><span data-ttu-id="dfeb4-136">Die Adresse an.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-136">The address to send to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.CorrelationFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="correlationFilter.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dfeb4-137">Konvertiert den Wert der aktuellen Instanz in die entsprechende Zeichenfolgendarstellung.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-137">Converts the value of the current instance to its equivalent string representation.</span></span>
            </summary>
        <returns><span data-ttu-id="dfeb4-138">Eine Zeichenfolgendarstellung der aktuellen Instanz.</span><span class="sxs-lookup"><span data-stu-id="dfeb4-138">A string representation of the current instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>