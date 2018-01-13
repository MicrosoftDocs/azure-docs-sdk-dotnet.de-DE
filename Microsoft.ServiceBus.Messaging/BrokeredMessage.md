<Type Name="BrokeredMessage" FullName="Microsoft.ServiceBus.Messaging.BrokeredMessage">
  <TypeSignature Language="C#" Value="public sealed class BrokeredMessage : IDisposable, System.Xml.Serialization.IXmlSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BrokeredMessage extends System.Object implements class System.IDisposable, class System.Xml.Serialization.IXmlSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BrokeredMessage&#xA;Implements IDisposable, IXmlSerializable" />
  <TypeSignature Language="F#" Value="type BrokeredMessage = class&#xA;    interface IXmlSerializable&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Xml.Serialization.IXmlSerializable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Xml.Serialization.XmlRoot("BrokeredMessage", Namespace="http://schemas.microsoft.com/netservices/2011/06/servicebus")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="831c7-101">Stellt die kommunikationseinheit zwischen Service Bus-Clients dar.</span><span class="sxs-lookup"><span data-stu-id="831c7-101">Represents the unit of communication between Service Bus clients.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="831c7-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="831c7-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage (System.IO.Stream messageBodyStream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream messageBodyStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (messageBodyStream As Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.BrokeredMessage : System.IO.Stream -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="new Microsoft.ServiceBus.Messaging.BrokeredMessage messageBodyStream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="messageBodyStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="messageBodyStream"><span data-ttu-id="831c7-103">Der Nachrichtentext-Streams.</span><span class="sxs-lookup"><span data-stu-id="831c7-103">The message body stream.</span></span></param>
        <summary><span data-ttu-id="831c7-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="831c7-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage (object serializableObject);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object serializableObject) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serializableObject As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.BrokeredMessage : obj -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="new Microsoft.ServiceBus.Messaging.BrokeredMessage serializableObject" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serializableObject" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="serializableObject"><span data-ttu-id="831c7-105">Das Objekt, das in den Nachrichtentext serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="831c7-105">The object to be serialized into the message body.</span></span></param>
        <summary><span data-ttu-id="831c7-106">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> Klasse aus einem Objekt mit einem binären XmlDictionaryWriter mithilfe von "DataContractSerializer".</span><span class="sxs-lookup"><span data-stu-id="831c7-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> class from a given object by using DataContractSerializer with a binary XmlDictionaryWriter.</span></span></summary>
        <remarks><span data-ttu-id="831c7-107">Eine standardmäßige <see cref="T:Microsoft.ServiceBus.Messaging.DataContractBinarySerializer" /> für die Serialisierung des Objekts verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="831c7-107">A default <see cref="T:Microsoft.ServiceBus.Messaging.DataContractBinarySerializer" /> is used for serializing the object.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage (System.IO.Stream messageBodyStream, bool ownsStream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream messageBodyStream, bool ownsStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor(System.IO.Stream,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (messageBodyStream As Stream, ownsStream As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.BrokeredMessage : System.IO.Stream * bool -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="new Microsoft.ServiceBus.Messaging.BrokeredMessage (messageBodyStream, ownsStream)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="messageBodyStream" Type="System.IO.Stream" />
        <Parameter Name="ownsStream" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="messageBodyStream"><span data-ttu-id="831c7-108">Der Nachrichtentext-Streams.</span><span class="sxs-lookup"><span data-stu-id="831c7-108">The message body stream.</span></span></param>
        <param name="ownsStream"><span data-ttu-id="831c7-109">"true", um anzugeben, dass der Stream geschlossen wird, wenn die Nachricht geschlossen wird; "false", um anzugeben, dass der Datenstrom nicht geschlossen wird, wenn die Nachricht geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="831c7-109">true to indicate that the stream will be closed when the message is closed; false to indicate that the stream will not be closed when the message is closed.</span></span></param>
        <summary><span data-ttu-id="831c7-110">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> -Klasse mithilfe des angegebenen Streams als Text.</span><span class="sxs-lookup"><span data-stu-id="831c7-110">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> class using the supplied stream as its body.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage (object serializableObject, System.Runtime.Serialization.XmlObjectSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object serializableObject, class System.Runtime.Serialization.XmlObjectSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor(System.Object,System.Runtime.Serialization.XmlObjectSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serializableObject As Object, serializer As XmlObjectSerializer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.BrokeredMessage : obj * System.Runtime.Serialization.XmlObjectSerializer -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="new Microsoft.ServiceBus.Messaging.BrokeredMessage (serializableObject, serializer)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serializableObject" Type="System.Object" />
        <Parameter Name="serializer" Type="System.Runtime.Serialization.XmlObjectSerializer" />
      </Parameters>
      <Docs>
        <param name="serializableObject"> <span data-ttu-id="831c7-111">Die serializable-Objekt.</span><span class="sxs-lookup"><span data-stu-id="831c7-111">The serializable object.</span></span> </param>
        <param name="serializer">         <span data-ttu-id="831c7-112">Das Serialisierungsprogrammobjekt.</span><span class="sxs-lookup"><span data-stu-id="831c7-112">The serializer object.</span></span> </param>
        <summary> <span data-ttu-id="831c7-113">Konstruktor, der von einem Objekt mithilfe der bereitgestellten XmlObjectSerializer eine "brokeredmessage" wird erstellt</span><span class="sxs-lookup"><span data-stu-id="831c7-113">Constructor that creates a BrokeredMessage from a given object using the provided XmlObjectSerializer</span></span> </summary>
        <remarks> <span data-ttu-id="831c7-114">Sie sollten beachten von Ausnahmen sein, dass ihre bereitgestellten Serialisierer auslösen kann, und ergreifen Sie entsprechende Maßnahmen.</span><span class="sxs-lookup"><span data-stu-id="831c7-114">You should be aware of the exceptions that their provided Serializer can throw and take appropriate actions.</span></span> <span data-ttu-id="831c7-115">Finden Sie unter <see href="http://msdn.microsoft.com/en-us/library/ms574055.aspx" /> eine mögliche Liste der Ausnahmen und deren Ursachen.</span><span class="sxs-lookup"><span data-stu-id="831c7-115">Please refer to <see href="http://msdn.microsoft.com/en-us/library/ms574055.aspx" /> for a possible list of exceptions and their cause.</span></span> </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="831c7-116">Wird ausgelöst, wenn null-Serialisierungsprogramm an die Methode mit einem SerializableObject ungleich Null übergeben wird</span><span class="sxs-lookup"><span data-stu-id="831c7-116">Thrown when null serializer is passed to the method with a non-null serializableObject</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Abandon() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Abandon" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon ()" />
      <MemberSignature Language="F#" Value="member this.Abandon : unit -&gt; unit" Usage="brokeredMessage.Abandon " />
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
        <summary><span data-ttu-id="831c7-117">Bricht die Sperre für eine Nachricht einsehen gesperrt ab.</span><span class="sxs-lookup"><span data-stu-id="831c7-117">Abandons the lock on a peek-locked message.</span></span></summary>
        <remarks> <span data-ttu-id="831c7-118">Dieser Vorgang sollte nur für eine Nachricht empfangen, die im Peek / Lock-Modus ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="831c7-118">This operation should only be exercised on a message received in peek-lock mode.</span></span></remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-119">Wird ausgelöst, wenn die Nachricht im Status "freigegeben wird" oder des Empfängers mit dem die Nachricht empfangen wurde verworfen Zustand.</span><span class="sxs-lookup"><span data-stu-id="831c7-119">Thrown when the message is in the disposed state or the receiver with which the message was received is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="831c7-120">Wird ausgelöst, wenn eine Nachricht, die nicht aus dem e-Mail-Server empfangen wurde aufgerufen oder auf eine Nachricht, die nicht im Peek / Lock-Modus empfangen wurde aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="831c7-120">Thrown when invoked on a message that has not been received from the message server or invoked on a message that has not been received in peek-lock mode.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="831c7-121">Wird ausgelöst, wenn ein Timeout eintritt. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span><span class="sxs-lookup"><span data-stu-id="831c7-121">Thrown when operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span></span> <span data-ttu-id="831c7-122">Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-122">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="831c7-123">Wird ausgelöst, wenn die Warteschlange oder das Abonnement, das die Nachricht empfängt, nicht mehr in der Message-Server vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-123">Thrown when the queue or subscription that receives the message is no longer present in the message server.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException"><span data-ttu-id="831c7-124">Beim Servicebus-Dienst ist ausgelastet und wird nicht verarbeitet die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="831c7-124">When service bus service is busy and is unable process the request.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="831c7-125">Wenn messaging-Entität die Nachricht von empfangen wurde, wurde gelöscht.</span><span class="sxs-lookup"><span data-stu-id="831c7-125">When messaging entity the message was received from has been deleted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="831c7-126">Wenn Sie die Sperre zugeordnet diese Nachricht wurde unterbrochen, oder das Sperrtoken nicht gefunden wurde.</span><span class="sxs-lookup"><span data-stu-id="831c7-126">When the lock associated with this message was lost or the lock token was not found.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException"><span data-ttu-id="831c7-127">Wenn diese Nachricht empfangen wurde, aus einer Sitzung und die Sperre der Sitzung zugeordnet ist verloren gegangen.</span><span class="sxs-lookup"><span data-stu-id="831c7-127">When this message was received from a Session and the lock associated with the session was lost.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="831c7-128">Wenn das Sicherheitstoken, die von der TokenProvider bereitgestellten keine Ansprüche zum Ausführen dieses Vorgangs enthält.</span><span class="sxs-lookup"><span data-stu-id="831c7-128">When the security token provided by the TokenProvider does not contain the claims to perform this operation.</span></span></exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException"><span data-ttu-id="831c7-129">Bei der die Anzahl gleichzeitiger Verbindungen mit einer Entität nicht überschreiten der maximal zulässige Wert.</span><span class="sxs-lookup"><span data-stu-id="831c7-129">When the number of concurrent connections to an entity exceed the maximum allowed value.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Abandon(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Abandon(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="member this.Abandon : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="brokeredMessage.Abandon propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify"><span data-ttu-id="831c7-130">Die Schlüssel / Wert-Paar-Auflistung von Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="831c7-130">The key-value pair collection of properties to modify.</span></span></param>
        <summary><span data-ttu-id="831c7-131">Bricht die Sperre für eine Nachricht einsehen gesperrt ab.</span><span class="sxs-lookup"><span data-stu-id="831c7-131">Abandons the lock on a peek-locked message.</span></span></summary>
        <remarks> <span data-ttu-id="831c7-132">Dieser Vorgang sollte nur für eine Nachricht empfangen, die im Peek / Lock-Modus ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="831c7-132">This operation should only be exercised on a message received in peek-lock mode.</span></span></remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-133">Wird ausgelöst, wenn <list type="bullet"> <item>Meldung wird verworfen Zustand.</item> <item>der Empfänger mit dem die Nachricht wurde empfangen befindet sich in freigegebenem Zustand</item></list></span><span class="sxs-lookup"><span data-stu-id="831c7-133">Thrown when <list type="bullet"><item>message is in disposed state.</item><item>the receiver with which the messsage was received is in disposed state</item></list></span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="831c7-134">Wird ausgelöst, wenn <list type="bullet"> <item>eine Nachricht, die nicht aus dem e-Mail-Server empfangen wurde aufgerufen.</item> <item>für eine Nachricht, die nicht im Peek / Lock-Modus empfangen wurde aufgerufen</item></list></span><span class="sxs-lookup"><span data-stu-id="831c7-134">Thrown when <list type="bullet"><item>invoked on a message that has not been received from the message server.</item><item>invoked on a message that has not been received in peek-lock mode</item></list></span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="831c7-135">Wird ausgelöst, wenn ein Timeout eintritt. Timeouts wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span><span class="sxs-lookup"><span data-stu-id="831c7-135">Thrown when operation times out. Timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span></span> <span data-ttu-id="831c7-136">Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-136">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if timeout value is relatively low.</span></span>
                                            <seealso cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></exception>
        <exception cref="T:System.ServiceModel.CommunicationException"><span data-ttu-id="831c7-137">Wird ausgelöst, wenn die Warteschlange oder das Abonnement, das die Nachricht empfangen wurde, nicht mehr in der Message-Server vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-137">Thrown when the queue or subscription that the message was received from is no longer present in the message server.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AbandonAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.AbandonAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.AbandonAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.AbandonAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="831c7-138">Abbricht, asynchron die Sperre für eine Nachricht einsehen gesperrt.</span><span class="sxs-lookup"><span data-stu-id="831c7-138">Asynchronously abandons the lock on a peek-locked message.</span></span></summary>
        <returns><span data-ttu-id="831c7-139">Das asynchrone Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="831c7-139">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AbandonAsync(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.AbandonAsync(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="member this.AbandonAsync : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.AbandonAsync propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify"><span data-ttu-id="831c7-140">Die Schlüssel / Wert-Paar-Auflistung von Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="831c7-140">The key-value pair collection of properties to modify.</span></span></param>
        <summary><span data-ttu-id="831c7-141">Abbricht, asynchron die Sperre für eine Nachricht einsehen gesperrt.</span><span class="sxs-lookup"><span data-stu-id="831c7-141">Asynchronously abandons the lock on a peek-locked message.</span></span></summary>
        <returns><span data-ttu-id="831c7-142">Das asynchrone Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="831c7-142">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="brokeredMessage.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="831c7-143">Klont eine Nachricht an, damit, dass es möglich ist, einen Klon einer Nachricht als eine neue Nachricht zu senden.</span><span class="sxs-lookup"><span data-stu-id="831c7-143">Clones a message, so that it is possible to send a clone of a message as a new message.</span></span></summary>
        <returns><span data-ttu-id="831c7-144">Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , das die geklonte Meldung enthält.</span><span class="sxs-lookup"><span data-stu-id="831c7-144">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> that contains the cloned message.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Complete">
      <MemberSignature Language="C#" Value="public void Complete ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Complete() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Complete" />
      <MemberSignature Language="VB.NET" Value="Public Sub Complete ()" />
      <MemberSignature Language="F#" Value="member this.Complete : unit -&gt; unit" Usage="brokeredMessage.Complete " />
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
        <summary><span data-ttu-id="831c7-145">Schließt den Empfangsvorgang einer Nachricht ab und gibt an, dass die Nachricht als verarbeitet gekennzeichnet werden soll und gelöscht.</span><span class="sxs-lookup"><span data-stu-id="831c7-145">Completes the receive operation of a message and indicates that the message should be marked as processed and deleted.</span></span></summary>
        <remarks> <span data-ttu-id="831c7-146">Diese Methode wird als ein Handshake zwischen dem Empfänger und die Service Bus für eine Zustellung der Nachricht verwendet.</span><span class="sxs-lookup"><span data-stu-id="831c7-146">This method is used as a handshake between the receiver and Service Bus for a guaranteed delivery of the message.</span></span> <span data-ttu-id="831c7-147">Wenn der Empfänger, die vor dem Aufrufen dieser Methode fehlgeschlagen ist, wird die Nachricht in der Warteschlange beibehalten.</span><span class="sxs-lookup"><span data-stu-id="831c7-147">If the receiver failed before calling this method, the message will be kept in the queue.</span></span></remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-148">Wird ausgelöst, wenn die Nachricht verworfen Status besitzt oder der Empfänger mit dem die Nachricht empfangen wurde befindet sich in freigegebenem Zustand.</span><span class="sxs-lookup"><span data-stu-id="831c7-148">Thrown when the message is in disposed state or the receiver with which the message was received is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="831c7-149">Wird ausgelöst, wenn eine Nachricht, die nicht aus dem e-Mail-Server empfangen wurde aufgerufen oder auf eine Nachricht, die nicht im Peek / Lock-Modus empfangen wurde aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="831c7-149">Thrown when invoked on a message that has not been received from the message server or invoked on a message that has not been received in peek-lock mode.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="831c7-150">Wird ausgelöst, wenn die Warteschlange oder das Abonnement, das die Nachricht empfängt, nicht mehr in der Message-Server vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-150">Thrown when the queue or subscription that receives the message is no longer present in the message server.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="831c7-151">Wird ausgelöst, wenn der Vorgang ein Timeout auftritt. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span><span class="sxs-lookup"><span data-stu-id="831c7-151">Thrown when the operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span></span> <span data-ttu-id="831c7-152">Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-152">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="831c7-153">Wird ausgelöst, wenn die Sperre für die Nachricht abgelaufen ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-153">Thrown if the lock on the message has expired.</span></span> <span data-ttu-id="831c7-154">LockDuration ist eine Entität serverweite Einstellung, und können durch initialisiert werden <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> und <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> für Warteschlangen und Abonnements bzw.</span><span class="sxs-lookup"><span data-stu-id="831c7-154">LockDuration is an entity-wide setting and can be initialized through <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> and <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> for queues and subscriptions respectively.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException"><span data-ttu-id="831c7-155">Wird ausgelöst, wenn die Sperre für die Sitzung abgelaufen ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-155">Thrown if the lock on the session has expired.</span></span> <span data-ttu-id="831c7-156">Die Dauer der Sperre ist identisch mit der Nachricht LockDuration und ist eine Entität serverweite Einstellung.</span><span class="sxs-lookup"><span data-stu-id="831c7-156">The session lock duration is the same as the message LockDuration and is an entity-wide setting.</span></span> <span data-ttu-id="831c7-157">Es kann durch initialisiert werden <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> und <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> für Warteschlangen und Abonnements bzw.</span><span class="sxs-lookup"><span data-stu-id="831c7-157">It can be initialized through <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> and <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> for queues and subscriptions respectively.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException"><span data-ttu-id="831c7-158">Beim Servicebus-Dienst ist ausgelastet und wird nicht verarbeitet die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="831c7-158">When service bus service is busy and is unable process the request.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="831c7-159">Wenn messaging-Entität die Nachricht von empfangen wurde, wurde gelöscht.</span><span class="sxs-lookup"><span data-stu-id="831c7-159">When messaging entity the message was received from has been deleted.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="831c7-160">Wenn das Sicherheitstoken, die von der TokenProvider bereitgestellten keine Ansprüche zum Ausführen dieses Vorgangs enthält.</span><span class="sxs-lookup"><span data-stu-id="831c7-160">When the security token provided by the TokenProvider does not contain the claims to perform this operation.</span></span></exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException"><span data-ttu-id="831c7-161">Bei der die Anzahl gleichzeitiger Verbindungen mit einer Entität nicht überschreiten der maximal zulässige Wert.</span><span class="sxs-lookup"><span data-stu-id="831c7-161">When the number of concurrent connections to an entity exceed the maximum allowed value.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CompleteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.CompleteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CompleteAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.CompleteAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="831c7-162">Asynchron abgeschlossen wird den Empfangsvorgang einer Nachricht und gibt an, dass die Nachricht als verarbeitet gekennzeichnet werden soll und gelöscht.</span><span class="sxs-lookup"><span data-stu-id="831c7-162">Asynchronously completes the receive operation of a message and indicates that the message should be marked as processed and deleted.</span></span></summary>
        <returns><span data-ttu-id="831c7-163">Das asynchrone Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="831c7-163">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-164">Ruft ab oder legt den Typ des Inhalts fest.</span><span class="sxs-lookup"><span data-stu-id="831c7-164">Gets or sets the type of the content.</span></span></summary>
        <value><span data-ttu-id="831c7-165">Der Typ des Inhalts des Nachrichtentexts.</span><span class="sxs-lookup"><span data-stu-id="831c7-165">The type of the content of the message body.</span></span> <span data-ttu-id="831c7-166">Dies ist ein Content-Type-Bezeichner von Sender und Empfänger für anwendungsspezifische Logik verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="831c7-166">This is a content type identifier utilized by the sender and receiver for application specific logic.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-167">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-167">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-168">Ruft ab oder legt den Bezeichner der Korrelation.</span><span class="sxs-lookup"><span data-stu-id="831c7-168">Gets or sets the identifier of the correlation.</span></span></summary>
        <value><span data-ttu-id="831c7-169">Der Bezeichner der Korrelation.</span><span class="sxs-lookup"><span data-stu-id="831c7-169">The identifier of the correlation.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-170">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-170">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeadLetter() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetter" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter ()" />
      <MemberSignature Language="F#" Value="member this.DeadLetter : unit -&gt; unit" Usage="brokeredMessage.DeadLetter " />
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
        <summary><span data-ttu-id="831c7-171">Verschiebt die Nachricht an die Dead Letter-Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="831c7-171">Moves the message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-172">Wird ausgelöst, wenn die Nachricht verworfen Status besitzt oder der Empfänger mit dem die Nachricht empfangen wurde befindet sich in freigegebenem Zustand.</span><span class="sxs-lookup"><span data-stu-id="831c7-172">Thrown when the message is in disposed state or the receiver with which the message was received is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="831c7-173">Wird ausgelöst, wenn eine Nachricht, die nicht aus dem e-Mail-Server empfangen wurde aufgerufen oder auf eine Nachricht, die nicht im Peek / Lock-Modus empfangen wurde aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="831c7-173">Thrown when invoked on a message that has not been received from the message server or invoked on a message that has not been received in peek-lock mode.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeadLetter(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetter(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="member this.DeadLetter : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="brokeredMessage.DeadLetter propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify"><span data-ttu-id="831c7-174">Die Schlüssel / Wert-Paar-Auflistung von Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="831c7-174">The key-value pair collection of properties to modify.</span></span></param>
        <summary><span data-ttu-id="831c7-175">Verschiebt die Nachricht an die Dead Letter-Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="831c7-175">Moves the message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeadLetter(string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetter(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (deadLetterReason As String, deadLetterErrorDescription As String)" />
      <MemberSignature Language="F#" Value="member this.DeadLetter : string * string -&gt; unit" Usage="brokeredMessage.DeadLetter (deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deadLetterReason"><span data-ttu-id="831c7-176">Der Grund für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="831c7-176">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="831c7-177">Die Beschreibungsinformationen für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="831c7-177">The description information for deadlettering the message.</span></span></param>
        <summary><span data-ttu-id="831c7-178">Verschiebt die Nachricht an die Dead Letter-Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="831c7-178">Moves the message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-179">Wird ausgelöst, wenn die Nachricht verworfen Status besitzt oder der Empfänger mit dem die Nachricht empfangen wurde befindet sich in freigegebenem Zustand.</span><span class="sxs-lookup"><span data-stu-id="831c7-179">Thrown when the message is in disposed state or the receiver with which the message was received is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="831c7-180">Wird ausgelöst, wenn eine Nachricht, die nicht aus dem e-Mail-Server empfangen wurde aufgerufen oder auf eine Nachricht, die nicht im Peek / Lock-Modus empfangen wurde aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="831c7-180">Thrown when invoked on a message that has not been received from the message server or invoked on a message that has not been received in peek-lock mode.</span></span></exception>
        <exception cref="T:System.ServiceModel.CommunicationException"><span data-ttu-id="831c7-181">Wird ausgelöst, wenn die Warteschlange oder das Abonnement, das die Nachricht empfängt, nicht mehr in der Message-Server vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-181">Thrown when the queue or subscription that receives the message is no longer present in the message server.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="831c7-182">Wird ausgelöst, wenn ein Timeout eintritt. Timeouts wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span><span class="sxs-lookup"><span data-stu-id="831c7-182">Thrown when operation times out. Timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span></span> <span data-ttu-id="831c7-183">Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-183">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="831c7-184">Wird ausgelöst, wenn die Sperre für die Nachricht abgelaufen ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-184">Thrown if the lock on the message has expired.</span></span> <span data-ttu-id="831c7-185">LockDuration ist eine Entität serverweite Einstellung, und können durch initialisiert werden <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> und <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> für Warteschlangen und Abonnements bzw.</span><span class="sxs-lookup"><span data-stu-id="831c7-185">LockDuration is an entity-wide setting and can be initialized through <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> and <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> for Queues and Subscriptions respectively.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException"><span data-ttu-id="831c7-186">Wird ausgelöst, wenn die Sperre für die Sitzung abgelaufen ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-186">Thrown if the lock on the session has expired.</span></span> <span data-ttu-id="831c7-187">Sperrdauer Sitzung ist identisch mit der Nachricht LockDuration und ist eine Entität serverweite Einstellung.</span><span class="sxs-lookup"><span data-stu-id="831c7-187">Session lock duration is the same as message LockDuration and is an entity-wide setting.</span></span> <span data-ttu-id="831c7-188">Es kann durch initialisiert werden <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> und <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> für Warteschlangen und Abonnements bzw.</span><span class="sxs-lookup"><span data-stu-id="831c7-188">It can be initialized through <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> and <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> for Queues and Subscriptions respectively.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeadLetterAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.DeadLetterAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeadLetterAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="831c7-189">Asynchron verschiebt die Nachricht an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="831c7-189">Asynchronously moves the message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="831c7-190">Das asynchrone Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="831c7-190">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeadLetterAsync(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterAsync(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="member this.DeadLetterAsync : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeadLetterAsync propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify"><span data-ttu-id="831c7-191">Die Schlüssel / Wert-Paar-Auflistung von Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="831c7-191">The key-value pair collection of properties to modify.</span></span></param>
        <summary><span data-ttu-id="831c7-192">Asynchron verschiebt die Nachricht an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="831c7-192">Asynchronously moves the message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="831c7-193">Das asynchrone Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="831c7-193">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeadLetterAsync(string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (deadLetterReason As String, deadLetterErrorDescription As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeadLetterAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeadLetterAsync (deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deadLetterReason"><span data-ttu-id="831c7-194">Der Grund für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="831c7-194">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="831c7-195">Die Beschreibungsinformationen für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="831c7-195">The description information for deadlettering the message.</span></span></param>
        <summary><span data-ttu-id="831c7-196">Asynchron verschiebt die Nachricht an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="831c7-196">Asynchronously moves the message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="831c7-197">Das asynchrone Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="831c7-197">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterSource">
      <MemberSignature Language="C#" Value="public string DeadLetterSource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeadLetterSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterSource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeadLetterSource As String" />
      <MemberSignature Language="F#" Value="member this.DeadLetterSource : string" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Defer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Defer" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer ()" />
      <MemberSignature Language="F#" Value="member this.Defer : unit -&gt; unit" Usage="brokeredMessage.Defer " />
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
        <summary><span data-ttu-id="831c7-198">Gibt an, dass der Empfänger die Verarbeitung für diese Meldung verzögern möchte.</span><span class="sxs-lookup"><span data-stu-id="831c7-198">Indicates that the receiver wants to defer the processing for this message.</span></span></summary>
        <remarks><span data-ttu-id="831c7-199">Vor dem Verschieben der Nachrichteninhalts, muss der Benutzer den Empfang der Nachricht für den späteren Abruf reserviert.</span><span class="sxs-lookup"><span data-stu-id="831c7-199">Before deferring the message, user MUST set aside the message receipt for later retrieval.</span></span> </remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-200">Wird ausgelöst, wenn die Nachricht im Status "freigegeben" oder der Empfänger mit dem die Nachricht empfangen wurde im Status "freigegeben" wird.</span><span class="sxs-lookup"><span data-stu-id="831c7-200">Thrown when the message is in the disposed state or the receiver with which the message was received is in the disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="831c7-201">Wird ausgelöst, wenn eine Nachricht, die nicht aus dem e-Mail-Server empfangen wurde aufgerufen oder auf eine Nachricht, die nicht im Peek / Lock-Modus empfangen wurde aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="831c7-201">Thrown when invoked on a message that has not been received from the message server or invoked on a message that has not been received in peek-lock mode.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="831c7-202">Wird ausgelöst, wenn die Warteschlange oder das Abonnement, das die Nachricht empfängt, nicht mehr in der Message-Server vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-202">Thrown when the queue or subscription that receives the message is no longer present in the message server.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="831c7-203">Wird ausgelöst, wenn der Vorgang ein Timeout auftritt. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span><span class="sxs-lookup"><span data-stu-id="831c7-203">Thrown when the operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span></span> <span data-ttu-id="831c7-204">Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-204">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="831c7-205">Wird ausgelöst, wenn die Sperre für die Nachricht abgelaufen ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-205">Thrown if the lock on the message has expired.</span></span> <span data-ttu-id="831c7-206">LockDuration ist eine Entität serverweite Einstellung, und können durch initialisiert werden <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> und <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> für Warteschlangen und Abonnements bzw.</span><span class="sxs-lookup"><span data-stu-id="831c7-206">LockDuration is an entity-wide setting and can be initialized through <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> and <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> for queues and subscriptions respectively.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException"><span data-ttu-id="831c7-207">Wird ausgelöst, wenn die Sperre für die Sitzung abgelaufen ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-207">Thrown if the lock on the session has expired.</span></span> <span data-ttu-id="831c7-208">Die Dauer der Sperre ist identisch mit der Nachricht LockDuration und ist eine Entität serverweite Einstellung.</span><span class="sxs-lookup"><span data-stu-id="831c7-208">The session lock duration is the same as the message LockDuration and is an entity-wide setting.</span></span> <span data-ttu-id="831c7-209">Es kann durch initialisiert werden <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> und <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> für Warteschlangen und Abonnements bzw.</span><span class="sxs-lookup"><span data-stu-id="831c7-209">It can be initialized through <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> and <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> for queues and subscriptions respectively.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException"><span data-ttu-id="831c7-210">Beim Servicebus-Dienst ist ausgelastet und wird nicht verarbeitet die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="831c7-210">When service bus service is busy and is unable process the request.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="831c7-211">Wenn messaging-Entität die Nachricht von empfangen wurde, wurde gelöscht.</span><span class="sxs-lookup"><span data-stu-id="831c7-211">When messaging entity the message was received from has been deleted.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="831c7-212">Wenn das Sicherheitstoken, die von der TokenProvider bereitgestellten keine Ansprüche zum Ausführen dieses Vorgangs enthält.</span><span class="sxs-lookup"><span data-stu-id="831c7-212">When the security token provided by the TokenProvider does not contain the claims to perform this operation.</span></span></exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException"><span data-ttu-id="831c7-213">Bei der die Anzahl gleichzeitiger Verbindungen mit einer Entität nicht überschreiten der maximal zulässige Wert.</span><span class="sxs-lookup"><span data-stu-id="831c7-213">When the number of concurrent connections to an entity exceed the maximum allowed value.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Defer(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Defer(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="member this.Defer : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="brokeredMessage.Defer propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify"><span data-ttu-id="831c7-214">Die Schlüssel / Wert-Paar-Auflistung von Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="831c7-214">The key-value pair collection of properties to modify.</span></span></param>
        <summary><span data-ttu-id="831c7-215">Gibt an, dass der Empfänger die Verarbeitung für diese Meldung verzögern möchte.</span><span class="sxs-lookup"><span data-stu-id="831c7-215">Indicates that the receiver wants to defer the processing for this message.</span></span></summary>
        <remarks><span data-ttu-id="831c7-216">Vor dem Verschieben der Nachrichteninhalts, muss der Benutzer den Empfang der Nachricht für den späteren Abruf reserviert.</span><span class="sxs-lookup"><span data-stu-id="831c7-216">Before deferring the message, user MUST set aside the message receipt for later retrieval.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeferAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeferAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.DeferAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeferAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="831c7-217">Gibt asynchron an, dass der Empfänger die Verarbeitung für diese Meldung verzögern möchte.</span><span class="sxs-lookup"><span data-stu-id="831c7-217">Asynchronously indicates that the receiver wants to defer the processing for this message.</span></span></summary>
        <returns><span data-ttu-id="831c7-218">Das asynchrone Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="831c7-218">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeferAsync(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeferAsync(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="member this.DeferAsync : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeferAsync propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify"><span data-ttu-id="831c7-219">Die Schlüssel / Wert-Paar-Auflistung von Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="831c7-219">The key-value pair collection of properties to modify.</span></span></param>
        <summary><span data-ttu-id="831c7-220">Gibt asynchron an, dass der Empfänger die Verarbeitung für diese Meldung verzögern möchte.</span><span class="sxs-lookup"><span data-stu-id="831c7-220">Asynchronously indicates that the receiver wants to defer the processing for this message.</span></span></summary>
        <returns><span data-ttu-id="831c7-221">Das asynchrone Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="831c7-221">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeliveryCount">
      <MemberSignature Language="C#" Value="public int DeliveryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DeliveryCount : int" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.DeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-222">Ruft die Anzahl der Übermittlungen ab.</span><span class="sxs-lookup"><span data-stu-id="831c7-222">Gets the number of deliveries.</span></span></summary>
        <value><span data-ttu-id="831c7-223">Die Anzahl der Übermittlungen.</span><span class="sxs-lookup"><span data-stu-id="831c7-223">The number of deliveries.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-224">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-224">Thrown if the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="831c7-225">Wird ausgelöst, wenn die Nachricht vom Service Bus nicht zugestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="831c7-225">Thrown if the message has not been delivered by ServiceBus.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="brokeredMessage.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="831c7-226">Führt anwendungsspezifische Aufgaben durch, die mit der Freigabe, der Zurückgabe oder dem Zurücksetzen von nicht verwalteten Ressourcen zusammenhängen.</span><span class="sxs-lookup"><span data-stu-id="831c7-226">Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedSequenceNumber">
      <MemberSignature Language="C#" Value="public long EnqueuedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 EnqueuedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.EnqueuedSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-227">Ruft ab oder legt die in die Warteschlange eingereihten Sequenznummer der Nachricht fest.</span><span class="sxs-lookup"><span data-stu-id="831c7-227">Gets or sets the enqueued sequence number of the message.</span></span></summary>
        <value><span data-ttu-id="831c7-228">Die in die Warteschlange eingereihten Sequenznummer der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="831c7-228">The enqueued sequence number of the message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-229">Ruft ab oder legt Datum und Uhrzeit der gesendeten Zeit in UTC.</span><span class="sxs-lookup"><span data-stu-id="831c7-229">Gets or sets the date and time of the sent time in UTC.</span></span></summary>
        <value><span data-ttu-id="831c7-230">Die in die Warteschlange einzureihen Zeit in UTC.</span><span class="sxs-lookup"><span data-stu-id="831c7-230">The enqueue time in UTC.</span></span> <span data-ttu-id="831c7-231">Dieser Wert stellt die tatsächliche Zeit des einreihen der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="831c7-231">This value represents the actual time of enqueuing the message.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-232">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-232">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ExpiresAtUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiresAtUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresAtUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ExpiresAtUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresAtUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresAtUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ExpiresAtUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-233">Ruft das Datum und die Uhrzeit in UTC, an dem die Nachricht abläuft festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-233">Gets the date and time in UTC at which the message is set to expire.</span></span></summary>
        <value><span data-ttu-id="831c7-234">Die Nachricht Ablaufzeit in UTC.</span><span class="sxs-lookup"><span data-stu-id="831c7-234">The message expiration time in UTC.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-235">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-235">Thrown if the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="831c7-236">Wenn die Nachricht nicht von ServerBus übermittelt wurden.</span><span class="sxs-lookup"><span data-stu-id="831c7-236">If the message has not been delivered by ServerBus.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ForcePersistence">
      <MemberSignature Language="C#" Value="public bool ForcePersistence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ForcePersistence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ForcePersistence" />
      <MemberSignature Language="VB.NET" Value="Public Property ForcePersistence As Boolean" />
      <MemberSignature Language="F#" Value="member this.ForcePersistence : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ForcePersistence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-237">Ruft ab oder legt einen Wert, der angibt, ob die Nachricht in die Datenbank sofort beibehalten werden, statt im Speicher für eine kurze Zeit aufrechterhalten wird.</span><span class="sxs-lookup"><span data-stu-id="831c7-237">Gets or sets a value that indicates whether the message is to be persisted to the database immediately, instead of being held in memory for a short time.</span></span> <span data-ttu-id="831c7-238">Diese Eigenschaft wird ignoriert, wenn die Nachricht an eine nicht-Express-Warteschlange oder ein Thema gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="831c7-238">This property is ignored if the message is sent to a non-express queue or topic.</span></span></summary>
        <value><span data-ttu-id="831c7-239">"true", wenn die Nachricht an die Datenbank sofort beibehalten werden, statt für kurze Zeit im Arbeitsspeicher gespeichert werden; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="831c7-239">true if the message is to be persisted to the database immediately, instead of being held in memory for a short time; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBody&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T GetBody&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!T GetBody&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.GetBody``1" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBody(Of T) () As T" />
      <MemberSignature Language="F#" Value="member this.GetBody : unit -&gt; 'T" Usage="brokeredMessage.GetBody " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T"><span data-ttu-id="831c7-240">Der Typ, den der Nachrichtentext deserialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="831c7-240">The type to which the message body will be deserialized.</span></span></typeparam>
        <summary><span data-ttu-id="831c7-241">Deserialisiert die vermittelte Nachrichtentext in ein Objekt des angegebenen Typs mithilfe der <see cref="T:System.Runtime.Serialization.DataContractSerializer" /> mit einer Binärdatei <see cref="T:System.Xml.XmlDictionaryReader" />.</span><span class="sxs-lookup"><span data-stu-id="831c7-241">Deserializes the brokered message body into an object of the specified type by using the <see cref="T:System.Runtime.Serialization.DataContractSerializer" /> with a binary <see cref="T:System.Xml.XmlDictionaryReader" />.</span></span></summary>
        <returns><span data-ttu-id="831c7-242">Das deserialisierte Objekt oder ein Diagramm.</span><span class="sxs-lookup"><span data-stu-id="831c7-242">The deserialized object or graph.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-243">Wenn die Nachricht, in verworfen wird wurde bereits Bundesland oder der Textdatenstrom Nachricht verworfen.</span><span class="sxs-lookup"><span data-stu-id="831c7-243">If the message is in disposed state or the message body stream is already disposed.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="831c7-244">Wenn die Nachricht einen null-Textdatenstrom enthält oder den Antworttext-Datenstrom keine Daten oder den Nachrichtentext enthält wurde bereits verwendet.</span><span class="sxs-lookup"><span data-stu-id="831c7-244">If the message contains a null body stream or the body stream contains no data or the message body has already been consumed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetBody&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T GetBody&lt;T&gt; (System.Runtime.Serialization.XmlObjectSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!T GetBody&lt;T&gt;(class System.Runtime.Serialization.XmlObjectSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.GetBody``1(System.Runtime.Serialization.XmlObjectSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBody(Of T) (serializer As XmlObjectSerializer) As T" />
      <MemberSignature Language="F#" Value="member this.GetBody : System.Runtime.Serialization.XmlObjectSerializer -&gt; 'T" Usage="brokeredMessage.GetBody serializer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="serializer" Type="System.Runtime.Serialization.XmlObjectSerializer" />
      </Parameters>
      <Docs>
        <typeparam name="T"> <span data-ttu-id="831c7-245">Generische Typparameter.</span><span class="sxs-lookup"><span data-stu-id="831c7-245">Generic type parameter.</span></span> </typeparam>
        <param name="serializer"> <span data-ttu-id="831c7-246">Das Serialisierungsprogrammobjekt.</span><span class="sxs-lookup"><span data-stu-id="831c7-246">The serializer object.</span></span> </param>
        <summary><span data-ttu-id="831c7-247">Deserialisiert den Text "brokeredmessage" in ein Objekt des angegebenen Typs eine binäre XmlObjectSerializer mit "DataContractSerializer".</span><span class="sxs-lookup"><span data-stu-id="831c7-247">Deserializes the BrokeredMessage body into an object of the specified type using DataContractSerializer with a Binary XmlObjectSerializer.</span></span> </summary>
        <returns> <span data-ttu-id="831c7-248">Des deserialisierten Objektdiagramms</span><span class="sxs-lookup"><span data-stu-id="831c7-248">The deserialized object/graph</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"> <span data-ttu-id="831c7-249">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-249">Thrown if the message is in disposed state.</span></span> </exception>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="831c7-250">Wird ausgelöst, wenn mit einem Null-Serialisierungsprogramm-Objekt aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="831c7-250">Thrown when invoked with a Null serializer object.</span></span> </exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="831c7-251">Wird ausgelöst, wenn die Nachricht eine Null-Textdatenstrom enthält keine Daten enthält oder wenn der Stream einmal (über alle Aufrufe GetBody()) gelesen wurde.</span><span class="sxs-lookup"><span data-stu-id="831c7-251">Thrown if the message contains a Null body stream, contains no data, or if the stream has been read once (through any GetBody() calls).</span></span> </exception>
      </Docs>
    </Member>
    <Member MemberName="IsBodyConsumed">
      <MemberSignature Language="C#" Value="public bool IsBodyConsumed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBodyConsumed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.IsBodyConsumed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBodyConsumed As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBodyConsumed : bool" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.IsBodyConsumed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-252">Gibt an, ob die Nachricht verbraucht wurde.</span><span class="sxs-lookup"><span data-stu-id="831c7-252">Specifies whether the message has been consumed.</span></span></summary>
        <value><span data-ttu-id="831c7-253">"true", wenn die Meldung verarbeitet wurde; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="831c7-253">true if the message has been consumed; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-254">Ruft ab oder legt die anwendungsspezifische Bezeichnung.</span><span class="sxs-lookup"><span data-stu-id="831c7-254">Gets or sets the application specific label.</span></span></summary>
        <value><span data-ttu-id="831c7-255">Die anwendungsspezifische Bezeichnung.</span><span class="sxs-lookup"><span data-stu-id="831c7-255">The application specific label.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-256">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-256">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-257">Ruft das Datum und die Uhrzeit in UTC bis zu dem die Nachricht in die Warteschlange/Abonnement gesperrt wird.</span><span class="sxs-lookup"><span data-stu-id="831c7-257">Gets the date and time in UTC until which the message will be locked in the queue/subscription.</span></span></summary>
        <value><span data-ttu-id="831c7-258">Das Datum und die Uhrzeit, die bis zu dem die Nachricht in die Warteschlange/Abonnement gesperrt wird.</span><span class="sxs-lookup"><span data-stu-id="831c7-258">The date and time until which the message will be locked in the queue/subscription.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-259">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-259">Thrown if the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="831c7-260">Wird ausgelöst, wenn die Nachricht aus der Service Bus nicht empfangen wurde.</span><span class="sxs-lookup"><span data-stu-id="831c7-260">Thrown if the message was not received from the ServiceBus.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public Guid LockToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockToken As Guid" />
      <MemberSignature Language="F#" Value="member this.LockToken : Guid" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-261">Ruft das Sperrtoken von Service Bus zugeordnet wird, diese Nachricht ab.</span><span class="sxs-lookup"><span data-stu-id="831c7-261">Gets the lock token assigned by Service Bus to this message.</span></span></summary>
        <value><span data-ttu-id="831c7-262">Das Sperrtoken von Service Bus zugeordnet wird, diese Nachricht.</span><span class="sxs-lookup"><span data-stu-id="831c7-262">The lock token assigned by Service Bus to this message.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-263">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-263">Thrown if the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="831c7-264">Wird ausgelöst, wenn die Nachricht aus der Service Bus nicht empfangen wurde.</span><span class="sxs-lookup"><span data-stu-id="831c7-264">Thrown if the message was not received from the ServiceBus.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-265">Ruft ab oder legt den Bezeichner der Nachricht fest.</span><span class="sxs-lookup"><span data-stu-id="831c7-265">Gets or sets the identifier of the message.</span></span> <span data-ttu-id="831c7-266">Dies ist ein benutzerdefiniertes-Wert, den zum Identifizieren doppelter Meldungen verwendet Service Bus verwenden können, wenn aktiviert.</span><span class="sxs-lookup"><span data-stu-id="831c7-266">This is a user-defined value that Service Bus can use to identify duplicate messages, if enabled.</span></span></summary>
        <value><span data-ttu-id="831c7-267">Der Bezeichner der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="831c7-267">The identifier of the message.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-268">Wird ausgelöst, wenn die Nachricht in einem freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="831c7-268">Thrown if the message is in a disposed state.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="831c7-269">Wird ausgelöst, wenn die Nachrichten-ID null ist oder mehr 128 Zeichen lang sein als.</span><span class="sxs-lookup"><span data-stu-id="831c7-269">Thrown if the message identifier is null or exceeds 128 characters in length.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-270">Ermittelt oder definiert einen Partitionsschlüssel für das Senden einer transaktionalen Nachricht an eine Warteschlange oder ein Thema, das nicht für Sitzungen aktivierte ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-270">Gets or sets a partition key for sending a transactional message to a queue or topic that is not session-aware.</span></span></summary>
        <value><span data-ttu-id="831c7-271">Der Partitionsschlüssel für eine transaktionale Nachricht senden.</span><span class="sxs-lookup"><span data-stu-id="831c7-271">The partition key for sending a transactional message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-272">Ruft den anwendungsspezifischen Meldungseigenschaften ab.</span><span class="sxs-lookup"><span data-stu-id="831c7-272">Gets the application specific message properties.</span></span></summary>
        <value><span data-ttu-id="831c7-273">Die anwendungsspezifischen Meldungseigenschaften.</span><span class="sxs-lookup"><span data-stu-id="831c7-273">The application specific message properties.</span></span></value>
        <remarks><span data-ttu-id="831c7-274">Die Größe der einzelnen Property-Objekt in der Eigenschaftensammlung darf 32 KB nicht überschreiten.</span><span class="sxs-lookup"><span data-stu-id="831c7-274">The size of each property object within the Properties bag cannot exceed 32 kilobytes.</span></span>
            <span data-ttu-id="831c7-275">Der gemeinsame Größe die Eigenschaftensammlung darf 64 KB nicht überschreiten.</span><span class="sxs-lookup"><span data-stu-id="831c7-275">The collective size of the Properties bag cannot exceed 64 kilobytes.</span></span></remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-276">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-276">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RenewLock">
      <MemberSignature Language="C#" Value="public void RenewLock ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RenewLock() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.RenewLock" />
      <MemberSignature Language="VB.NET" Value="Public Sub RenewLock ()" />
      <MemberSignature Language="F#" Value="member this.RenewLock : unit -&gt; unit" Usage="brokeredMessage.RenewLock " />
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
        <summary><span data-ttu-id="831c7-277">Erneuert die Sperre für eine Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="831c7-277">Renews the lock on a message.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="831c7-278">Wenn <see cref="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" /> ist "true", können Sie den Vorgang sofort wiederholen.</span><span class="sxs-lookup"><span data-stu-id="831c7-278">If <see cref="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" /> is true, you can retry the operation immediately.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="831c7-279">Sie können sofort den Vorgang wiederholen.</span><span class="sxs-lookup"><span data-stu-id="831c7-279">You can retry the operation immediately.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="831c7-280">Wird ausgelöst, wenn Sie aufgerufen haben <see cref="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.RenewLock" /> zu spät.</span><span class="sxs-lookup"><span data-stu-id="831c7-280">Thrown if you have called <see cref="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.RenewLock" /> too late.</span></span> <span data-ttu-id="831c7-281">In einer Sitzung wird dies niemals ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="831c7-281">In a session, this is never thrown.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException"><span data-ttu-id="831c7-282">Wird ausgelöst, anstelle von <see cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException" /> ist die Nachricht aus einer <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />.</span><span class="sxs-lookup"><span data-stu-id="831c7-282">Thrown instead of <see cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException" /> if the message is from a <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewLockAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RenewLockAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.RenewLockAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewLockAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RenewLockAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.RenewLockAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="831c7-283">Die Sperre für eine Nachricht erneuert asynchron.</span><span class="sxs-lookup"><span data-stu-id="831c7-283">Asynchronously renews the lock on a message.</span></span></summary>
        <returns><span data-ttu-id="831c7-284">Das asynchrone Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="831c7-284">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ReplyTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-285">Ruft ab oder legt die Adresse der Warteschlange, an die geantwortet.</span><span class="sxs-lookup"><span data-stu-id="831c7-285">Gets or sets the address of the queue to reply to.</span></span></summary>
        <value><span data-ttu-id="831c7-286">Die Antwort auf die Adresse.</span><span class="sxs-lookup"><span data-stu-id="831c7-286">The reply to queue address.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-287">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-287">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ReplyToSessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-288">Ermittelt oder definiert die Sitzungs-ID, um zu antworten.</span><span class="sxs-lookup"><span data-stu-id="831c7-288">Gets or sets the session identifier to reply to.</span></span></summary>
        <value><span data-ttu-id="831c7-289">Die Sitzungs-ID, an die geantwortet werden soll.</span><span class="sxs-lookup"><span data-stu-id="831c7-289">The session identifier to reply to.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-290">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-290">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ScheduledEnqueueTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime ScheduledEnqueueTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduledEnqueueTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ScheduledEnqueueTimeUtc : DateTime with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ScheduledEnqueueTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-291">Ruft ab oder legt das Datum und die Uhrzeit in UTC, an dem die Nachricht in die Warteschlange eingereiht werden.</span><span class="sxs-lookup"><span data-stu-id="831c7-291">Gets or sets the date and time in UTC at which the message will be enqueued.</span></span> <span data-ttu-id="831c7-292">Diese Eigenschaft gibt die Zeit in UTC; Wenn die Eigenschaft festlegen, muss der angegebene DateTime-Wert auch in UTC.</span><span class="sxs-lookup"><span data-stu-id="831c7-292">This property returns the time in UTC; when setting the property, the supplied DateTime value must also be in UTC.</span></span></summary>
        <value><span data-ttu-id="831c7-293">Die geplante Enqueue-Zeit in UTC.</span><span class="sxs-lookup"><span data-stu-id="831c7-293">The scheduled enqueue time in UTC.</span></span> <span data-ttu-id="831c7-294">Dieser Wert ist für das verzögerte zu nachrichtensenden.</span><span class="sxs-lookup"><span data-stu-id="831c7-294">This value is for delayed message sending.</span></span> <span data-ttu-id="831c7-295">Es wird verwendet, um Nachrichten senden zu einem bestimmten Zeitpunkt in der Zukunft zu verzögern.</span><span class="sxs-lookup"><span data-stu-id="831c7-295">It is utilized to delay messages sending to a specific time in the future.</span></span></value>
        <remarks> <span data-ttu-id="831c7-296">Zeitpunkt der Enquing bedeutet nicht, dass die Nachricht zur gleichen Zeit gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="831c7-296">Message enquing time does not mean that the message will be sent at the same time.</span></span> <span data-ttu-id="831c7-297">Erhalten sie in die Warteschlange eingereiht, aber tatsächliche sendende erforderliche Zeit hängt von der Warteschlange arbeitsauslastung und den Zustand.</span><span class="sxs-lookup"><span data-stu-id="831c7-297">It will get enqueued, but the actual sending time depends on the queue's workload and its state.</span></span> <seealso cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedTimeUtc" /></remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-298">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-298">Thrown if the message is in disposed state.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="831c7-299">Wird ausgelöst, wenn der übergebene Wert DateTime.MaxValue ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-299">Thrown if the passed in value is DateTime.MaxValue.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-300">Ruft die eindeutige Nummer, die eine Nachricht vom Servicebus zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="831c7-300">Gets the unique number assigned to a message by the Service Bus.</span></span></summary>
        <value><span data-ttu-id="831c7-301">Die eindeutige Nummer, die eine Nachricht vom Servicebus zugewiesen wird.</span><span class="sxs-lookup"><span data-stu-id="831c7-301">The unique number assigned to a message by the Service Bus.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-302">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-302">Thrown if the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="831c7-303">Wird ausgelöst, wenn die Nachricht nicht aus dem e-Mail-Server empfangen wurde.</span><span class="sxs-lookup"><span data-stu-id="831c7-303">Thrown if the message was not received from the message server.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-304">Ruft ab oder legt den Bezeichner der Sitzung fest.</span><span class="sxs-lookup"><span data-stu-id="831c7-304">Gets or sets the identifier of the session.</span></span></summary>
        <value><span data-ttu-id="831c7-305">Der Bezeichner der Sitzung.</span><span class="sxs-lookup"><span data-stu-id="831c7-305">The identifier of the session.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-306">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-306">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public long Size { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.Size" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Size As Long" />
      <MemberSignature Language="F#" Value="member this.Size : int64" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.Size" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-307">Ruft die Größe der Nachricht in Bytes ab.</span><span class="sxs-lookup"><span data-stu-id="831c7-307">Gets the size of the message in bytes.</span></span></summary>
        <value><span data-ttu-id="831c7-308">Die Nachrichtengröße in Byte.</span><span class="sxs-lookup"><span data-stu-id="831c7-308">The message size in bytes.</span></span></value>
        <remarks><span data-ttu-id="831c7-309">Der Wert der Größe ist nur genau, nachdem die Instanz "brokeredmessage" gesendet oder empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="831c7-309">The value of Size is only accurate after the BrokeredMessage instance is sent or received.</span></span></remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-310">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-310">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageState State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.MessageState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As MessageState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.ServiceBus.Messaging.MessageState" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-311">Ruft ab oder legt den Status der Nachricht fest.</span><span class="sxs-lookup"><span data-stu-id="831c7-311">Gets or sets the state of the message.</span></span></summary>
        <value><span data-ttu-id="831c7-312">Der Status der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="831c7-312">The state of the message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Xml.Serialization.IXmlSerializable.GetSchema">
      <MemberSignature Language="C#" Value="System.Xml.Schema.XmlSchema IXmlSerializable.GetSchema ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Xml.Schema.XmlSchema System.Xml.Serialization.IXmlSerializable.GetSchema() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.System#Xml#Serialization#IXmlSerializable#GetSchema" />
      <MemberSignature Language="VB.NET" Value="Function GetSchema () As XmlSchema Implements IXmlSerializable.GetSchema" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.GetSchema</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.Schema.XmlSchema</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="831c7-313">Diese Methode ist reserviert und sollte nicht verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="831c7-313">This method is reserved and should not be used.</span></span> <span data-ttu-id="831c7-314">Wenn Sie die IXmlSerializable-Schnittstelle implementieren, sollten Sie null (Nothing in Visual Basic) von dieser Methode zurückgeben und stattdessen angeben eines benutzerdefinierten Schemas erforderlich ist, gelten die XmlSchemaProviderAttribute für die Klasse.</span><span class="sxs-lookup"><span data-stu-id="831c7-314">When implementing the IXmlSerializable interface, you should return null (Nothing in Visual Basic) from this method, and instead, if specifying a custom schema is required, apply the XmlSchemaProviderAttribute to the class.</span></span></summary>
        <returns><span data-ttu-id="831c7-315">Ein XmlSchema, das die XML-Darstellung des Objekts beschreibt, die von der Methode WriteXml und von der ReadXml-Methode genutzt wird.</span><span class="sxs-lookup"><span data-stu-id="831c7-315">An XmlSchema that describes the XML representation of the object that is produced by the WriteXml method and consumed by the ReadXml method.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Xml.Serialization.IXmlSerializable.ReadXml">
      <MemberSignature Language="C#" Value="void IXmlSerializable.ReadXml (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Xml.Serialization.IXmlSerializable.ReadXml(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.System#Xml#Serialization#IXmlSerializable#ReadXml(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Sub ReadXml (reader As XmlReader) Implements IXmlSerializable.ReadXml" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.ReadXml(System.Xml.XmlReader)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="831c7-316">Der XmlReader-Datenstrom, aus dem das Objekt deserialisiert wird.</span><span class="sxs-lookup"><span data-stu-id="831c7-316">The XmlReader stream from which the object is deserialized.</span></span></param>
        <summary><span data-ttu-id="831c7-317">Generiert ein Objekt aus seiner XML-Darstellung.</span><span class="sxs-lookup"><span data-stu-id="831c7-317">Generates an object from its XML representation.</span></span> <span data-ttu-id="831c7-318">Diese Methode ist für die interne Verwendung reserviert und sollte nicht verwendet werden direkt oder indirekt (z. B. über ein Serialisierungsprogramm oder ein Formatierungsprogramm).</span><span class="sxs-lookup"><span data-stu-id="831c7-318">This method is reserved for internal use and should not be used directly or indirectly (for example, using a serializer or a formatter).</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Xml.Serialization.IXmlSerializable.WriteXml">
      <MemberSignature Language="C#" Value="void IXmlSerializable.WriteXml (System.Xml.XmlWriter writer);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Xml.Serialization.IXmlSerializable.WriteXml(class System.Xml.XmlWriter writer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.System#Xml#Serialization#IXmlSerializable#WriteXml(System.Xml.XmlWriter)" />
      <MemberSignature Language="VB.NET" Value="Sub WriteXml (writer As XmlWriter) Implements IXmlSerializable.WriteXml" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.WriteXml(System.Xml.XmlWriter)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
      </Parameters>
      <Docs>
        <param name="writer"><span data-ttu-id="831c7-319">Der XmlWriter-Datenstrom, der das Objekt serialisiert wird.</span><span class="sxs-lookup"><span data-stu-id="831c7-319">The XmlWriter stream to which the object is serialized.</span></span></param>
        <summary><span data-ttu-id="831c7-320">Konvertiert ein Objekt in seine XML-Darstellung.</span><span class="sxs-lookup"><span data-stu-id="831c7-320">Converts an object into its XML representation.</span></span> <span data-ttu-id="831c7-321">Diese Methode ist für die interne Verwendung reserviert und sollte nicht verwendet werden, direkt oder indirekt (z. B. ein Serialisierungsprogramm oder ein Formatierungsprogramm verwenden).</span><span class="sxs-lookup"><span data-stu-id="831c7-321">This method is reserved for internal use and should not be used directly or indirectly (e.g. using a serializer or a formatter).</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-322">Ruft ab oder legt die Nachricht TTL-Wert.</span><span class="sxs-lookup"><span data-stu-id="831c7-322">Gets or sets the message’s time to live value.</span></span> <span data-ttu-id="831c7-323">Hierbei handelt es sich um den Zeitraum, nach dem Ablauf die Nachricht beginnend ab dem Zeitpunkt der Nachricht an den Servicebus gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="831c7-323">This is the duration after which the message expires, starting from when the message is sent to the Service Bus.</span></span> <span data-ttu-id="831c7-324">Nachrichten, die älter als ihr TimeToLive-Wert abläuft und nicht länger im Nachrichtenspeicher beibehalten.</span><span class="sxs-lookup"><span data-stu-id="831c7-324">Messages older than their TimeToLive value will expire and no longer be retained in the message store.</span></span> <span data-ttu-id="831c7-325">Abonnenten werden können abgelaufene Nachrichten empfangen. TimeToLive ist die maximale Lebensdauer, die eine Nachricht empfangen kann, aber der Wert darf nicht die angegebene Entität überschreiten die <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" /> Wert an die Zielwarteschlange oder das Abonnement.</span><span class="sxs-lookup"><span data-stu-id="831c7-325">Subscribers will be unable to receive expired messages.TimeToLive is the maximum lifetime that a message can receive, but its value cannot exceed the entity specified the <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" /> value on the destination queue or subscription.</span></span> <span data-ttu-id="831c7-326">Wenn Sie ein niedriger TimeToLive-Wert angegeben wird, wird er auf die einzelne Nachricht angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="831c7-326">If a lower TimeToLive value is specified, it will be applied to the individual message.</span></span> <span data-ttu-id="831c7-327">Ein höheren Wert für die Nachricht angegebenen wird jedoch durch die Entität DefaultMessageTimeToLive Wert überschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="831c7-327">However, a larger value specified on the message will be overridden by the entity’s DefaultMessageTimeToLive value.</span></span></summary>
        <value><span data-ttu-id="831c7-328">Die Nachricht Gültigkeitsdauerwert.</span><span class="sxs-lookup"><span data-stu-id="831c7-328">The message’s time to live value.</span></span></value>
        <remarks><span data-ttu-id="831c7-329">Wenn die Gültigkeitsdauer (TTL) für eine Nachricht festlegen, indem der Absender das Ziel Gültigkeitsdauer (TTL) überschreitet, werden Gültigkeitsdauer der Nachricht durch die neuere Version überschrieben.</span><span class="sxs-lookup"><span data-stu-id="831c7-329">If the TTL set on a message by the sender exceeds the destination's TTL, then the message's TTL will be overwritten by the later one.</span></span>
            <span data-ttu-id="831c7-330">Finden Sie unter <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" />, <see cref="P:Microsoft.ServiceBus.Messaging.TopicDescription.DefaultMessageTimeToLive" /> und <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.DefaultMessageTimeToLive" /> erfahren Sie mehr über das Nachrichten-TTL auf eine Entitätsebene steuern.</span><span class="sxs-lookup"><span data-stu-id="831c7-330">See <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" />, <see cref="P:Microsoft.ServiceBus.Messaging.TopicDescription.DefaultMessageTimeToLive" /> and <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.DefaultMessageTimeToLive" /> to learn more about how to control message TTL at an entity level.</span></span></remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-331">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-331">Thrown if the message is in disposed state.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="831c7-332">Wird ausgelöst, wenn der übergebene Wert kleiner als oder gleich TimeSpan.Zero ist.</span><span class="sxs-lookup"><span data-stu-id="831c7-332">Thrown if the passed in value is less than or equal to TimeSpan.Zero.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-333">Ruft ab, oder legt senden zu Adresse.</span><span class="sxs-lookup"><span data-stu-id="831c7-333">Gets or sets the send to address.</span></span></summary>
        <value><span data-ttu-id="831c7-334">Die Adresse des Empfängers.</span><span class="sxs-lookup"><span data-stu-id="831c7-334">The send to address.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="831c7-335">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</span><span class="sxs-lookup"><span data-stu-id="831c7-335">Thrown if the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="brokeredMessage.ToString " />
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
        <summary><span data-ttu-id="831c7-336">Gibt eine Zeichenfolge, die die aktuelle Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="831c7-336">Returns a string that represents the current message.</span></span></summary>
        <returns><span data-ttu-id="831c7-337">Die Zeichenfolgendarstellung der aktuellen Nachricht.</span><span class="sxs-lookup"><span data-stu-id="831c7-337">The string representation of the current message.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ViaPartitionKey">
      <MemberSignature Language="C#" Value="public string ViaPartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ViaPartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ViaPartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ViaPartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.ViaPartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ViaPartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="831c7-338">Ruft ab oder legt einen Wert für den Partitionsschlüssel wird eine Transaktion zum Senden von Nachrichten über eine Übertragungswarteschlange verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="831c7-338">Gets or sets a partition key value when a transaction is to be used to send messages via a transfer queue.</span></span></summary>
        <value><span data-ttu-id="831c7-339">Der partitionsschlüsselwert wird eine Transaktion zum Senden von Nachrichten über eine Übertragungswarteschlange verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="831c7-339">The partition key value when a transaction is to be used to send messages via a transfer queue.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>