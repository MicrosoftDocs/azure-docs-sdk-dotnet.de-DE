<Type Name="Document" FullName="Microsoft.Azure.Documents.Document">
  <TypeSignature Language="C#" Value="public class Document : Microsoft.Azure.Documents.Resource, System.Dynamic.IDynamicMetaObjectProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Document extends Microsoft.Azure.Documents.Resource implements class System.Dynamic.IDynamicMetaObjectProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Document" />
  <TypeSignature Language="VB.NET" Value="Public Class Document&#xA;Inherits Resource&#xA;Implements IDynamicMetaObjectProvider" />
  <TypeSignature Language="F#" Value="type Document = class&#xA;    inherit Resource&#xA;    interface IDynamicMetaObjectProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Dynamic.IDynamicMetaObjectProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="67c14-101">Stellt ein Dokument in der Azure-Cosmos-DB-Dienst dar.</span><span class="sxs-lookup"><span data-stu-id="67c14-101">Represents a document in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks> 
            <span data-ttu-id="67c14-102">Ein Dokument ist eine strukturierte JSON-Dokument.</span><span class="sxs-lookup"><span data-stu-id="67c14-102">A document is a structured JSON document.</span></span> <span data-ttu-id="67c14-103">Es gibt kein Schema Satz für die JSON-Dokumente, und ein Dokument kann eine beliebige Anzahl von benutzerdefinierten Eigenschaften sowie eine optionale Liste von Anlagen enthalten.</span><span class="sxs-lookup"><span data-stu-id="67c14-103">There is no set schema for the JSON documents, and a document may contain any number of custom properties as well as an optional list of attachments.</span></span> <span data-ttu-id="67c14-104">Dokument ist eine Anwendungsressource und mit dem Hauptschlüssel oder / / Ressourcenschlüssel autorisiert werden kann.</span><span class="sxs-lookup"><span data-stu-id="67c14-104">Document is an application resource and can be authorized using the master key or resource keys.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Document ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Document.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="67c14-105">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Document" /> Klasse für den Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="67c14-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Document" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AttachmentsLink">
      <MemberSignature Language="C#" Value="public string AttachmentsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AttachmentsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Document.AttachmentsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AttachmentsLink As String" />
      <MemberSignature Language="F#" Value="member this.AttachmentsLink : string" Usage="Microsoft.Azure.Documents.Document.AttachmentsLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67c14-106">Ruft ab, der Self-link entsprechenden Anlagen des Dokuments aus dem Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="67c14-106">Gets the self-link corresponding to attachments of the document from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="67c14-107">Die Self-link, entspricht die Anlagen des Dokuments.</span><span class="sxs-lookup"><span data-stu-id="67c14-107">The self-link corresponding to attachments of the document.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="67c14-108">Jedes Dokument kann zwischen 0 (null) und viele Anhänge aufweisen.</span><span class="sxs-lookup"><span data-stu-id="67c14-108">Every document can have between zero and many attachments.</span></span> <span data-ttu-id="67c14-109">Der Anlagen-Link enthält einen Feed von Anlagen, die auf das Dokument gehören.</span><span class="sxs-lookup"><span data-stu-id="67c14-109">The attachments link contains a feed of attachments that belong to the document.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject">
      <MemberSignature Language="C#" Value="System.Dynamic.DynamicMetaObject IDynamicMetaObjectProvider.GetMetaObject (System.Linq.Expressions.Expression parameter);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Dynamic.DynamicMetaObject System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject(class System.Linq.Expressions.Expression parameter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Document.System#Dynamic#IDynamicMetaObjectProvider#GetMetaObject(System.Linq.Expressions.Expression)" />
      <MemberSignature Language="VB.NET" Value="Function GetMetaObject (parameter As Expression) As DynamicMetaObject Implements IDynamicMetaObjectProvider.GetMetaObject" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject(System.Linq.Expressions.Expression)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Dynamic.DynamicMetaObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameter" Type="System.Linq.Expressions.Expression" />
      </Parameters>
      <Docs>
        <param name="parameter">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Document.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.Document.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="ttl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67c14-110">Ruft ab oder legt die Zeit in Sekunden für das Dokument in der Azure-Cosmos-DB-Dienst Gültigkeitsdauer fest.</span><span class="sxs-lookup"><span data-stu-id="67c14-110">Gets or sets the time to live in seconds of the document in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="67c14-111">Es ist eine optionale Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="67c14-111">It is an optional property.</span></span> <span data-ttu-id="67c14-112">Ein gültiger Wert muss entweder eine positive ganze Zahl ungleich NULL, "1", oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="67c14-112">A valid value must be either a nonzero positive integer, '-1', or <c>null</c>.</span></span>
            <span data-ttu-id="67c14-113">Standardmäßig TimeToLive festgelegt ist, um null Bedeutung des Dokuments erbt der Auflistung <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />.</span><span class="sxs-lookup"><span data-stu-id="67c14-113">By default, TimeToLive is set to null meaning the document inherits the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />.</span></span>
            <span data-ttu-id="67c14-114">Die Maßeinheit ist Sekunden.</span><span class="sxs-lookup"><span data-stu-id="67c14-114">The unit of measurement is seconds.</span></span> <span data-ttu-id="67c14-115">Die zulässige Maximalwert ist 2147483647.</span><span class="sxs-lookup"><span data-stu-id="67c14-115">The maximum allowed value is 2147483647.</span></span>
            <span data-ttu-id="67c14-116">Der Wert "-1" ist, bedeutet dies nie ablaufen sollen, unabhängig von der Auflistung <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="67c14-116">When the value is '-1', it means never expire regardless of the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> value.</span></span>
            </value>
        <remarks>
          <para>
            <span data-ttu-id="67c14-117">Die endgültige Time-to-live-Richtlinie eines Dokuments nach Rücksprache mit der Auflistung überprüft <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />.</span><span class="sxs-lookup"><span data-stu-id="67c14-117">The final time-to-live policy of a document is evaluated after consulting the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />.</span></span>
            </para>
          <para>
            <span data-ttu-id="67c14-118">Wenn die <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> ist <c>null</c>, erbt der Auflistung das Dokument <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />.</span><span class="sxs-lookup"><span data-stu-id="67c14-118">When the <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> is <c>null</c>, the document inherits the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />.</span></span>
            <span data-ttu-id="67c14-119">Wenn der Auflistung <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> ist eine positive ganze Zahl ungleich NULL, und klicken Sie dann das Dokument diesen Wert als seine-Gültigkeitsdauer in Sekunden übernimmt, und nach dem Standardverhalten Gültigkeitsdauer in Sekunden abgelaufen wird, seit der letzten Schreibzugriffs.</span><span class="sxs-lookup"><span data-stu-id="67c14-119">If the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> is a nonzero positive integer, then the document will inherit that value as its time-to-live in seconds, and will be expired after the default time-to-live in seconds since its last write time.</span></span> <span data-ttu-id="67c14-120">Im Hintergrund werden die abgelaufenen Dokumente gelöscht.</span><span class="sxs-lookup"><span data-stu-id="67c14-120">The expired documents will be deleted in background.</span></span>
            <span data-ttu-id="67c14-121">Andernfalls wird das Dokument nie ablaufen.</span><span class="sxs-lookup"><span data-stu-id="67c14-121">Otherwise, the document will never expire.</span></span>
            </para>
          <para>
            <span data-ttu-id="67c14-122">Wenn die <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> ist "1", das Dokument wird nie ablaufen, unabhängig von der Auflistung <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="67c14-122">When the <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> is '-1', the document will never expire regardless of the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> value.</span></span>
            </para>
          <para>
            <span data-ttu-id="67c14-123">Wenn die <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> ist eine positive ganze Zahl ungleich NULL, überprüfen Sie die Auflistung müssen <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />.</span><span class="sxs-lookup"><span data-stu-id="67c14-123">When the <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> is a nonzero positive integer, need to check the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />.</span></span>
            <span data-ttu-id="67c14-124">Wenn der Auflistung <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> ist <c>null</c>, d. h. die Time-to-live wurde deaktiviert, auf die Sammlung und des Dokuments <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> nicht berücksichtigt werden sollten und das Dokument nicht abläuft.</span><span class="sxs-lookup"><span data-stu-id="67c14-124">If the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> is <c>null</c>, which means the time-to-live has been turned off on the collection, and the document's <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> should be disregarded and the document will never expire.</span></span>
            <span data-ttu-id="67c14-125">Andernfalls des Dokuments <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> wird berücksichtigt werden.</span><span class="sxs-lookup"><span data-stu-id="67c14-125">Otherwise, the document's <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> will be honored.</span></span> <span data-ttu-id="67c14-126">Das Dokument wird nach dem Standardverhalten Gültigkeitsdauer in Sekunden, seit der letzten Schreibzugriffs abgelaufen sein.</span><span class="sxs-lookup"><span data-stu-id="67c14-126">The document will be expired after the default time-to-live in seconds since its last write time.</span></span> <span data-ttu-id="67c14-127">Im Hintergrund werden die abgelaufenen Dokumente gelöscht.</span><span class="sxs-lookup"><span data-stu-id="67c14-127">The expired documents will be deleted in background.</span></span>
            </para>
          <para>
            <span data-ttu-id="67c14-128">Folgende Tabelle zeigt ein Beispiel für die Matrix die endgültigen Time-to-live-Richtlinie mit einem Collection auszuwerten <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> und ein Dokument <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />.</span><span class="sxs-lookup"><span data-stu-id="67c14-128">The table below shows an example of the matrix to evaluate the final time-to-live policy given a collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> and a document's <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />.</span></span>
            </para>
          <list type="table">
            <listheader>
              <term><span data-ttu-id="67c14-129">Sammlung</span><span class="sxs-lookup"><span data-stu-id="67c14-129">Collection</span></span></term>
              <description><span data-ttu-id="67c14-130">Matrix</span><span class="sxs-lookup"><span data-stu-id="67c14-130">Matrix</span></span></description>
            </listheader>
            <item>
              <term><span data-ttu-id="67c14-131">DefaultTimeToLive = Null</span><span class="sxs-lookup"><span data-stu-id="67c14-131">DefaultTimeToLive = null</span></span></term>
              <description>
                <list type="table">
                  <listheader>
                    <term><span data-ttu-id="67c14-132">Dokument</span><span class="sxs-lookup"><span data-stu-id="67c14-132">Document</span></span></term>
                    <description><span data-ttu-id="67c14-133">Ergebnis</span><span class="sxs-lookup"><span data-stu-id="67c14-133">Result</span></span></description>
                  </listheader>
                  <item>
                    <term><span data-ttu-id="67c14-134">TimeToLive = Null</span><span class="sxs-lookup"><span data-stu-id="67c14-134">TimeToLive = null</span></span></term>
                    <description><span data-ttu-id="67c14-135">Gültigkeitsdauer (TTL) ist deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="67c14-135">TTL is disabled.</span></span> <span data-ttu-id="67c14-136">Das Dokument läuft nie ab (Standard).</span><span class="sxs-lookup"><span data-stu-id="67c14-136">The document will never expire (default).</span></span></description>
                  </item>
                  <item>
                    <term><span data-ttu-id="67c14-137">TimeToLive =-1</span><span class="sxs-lookup"><span data-stu-id="67c14-137">TimeToLive = -1</span></span></term>
                    <description><span data-ttu-id="67c14-138">Gültigkeitsdauer (TTL) ist deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="67c14-138">TTL is disabled.</span></span> <span data-ttu-id="67c14-139">Das Dokument abläuft nicht.</span><span class="sxs-lookup"><span data-stu-id="67c14-139">The document will never expire.</span></span></description>
                  </item>
                  <item>
                    <term><span data-ttu-id="67c14-140">TimeToLive = 2000</span><span class="sxs-lookup"><span data-stu-id="67c14-140">TimeToLive = 2000</span></span></term>
                    <description><span data-ttu-id="67c14-141">Gültigkeitsdauer (TTL) ist deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="67c14-141">TTL is disabled.</span></span> <span data-ttu-id="67c14-142">Das Dokument abläuft nicht.</span><span class="sxs-lookup"><span data-stu-id="67c14-142">The document will never expire.</span></span></description>
                  </item>
                </list>
              </description>
            </item>
            <item>
              <term><span data-ttu-id="67c14-143">DefaultTimeToLive =-1</span><span class="sxs-lookup"><span data-stu-id="67c14-143">DefaultTimeToLive = -1</span></span></term>
              <description>
                <list type="table">
                  <listheader>
                    <term><span data-ttu-id="67c14-144">Dokument</span><span class="sxs-lookup"><span data-stu-id="67c14-144">Document</span></span></term>
                    <description><span data-ttu-id="67c14-145">Ergebnis</span><span class="sxs-lookup"><span data-stu-id="67c14-145">Result</span></span></description>
                  </listheader>
                  <item>
                    <term><span data-ttu-id="67c14-146">TimeToLive = Null</span><span class="sxs-lookup"><span data-stu-id="67c14-146">TimeToLive = null</span></span></term>
                    <description><span data-ttu-id="67c14-147">Gültigkeitsdauer (TTL) aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="67c14-147">TTL is enabled.</span></span> <span data-ttu-id="67c14-148">Das Dokument läuft nie ab (Standard).</span><span class="sxs-lookup"><span data-stu-id="67c14-148">The document will never expire (default).</span></span></description>
                  </item>
                  <item>
                    <term><span data-ttu-id="67c14-149">TimeToLive =-1</span><span class="sxs-lookup"><span data-stu-id="67c14-149">TimeToLive = -1</span></span></term>
                    <description><span data-ttu-id="67c14-150">Gültigkeitsdauer (TTL) aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="67c14-150">TTL is enabled.</span></span> <span data-ttu-id="67c14-151">Das Dokument abläuft nicht.</span><span class="sxs-lookup"><span data-stu-id="67c14-151">The document will never expire.</span></span></description>
                  </item>
                  <item>
                    <term><span data-ttu-id="67c14-152">TimeToLive = 2000</span><span class="sxs-lookup"><span data-stu-id="67c14-152">TimeToLive = 2000</span></span></term>
                    <description><span data-ttu-id="67c14-153">Gültigkeitsdauer (TTL) aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="67c14-153">TTL is enabled.</span></span> <span data-ttu-id="67c14-154">Das Dokument läuft nach 2000 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="67c14-154">The document will expire after 2000 seconds.</span></span></description>
                  </item>
                </list>
              </description>
            </item>
            <item>
              <term><span data-ttu-id="67c14-155">DefaultTimeToLive = 1000</span><span class="sxs-lookup"><span data-stu-id="67c14-155">DefaultTimeToLive = 1000</span></span></term>
              <description>
                <list type="table">
                  <listheader>
                    <term><span data-ttu-id="67c14-156">Dokument</span><span class="sxs-lookup"><span data-stu-id="67c14-156">Document</span></span></term>
                    <description><span data-ttu-id="67c14-157">Ergebnis</span><span class="sxs-lookup"><span data-stu-id="67c14-157">Result</span></span></description>
                  </listheader>
                  <item>
                    <term><span data-ttu-id="67c14-158">TimeToLive = Null</span><span class="sxs-lookup"><span data-stu-id="67c14-158">TimeToLive = null</span></span></term>
                    <description><span data-ttu-id="67c14-159">Gültigkeitsdauer (TTL) aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="67c14-159">TTL is enabled.</span></span> <span data-ttu-id="67c14-160">Das Dokument läuft nach 1000 Sekunden (Standard).</span><span class="sxs-lookup"><span data-stu-id="67c14-160">The document will expire after 1000 seconds (default).</span></span></description>
                  </item>
                  <item>
                    <term><span data-ttu-id="67c14-161">TimeToLive =-1</span><span class="sxs-lookup"><span data-stu-id="67c14-161">TimeToLive = -1</span></span></term>
                    <description><span data-ttu-id="67c14-162">Gültigkeitsdauer (TTL) aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="67c14-162">TTL is enabled.</span></span> <span data-ttu-id="67c14-163">Das Dokument abläuft nicht.</span><span class="sxs-lookup"><span data-stu-id="67c14-163">The document will never expire.</span></span></description>
                  </item>
                  <item>
                    <term><span data-ttu-id="67c14-164">TimeToLive = 2000</span><span class="sxs-lookup"><span data-stu-id="67c14-164">TimeToLive = 2000</span></span></term>
                    <description><span data-ttu-id="67c14-165">Gültigkeitsdauer (TTL) aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="67c14-165">TTL is enabled.</span></span> <span data-ttu-id="67c14-166">Das Dokument läuft nach 2000 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="67c14-166">The document will expire after 2000 seconds.</span></span></description>
                  </item>
                </list>
              </description>
            </item>
          </list>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <example>
            <span data-ttu-id="67c14-167">Im folgenden Beispiel entfernt "Ttl" aus dem Inhalt des Dokuments.</span><span class="sxs-lookup"><span data-stu-id="67c14-167">The example below removes 'ttl' from document content.</span></span>
            <span data-ttu-id="67c14-168">Das Dokument wird der Auflistung erben <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> als Time-to-live Wert.</span><span class="sxs-lookup"><span data-stu-id="67c14-168">The document will inherit the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> as its time-to-live value.</span></span>
            <code language="c#"><![CDATA[
                document.TimeToLive = null;
            ]]></code></example>
        <example>
            <span data-ttu-id="67c14-169">Im folgenden Beispiel wird sichergestellt, dass das Dokument unabhängig davon nie ablaufen sollen.</span><span class="sxs-lookup"><span data-stu-id="67c14-169">The example below ensures that the document should never expire regardless.</span></span>
            <code language="c#"><![CDATA[
                document.TimeToLive = -1;
            ]]></code></example>
        <example>
            <span data-ttu-id="67c14-170">Das folgende Beispiel legt die Time-to-live in Sekunden für ein Dokument fest.</span><span class="sxs-lookup"><span data-stu-id="67c14-170">The example below sets the time-to-live in seconds on a document.</span></span>
            <span data-ttu-id="67c14-171">Das Dokument läuft nach 1000 Sekunden seit seiner letzten Schreibvorgang, wenn Zeit der Auflistung <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> nicht <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="67c14-171">The document will expire after 1000 seconds since its last write time when the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> is not <c>null</c>.</span></span>
            <code language="c#"><![CDATA[
            document.TimeToLive = 1000;
                ]]></code></example>
      </Docs>
    </Member>
  </Members>
</Type>